# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the special `.github` repository for the CoMPhy-Lab (Computational Multiphase Physics Lab) GitHub organization. The repository serves as:
- Organization profile that appears on the main GitHub organization page
- Container for organization-wide GitHub configurations and templates

## Repository Structure

```
.github/
├── profile/
│   └── README.md    # Organization profile displayed on github.com/comphy-lab
└── README.md        # Repository documentation
```

## Key Files

### profile/README.md
The main organization profile that displays:
- Development workflow statistics (pull requests, commits, issues)
- Community participation metrics
- Activity visualizations using OSS Insight widgets

## Development Guidelines

### Editing the Organization Profile
- The organization profile is located at `profile/README.md`
- Changes to this file will be reflected on the CoMPhy-Lab GitHub organization page
- The profile uses OSS Insight widgets for dynamic statistics visualization

### Widget Configuration
The profile uses OSS Insight widgets with:
- Organization ID: 114741869
- Time period: past_12_months
- Both light and dark theme support using `<picture>` elements

### Common Tasks

To update organization statistics displays:
1. Edit `profile/README.md`
2. Widgets auto-update based on the configured time period

To modify organization profile appearance:
1. Edit the markdown content in `profile/README.md`
2. Preview changes before committing

## Important Notes

- This repository does not contain code or require building/testing
- Changes to `profile/README.md` directly affect the organization's public profile
- The repository uses standard markdown with HTML elements for advanced formatting