# comicbook-core

## Truth Files

- `COMPREHENSION.md`
- `DECISIONS.md`
- `ROADMAP.md`
- `GLOSSARY.md`


## Agent and Logs

- Agent profile: `AGENTS.md`
- Logs (local-only): `CONVERSATION.md`, `BOOKMARKS.md`, `Action-Log.md` (when present)


Shared library: naming rules, path builders, models, archive utilities, logging helpers, CSV reporting.

## Quickstart
```bash
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

## Action Log
- 2025-10-19 — Initialized repository skeleton (MIT, Python 3 only).

## Appendix: Directory Structure — comicbook-core

<!-- BEGIN DIR TREE -->
```
comicbook-core
├── comicbook_core
│   ├── __init__.py
│   ├── config_naming.py
│   ├── logging_utils.py
│   ├── models.py
│   └── report.py
├── LICENSE
├── Makefile
├── README.md
└── requirements.txt
```
<!-- END DIR TREE -->
