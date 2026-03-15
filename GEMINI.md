# formidablae

## Project Identity

| Field | Value |
|-------|-------|
| **Name** | formidablae |
| **Type** | Developer Profile Repository |
| **Platform** | GitHub |
| **Content** | Markdown, HTML, YAML |
| **Automation** | GitHub Actions (metrics, 3D contributions) |

---

## Prime Directives

> These rules are **MANDATORY** and **MUST** be followed on **EVERY** prompt and **EVERY** change, without exception.

### 1. Profile Consistency

> This profile has a counterpart on GitLab (`bonafidae/bonafidae`). Shared content **MUST** be kept in sync.

- **Shared sections** that must remain identical across both profiles: **About Me**, **Technologies**, **Connect** (structure).
- **Platform-specific sections** (stats widgets, 3D contributions, workflows) are maintained independently.
- When modifying a shared section, note that the same change must be applied to the counterpart repository.

### 2. README.md

> The README **IS** the profile. It is the primary artifact of this repository.

- **EVERY** time changes are made to this repo, the `README.md` **MUST** be updated to reflect those changes.
- Keep content professional, accurate, and current.
- Ensure all badge URLs, image links, and external links are valid.

### 3. Read Before Write

- **ALWAYS** read existing files before modifying them.
- Understand existing content structure, badge conventions, and markdown patterns before making any changes.
- Never blindly overwrite or assume file contents.

### 4. Minimal and Focused Changes

- Only make changes that are directly requested or clearly necessary to fulfill the request.
- Do **NOT** refactor, "improve", or add content beyond what was asked.
- Do **NOT** add unnecessary sections or badges without explicit approval.

### 5. Follow Existing Patterns

- Match the existing markdown style, badge conventions, and section structure.
- Use **shields.io** for all badges — do **NOT** introduce alternative badge services.
- Do **NOT** change the section structure without explicit approval.

---

## Content Quality Requirements

### Markdown & HTML Quality

- Ensure valid markdown and HTML rendering on GitHub.
- No broken image links or dead badge URLs.
- Centered content uses `<p align="center">` consistently.

### Badge Maintenance

- All badges use shields.io `style=for-the-badge` format.
- Verify badge logos, colors, and labels are current when updating.
- When adding new technology badges, follow the existing alphabetical ordering within categories.

### Link Validation

- All external links (profile URLs, project links, social links) must be valid and current.
- GitHub stats widget URLs must use working service endpoints.

### Security

- **NEVER** hardcode tokens, API keys, or secrets in any file.
- GitHub Actions workflows use repository secrets exclusively.

---

## Git Conventions

- Use **conventional commits**: `type(scope): description`
- Types: `feat`, `fix`, `docs`, `style`, `refactor`, `chore`, `build`, `ci`
- Keep commits focused and atomic — one logical change per commit.
- Write clear commit messages that explain **why**, not just **what**.
- Do not force-push or rewrite shared history without approval.

---

## Change Checklist

On **every** change, verify:

- [ ] Content follows existing markdown patterns and badge conventions
- [ ] Shared sections match across GitHub and GitLab profile repos
- [ ] README accurately reflects the current profile
- [ ] All badge URLs and external links are valid
- [ ] No secrets or credentials in committed content
- [ ] Commit message follows conventional commits format
