## Git Commit Guidelines

- Follow conventional commit format (feat:, fix:, docs:, etc.)
- Keep the subject line under 72 characters
- Use the `Assisted-By:` trailer (not `Generated-By:`) — this repo contains
  human-originated code with AI-assisted improvements
- Do NOT include `Co-Authored-By` — the `Assisted-By` trailer is sufficient
- Always include: Signed-off-by: Ciro Iriarte <ciro.iriarte+software@gmail.com>

## Coding standards

- Versioning should follow https://semver.org
- Use all the Bash available feature as much as possible before introducing external dependencies
- Documentation must always follow code changes
- Each script should have its own version
- Bundle/Repo should have a version and release at GitHub
- Version bumping for the repository shouldn't be automatic but created on demand.

