# Activepieces community-source licence boundary audit

Upstream root LICENSE separates MIT community source from commercial Enterprise paths.

- Restricted paths audited: `packages/ee/` and `packages/server/api/src/app/ee/`
- Restricted implementation files removed from `main`: **229**
- Enterprise licence notice retained: **1**
- Other existing tracked files before filtering: **36468**
- Original source attribution and `TRILLIONAI_REFERENCE.md` retained.
- This cleanup changes the current Git branch only. Prior public commits and snapshot branches may still contain earlier content; full history sanitation needs a separate assessment.
- No upstream code or package installation was executed.
- Any re-import should enforce this licence filter before publishing.
