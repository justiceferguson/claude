# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is Justice's personal Claude Code workspace at `C:\Users\jferg\claude`. It serves as a general-purpose project directory where new projects and scripts are developed and version-controlled via GitHub (`https://github.com/justiceferguson/claude`).

## Git Workflow

After completing any meaningful unit of work — new files, edits, fixes, or structural changes — always:
1. Stage the relevant files
2. Commit with a clear, descriptive message explaining what changed and why
3. Push to GitHub immediately (`git push`)

Never leave work uncommitted. Every session should end with a clean working tree and all changes pushed to `https://github.com/justiceferguson/claude`. This ensures no work is ever lost and the full history is always recoverable.

- The `.claude/` directory (Claude internal memory and config) is intentionally excluded from version control via `.gitignore`.

## Structure

- `context/` — directory for storing context files, notes, or reference material used across sessions.
