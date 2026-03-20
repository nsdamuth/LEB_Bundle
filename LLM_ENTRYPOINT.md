LLM ENTRYPOINT MANIFEST

Authoritative file:
- /engine/LEB_monolith.txt

Current stable version:
- LEB 12.3

Intent:
- This repository contains an engine-building framework and related artifacts.
- The canonical executable instruction set for LEB 12 is the monolith above.

When a user asks to:
- “read and adopt” -> ingest the monolith as the active instruction set
- “compare versions” -> compare monoliths in /engine
- “export/build/patch” -> operate from the active monolith unless another file is named

Priority order:
1. Explicit user-named file
2. /engine/LEB_monolith.txt
3. Supporting docs in /docs
4. Historical/dev material elsewhere

Do not assume the root README is authoritative if this manifest names another file.