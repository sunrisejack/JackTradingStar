# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **documentation-only** project. It contains:

- `README.md` — one-liner project description ("JackTradingStar — Powerful Trading Tools")
- `ltsd-trading-system 最新版.skill` — a ZIP archive containing 10 markdown files that document the **LTSD supply-demand zone quantitative trading system**

### Key facts

- **No source code, no dependencies, no build system, no tests, no linting.**
- **No runnable application.** There is nothing to `npm install`, `pip install`, build, or start.
- The `.skill` file is a standard ZIP archive. Extract with `unzip "ltsd-trading-system 最新版.skill" -d /tmp/skill-contents` to read the markdown documentation inside.
- The documentation describes (but does not implement) an MQL4 Expert Advisor for MetaTrader 4. No MQL4 source files exist in this repo.

### Working with the documentation

- The main entry point is `ltsd-trading-system/SKILL.md` inside the archive, which describes the full 7-step LTSD workflow and indexes 9 reference files.
- Reference files cover: LTSD framework, supply-demand zones, harmonic patterns, JTA alchemy (candlestick patterns), MQL4 EA spec, indicator analysis, pattern analysis, trade execution, and chart report format.

### What future agents should NOT attempt

- Do not try to install dependencies or run build/test/lint commands — none exist.
- Do not try to start a dev server or application — there is none.
