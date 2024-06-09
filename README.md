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


## How to submit a PR
1. Clone the main [Sefaria-Project](https://github.com/Sefaria/Sefaria-Project) repository. 
2. Navigate to `e2e-tests/` (or click [here](https://github.com/Sefaria/Sefaria-Project/tree/master/e2e-tests)).
3. Write your tests with the testing framework running (you can see the instructions for running the framework above ☝️)
4. Once you feel confident that your tests are ready for review, submit your PR. Make sure you link the issue from this tracking repository to the PR so we can keep track of your efforts.

Questions? We're here to help. Feel free to reach out at developers@sefaria.org anytime. 

---

You're now set up to start running Playwright tests for the Sefaria project. If you encounter any issues or have questions, please refer to the [Playwright documentation](https://playwright.dev/docs/intro) for more detailed information.
