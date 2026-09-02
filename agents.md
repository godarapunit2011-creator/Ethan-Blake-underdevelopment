# ETHAN — AGENT INSTRUCTIONS

## Project

Ethan is a personal AI assistant currently being developed as a prototype.

## Owner

Punit is the final decision-maker for the project.

## AI Roles

### GLM-5.3 / ZCode
Primary implementation agent.

### Claude
Principal architect and code reviewer.

### Manus
Research and investigation agent.

### ChatGPT
Strategic and product advisor.

## Development Rules

1. Read this file before modifying the repository.

2. Inspect the existing code before making assumptions.

3. Do not modify unrelated files.

4. Do not introduce paid services without approval.

5. Prefer simple solutions during the prototype stage.

6. Do not expose secrets.

7. Never commit API keys, passwords, tokens, or .env files.

8. Do not directly modify the main branch.

9. Use feature branches for development.

10. Run relevant tests before declaring a task complete.

11. Never claim something works unless it was actually tested.

12. Document important architectural decisions.

13. Preserve working functionality unless there is a specific reason to change it.

14. Do not add unnecessary dependencies.

15. Ask for clarification when an important requirement is ambiguous.

## Git Workflow

main = stable code.

Feature work should happen on separate branches.

Typical workflow:

feature branch
→ implementation
→ testing
→ pull request
→ review
→ approval
→ merge into main

## Philosophy

Build the smallest reliable system that proves the idea.

Do not optimize prematurely.

Do not over-engineer the prototype.

Prefer maintainable and understandable code over impressive complexity.
