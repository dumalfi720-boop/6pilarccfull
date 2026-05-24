# COURSE: Mastering the Claude Code - The 6 Pillars

**Target audience:** AI automators, devs and professionals who want to use Claude Code as a productivity tool.

---

## MODULE 0 - Introduction
- What is Claude Code and why it changes the game
- Difference between Claude Chat, Claude Code and Cowork
- Prerequisites (Anthropic account, terminal, Node.js)
- Installation of Claude Code (`npm install -g @anthropic-ai/claude-code`)
- First session: running`claude`in the terminal

---

## MODULE 1 - Claude's Shortcuts
*Pillar 1 - Accelerate your use with shortcuts*

- **Class 1.1** - Essential terminal commands (`/help`, `/clear`, `/compact`, `/cost`)
- **Class 1.2** - Native Slash commands (`/commit`, `/review`, `/pr`, `/init`)
- **Class 1.3** - Command line flags (`-p`, `--model`, `--resume`)
- **Class 1.4** - Data pipe: sending files and logs to Claude (`cat | claude -p`)
- **Class 1.5** - Keyboard shortcuts and quick navigation in the session
- **Practice:** Create an alias in the shell that runs Claude with your favorite flags

---

## MODULE 2 - Starter Pack
*Pillar 2 - Configure Claude to understand your project in 60 seconds*

- **Class 2.1** - What is`CLAUDE.md`and why it exists
- **Class 2.2** - Anatomy of the perfect CLAUDE.md (stack, commands, conventions, prohibitions)
- **Class 2.3** - Scopes: root project vs subdirectory vs global (`~/.claude/CLAUDE.md`)
- **Class 2.4** - Real example: Next.js SaaS App
- **Class 2.5** - Real example: Python FastAPI Backend
- **Class 2.6** - The command`/init`to generate CLAUDE.md automatically
- **Practice:** Create CLAUDE.md from a student's personal project

---

## MODULE 3 - 9 Claude Code Workflows
*Pillar 3 - The flows that cover 90% of the real work*

- **Class 3.1** - Workflow 1: Fix a Bug (context > stack trace > diagnosis > fix > commit)
- **Class 3.2** - Workflow 2: Build New Feature (Plan Mode > approval > implementation > tests)
- **Class 3.3** - Workflow 3: Refactor Code (understand > define objective > diff > test)
- **Class 3.4** - Workflow 4: Understanding a New Codebase (big picture > zoom in > trace flow > /init)
- **Class 3.5** - Workflow 5: Writing Tests (gaps > generate > verify > coverage)
- **Class 3.6** - Workflow 6: Code Review (review > feedback > re-review)
- **Class 3.7** - Workflow 7: Create Pull Request (`/pr`automatic)
- **Class 3.8** - Workflow 8: Debug with Logs and Errors (direct paste or pipe)
- **Class 3.9** - Workflow 9: Multi-file Refactoring (plan mode > batches > tests > sweep)
- **Practice:** Take an open source repo, clone it, and run workflows 4, 1 and 7 in sequence

---

## MODULE 4 - Executive Prompt Panel
*Pillar 4 - The prompts that separate amateur from operator*

- **Class 4.1** - The 5 daily prompts (95% Confidence, Plan Mode, Structured Bug, Brutal Audit, Teach Me)
- **Class 4.2** - Getting Started Prompts (kickoff, onboarding)
- **Class 4.3** - Building Prompts (feature blueprint, build with tests)
- **Class 4.4** - Debugging Prompts (structured bug, log analysis)
- **Class 4.5** - Code Quality Prompts (review, refactor guardrails)
- **Class 4.6** - Architecture Prompts (architectural decision, API design)
- **Class 4.7** - Deployment Prompts (prep, CI/CD)
- **Class 4.8** - Usage strategy: when to use each prompt
- **Practice:** Create your own "prompt dashboard" customized for your type of work

---

## MODULE 5 - AI Skills
*Pillar 5 - Build once, use forever*

- **Class 5.1** - What are Skills, MCPs and Plugins (and when to use each one)
- **Class 5.2** - Where skills live (`.claude/commands/`) and how Claude discovers them
- **Class 5.3** - Skill template: the standard structure (Purpose > Inputs > Steps > Quality > Output)
- **Class 5.4** - Practical skill 1: Screenshot to Website
- **Class 5.5** - Practical skill 2: Lead Research
- **Class 5.6** - Practical skill 3: Senior Code Review
- **Class 5.7** - Where to find ready-made skills (awesome-claude-code, SkillsMP, SkillHub)
- **Class 5.8** - Plugins: the game-changer (Supabase, Cowork built-ins)
- **Class 5.9** - Synchronizing skills between Claude Code and Cowork
- **Class 5.10** - Security: what to check before installing a skill
- **Class 5.11** - Token math: 90% savings with skills vs re-typing prompts
- **Practice:** Create 3 personalized skills for the student's workflow

---

## MODULE 6 - Connecting Claude (MCPs)
*Pillar 6 - USB ports for Claude*

- **Class 6.1** - What are MCPs and the "Token Tax" (context cost)
- **Class 6.2** - Decision framework: Skill vs MCP
- **Class 6.3** - MCP #1: Filesystem (access to files outside the repo)
- **Class 6.4** - MCP #2: GitHub (issues, PRs, CI, search)
- **Class 6.5** - MCP #3: Browser/Chrome DevTools (screenshot, scrape, interaction)
- **Class 6.6** - MCP #4: Database/Supabase (queries, schema, migrations)
- **Class 6.7** - MCP #5: Google Sheets (reading/writing spreadsheets)
- **Class 6.8** - Managing MCPs (`mcp add`, `mcp list`, `mcp remove`)
- **Class 6.9** - Active rotation strategy (which MCPs for each type of task)
- **Class 6.10** - MCP Troubleshooting
- **Practice:** Install Filesystem + GitHub, do a real task connecting the two

---

## MODULE 7 - Final Project
*Putting it all together*

- **Class 7.1** - Setting up your complete environment (CLAUDE.md + skills + MCPs)
- **Class 7.2** - Practical project: Build a feature from scratch using all 6 pillars
- **Class 7.3** - Personal automation: creating your "AI OS" with customized skills
- **Class 7.4** - Operator Checklist: the 10 golden rules

---

## Structure Summary

| Module | Classes | Focus |
|--------|-------|------|
| 0 - Introduction | 5 | Setup |
| 1 - Shortcuts | 5 + practice | Speed ​​|
| 2 - Starter Pack | 6 + practice | Configuration |
| 3 - Workflows | 9 + practice | Execution |
| 4 - Prompts | 8 + practice | Strategy |
| 5 - Skills | 11 + practice | Scalability |
| 6 - MCPs | 10 + practice | Integration |
| 7 - Final Project | 4 | Consolidation |
| **Total** | **58 classes** | |