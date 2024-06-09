# Sefaria Playwright Tests
Welcome! We're so grateful you're considering contributing to Sefaria's test coverage. We are so appreciative for our enthusiastic community of developers. 

Playwright tests bulletproof Sefaria from bugs. They are easy to contribute and make our digital library more resilient. This repo uses issues and projects to manage volunteer contributions to tests. All pull requests will need to be to the main [Sefaria-Project](https://github.com/Sefaria/Sefaria-Project) repository. 

Questions? Contact us at developers@sefaria.org

## Getting Started

### 1. Clone the Sefaria Project

First, clone the Sefaria project repository:

```bash
git clone https://github.com/Sefaria/Sefaria-Project.git
```

### 2. Install Playwright

Next, install Playwright and its test runner:

```bash
npm install playwright@latest
npm install @playwright/test
npx playwright install
```

### 3. Run the Testing Framework

Finally, run the Playwright test UI:

```bash
npx playwright test --ui
```

This command will launch the Playwright test user interface where you can run and manage your tests.


## Contributing
### Fork the Repository
1. Go to the [Sefaria-Project](https://github.com/Sefaria/Sefaria-Project) repository on GitHub.
2. Click the "Fork" button at the top right of the page. This will create a copy of the repository in your GitHub account.
### Clone Your Fork
Once you've forked the repository, clone your fork to your local machine:
```bash
git clone https://github.com/your-username/Sefaria-Project.git
```
Replace `your-username` with your GitHub username.
### Create a Branch
Before making any changes, create a new branch for your work:
```bash
git checkout -b your-branch-name
```
Replace `your-branch-name` with a descriptive name for your branch.
### Make Your Changes
Make the necessary changes to the codebase and commit them:
```bash
git add .
git commit -m "Description of your changes"
```
### Push Your Changes
Push your changes to your forked repository:
```bash
git push origin your-branch-name
```
### Create a Pull Request
1. Go to your forked repository on GitHub.
2. Click the "Compare & pull request" button.
3. Ensure the base repository is `Sefaria/Sefaria-Project` and the base branch is `master`.
4. Fill in the title and description for your pull request. **Make sure to include a reference to the relevant GitHub issue from _this_ repo by using `Fixes #issue_number` or `Closes #issue_number` in the description.** This will automatically link your pull request to the issue.

   
Questions? We're here to help. Feel free to reach out at developers@sefaria.org anytime. 

---

You're now set up to start running Playwright tests for the Sefaria project. If you encounter any issues or have questions, please refer to the [Playwright documentation](https://playwright.dev/docs/intro) for more detailed information.
