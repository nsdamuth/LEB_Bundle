# LEB_Bundle
# Start Here

Canonical active engine:
- /engine/LEB_v12_monolith.txt

Primary instruction for an LLM:
- Read /engine/LEB_v12_monolith.txt first.
- Treat it as the authoritative monolith unless the user explicitly asks for another version.
- Use other files only as supporting documentation, changelog, templates, or dev artifacts.

Repository structure:
- /engine = canonical engine files
- /docs = explanatory documentation
- /templates = reusable scaffolds
- /devkit = development/support material
- /diagrams = visual references
- /starter-pack = optional onboarding material

If the user says “read and adopt the LEB 12 monolith,” open:
- /engine/LEB_v12_monolith.txt
# LEB Master Bundle

This package contains the full distribution of the LEB Engine Builder framework.

Contents:

engine/
    Runtime engine file

docs/
    Detailed documentation
    - Engineering Notes
    - Features
    - System Overview
    - Architecture Maps
    - Capability Matrix

diagrams/
    Visual architecture diagrams

Purpose:
Provide a complete package for users, engineers, and contributors to understand,
operate, and extend the LEB system.

Recommended reading order:

1. SYSTEM_OVERVIEW.md
2. MASTER_ARCHITECTURE_MAP.md
3. ENGINEERING_NOTES_DETAILED.md
4. FEATURES_DETAILED.md
