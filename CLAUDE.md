# CLAUDE.md - AI Assistant Guidelines

This document provides guidance for AI assistants (like Claude) working with this codebase.

## Project Overview

**Project Name:** app
**Owner:** BlackRoad-OS
**Status:** Initial Development

This is a new repository in its early stages of development. The project structure and technology stack will evolve as development progresses.

## Repository Structure

```
/home/user/app/
├── .git/              # Git repository
├── CLAUDE.md          # AI assistant guidelines (this file)
└── README.md          # Project description
```

> **Note:** This structure will expand as the project develops. Update this section when new directories or significant files are added.

## Development Workflows

### Git Workflow

- **Main Branch:** `main`
- **Feature Branches:** Use descriptive branch names prefixed appropriately (e.g., `feature/`, `fix/`, `docs/`)
- **Commit Messages:** Write clear, descriptive commit messages explaining the "why" behind changes

### Getting Started

```bash
# Clone the repository
git clone <repository-url>
cd app

# Create a feature branch
git checkout -b feature/your-feature-name
```

## Code Conventions

### General Guidelines

1. **Keep it simple:** Avoid over-engineering. Make only changes that are directly requested or clearly necessary
2. **Read before modifying:** Always read existing code before suggesting modifications
3. **Security first:** Be careful not to introduce security vulnerabilities (command injection, XSS, SQL injection, etc.)
4. **Clean code:** Remove unused code rather than commenting it out

### File Organization

- Keep related files together in logical directories
- Use clear, descriptive file names
- Separate concerns appropriately

## Technology Stack

> **To be defined:** The technology stack has not been selected yet. Update this section once frameworks and tools are chosen.

### Planned/Potential Technologies

- [ ] Language: TBD
- [ ] Framework: TBD
- [ ] Database: TBD
- [ ] Testing: TBD
- [ ] Build Tools: TBD

## Commands Reference

> **Note:** Update this section as build scripts and commands are established.

### Common Commands

```bash
# Build (when configured)
# npm run build

# Test (when configured)
# npm test

# Lint (when configured)
# npm run lint

# Development server (when configured)
# npm run dev
```

## Testing

> **To be configured:** Testing framework and patterns will be documented here once established.

### Testing Guidelines

- Write tests for new features and bug fixes
- Maintain test coverage for critical paths
- Run tests before committing changes

## Configuration

### Environment Variables

> **To be defined:** Document required environment variables here once the project requires them.

```bash
# Example (update when actual variables are needed):
# DATABASE_URL=
# API_KEY=
```

### Configuration Files

> **To be added:** Configuration files will be documented here as they are created.

## Key Files and Entry Points

> **To be documented:** Update this section as the project structure develops to highlight important files.

## AI Assistant Instructions

### When Working on This Codebase

1. **Understand context first:** Read relevant files before making changes
2. **Follow existing patterns:** Match the style and conventions already in use
3. **Make minimal changes:** Only modify what's necessary to complete the task
4. **Test your changes:** Verify changes work as expected before committing
5. **Document significant changes:** Update this file and other documentation as needed

### Do's

- Read existing code before modifying it
- Follow the established coding conventions
- Write clear commit messages
- Keep changes focused and minimal
- Update documentation when adding new features or changing workflows

### Don'ts

- Don't over-engineer solutions
- Don't add features beyond what was requested
- Don't introduce security vulnerabilities
- Don't leave commented-out code
- Don't skip testing

### Handling Ambiguity

When requirements are unclear:
1. Review existing code patterns for guidance
2. Choose the simplest solution that meets the requirement
3. Document assumptions made
4. Ask for clarification if critical decisions are uncertain

## Project-Specific Notes

> **Add project-specific guidelines here as the project evolves.**

---

## Changelog

| Date | Change | Author |
|------|--------|--------|
| 2026-01-27 | Initial CLAUDE.md created | AI Assistant |

---

*This document should be updated as the project evolves to reflect current practices and conventions.*
