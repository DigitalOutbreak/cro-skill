# Conversion-focused web design

An Agent Skill for coding agents building customer-facing websites and improving the journey from first visit to qualified inquiry, booking, signup or purchase. Four modes cover implementation, evidence-based audits, brand-preserving redesigns and measured optimization.

## Install

Run this command in the target project:

```sh
npx skills add DigitalOutbreak/cro-skill --skill conversion-focused-web-design
```

For a user-wide Codex installation append `--agent codex --global`. For an unpacked copy, run the following from its root:

```sh
npx skills add . --list
npx skills add . --skill conversion-focused-web-design --agent codex
```

Use with Codex, Claude Code, Cursor or another skills CLI-supported agent. Codex project installation was exercised. Other clients can differ in discovery and invocation. In Codex, name `$conversion-focused-web-design` explicitly, or describe the visitor-facing task. No additional runtime package or account is required by the skill itself.

## Try it

- **Build** — “Build a garage door repair landing page for a mobile Google Ads visitor. Use our actual coverage, hours and dispatch number.”
- **Audit** — “Walk our signup page by keyboard and on mobile. Show reproducible evidence and score the path.”
- **Redesign** — “Redesign our water restoration quote page. Keep our brand, campaign URLs, form handler and CRM handoff.”
- **Optimize** — “Our paid landing page generates phone calls but few bookings. Reconcile the counts and choose the next change to evaluate.”

## Contents and approach

Start at [SKILL.md](skills/conversion-focused-web-design/SKILL.md). The six references cover visual composition, usability and accessibility, conversion paths, service businesses, experimentation and an eight-dimension evaluation rubric. It works with existing project components and available testing tools. An audit records unknown states explicitly.

## Sources and credit

| Work | Contribution to the synthesis |
| --- | --- |
| *Refactoring UI*, Adam Wathan and Steve Schoger | Attention hierarchy, deliberate scales, type, color and spatial grouping |
| *Making Websites Win*, Karl Blanks and Ben Jesson | Customer research, diagnosis, objections, offers and downstream outcomes |
| *Laws of UX*, second edition, Jon Yablonski | Familiarity, target acquisition, chunking, decision load, feedback and ethical design |
| *Don't Make Me Think, Revisited*, third edition, Steve Krug | Scanning, orientation, recognizable controls and task-based observation |
| *You Should Test That!*, Chris Goward | Prioritizing test opportunities, value proposition, barriers to action and controlled experiments |

The checklists, examples, rubric and workflows are original instructional material. The authors retain rights in their respective books. This is an independent project.

[Agent Skills specification](https://agentskills.io/specification) · [Skills CLI](https://skills.sh/docs/cli) · [WCAG 2.2](https://www.w3.org/TR/WCAG22/) · [Core Web Vitals](https://web.dev/articles/vitals)
