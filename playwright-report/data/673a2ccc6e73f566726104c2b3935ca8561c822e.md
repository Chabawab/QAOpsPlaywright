# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: RatherChat.spec.js >> @Webst Client App login
- Location: PlayWrightAutomation\tests\RatherChat.spec.js:3:1

# Error details

```
Test timeout of 30000ms exceeded.
```

```
Error: page.goto: Test timeout of 30000ms exceeded.
Call log:
  - navigating to "https://nx-staging.iwyzelife.co.za/", waiting until "load"

```

# Test source

```ts
  1 | const { test, expect } = require('@playwright/test');
  2 | 
  3 | test('@Webst Client App login', async ({ page }) => {
> 4 |     await page.goto("https://nx-staging.iwyzelife.co.za/");
    |                ^ Error: page.goto: Test timeout of 30000ms exceeded.
  5 | 
  6 | })
```