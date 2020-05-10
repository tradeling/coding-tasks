# Coding task for QA Automation Engineer @tradeling

## The Goal

Your task is to write automated tests preferably with [Cypress](https://www.cypress.io), [NightWatch](https://nightwatchjs.org/) or [Puppeteer](https://pptr.dev/) to demonstrate your test automation abilities.


## The Process

1. Start a new private github repository with detailed "readme" document on how to execute the tests.
1. Write end-to-end tests fulfilling the [Acceptance Criteria](#acceptance-criteria) below.
1. Publish test execution report in html format.
1. Prepare a test summary report and include the information about platform, browser, tools etc
1. Include all tests related document in same github repository.


## Acceptance Criteria

1. Scenario 1: [Check your gift card's balance is $0.00]
   1. Starts on the [Amazon](https://www.amazon.com/)
   2. Click on 'Start here' from Account and Lists
   3. Create Account and login
   4. Click on Your account
   5. Click on Gift Cards
   6. Check the balance of your gift card is $0.00

1. Scenario 2: [Check the total displayed number of results for category Smart Home | Televisions]
   1. Go to Categories list
   2. Choose category 'Smart Home'
   3. Chhose sub-category 'Televisions'
   4. Check the total number of results match the total displayed products

1. Scenario 3: [Check the selected currency displayed for the products' price]
   1. Go to Currency Settings
   2. Change currency to 'AED'
   3. Save changes
   4. Check the selected currency displayed for the products' price


## Bonus Round (not required, but nice-to-have)

- Usage of code quality tools such as eslint, prettier, typescript
- Integration of your tests into a CI pipeline
- Manual test cases for given scenarios
- Brief Performance report on home page using Jmeter or any similar tool
- Security and Vulnerability assessment
- Surprise us…

## How we're evaluating the result

Prioritized from most important to least important, here are our evaluation criteria:

1. **Acceptance Criteria**: Have all acceptance criteria been fulfilled correctly?
1. **Code Quality**: Is the code that you've written clean, well-structured and easy to understand?
1. **Documentation**: Did you document how to run your tests well? Is your written communication clear and easy-to-understand?
1. **The extra mile**: Everything you did on top of the acceptance criteria.
