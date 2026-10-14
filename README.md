# AI in Actions

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey djc1arke!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/djc1arke/skills-ai-in-actions/issues/1)

## Running Ask AI

[GitHub Models retired on July 30, 2026](https://docs.github.com/en/github-models),
so the Ask AI workflow now uses the Copilot CLI provider of `actions/ai-inference`.
The original exercise's GitHub Models instructions no longer apply to this workflow.

Before running it, create a fine-grained personal access token for an account with
Copilot access, granting the **Copilot Requests** permission. Save it as the
`COPILOT_PAT` repository secret under **Settings → Secrets and variables → Actions**.
The built-in `GITHUB_TOKEN` is not sufficient for Copilot authentication in this
user-owned repository. The Issue Completeness workflow uses this same secret to
analyze and comment on newly opened issues. See the
[Copilot CLI authentication instructions](https://docs.github.com/en/copilot/how-tos/copilot-cli/automate-copilot-cli/automate-with-actions#authenticate).

Then run **Ask AI** manually from the **Actions** tab. The workflow installs the CLI
and writes the programming joke to the run summary without granting Copilot tools
access to the repository.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
