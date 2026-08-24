# Apply Design Best Practices

I had 20–30 design skills and kept running into the same problem: the hard
part was no longer finding advice. It was remembering which skill was best for
the exact job in front of me.

This meta-skill routes a UI task to the strongest specialist skill for that
task, fetches its current instructions, and applies them without installing the
whole collection.

The routing table covers motion, frontend generation, audits and polish,
landing pages, typography, color, design systems, accessibility, UX writing,
mobile, dashboards, icons, 3D, email, forms, data tables, responsive layout,
brand identity, video, and Figma-to-code.

Rankings start with real usage reports—what people used a skill for, what it
improved, and where it fell short. skills.sh installs and GitHub stars are
secondary adoption signals, not proof of quality. Every recommendation links
to a fetchable `SKILL.md`, and CI checks the links for rot.

## Install

```bash
npx skills add aboul3ata/apply-design-best-practices
```

## Use

Ask your agent naturally:

```text
Apply design best practices to this checkout form.
Use the best design skill to review this animation.
Which design skill should drive this dashboard redesign?
```

The router borrows the selected skill's expertise for the task. It does not
install third-party skills or replace real product evidence, user research, or
measured experiment results.

## Contributing

Open an issue or pull request with the task, the candidate skill's raw
`SKILL.md`, and independent evidence of how people actually use it. Popularity
alone is not enough to change a default route.

MIT licensed.
