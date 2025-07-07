# Advance# Mini Project - Advanced GitHub Actions and Best Practices (Local Setup)

## Project Overview
This project automates a CI pipeline for a Node.js application using modular, optimized, and secure GitHub Actions workflows. It uses build matrices across Node.js versions 12.x, 14.x, and 16.x, caches dependencies, and secures secrets. Executed on WSL Ubuntu with VS Code and Git Bash.

## Setup
- Initiated on Jul 07, 2025, 12:07 PM WAT.
- Used WSL Ubuntu, VS Code, and Git Bash in `C:\Users\Abraham\Documents\Workspace\Advanced_GitHub_Actions`.

## Execution Steps
1. **Set Up Node.js Application**:
   - Initialized Node.js project, installed Express.js, Jest, Supertest, and ESLint, and created `index.js` with `/health` endpoint.
   - Added tests in `__tests__/app.test.js` and configured `.eslintrc.json`.
   - [Screenshot: `nodejs_npm_version_local.png` - Shows Node.js and npm versions.]
   - [Screenshot: `npm_install_output_local.png` - Shows dependency installation.]
   - [Screenshot: `npm_test_output_local.png` - Shows test output.]
   - [Screenshot: `eslint_output_local.png` - Shows ESLint output.]
   - [Screenshot: `nodejs_app_output_local.png` - Shows app output.]
2. **Create Modular GitHub Actions Workflows**:
   - Added `.github/workflows/build.yml` and `test.yml` with build matrix and caching.
   - Secured secrets with GitHub Secrets.
   - Pushed to `https://github.com/westgrin/advanced-github-actions`.
   - [Screenshot: `github_repo_files_local.png` - Shows repository files.]
   - [Screenshot: `github_secrets_config_local.png` - Shows secrets setup.]
   - [Screenshot: `github_actions_run_local.png` - Shows workflow runs.]
3. **Side Hustle Task**:
   - Added `lint` job for pull requests and tested with a PR.
   - [Screenshot: `github_actions_lint_run_local.png` - Shows lint job run.]

## Learning Summary
This project advanced my GitHub Actions expertise, focusing on modular workflows, performance optimization with caching, and secure secret management. The side hustle task reinforced conditional execution, aligning with my DevOps goals (June 16, 2025) for scalable automation.

## Tools Used
- **WSL Ubuntu Terminal**: For Node.js and Git commands.
- **VS Code**: For editing code and `README.md`.
- **Git Bash**: For GitHub operations.
- **GitHub Actions**: For CI automation.

## Project Deliverables
- **Documentation**: This `README.md` with steps and learning summary.
- **Screenshots**:
  - `nodejs_npm_version_local.png`
  - `npm_install_output_local.png`
  - `npm_test_output_local.png`
  - `eslint_output_local.png`
  - `nodejs_app_output_local.png`
  - `github_repo_files_local.png`
  - `github_secrets_config_local.png`
  - `github_actions_run_local.png`
  - `github_actions_lint_run_local.png`
- **Script Link**: [GitHub Repository](https://github.com/westgrin/advanced-github-actions)

## Troubleshooting
- Fixed `ECONNRESET` error by setting DNS to `8.8.8.8` and clearing npm cache.
- Ensured commands were run in `/mnt/c/Users/Abraham/Documents/Workspace/Advanced_GitHub_Actions`.
- Verified secrets were correctly configured.

## Conclusion
This project successfully implemented advanced GitHub Actions workflows, ensuring maintainability, performance, and security. The side hustle task enhanced my skills in conditional workflows, preparing me for complex CI/CD pipelines.d_GitHub_Actions