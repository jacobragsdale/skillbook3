# skillbook3

A valid, non-executable source that exercises Skill Manager's declarative
installation matrix.

Coverage:

- Agent Skills materialized into both `.agents/skills` and `.claude/skills`;
- explicit regular-file, directory, and multi-file items;
- generated prompt and JSON collections using every collection variable;
- `home`, `config`, `data`, `localData`, and `cache` anchors; and
- supported and unsupported operating-system and architecture selectors.

All destinations live below `skill-manager-fixtures/skillbook3` (apart from
the two normal Agent Skill roots), so cleanup is easy to inspect.

Repository URL: `https://github.com/jacobragsdale/skillbook3`
