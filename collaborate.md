#### **Flags and Their Usage**

- **✨ feat:**  
  Use for commits that introduce new features or functionalities.  
  _Example:_ `feat: add user profile page`

- **🐛 fix:**  
  Use for commits that fix bugs or correct errors in the code.  
  _Example:_ `fix: resolve crash on login due to null value`

- **📚 docs:**  
  Use for commits that involve changes or updates to documentation (e.g., README files, inline comments).  
  _Example:_ `docs: update API usage section`

- **🎨 style:**  
  Use for commits that modify code formatting, whitespace, or stylistic changes that do not affect logic.  
  _Example:_ `style: format code to comply with linting rules`

- **♻️ refactor:**  
  Use for commits that restructure or reorganize code without changing its external behavior.  
  _Example:_ `refactor: simplify function for data processing`

- **🔧 chore:**  
  Use for commits related to maintenance tasks, build processes, dependency updates, or tools configuration.  
  _Example:_ `chore: update dependencies to latest versions`

- **🚀 perf:**  
  Use for commits that improve performance or optimize code.  
  _Example:_ `perf: reduce API response time by caching`

- **✅ test:**  
  Use for commits that add or update tests.  
  _Example:_ `test: add unit tests for user authentication`

- **🔒 security:**  
  Use for commits that address security issues or vulnerabilities.  
  _Example:_ `security: fix XSS vulnerability in comment section`

- **💥 breaking:**  
  Use for commits that introduce breaking changes to the codebase.  
  _Example:_ `breaking: update API contract for user services`

- **⚡ ci:**  
  Use for commits related to Continuous Integration (CI) configuration or automation.  
  _Example:_ `ci: add deployment step to GitHub Actions`

- **📦 build:**  
  Use for commits that affect the build system or external dependencies.  
  _Example:_ `build: switch bundler to Vite for faster builds`

- **🗑️ revert:**  
  Use for commits that revert changes made in previous commits.  
  _Example:_ `revert: undo changes from commit abc123`

- **🔀 merge:**  
  Use for commits that merge branches.  
  _Example:_ `merge: feature-login into main`

- **🛠️ wip:**  
  Use for commits that are part of work in progress and not yet complete.  
  _Example:_ `wip: draft implementation of notification system`

- **🏷️ release:**  
  Use for commits related to version tagging or release preparations.  
  _Example:_ `release: version 1.0.0`

---

#### **Commit Message Format**

Each commit message should include the following components:
1. **Flag**: Indicates the type of change (e.g., feat, fix).
2. **Short Description**: A concise summary of the change (written in imperative form).  
   - Length: Preferably under 50 characters.
3. **Optional Body**: Provide additional details if necessary, wrapped at 72 characters per line.

---

#### **Example Commit Messages**
- `✨ feat: implement user authentication via OAuth`
- `🐛 fix: correct typo in error message on login failure`
- `📚 docs: add contributing guidelines to the repository`
- `🎨 style: reformat files to adhere to style guide`
- `♻️ refactor: extract utility functions into separate module`
- `🚀 perf: optimize image loading in the homepage`
- `✅ test: add integration tests for payment module`
- `🔒 security: patch SQL injection vulnerability`
- `💥 breaking: remove deprecated API endpoints`
- `⚡ ci: configure GitHub Actions for CI/CD`
- `📦 build: upgrade webpack to version 5`
- `🗑️ revert: undo changes from commit abc123`
- `🔀 merge: feature-login into main`
- `🛠️ wip: draft implementation of notification system`
- `🏷️ release: version 1.0.0`