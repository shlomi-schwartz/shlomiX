# UX Expert

**Your always-on UX advisor for Claude Code** — surfaces relevant Laws of UX when you build or modify user interfaces.

[![skills.sh](https://img.shields.io/badge/skills.sh-shlomi--schwartz%2FshlomiX-blue)](https://skills.sh/shlomi-schwartz/shlomiX)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## What it does

UX Expert **proactively activates** during any UI/UX work — creating components, building layouts, designing navigation, wiring up forms, adding interactions, or tweaking visual design. No slash command needed. It reads the context of what you're doing and surfaces the UX laws that matter.

It covers **30 Laws of UX** from [lawsofux.com](https://lawsofux.com) across 6 categories:

| Category | Laws |
|----------|------|
| **Decision & Choice** | Choice Overload, Hick's Law, Tesler's Law, Postel's Law |
| **Cognitive Capacity** | Cognitive Load, Miller's Law, Chunking, Working Memory, Selective Attention |
| **Visual Organization (Gestalt)** | Proximity, Similarity, Common Region, Uniform Connectedness, Pragnanz |
| **Memory & Perception** | Serial Position Effect, Von Restorff Effect, Peak-End Rule, Zeigarnik Effect, Cognitive Bias |
| **Engagement & Motivation** | Flow, Goal-Gradient Effect, Paradox of the Active User, Parkinson's Law |
| **Design Principles** | Jakob's Law, Aesthetic-Usability Effect, Doherty Threshold, Fitts's Law, Mental Model, Occam's Razor, Pareto Principle |

### Smart retrieval

The skill doesn't dump all 30 laws on you. It:

1. Reads the 1-3 most relevant law files based on your current context
2. Traverses related laws when the context spans multiple UX dimensions
3. Fetches external research (NNGroup, Interaction Design Foundation, etc.) when evidence-based justification is needed for significant design decisions

Output is concise — 3-6 sentences of specific, actionable advice backed by the relevant law(s).

## Install

### Via skills CLI (recommended)

```bash
npx skills add shlomi-schwartz/shlomiX
```

### Via Claude Code plugin

```
/plugin marketplace add shlomi-schwartz/shlomiX
/plugin install ux-expert@shlomiX
```

## Examples

**You add a dropdown with 15 options:**
> Hick's Law suggests decision time increases with the number of choices. Consider grouping these options into categories or using progressive disclosure (e.g., a searchable combobox). Both Hick's Law and Choice Overload point to the same remedy — reduce the visible options at any given moment.

**You build a multi-step checkout form:**
> The Zeigarnik Effect shows that incomplete tasks stick in memory — add a progress indicator to leverage this and drive completion. Peak-End Rule reminds us that users judge the experience by its peak and ending: make the confirmation step feel rewarding, not just functional.

**You place a small "Submit" button in the corner of a modal:**
> Fitts's Law says acquisition time depends on distance and size — make the primary action button large and position it where the user's attention already is. Consider placing it at the bottom-right of the modal with generous padding and clear visual weight.

## How it works

```
UI/UX context detected
  → Scan law index (30 laws, 6 categories)
    → Read 1-3 most relevant law files
      → Check Related sections, follow when applicable
        → Fetch Further Reading for major design decisions
          → Synthesize concise, law-backed advice
```

The skill activates when it detects:
- Component creation or modification (buttons, forms, navigation, modals)
- Layout and spacing changes
- Options, choices, or menu items being added
- Interactive elements, touch targets, or click areas
- Loading states or response time work
- Any user-facing interface where UX quality matters

## Repository structure

```
shlomiX/
├── .claude-plugin/
│   └── marketplace.json      # Plugin marketplace config
├── README.md
└── skills/
    └── ux-expert/
        ├── SKILL.md           # Skill definition & law index
        └── references/
            └── laws/          # 30 individual law files
```

## Contributing

Contributions welcome. If you'd like to add laws, improve retrieval logic, or fix issues:

1. Fork the repo
2. Make your changes
3. Open a PR

## License

MIT
