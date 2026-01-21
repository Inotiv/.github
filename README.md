# Inotiv Organization Public Configuration

## What is this repository?

This is a special **organization-level `.github` repository** that provides default configurations, templates, and documentation for all public repositories in the Inotiv organization.

## Why does this exist?

Instead of duplicating the same files (contributing guidelines, issue templates, security policies, etc.) across dozens of repositories, we maintain them once here. Any repository in the organization that doesn't have its own version of these files will automatically inherit them from this central location.

**Benefits:**
- **Consistency**: All repos follow the same standards and processes
- **Maintainability**: Update once, apply everywhere
- **Efficiency**: New repositories get best practices by default
- **Discoverability**: Contributors find the same familiar structure across all our projects

## What goes in this repository?

### Community Health Files (root directory)
- `CODE_OF_CONDUCT.md` - Standards for community behavior
- `CONTRIBUTING.md` - How to contribute to our projects
- `SECURITY.md` - How to report security vulnerabilities
- `SUPPORT.md` - Where to get help

These files will appear in any organization repository that doesn't have its own version.

### Issue & Pull Request Templates (`.github/` directory)
- `ISSUE_TEMPLATE/` - Templates for bug reports, feature requests, etc.
- `PULL_REQUEST_TEMPLATE.md` - Template for pull request descriptions

### Organization Profile (`profile/` directory)
- `profile/README.md` - The public-facing profile shown at https://github.com/Inotiv

### Workflow Templates (`.github/workflow-templates/` directory)
- Reusable GitHub Actions workflow templates that team members can quickly add to their repositories

### Dependabot Configuration
- `.github/dependabot.yml` - Organization-wide dependency update settings

## How to use this repository

### For Repository Maintainers
- Your repository will automatically inherit files from this repo if you don't have your own versions
- To override a default, simply add your own version of the file to your repository
- To use a workflow template, navigate to Actions → New workflow in your repo

### For Contributors
- When contributing to any Inotiv repository, check this repo for organization-wide guidelines
- If a repository doesn't have a specific policy, the ones here apply by default

## Important Notes

⚠️ **This repository is PUBLIC** - Do not commit any sensitive information, credentials, or internal documentation here. Use the `.github-private` repository for internal-only content.

## Making Changes

When updating files in this repository, remember that changes will affect all organization repositories that don't override these defaults. Consider:
1. Discussing significant changes with the team first
2. Testing templates before committing
3. Communicating updates to repository maintainers

## Questions?

If you have questions about this repository or need to add/modify organization-wide configurations, please open an issue or contact the automation team.

---

**Related Resources:**
- [GitHub Documentation: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Documentation: Sharing workflows with your organization](https://docs.github.com/en/actions/using-workflows/sharing-workflows-secrets-and-runners-with-your-organization)

