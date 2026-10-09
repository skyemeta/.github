# Contributing to Skye Meta projects

Thanks for taking the time to help. These guidelines apply to every public repository in the [Skye Meta](https://github.com/skyemeta) organization.

## Reporting a bug

Open an issue in the repository concerned. Include:

- what you did, what you expected, and what happened instead
- the package version (`npm ls @skyemeta/skyegate`, for example) and your Node.js and framework versions
- the smallest code sample that shows the problem

Never paste a license key, API key, private key or seed phrase into an issue. Replace them with placeholders.

## Security issues

Do not open a public issue. Use **Report a vulnerability** on the repository's Security tab, which reaches us privately. Each repository's `SECURITY.md` has the details.

## Suggesting a change

For anything larger than a small fix, open an issue first so we can agree on the approach before you spend time on it.

## Pull requests

1. Fork the repository and branch from `main`.
2. Keep the change focused: one fix or feature per pull request.
3. Run the project's build and tests before you open it (`npm run build`, and `npm test` where the project has tests).
4. Update the README or examples if the change affects how the package is used.
5. Describe what changed and why in the pull request.

## Licensing

By contributing, you agree that your contribution is licensed under that repository's license (MIT for every repository here today).

## What is open source, and what is not

The code in these repositories is open source under its license. The services it connects to are not: the SkyeGate license and verification service, the AgentTalk service at skyemeta.com, and InsumerAPI, which Skye Meta builds on. Using those services needs a license, credits or an API key, and is governed by the [Skye Meta Terms](https://skyemeta.com/terms/) or, for InsumerAPI, by [its own terms](https://insumermodel.com/terms-of-service/). A contribution to a repository here grants no rights in those services.

## Questions

For anything that is not a bug or a change request, email support@skyemeta.com.
