# CLAUDE.md

Guidance for agents working in this repository.

## Repository purpose

Special `.github` repository for the CoMPhy Lab (Computational Multiphase Physics Lab) GitHub organization. It holds:

- The organization profile shown on [github.com/comphy-lab](https://github.com/comphy-lab)
- Organization-wide GitHub configuration when added later

## Layout

```
profile/
  README.md    # Organization profile (public-facing)
README.md      # This repo's short description
CLAUDE.md      # Agent guidance
```

## Organization profile (`profile/README.md`)

Tone: scholarly lab voice. Dense, informative, low clutter. Prefer plain markdown links and short prose over badge walls, emoji headers, profile-view counters, and auto-generated activity widgets.

Keep these elements when editing:

- Lab name and one crisp mission paragraph
- Research themes as short prose or a tight list
- Compact primary links (website, people, research, contact, key socials)
- Affiliation/location in one line
- Optional curated featured-repos table with real `comphy-lab` public repos
- The `<!-- RECENT_PUBLICATIONS_START -->` / `<!-- RECENT_PUBLICATIONS_END -->` block (synced from the lab website)

Do not reintroduce:

- Large `for-the-badge` / shields.io grids for themes, languages, or frameworks
- OSS Insight or similar metric-widget walls
- Profile-view counters
- Decorative emoji section headers
- Placeholder “featured projects” that link only to the org root

## Notes

- No build or test suite in this repository
- Edits to `profile/README.md` appear on the public organization page after merge
