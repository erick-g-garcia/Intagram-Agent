# Port from Claude to ChatGPT

## What changed
- Claude home-directory state paths were replaced with project-local instagram/ files.
- Claude plugin packaging was removed.
- CHATGPT.md and AGENTS.md were added as orchestration entry points.
- Evidence discipline was added to each skill.
- Original Python utilities and data files were preserved.

## What did not change
The original content frameworks, scoring code, rubric data, humanizer logic, swipe analysis, and MIT license remain the upstream foundation.

## Future integration
A personal Instagram integration should prefer official Meta APIs and explicit user approval. Browser automation, bulk scraping, automated unsolicited DMs, follows, likes, or comments are intentionally out of scope.
