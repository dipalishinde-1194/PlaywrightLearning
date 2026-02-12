# PlaywrightLearning

Playwright learning repo with example scripts and exercises.

Repository: https://github.com/dipalishinde-1194/PlaywrightLearning

Project structure

- chapter_01_basics/: basic examples
- chapter_02_JS_concepts/: JS concept exercises

Prerequisites

- Node.js (14+)
- Git

Quick start

1) Initialize npm (if you don't have a package.json):

```bash
npm init -y
```

2) Install Playwright Test:

```bash
npm install -D @playwright/test
npx playwright install
```

3) Run tests (runs all tests in repository):

```bash
npx playwright test
```

Or run a single file or folder:

```bash
npx playwright test chapter_01_basics
```

Notes

- Add a `package.json` with test scripts if you want shortcuts.
- Let me know if you want a GitHub Actions workflow to run Playwright tests on push.
