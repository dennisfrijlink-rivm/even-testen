<p align="center"><img alt="" width="80" height="auto" src="./public/images/logo.svg"></p>

# Even testen (overzicht test libraries)

## ☕ Intro
Een compact overzicht van de verschillende Javascript test frameworks met hun doel + de voor- en nadelen. Tegenover de wens en vereisten.

## 🧪 Soorten tests
Kort overzicht van de verschillende soorten tests en waarvoor ze bedoeld zijn.

### Unit tests
Unit tests zijn kleine tests die een specifiek onderdeel van uw code testen, zoals een functie of methode. Ze zijn bedoeld om ervoor te zorgen dat elk onderdeel van uw code correct werkt.

### Integratie tests
Integratie tests testen hoe verschillende onderdelen van uw code samenwerken. Ze zijn bedoeld om ervoor te zorgen dat uw code als geheel correct werkt. 

### End-to-end tests
End-to-end tests testen de hele applicatie van begin tot eind. Ze zijn bedoeld om ervoor te zorgen dat de applicatie correct werkt in een realistische omgeving.

## 🚀 Populaire test libraries
> "*It's rare to see a trend as clear as Vitest's ascencion through the ranks over the past few years. While it may "only" be number four in terms of usage, it already tops the interest, retention, and overall positivity rankings – and shows no sign of conceding the top spot anytime soon.*" - State of JS

Een overzicht van de meest gebruikte testing libraries over tijd (gesorteerd op positiviteit):

<img src="./public/images/state-of-js-metrics.png">

[Bron: stateofjs 2024](https://2024.stateofjs.com/en-US/libraries/testing/)

### 🙈 Libraries niet meegenomen in de afweging:


- <img alt="" width="20" height="auto" src="./public/images/storybook.svg"> **Storybook**: 
Buiten het feit dat Storybook een geweldige optie voor het ontwikkelen, visualiseren, documenteren en bijhouden van custom components, is het niet ontworpen voor het schrijven van E2E-tests die de volledige functionaliteit van een webapplicatie testen of unit-tests voor specifieke functies.


- <img alt="" width="20" height="auto" src="./public/images/msw.svg"> **Mock Service Worker**: Het doel van Mock Service Worker is het isoleren van de frontend tijdens het testen, zodat de tests niet afhankelijk zijn van een echte backend. Dit is heel handig (al helemaal als we gaan werken met externe bronnen als een API). MSW kan altijd later nog toegevoegd worden aan het project.

- <img alt="" width="20" height="auto" src="./public/images/testing-library.svg"> **Testing Library**:
Testing Library is geen test runner of vergelijkbaar met een ander testing framework. Testing Library is een bibliotheek die je helpt om betere UI-tests te schrijven, vanuit het perspectief van de gebruiker door het kunnen renderen van een DOM en custom components. Erg handig maar kan altijd later geïmplementeerd worden.

- <img alt="" width="20" height="auto" src="./public/images/nodejs.svg"> **Node Test Runner**: Node Test Runner is een test runner gebouwd in Node.js zelf. Dus geen browserinteractie mogelijk, wat wel een vereiste is.


### Overzicht van libraries:
```text
✅ = Functie bestaat (mogelijk in beperkte vorm)

🚧 = Functie is mogelijk aanwezig, maar niet praktisch of officieel uitgebracht

❌ = Functie bestaat (nog) niet
```
| **Library** | [Jest](https://github.com/facebook/jest) | [Mocha](https://github.com/mochajs/mocha) | [Cypress](https://github.com/cypress-io/cypress) | [Puppeteer](https://github.com/puppeteer/puppeteer) | [Playwright](https://github.com/microsoft/playwright) | [WebdriverIO](https://github.com/webdriverio/webdriverio) | [Vitest](https://github.com/vitest-dev/vitest) | [Selenium](https://github.com/SeleniumHQ/selenium) | [TestCafe](https://github.com/DevExpress/testcafe)
|---|---|---|---|---|---|---|---|---|---|
| **Logo** | <center><img style="width: 50px;" src="./public/images/jest.svg"></center> | <center><img style="width: 50px;" src="./public/images/mocha.svg"></center> | <center><img style="width: 50px;" src="./public/images/cypress.svg"></center> | <center><img style="width: 50px;" src="./public/images/puppeteer.svg"></center> | <center><img style="width: 50px;" src="./public/images/playwright.svg"></center> | <center><img style="width: 50px;" src="./public/images/webdriverio.svg"></center> | <center><img style="width: 50px;" src="./public/images/vitest.svg"></center> | <center><img style="width: 50px;" src="./public/images/selenium.svg"></center> | <center><img style="width: 50px;" src="./public/images/testcafe.svg"></center> |
| Github stars | ![Sterren](https://img.shields.io/github/stars/facebook/jest) | ![Sterren](https://img.shields.io/github/stars/mochajs/mocha) | ![Sterren](https://img.shields.io/github/stars/cypress-io/cypress) | ![Sterren](https://img.shields.io/github/stars/puppeteer/puppeteer) | ![Sterren](https://img.shields.io/github/stars/microsoft/playwright) | ![Sterren](https://img.shields.io/github/stars/webdriverio/webdriverio) | ![Sterren](https://img.shields.io/github/stars/vitest-dev/vitest) | ![Sterren](https://img.shields.io/github/stars/SeleniumHQ/selenium) | ![Sterren](https://img.shields.io/github/stars/DevExpress/testcafe) |
| Contributors | ![Bijdragers](https://img.shields.io/github/contributors/facebook/jest) | ![Bijdragers](https://img.shields.io/github/contributors/mochajs/mocha) | ![Bijdragers](https://img.shields.io/github/contributors/cypress-io/cypress) | ![Bijdragers](https://img.shields.io/github/contributors/puppeteer/puppeteer) | ![Bijdragers](https://img.shields.io/github/contributors/microsoft/playwright) | ![Bijdragers](https://img.shields.io/github/contributors/webdriverio/webdriverio) | ![Bijdragers](https://img.shields.io/github/contributors/vitest-dev/vitest) | ![Bijdragers](https://img.shields.io/github/contributors/SeleniumHQ/selenium) | ![Bijdragers](https://img.shields.io/github/contributors/DevExpress/testcafe) |
| Last Commit | ![Laatste commit](https://img.shields.io/github/last-commit/facebook/jest) | ![Laatste commit](https://img.shields.io/github/last-commit/mochajs/mocha) | ![Laatste commit](https://img.shields.io/github/last-commit/cypress-io/cypress) | ![Laatste commit](https://img.shields.io/github/last-commit/puppeteer/puppeteer) | ![Laatste commit](https://img.shields.io/github/last-commit/microsoft/playwright) | ![Laatste commit](https://img.shields.io/github/last-commit/webdriverio/webdriverio) | ![Laatste commit](https://img.shields.io/github/last-commit/vitest-dev/vitest) | ![Laatste commit](https://img.shields.io/github/last-commit/SeleniumHQ/selenium) | ![Laatste commit](https://img.shields.io/github/last-commit/DevExpress/testcafe) |
| License | ![Licentie](https://img.shields.io/github/license/facebook/jest) | ![Licentie](https://img.shields.io/github/license/mochajs/mocha) | ![Licentie](https://img.shields.io/github/license/cypress-io/cypress) | ![Licentie](https://img.shields.io/github/license/puppeteer/puppeteer) | ![Licentie](https://img.shields.io/github/license/microsoft/playwright) | ![Licentie](https://img.shields.io/github/license/webdriverio/webdriverio) | ![Licentie](https://img.shields.io/github/license/vitest-dev/vitest) | ![Licentie](https://img.shields.io/github/license/SeleniumHQ/selenium) | ![Licentie](https://img.shields.io/github/license/DevExpress/testcafe) |
| Unit tests | ✅ | ✅ | 🚧 | ❌ | 🚧 | 🚧 | ✅ | ❌ | ❌ |
| Integratietests | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| End-to-end tests | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ |
| Screenshots | ❌ | ❌ | ✅  | ✅  | ✅  | ❌ | ❌ | ❌ | ✅  |
| Typescript ondersteuning | ✅  | ❌ | ✅  | ✅  | ✅  | ✅  | ✅  | ❌ | ✅  |
| Kosten | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 | Gratis 💸 |
| Ondersteuning meerdere browsers | 🚧, alleen via mocking | ❌ | 🚧, alleen Chromium gebaseerd | ✅ , Chromium, Firefox, WebKit | ✅ , Chromium, Firefox, WebKit | ✅ , Chromium, Firefox, WebKit | 🚧, alleen via mocking | ✅ , Chromium, Firefox, WebKit | ✅ , Chromium, Firefox, WebKit |