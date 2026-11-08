# CI budget

Normal pull-request feedback targets 90 seconds, with a 120-second slow-run budget,
including checkout and dependency setup. Keep authentication, data preservation,
public contracts and changed/new tests covered. A missing, skipped, cancelled or
timed-out required check must never become green.

Keep deeper platform/release validation on main-branch and manual runs. Do not
delete coverage to conceal a slow check. Cache dependencies, cancel superseded
pull-request runs, and report cold-cache/platform-queue exceptions separately.
