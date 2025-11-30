<!--
Version change: 1.0.0 -> 1.1.0
List of modified principles:
  - I. Test-Driven Development (TDD) (refined)
  - III. Code Clarity (refined)
  - New: VII. Code Formatting and Linting
  - New: VIII. Robust Error Handling
  - New: IX. Comprehensive Documentation
  - New: X. Data Structure Standards
Added sections: None
Removed sections:
  - Quality Requirements
Templates requiring updates:
  - .specify/templates/plan-template.md ⚠ pending
  - .specify/templates/spec-template.md ⚠ pending
  - .specify/templates/tasks-template.md ⚠ pending
  - .gemini/commands/sp.adr.toml ⚠ pending
  - .gemini/commands/sp.analyze.toml ⚠ pending
  - .gemini/commands/sp.checklist.toml ⚠ pending
  - .gemini/commands/sp.clarify.toml ⚠ pending
  - .gemini/commands/sp.constitution.toml ⚠ pending
  - .gemini/commands/sp.git.commit_pr.toml ⚠ pending
  - .gemini/commands/sp.implement.toml ⚠ pending
  - .gemini/commands/sp.phr.toml ⚠ pending
  - .gemini/commands/sp.plan.toml ⚠ pending
  - .gemini/commands/sp.specify.toml ⚠ pending
  - .gemini/commands/sp.tasks.toml ⚠ pending
Follow-up TODOs: None
-->
# hellow_nowsh Constitution

## Core Principles

### I. Test-Driven Development (TDD)
All new features and bug fixes must follow a Test-Driven Development (TDD) approach. Tests must be written before implementation code, pass reliably, and maintain at least 80% code coverage.

### II. Python Typing and Version
All Python code must use Python 3.12 or newer. Type hints must be used consistently throughout the codebase for improved readability and maintainability.

### III. Code Clarity
Code must be clean, well-structured, and easy to read and understand by other developers. Prioritize simplicity, maintainability, and adherence to established design patterns.

### IV. Architectural Decision Records (ADRs)
Important architectural decisions must be documented using Architectural Decision Records (ADRs) to capture context, rationale, and consequences.

### V. Object-Oriented Programming (OOP)
Adhere to essential Object-Oriented Programming (OOP) principles (e.g., Encapsulation, Inheritance, Polymorphism, Abstraction) to ensure modular, flexible, and scalable code.

### VI. Version Control
All project files must be tracked and managed using Git for version control. Regular commits with descriptive messages are required.

### VII. Code Formatting and Linting
All code must adhere to consistent formatting standards, enforced by automated tools like Black. Linting tools (e.g., Ruff) must be used to identify and fix code quality issues, ensuring no linting errors or warnings are present.

### VIII. Robust Error Handling
Errors must be handled gracefully across the application. Implement clear exception handling strategies, log errors effectively, and provide informative messages to users or calling systems. Avoid broad exception catches.

### IX. Comprehensive Documentation
All modules, classes, functions, and complex logic blocks must be documented with clear, concise, and up-to-date docstrings. External-facing APIs and significant architectural components require comprehensive READMEs or dedicated documentation.

### X. Data Structure Standards
For structured data, `dataclasses` must be used in Python to define clear, concise, and type-hinted data models, enhancing readability and reducing boilerplate.

## Technical Stack

- Python 3.12+
- uv package manager
- Black (code formatter)
- Ruff (linter)

## Governance
Constitution supersedes all other practices; Amendments require documentation, approval, and a migration plan. All Pull Requests (PRs)/code reviews must verify compliance; Complexity must be justified.

**Version**: 1.1.0 | **Ratified**: 2025-11-29 | **Last Amended**: 2025-11-30