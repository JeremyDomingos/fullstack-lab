# Fullstack-Lab
Fullstack-Lab is a collaborative repository for learning and practicing frontend, backend, and security development. The repo contains small projects (each with a frontend and backend), security exercises, CI/CD examples, and automation to help your team learn secure development workflows.

Goals

- Build small fullstack apps end-to-end
- Practice pull-request based development, code review, and CI
- Learn and apply security hardening and automated scanning (CodeQL, Dependabot)
- Keep changes small and reviewable; encourage each team member to open PRs

Getting started

1. Fork or clone the repository.
2. Create a feature branch: `git checkout -b feature/<short-desc>`
3. Run the project-specific README in `projects/<project>/...` for project-specific setup (each project includes a `README.md`).
4. Open a PR against `develop` (or `main` if you don't use `develop`).

Repository layout

- projects/ — each project has `frontend/` and `backend/` subfolders
- docs/ — threat models, security checklist, and architecture docs
- .github/ — PR & issue templates, CI workflows, code scanning config

Rules of engagement

- Always open PRs; no direct pushes to main
- Small, focused PRs are easier to review
- Require at least one approving review and passing CI to merge
- Use labels (good first issue, security, etc.) to signal work areas

Security

- Follow the security checklist in `docs/security-checklist.md`.
- Use the `buglab` project to practice finding and fixing vulnerabilities in a safe environment.

License

- MIT — see LICENSE file
