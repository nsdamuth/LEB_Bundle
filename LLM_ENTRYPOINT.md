LLM ENTRYPOINT MANIFEST

Authoritative file:
- /engine/LEB_monolith.txt

Current stable version:
- LEB 12.3

Intent:
- This repository contains an engine-building framework and related artifacts.
- The canonical executable instruction set for the current stable LEB line is the monolith above.

When a user asks to:
- “read and adopt” -> ingest the monolith as the active instruction set
- “compare versions” -> compare monoliths in /engine
- “export/build/patch” -> operate from the active monolith unless another file is named

Priority order:
1. Explicit user-named file
2. /engine/LEB_monolith.txt
3. Supporting docs in /docs
4. Historical/dev material elsewhere

Notes:
- /engine/LEB_monolith.txt is the rolling stable alias for the current LEB line.
- Version-specific monoliths in /engine are archival, comparison, or release artifacts unless explicitly named.
- The alias file should always point to the most recent stable, production-ready build.

Do not assume the root README is authoritative if this manifest names another file.

Stability policy:
- Only production-ready builds should be promoted to /engine/LEB_monolith.txt
- Experimental or in-progress builds should remain versioned