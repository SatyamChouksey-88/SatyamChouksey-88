# Profile maintenance

## Repo-side (Cursor / PR)

- [ ] Featured table matches each repo’s public README and description (no invented test counts).
- [ ] Every **Live report** URL returns HTTP 200 (or CI link for repos without Pages).
- [ ] No links to private, archived, or employer-named repos.
- [ ] README stays under 60 lines; contact is LinkedIn only (no email or phone).
- [ ] Weekly link-check workflow is green on `main` (LinkedIn is excluded from lychee; verify the slug manually — see UI checklist).
- [ ] After changing the featured table, run link-check on the PR branch before merge.

## UI-side (GitHub profile settings — you only)

- [ ] **Pins** (same order as README): `playwright-qa-framework`, `api-automation-restassured`, `performance-jmeter-suite`, `trashbot`, optional `PlaywrightLearning` after Pages works.
- [ ] **Bio**, **location** (Bhopal), and **website**: until a dedicated portfolio repo exists, use **https://satyamchouksey-88.github.io/playwright-qa-framework/** as the temporary website (primary live test report).
- [ ] **Company** field: your choice whether recruiters see an employer name on the profile card.
- [ ] **LinkedIn:** open https://www.linkedin.com/in/satyam-chouksey-322a8126a once after each README edit (not checked by automation).
- [ ] Archive or privatize old learning repos (`Git_Hub`, `git-journey`, `Prodmate`, etc.) so they do not dominate “Popular”.
- [ ] Social preview images on flagship repos (optional).
- [ ] Logged-out browser check: profile shows pins + README, no placeholders.
