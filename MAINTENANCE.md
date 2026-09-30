# Profile maintenance

## Repo-side (Cursor / PR)

- [ ] Featured table matches each repo’s public README and description (no invented test counts).
- [ ] Every **Live report** URL returns HTTP 200 (or CI link for repos without Pages).
- [ ] No links to private, archived, or employer-named repos.
- [ ] README stays under 60 lines; contact is LinkedIn only (no email or phone).
- [ ] Weekly link-check workflow is green on `main` (LinkedIn may return HTTP 999 to bots; workflow accepts 200/429/999).

## UI-side (GitHub profile settings — you only)

- [ ] **Pins** (same order as README): `playwright-qa-framework`, `api-automation-restassured`, `performance-jmeter-suite`, `trashbot`, optional `PlaywrightLearning` if you showcase it.
- [ ] **Bio**, **location** (Bhopal), and **website** (e.g. primary Pages report URL) match the README headline.
- [ ] Archive or privatize old learning repos (`Git_Hub`, `git-journey`, `Prodmate`, etc.) so they do not dominate “Popular”.
- [ ] Social preview images on flagship repos (optional).
- [ ] Logged-out browser check: profile shows pins + README, no placeholders.
