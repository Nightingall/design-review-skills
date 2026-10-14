# Design review skills for Claude

Two skills that give Claude a sharper eye for design. They work as a pair:

| Skill | Question it asks | Use it for |
| --- | --- | --- |
| **dieter-rams-review** | *Should this exist, and does it serve the user?* | Deciding whether to build or cut a feature, screens that feel bloated or gimmicky, comparing two product directions |
| **ui-craft-review** | *Is it built with care?* | Pixel-level polish: hierarchy, grid, typography, colour, spacing, states, motion |

Run the Rams review first, then the craft review. A screen can pass one and fail the other.

Each review walks through ten principles, gives each relevant one a **Pass / Tension / Fail** verdict with a specific observation and the smallest fix, then ends with a headline verdict and a short ranked list of actions.

## Install

### Claude Code (plugin)

Run these two commands inside Claude Code:

```
/plugin marketplace add Nightingall/design-review-skills
/plugin install design-review@design-review-skills
```

Then ask for a "Rams review" or a "UI craft review", or call the skills directly with `/design-review:dieter-rams-review` and `/design-review:ui-craft-review`.

### Claude Code (copy the files)

Download this repo (**Code → Download ZIP**) and copy both folders from `skills/` into `~/.claude/skills/`:

```
~/.claude/skills/dieter-rams-review/SKILL.md
~/.claude/skills/ui-craft-review/SKILL.md
```

They then work as `/dieter-rams-review` and `/ui-craft-review`.

### Claude app and claude.ai

No technical setup needed. On a computer:

1. Download both zips (don't unzip them): [dieter-rams-review.zip](https://github.com/Nightingall/design-review-skills/releases/latest/download/dieter-rams-review.zip) and [ui-craft-review.zip](https://github.com/Nightingall/design-review-skills/releases/latest/download/ui-craft-review.zip).
2. In Claude, open **Settings → Capabilities** and check **Code execution and file creation** is switched on.
3. Go to **Customize → Skills**, click **+**, then **Create skill → Upload a skill**. Upload the first zip, then repeat for the second.
4. Check both skills are switched on in your skills list.

Then ask Claude for a "Rams review" or a "UI craft review" and share a screenshot, link or design.

On a Mac with Safari, the download may unzip itself into a folder. If so, right-click the folder, choose **Compress**, and upload the new zip.

## What's inside

- [`skills/dieter-rams-review/SKILL.md`](skills/dieter-rams-review/SKILL.md): Dieter Rams' ten principles of good design, translated for digital products.
- [`skills/ui-craft-review/SKILL.md`](skills/ui-craft-review/SKILL.md): ten craft principles drawn from Müller-Brockmann, Vignelli, Spiekermann, *Refactoring UI*, Rauno Freiberg, Emil Kowalski and Benjamin De Cock.

Each skill is a single Markdown file. Edit it to suit your own taste.

## Licence

[MIT](LICENSE). Use, change and share freely.
