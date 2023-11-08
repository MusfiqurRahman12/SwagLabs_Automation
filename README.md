# SwagLabs_Automation
Install VS_Code 
Run the install command and select the following to get started:

Choose between TypeScript or JavaScript (default is TypeScript)
Name of your Tests folder (default is tests or e2e if you already have a tests folder in your project)
Add a GitHub Actions workflow to easily run tests on CI
Install Playwright browsers (default is true)
**Terminal Comand (npm init playwright@latest)
Playwright will download the browsers needed as well as create the following files.**

playwright.config.ts
package.json
package-lock.json
tests/
  example.spec.ts
tests-examples/
  demo-todo-app.spec.ts

**Running the Example Test**
Terminal Comand -  (npx playwright test S.spec.js --project=chromium --headed)
This comand will run the test in chromium as we specified in the comand, also one can visually see the test case being exicuted throughly.

**To see the test result in html format one should type this comand in Terminal**
Click = Ctrl + C & hit =Y
Terminal Comand- (npx playwright show-report)
