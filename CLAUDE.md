# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML project with no build system, bundler, or package manager. Each HTML file is a self-contained single-file application with inline CSS and JavaScript — no external dependencies beyond Google Fonts.

## Architecture

- **test.html** — RAFINO (Retired Army Finance Organization) landing page. Static marketing/info page with responsive layout using CSS Grid and Flexbox.
- **tictactoe.html** — Tic Tac Toe game with minimax AI opponent. All game logic is vanilla JS in a single `<script>` block.

Both files follow the same pattern: single HTML file with `<style>` in `<head>` and `<script>` before `</body>`.

## Development

No build or install step. Open HTML files directly in a browser or serve via any static file server (the project lives under `/var/www/html/`).

## Git Workflow

- GitHub: `arundiundi/ClaudeCodeTest`
- Branch: `master`
- **After completing any meaningful unit of work, commit and push to GitHub.** Use clean, descriptive commit messages. Do not let work sit uncommitted — always commit and push so progress is never lost.
