# Testing Agents Repository

A curated collection of intelligent agents, coding instructions, and reusable skills designed to enhance development workflows and maintain consistent coding standards across multiple technologies.

## Overview

This repository serves as a centralized knowledge base containing:

- **Agents**: Specialized autonomous agents for specific development tasks
- **Instructions**: Coding guidelines and best practices for various languages and frameworks
- **Skills**: Reusable competencies that agents can leverage for common operations

## Repository Structure

```
.github/
├── agents/              # Autonomous agent definitions
├── instructions/        # Language and framework coding standards
└── skills/              # Reusable agent capabilities
```

## Agents

Autonomous agents designed to handle specific development workflows:

### Available Agents

- **Task Planner** (`agents/task-planner.agent.md`)  
  A comprehensive task planning agent that creates actionable implementation plans based on verified research. Produces plan checklists, implementation details, and prompts for systematic project execution.

- **PRD Agent** (`agents/prd.agent.md`)  
  Assists with product requirements documentation and specification planning.

## Instructions

Detailed coding guidelines and best practices for maintaining consistency across the codebase:

### Language & Framework Instructions

- **TypeScript 5 / ES2022** (`typescript-5-es2022.instructions.md`)  
  TypeScript 5.x development standards targeting ES2022 output

- **Vue.js 3** (`vuejs3.instructions.md`)  
  Vue 3 development standards with Composition API and TypeScript best practices

- **Python** (`python.instructions.md`)  
  Python coding conventions and guidelines

- **Go** (`go.instructions.md`)  
  Idiomatic Go practices following community standards

- **PowerShell** (`powershell.instructions.md`)  
  PowerShell cmdlet and scripting best practices based on Microsoft guidelines

- **SQL & Stored Procedures** (`sql-sp-generation.instructions.md`)  
  Guidelines for generating SQL statements and stored procedures

### Workflow Instructions

- **Git Workflow** (`git-workflow.instructions.md`)  
  Git branching and commit workflow for implementation tasks

- **Tailwind CSS v4 + Vite** (`tailwind-v4-vite.instructions.md`)  
  Installation and configuration guide for Tailwind CSS v4+ with the official @tailwindcss/vite plugin in Vite projects

## Skills

Reusable, domain-specific competencies available to agents:

### Available Skills

- **git-commit** (`skills/git-commit/SKILL.md`)  
  Execute git commits with conventional commit message analysis, intelligent staging, and automated message generation. Supports auto-detection of commit type/scope, diff analysis, and interactive commit workflows.

## Usage

These resources are designed to be referenced and utilized in development workflows:

1. **For Agents**: Reference agent files to understand specialized workflows and task planning methodologies
2. **For Instructions**: Apply coding guidelines when working in specific languages or frameworks
3. **For Skills**: Leverage reusable capabilities to streamline common development operations

## Contributing

When adding new agents, instructions, or skills:

- Follow the established naming conventions
- Include comprehensive documentation with examples
- Store files in the appropriate subdirectories under `.github/`
- Update this README with descriptions of new additions
