# What's New

**One feed for every changelog.**

[whatsnew.fyi](https://whatsnew.fyi) collects release notes and patch notes from
open-source projects, games, operating systems and desktop apps into one
reverse-chronological feed. It tracks over 1,700 products, and every entry links
to the vendor's own notes.

## Repositories

- **[dataset](https://github.com/whatsnew-fyi/dataset)**: the release facts as a
  nightly JSONL dataset (products, versions, dates, CVE ids, breaking-change
  signals), licensed CC BY 4.0.
- **[skills](https://github.com/whatsnew-fyi/skills)**: agent skills that read the
  release notes before you upgrade. A Claude Code plugin plus the MCP server.
- **[upgrade-notes-action](https://github.com/whatsnew-fyi/upgrade-notes-action)**: a
  GitHub Action that comments on Dependabot, Renovate and lockfile PRs with the
  vendor's breaking changes, migration notes and CVE fixes for every version in between.
- **[declarative-changelog](https://github.com/whatsnew-fyi/declarative-changelog)**:
  validator, reference parser, GitHub Action and pre-commit hook for
  [Declarative Changelogs](https://whatsnew.fyi/spec), a `CHANGELOG.md` a machine can
  read without guessing.

## Use it

- **Site**: [whatsnew.fyi](https://whatsnew.fyi) · [blog](https://whatsnew.fyi/blog)
- **API**: [whatsnew.fyi/api/v1](https://whatsnew.fyi/api/v1/openapi.json) (OpenAPI)
- **MCP server**: `fyi.whatsnew/changelogs` at [whatsnew.fyi/mcp](https://whatsnew.fyi/mcp)
  ([setup](https://whatsnew.fyi/mcp/setup))
- **Feeds**: [RSS](https://whatsnew.fyi/feed.xml) · [llms.txt](https://whatsnew.fyi/llms.txt)
- **Social**: [Bluesky](https://bsky.app/profile/whatsnew.fyi) ·
  [Mastodon](https://mastodon.social/@whatsnew_fyi)
- **Missing a product?** Ask for it at [whatsnew.fyi/suggest](https://whatsnew.fyi/suggest).

Not affiliated with any product listed.
