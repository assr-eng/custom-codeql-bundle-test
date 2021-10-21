<h1 align="center">Introduction to GitHub Advanced Security</h1>
<h5 align="center">Content created by @rvermeulen</h3>
<h5 align="center">Presented by Professional Services Advanced Security Team</h3>

<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a>
</p>

> `octo-gallery` is a fictitious web application that can be used to introduce GitHub Advanced Security.

## :mega: Prerequisites

To participate in the workshop you need a GitHub account and need to be invited to the workshop organization [advanced-security](https://github.com/advanced-security). If your repository hasn't been created in the organization by the AdvSec services team, there are two ways to push a copy of this repository:

1. Create a new repository and push a copy of the `octo-gallery` repository.

```bash
git clone https://github.com/advanced-security/octo-gallery.git
cd octo-gallery
git remote set-url origin https://github.com/advanced-security/<your project>.git
```

2. Use the template functionality to create a new repository from `octo-gallery`.

```
https://github.com/advanced-security/octo-gallery/generate
```

## :books: Resources
- [About code scanning](https://docs.github.com/en/github/finding-security-vulnerabilities-and-errors-in-your-code/about-code-scanning)
- [About dependency scanning](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)
- [About secret scanning](https://docs.github.com/en/github/administering-a-repository/about-secret-scanning)
- [Action events that trigger workflows](https://docs.github.com/en/free-pro-team@latest/actions/reference/events-that-trigger-workflows)
- [Configuring builds for compiled languages](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-the-codeql-workflow-for-compiled-languages)
- [Configuring code scanning](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning)
- [Configuring notifications for dependabot alerts](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/configuring-notifications-for-vulnerable-dependencies#configuring-notifications-for-dependabot-alerts)
- [Customizing dependency updates](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/customizing-dependency-updates)
- [Dependency update configuration options](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/configuration-options-for-dependency-updates)
- [Filter pattern cheat sheet](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet)
- [Running additional queries](
https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/configuring-code-scanning#running-additional-queries)
- [Troubleshooting code scanning workflow](https://docs.github.com/en/free-pro-team@latest/github/finding-security-vulnerabilities-and-errors-in-your-code/troubleshooting-the-codeql-workflow)
- [Code scanning API](https://docs.github.com/en/free-pro-team@latest/rest/reference/code-scanning)
- [GraphQL API](https://docs.github.com/en/free-pro-team@latest/graphql)
  - [RepositoryVulnerabilityAlert](https://docs.github.com/en/free-pro-team@latest/graphql/reference/objects#repositoryvulnerabilityalert)
- [REST API](https://docs.github.com/en/free-pro-team@latest/rest)
  - [Secret scanning API](https://docs.github.com/en/free-pro-team@latest/rest/reference/secret-scanning)
