# project_setup_checklists

## typescript:
✅ Essential Setup

✔ ESLint (Configured & Auto-fixed on Save)✔ Prettier (Auto-formats Code)✔ TypeScript Config Optimized (tsconfig.json)✔ Node.js Version Enforced (.nvmrc)✔ Setup Script (setup.sh to automate repo setup)✔ VSCode Settings & Extensions Optimized (.vscode/settings.json)

✅ Git Hooks & Code Quality

✔ Husky & Lint-Staged (Prevents Bad Commits)✔ Commitlint & Commitizen (Enforces Conventional Commits)✔ Jest (Testing Set Up)

✅ Configuration Files

Ensure you have the following config files in place:

jest.config.js – Jest Testing Config

babel.config.js – Babel Config (if using Babel)

eslint.config.mjs – ESLint Configuration

prettier.config.js / .prettierrc – Prettier Config

.prettierignore – Files ignored by Prettier

setupTests.ts – Global setup for tests

commitlint.config.js – Commit Message Validation

global.d.ts – Global TypeScript Declarations

✅ CI/CD & Automation

✔ GitHub Actions or Other CI/CD Pipeline (Optional but useful)✔ Automated TypeScript Type Checking (npm run typecheck)✔ Automated Linting & Formatting on Commit (husky - commit-msg, pre-commit, pre-commit-fix, pre-push, prepare-commit-msg)
