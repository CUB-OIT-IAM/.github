# Organization Default Configuration (`.github`)

This repository holds organization-wide default community health files, issue templates, and pull request templates for **UCB-OIT-IAM**.

## How Inheritance Works
- **Automatic Fallback:** Any repository in this organization without its own version of these files will automatically inherit the defaults defined here.
- **Local Overrides:** Creating a local version of a file (e.g., `.github/PULL_REQUEST_TEMPLATE.md` or `CONTRIBUTING.md`) in an individual repository completely overrides the organization default.
- **Issue Templates:** If a repository defines its own `.github/ISSUE_TEMPLATE/` folder, all organization-level issue templates are ignored for that repository.

## Updating Defaults
Changes to this repository affect all repositories across the organization. Please open an issue or pull request for review by DEVs.

