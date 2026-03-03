# AGENTS.md — Strict Rules for AI Agents

**Purpose**: This file contains STRICT, ENFORCEABLE rules for AI agents working on Dissect project.

---

## RULE 1: Read Rules First — MANDATORY

### Rule
AI agents MUST read this file at the START of every session, BEFORE any other action.

---

## RULE 2: Mom Test Gate — MANDATORY

### Rule
Project CANNOT exceed 10% progress until Mom Test is COMPLETE.

---

## RULE 3: Progress Tracking — MANDATORY

### Rule
Every project MUST track progress in `SESSION_SUMMARY.md` with PESSIMISTIC estimates.

---

## RULE 4: Session Summary — MANDATORY

### Rule
Every session MUST update `SESSION_SUMMARY.md` with BOTH English and French versions.

---

## RULE 5: Testing Requirements — MANDATORY

### Rule
All code MUST have minimum 60% test coverage. No exceptions.

---

## RULE 6: Security Scanning — MANDATORY

### Rule
All code MUST pass security scans before commit.

---

## RULE 7: No Silent Failures — MANDATORY

### Rule
If any step fails, the agent MUST report it and retry.

---

## RULE 8: Critical Thinking — MANDATORY

### Rule
AI agents are CO-ENGINEERS, not typists. Push back on bad ideas.

---

## RULE 9: No Emojis Anywhere — MANDATORY

### Rule
Emojis are FORBIDDEN in ALL project files, code, comments, documentation. No exceptions.

---

## RULE 10: File Protection — MANDATORY

### Rule
Certain files MUST be in `.gitignore` and NEVER committed publicly.

---

## RULE 11: Sync Rule — MANDATORY

### Rule
When rules are updated in ANY project, SYNC to `~/Documents/kuro-rules` (master copy).

---

## RULE 12: Roadmap Adherence — MANDATORY

### Rule
Every project MUST have a roadmap file (PLAN.md or ROADMAP.md) and all development MUST follow it.

---

## RULE 13: Roadmap Duration — MANDATORY

### Rule
Every roadmap MUST have a minimum duration of **one month** with clearly defined phases.

---

## RULE 14: Periodic Validation — MANDATORY

### Rule
At progress milestones (25%, 50%, 75%, 90%, 95%), the product MUST be validated through Mom Test and Marketing Test before continuing.

---

## RULE 15: Rule Synchronization — MANDATORY

### Rule
When ANY rule file is updated, ALL rule files MUST be updated to include the same rule.

---

## RULE 34: Repo Hygiene and Unused File Cleanup -- MANDATORY

### Rule
AI agents MUST proactively identify and remove unused, outdated, or obsolete files, folders, and residues from the repository before and during any coding session.

### What to Check For
| Category | Examples |
|----------|----------|
| **Dated Files** | Old log files, timestamped backups, deprecated feature files |
| **Unused Files** | Dead code, unused modules, orphaned test files |
| **Old Residues** | Temporary files, cache folders, build artifacts (.pyc, __pycache__) |
| **Unnecessary Folders** | Empty directories, duplicate folders, obsolete feature folders |

### Verification Checklist
```
BEFORE starting any coding session:
  1. SCAN: List all files in the repository
  2. IDENTIFY: Look for files with dates in names, old versions, deprecated features
  3. VERIFY: Check each file is still used/necessary
  4. REPORT: List any unused/outdated items to user
  5. DELETE: Remove only after user confirmation
```

---

## RULE 35: Cross-Project Session Summary Repository -- MANDATORY

### Rule
All session summaries from ALL projects MUST be consolidated in a central location for easy reference and cross-project intelligence.

### Repository Location
```
~/Documents/docs/
```

### Structure
```
~/Documents/docs/
├── session_summaries/
│   ├── project-name-1/
│   │   ├── 2025-01-15.md
│   │   └── ...
│   └── README.md
└── SYNC_LOG.md
```

### Requirements
1. **Every session** from every project MUST create a summary in this central folder
2. **Naming convention**: `YYYY-MM-DD-project-name.md`
3. **Bilingual**: Each summary must include both English and French sections
4. **Central Sync**: Copy session summaries here after each session ends

---

## ENFORCEMENT SUMMARY

| Rule | Consequence of Violation |
|------|--------------------------|
| Rule 1 (Read First) | STOP and read rules |
| Rule 2 (Mom Test) | STOP implementation, complete deliverables |
| Rule 3 (Progress) | Recalculate with pessimistic estimate |
| Rule 4 (Session Summary) | Create summary immediately |
| Rule 5 (Testing) | STOP features, write tests |
| Rule 6 (Security) | STOP commit, fix vulnerabilities |
| Rule 7 (No Silent Failures) | Report and retry |
| Rule 8 (Critical Thinking) | Apply questions retroactively |
| Rule 9 (No Emojis) | REMOVE emojis immediately |
| Rule 10 (File Protection) | Remove from git, add to .gitignore |
| Rule 11 (Sync) | Sync to kuro-rules immediately |
| Rule 12 (Roadmap) | STOP and create PLAN.md |
| Rule 13 (Roadmap Duration) | STOP and expand plan if < 1 month |
| Rule 14 (Periodic Validation) | STOP and conduct validation |
| Rule 15 (Rule Sync) | SYNC immediately |
| Rule 34 (Repo Hygiene) | LIST and DELETE unused files |
| Rule 35 (Central Summaries) | COPY to ~/Documents/docs/ |

---

## FINAL NOTE

These rules are NON-NEGOTIABLE. They exist to ensure:
- User problems are validated before building solutions
- Code quality meets professional standards
- Security is never compromised
- Progress is accurately tracked
- Knowledge persists across sessions