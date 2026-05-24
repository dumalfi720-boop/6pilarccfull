# TODO - 6 Pillars of Claude Code (Full Edition 2026)

**Repo:** git@github.com:inematds/6pilarccfull.git
**Pages:** https://inematds.github.io/6pilarccfull/
**Skill:** course-format (ALWAYS use when creating HTML pages)
**Last updated:** 2026-03-08

---

## PHASE 0 - INFRASTRUCTURE

- [ ] Initialize git (`git init`)
- [ ] Add remote (`git remote add origin git@github.com:inematds/6pilarccfull.git`)
- [ ] Initial commit (doc/ + index.html + modulo-1-1.html)
- [ ] Push to main
- [ ] Enable GitHub Pages (Settings > Pages > Source: main) -- MANUAL

---

## PHASE 1 - TRACK 1: Shortcuts and Fundamentals (Emerald)

### Trail Page
- [ ]`curso/trilha1/index.html`-- Hub with 8 module cards, 48 expandable topics, 8 modals with iframe
  - NOTE: large file, created in parts (first skeleton + cards, then topics per module)

### Modules
- [x]`curso/trilha1/modulo-1-1.html`-- Introduction to Claude Code (6 topics + exercise)
- [ ]`curso/trilha1/modulo-1-2.html`-- Essential Terminal Commands
  - Topics: /help, /clear, /compact, /cost, /status, Combining commands
  - Exercise: Use /help, /clear, /compact, /cost in a real session
- [ ]`curso/trilha1/modulo-1-3.html`-- Native Slash Commands
  - Topics: /commit, /review, /pr, /init, /doctor, Full flow
  - Exercise: Run /commit, /review, /pr in a test repo
- [ ]`curso/trilha1/modulo-1-4.html`-- Command Line Flags
  - Topics: -p (prompt), --model, --resume, --allowedTools, --output-format, Combining flags
  - Exercise: Create 3 commands with -p, --model, --resume
- [ ]`curso/trilha1/modulo-1-5.html`-- Data Pipe and Unix Integration
  - Topics: cat | claude, Logs pipe, Multiple pipes, Redirection, Unix philosophy, Advanced pipelines
  - Exercise: Create pipeline cat + grep + claude -p
- [ ]`curso/trilha1/modulo-1-6.html`-- Keyboard Shortcuts and Navigation
  - Topics: Session navigation, Prompt editing, Execution control, History, Multi-line, Custom shortcuts
  - Exercise: Practice all shortcuts in a timed session
- [ ]`curso/trilha1/modulo-1-7.html`-- Creating Aliases and Scripts
  - Topics: What are aliases, Basic aliases, Compound aliases, Bash scripts, Shell functions, .zshrc organization
  - Exercise: Create 5 aliases in .zshrc/.bashrc
- [ ]`curso/trilha1/modulo-1-8.html`-- Headless Mode and CLI Automation
  - Topics: What is headless, claude -p basico, --output-format json, --allowedTools, Loop bash, CI/CD intro
  - Exercise: Create bash script that uses claude -p in a loop

### Post-track 1
- [ ] Commit and push track 1 complete
- [ ] Test all links and modals

---

## PHASE 2 - TRACK 2: CLAUDE.md and Memoria (Blue)

### Structure
- [ ]`curso/trilha2/`-- Create directory
- [ ]`curso/trilha2/index.html`-- Hub with 8 cards

### Modules
- [ ]`curso/trilha2/modulo-2-1.html`-- What is CLAUDE.md and Why Does It Exist
  - Exercise: Explore CLAUDE.md from 3 open source projects
- [ ]`curso/trilha2/modulo-2-2.html`-- Anatomy of CLAUDE.md Perfect
  - Exercise: Create complete CLAUDE.md for personal project
- [ ]`curso/trilha2/modulo-2-3.html`-- Scopes and Memory Hierarchy
  - Exercise: Create global CLAUDE.md + project + subdirectory
- [ ]`curso/trilha2/modulo-2-4.html`-- Modular Rules (.claude/rules/)
  - Exercise: Create 3 modular rules files
- [ ]`curso/trilha2/modulo-2-5.html`-- Auto-Memory and Persistence
  - Exercise: Configure auto-memory and check what Claude saves
- [ ]`curso/trilha2/modulo-2-6.html`-- /init - Automatic Generation
  - Exercise: Run /init in 3 projects and compare results
- [ ]`curso/trilha2/modulo-2-7.html`-- Templates by Stack (Next.js, Python, Go)
  - Exercise: Create CLAUDE.md template for 2 different stacks
- [ ]`curso/trilha2/modulo-2-8.html`-- Good Practices and Optimization (< 200 lines)
  - Exercise: Audit and optimize existing CLAUDE.md

### Post-track 2
- [ ] Update index.html (T2 available, remove opacity-60)
- [ ] Update track nav1 (working T2 link)
- [ ] Commit and push

---

## PHASE 3 - TRACK 3: Workflows (Purple)

### Structure
- [ ]`curso/trilha3/`-- Create directory
- [ ]`curso/trilha3/index.html`-- Hub with 9 cards

### Modules
- [ ]`curso/trilha3/modulo-3-1.html`-- Fix a Bug
  - Exercise: Reproduce and fix real bug in an example repo
- [ ]`curso/trilha3/modulo-3-2.html`-- Build New Feature
  - Exercise: Implement complete feature with Plan Mode
- [ ]`curso/trilha3/modulo-3-3.html`-- Refactor Code
  - Exercise: Refactor module while keeping tests green
- [ ]`curso/trilha3/modulo-3-4.html`-- Understand New Codebase
  - Exercise: Clone unknown repo and map architecture
- [ ]`curso/trilha3/modulo-3-5.html`-- Write Tests
  - Exercise: Increase coverage from 40% to 80% in a project
- [ ]`curso/trilha3/modulo-3-6.html`-- Code Review and Pull Request
  - Exercise: Make review + complete PR with /review and /pr
- [ ]`curso/trilha3/modulo-3-7.html`-- Debug with Logs and Errors
  - Exercise: Diagnose 3 different errors via log pipe
- [ ]`curso/trilha3/modulo-3-8.html`-- Multi-file migration
  - Exercise: Run rename/refactor on 10+ files
- [ ]`curso/trilha3/modulo-3-9.html`-- Agent Teams and Loop Agentico (2026)
  - Exercise: Configure agent teams with CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS

### Post-track 3
- [ ] Update index.html (T3 available)
- [ ] Update navs from previous tracks
- [ ] Commit and push

---

## PHASE 4 - TRACK 4: Strategic Prompts (Amber)

### Structure
- [ ]`curso/trilha4/`-- Create directory
- [ ]`curso/trilha4/index.html`-- Hub with 8 cards

### Modules
- [ ]`curso/trilha4/modulo-4-1.html`-- The 5 Daily Prompts (Daily Drivers)
  - Exercise: Use each of the 5 prompts in a real task
- [ ]`curso/trilha4/modulo-4-2.html`-- Getting Started and Kickoff prompts
  - Exercise: Start a new project using 95% Confidence + Kickoff
- [ ]`curso/trilha4/modulo-4-3.html`-- Building and TDD prompts
  - Exercise: Build feature using Build With Tests prompt
- [ ]`curso/trilha4/modulo-4-4.html`-- Debugging and Log Analysis prompts
  - Exercise: Diagnose 3 bugs using structured prompts
- [ ]`curso/trilha4/modulo-4-5.html`-- Code Quality and Auditing Prompts
  - Exercise: Run Brutal Audit in your own code and correct
- [ ]`curso/trilha4/modulo-4-6.html`-- Architecture and API Design Prompts
  - Exercise: Design complete REST API using architectural prompts
- [ ]`curso/trilha4/modulo-4-7.html`-- Outcome Delegation (Tecnica 2026)
  - Exercise: Rewrite 5 imperative prompts as outcome delegation
- [ ]`curso/trilha4/modulo-4-8.html`-- Verification and Self-Validating Prompts
  - Exercise: Create 3 prompts with built-in verification criteria

### Post-track 4
- [ ] Update index.html (T4 available)
- [ ] Update navs from previous tracks
- [ ] Commit and push

---

## PHASE 5 - TRACK 5: Skills and Plugins (Teal)

### Structure
- [ ]`curso/trilha5/`-- Create directory
- [ ]`curso/trilha5/index.html`-- Hub with 8 cards

### Modules
- [ ]`curso/trilha5/modulo-5-1.html`-- What are Skills and How They Work
  - Exercise: Create first skill following the standard template
- [ ]`curso/trilha5/modulo-5-2.html`-- Anatomy of a Skill (Full Template)
  - Exercise: Build skill with Purpose, Steps, Quality Checks
- [ ]`curso/trilha5/modulo-5-3.html`-- Practical Skills: Screenshot to Website
  - Exercise: Implement and test the screenshot skill
- [ ]`curso/trilha5/modulo-5-4.html`-- Practical Skills: Lead Research and Code Review
  - Exercise: Implement 2 productivity skills
- [ ]`curso/trilha5/modulo-5-5.html`-- Where to Find Ready Skills
  - Exercise: Audit 10 awesome-claude-code skills
- [ ]`curso/trilha5/modulo-5-6.html`-- Plugins: Architecture and Ecosystem (9000+)
  - Exercise: Install and configure 2 marketplace plugins
- [ ]`curso/trilha5/modulo-5-7.html`-- Hooks: 12 Lifecycle Events
  - Exercise: Create PreToolUse + PostToolUse hook
- [ ]`curso/trilha5/modulo-5-8.html`-- Subagents and /simplify /batch (2026)
  - Exercise: Use /simplify in a project and analyze results

### Post-track 5
- [ ] Update index.html (T5 available)
- [ ] Update navs from previous tracks
- [ ] Commit and push

---

## PHASE 6 - TRACK 6: MCPs and Automation (Rose)

### Structure
- [ ]`curso/trilha6/`-- Create directory
- [ ]`curso/trilha6/index.html`-- Hub with 8 cards

### Modules
- [ ]`curso/trilha6/modulo-6-1.html`-- What are MCPs and Token Tax
  - Exercise: Measuring context overhead with 0, 2 and 5 MCPs
- [ ]`curso/trilha6/modulo-6-2.html`-- MCP Filesystem and GitHub
  - Exercise: Install both and run cross-repo task
- [ ]`curso/trilha6/modulo-6-3.html`-- MCP Browser and Chrome DevTools
  - Exercise: Take screenshot + scrape web page
- [ ]`curso/trilha6/modulo-6-4.html`-- MCP Database (Postgres/Supabase)
  - Exercise: Connect bank, run queries, check schema
- [ ]`curso/trilha6/modulo-6-5.html`-- MCP Google Sheets and Others
  - Exercise: Export data to spreadsheet via MCP
- [ ]`curso/trilha6/modulo-6-6.html`-- Active Rotation Strategy
  - Exercise: Create personal rotation table by type of task
- [ ]`curso/trilha6/modulo-6-7.html`-- CI/CD Pipelines with Claude Headless
  - Exercise: Create GitHub Action with claude -p and --allowedTools
- [ ]`curso/trilha6/modulo-6-8.html`-- Claude Cowork and Desktop Agent (2026)
  - Exercise: Explore Cowork: scheduling, connectors, skills

### Post-track 6
- [ ] Update index.html (all tracks available)
- [ ] Update navs of all tracks (cross links)
- [ ] Commit and push

---

## PHASE 7 - FINALIZATION

- [ ] General link review (no href="#" remaining)
- [ ] Test dark/light mode on all pages
- [ ] Test mobile responsiveness on all pages
- [ ] Check all modals and iframes
- [ ] Run checklist CHECKLIST_REVISAO.md on all pages
- [ ] Add course to portal (duclub) -- courses.ts + Portal.tsx
- [ ] Update report_situacao.md with final status
- [ ] Final push and confirm active GitHub Pages

---

## EXECUTION RULES

1. **Always use skill`formato-curso`** when creating any HTML page
2. **6 topics per module** with "What is / Why to learn / Key concepts" sections
3. **Numbered circles** (1-6), never arrows
4. **justify-start buttons** (left), never centered
5. **Colors per trail:** T1 Emerald, T2 Blue, T3 Purple, T4 Amber, T5 Teal, T6 Rose
6. **Primary Yellow:** #FACC15 | **duclub links:** text-sky-400
7. **Dark/light mode mandatory** with toggle and localStorage
8. **Modals with iframe** pointing to modulo-X-X.html
9. **Practical exercise** in each module with step-by-step instructions and checklist
10. **Commit per track** (not per individual module)
11. **Trilha1/index.html is big** -- create skeleton first, then fill topics in blocks

---

## ACCOUNTANTS

| Item | Total | Done | Missing |
|------|-------|-------|-------|
| HTML Pages | 62 | 2 | 60 |
| Index trail | 6 | 0 | 6 |
| Modules | 49 | 1 | 48 |
| Landing page | 1 | 1 | 0 |
| Topics | ~294 | 6 | ~288 |
| Exercises | 49 | 1 | 48 |
| Commits | ~7 | 0 | ~7 |

---

## REFERENCE DOCUMENTS

| Archive | What is it for |
|---------|--------------------------|
|`doc/plano_curso_full.md`| Complete plan with all modules and exercises |
|`doc/relatorio_situacao.md`| Current project status |
|`doc/6_pilares_claude_code.md`| Base content of the 6 pillars |
|`doc/9_claude_code_workflows.md`| 9 detailed workflows |
|`doc/claude_ai_skills.md`| Skills and extensibility |
|`doc/claude_starter_pack.md`| CLAUDE.md and configuration |
|`doc/connecting_claude.md`| MCPs and connections |
|`doc/executive_prompt_dashboard.md`| Strategic prompts |
|`~/.claude/skills/formato-curso/references/MASTER_COMPLETO.md`| Master HTML Template |
|`~/.claude/skills/formato-curso/references/CHECKLIST_REVISAO.md`| Quality checklist |