# Act 1 — The Karpathy CLAUDE.md File: Fix the Brain

This project demonstrates how a simple `CLAUDE.md` file can influence how Claude Code approaches software development. Instead of only telling Claude **what to build**, the file provides rules for **how it should work**.

The project compares Claude Code with and without Karpathy-inspired `CLAUDE.md` instructions using the same project and identical test prompts.

### Key Features

* Before-and-after Claude Code comparison.
* Four core principles:

  * Think Before Coding
  * Simplicity First
  * Surgical Changes
  * Goal-Driven Execution
* Identical prompts for fair testing.
* Clarification before implementation.
* Reuse of existing code and CSS variables.
* Minimal and targeted code changes.
* Task verification and testing.
* Real-world bug fixing.
* Automated HTML comparison reports.
* Side-by-side result analysis.

### Workflow

1. Create two identical copies of the project.
2. Keep one project completely untouched.
3. Add the Karpathy-inspired `CLAUDE.md` to the second project.
4. Run the same four tests in both projects.
5. Compare Claude's decisions, implementation, changes, and verification.
6. Generate `report.html` for each session.
7. Compare the results side by side.

### The Four Tests

1. **Notification System** — tests whether Claude asks for clarification.
2. **Dark Mode** — tests whether Claude chooses a simple existing solution.
3. **Button Color** — tests whether Claude makes only the necessary changes.
4. **Mobile Menu Bug** — tests whether Claude finds, fixes, and verifies the issue.

The goal is to demonstrate how project-level instructions can steer Claude Code toward **better decisions, simpler implementations, smaller changes, and stronger verification**, forming the foundation for the larger Act 1 → Act 2 → Act 3 → Act 4 AI development system.
