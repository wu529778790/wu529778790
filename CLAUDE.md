# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **GitHub profile repository** (wu529778790) that serves as a personal landing page. It is a documentation-only repository containing:

- `README.md` - Personal profile page with project listings, tech stack, and contact information (in Chinese)
- `.github/workflows/snake.yml` - GitHub Action that generates a snake contribution graph animation
- `.claude/settings.local.json` - Claude Code local settings

## Repository Purpose

This repository does not contain application code. It is used to:
1. Display a personalized GitHub profile page
2. Showcase the user's AI agent projects (TGAgent, open-im) as primary focus
3. Highlight other notable projects (i18n-automatically, VibeDesk, newshub, etc.)
4. Generate an animated snake contribution graph via GitHub Actions

## Content Structure

The README.md contains:
- Personal branding and introduction (in Chinese)
- GitHub statistics badges and contribution visualization
- **AI Agent projects** (TGAgent, open-im) - primary focus
- Project portfolio table with links to external repositories and services
- Technology stack badges
- Contact information

## Development Notes

- There are no build, test, or lint commands as this is a documentation-only repository
- Changes to this repository are typically documentation updates to the README.md
- The snake.yml workflow runs daily via cron schedule to update the contribution graph
