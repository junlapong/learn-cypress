# Learn Cypress

## Step

### 1. Create directory

```
mkdir test-cypress
cd test-cypress
```

### 2. Install Cypress

```
npm init
npm install cypress --save-dev
```

### 3. Setup scripts

add below script in `package.json`

```
{
  "scripts": {
    "cy:open": "cypress open",
    "cy:run": "cypress run"
  }
}
```

### 4. Run Cypress

#### GUI

```
npm run cy:open
```

#### Command Line

```
npm run cy:run -- --spec "cypress/integration/test/cypress_sample.spec.js"
```

[![asciicast](https://asciinema.org/a/245184.svg)](https://asciinema.org/a/245184)

for setup video record key [see](https://docs.cypress.io/guides/core-concepts/dashboard-service.html#Setup)

## Tools

### Chrome Extensions
 - [Cypress Scenario Recorder](https://chrome.google.com/webstore/detail/cypress-scenario-recorder/fmpgoobcionmfneadjapdabmjfkmfekb)


## References

- https://docs.cypress.io
- [Cypress: The future of end-to-end testing for web applications](https://medium.com/tech-quizlet/cypress-the-future-of-end-to-end-testing-for-web-applications-8ee108c5b255)
- [รู้จัก Cypress: Web Test Framework ที่จะทำให้คุณลืม Selenium ไปได้เลย](https://medium.com/linedevth/%E0%B8%Acea3ffd1-fdc1-477b-b608-85a5f3537e943%E0%B8%B9%E0%B9%89%E0%B8%88%E0%B8%B1%E0%B8%81-cypress-web-test-framework-%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%88%E0%B8%B0%E0%B8%97%E0%B8%B3%E0%B9%83%E0%B8%AB%E0%B9%89%E0%B8%84%E0%B8%B8%E0%B8%93%E0%B8%A5%E0%B8%B7%E0%B8%A1-selenium-%E0%B9%84%E0%B8%9B%E0%B9%84%E0%B8%94%E0%B9%89%E0%B9%80%E0%B8%A5%E0%B8%A2-405a11d7341)
- [Cypress 101: ใครไม่เคยเขียน Web Automated Test มาเริ่มด้วย Cypress กันเพียง 3 ขั้นตอนง่ายๆ](https://medium.com/linedevth/cypress-101-%E0%B9%83%E0%B8%84%E0%B8%A3%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%80%E0%B8%84%E0%B8%A2%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99-web-automated-test-%E0%B8%A1%E0%B8%B2%E0%B9%80%E0%B8%A3%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-cypress-%E0%B8%81%E0%B8%B1%E0%B8%99%E0%B9%80%E0%B8%9E%E0%B8%B5%E0%B8%A2%E0%B8%87-3-%E0%B8%82%E0%B8%B1%E0%B9%89%E0%B8%99%E0%B8%95%E0%B8%AD%E0%B8%99%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2%E0%B9%86-10cea3b05cbc)
- [เริ่มต้นเขียน Automated Test ด้วย Cypress.io แบบลงมือทำ](https://medium.com/nellika/%E0%B9%80%E0%B8%A3%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B8%95%E0%B9%89%E0%B8%99%E0%B9%80%E0%B8%82%E0%B8%B5%E0%B8%A2%E0%B8%99-automated-test-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-cypress-io-%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B8%A5%E0%B8%87%E0%B8%A1%E0%B8%B7%E0%B8%AD%E0%B8%97%E0%B8%B3-dcda05f3a585)
