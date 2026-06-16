## Week 1 - Software Testing Fundamentals

Started with fundamentals of software testing and QA basics.

- Learned about Software Testing concepts:
  - What is testing and why it is important
  - Difference between QA and QC
  - Types of testing (manual vs automation)

- Understood SDLC (Software Development Life Cycle)

- Learned about STLC (Software Testing Life Cycle)

- Explored different testing types:
  - Functional testing
  - Non-functional testing
  - Smoke and sanity testing

- Learned about bug lifecycle:
  - How bugs are identified, reported, and tracked

- Practiced writing basic test cases:
  - simple scenarios for login and form validation
  - focused on step-by-step clarity

- Introduction to bug reporting:
  - basic structure (title, steps, expected, actual)

- Started using tools:
  - basic understanding of version control (Git)

### Challenges
- Understanding different testing types initially
- Writing clear and structured test cases
- Differentiating between similar concepts (smoke vs sanity)
- Learning proper bug reporting format



## Week 2 - Manual Testing

Focused on manual testing practice and improving test case quality.

- Practiced writing detailed test cases:
  - covered positive and negative scenarios
  - improved clarity and completeness

- Worked on real-world scenarios:
  - login functionality
  - signup forms
  - input validations

- Learned about test case design techniques:
  - boundary value analysis (basic idea)
  - equivalence partitioning (basic idea)

- Performed manual testing on sample/demo applications:
  - executed test cases step by step
  - identified bugs and inconsistencies

- Improved bug reporting:
  - added clear steps to reproduce
  - included expected vs actual results
  - focused on clear and concise descriptions

- Learned importance of:
  - edge cases
  - user perspective while testing

- Organized test cases in a structured format

### Challenges
- Covering all possible test scenarios
- Writing negative test cases properly
- Identifying edge cases
- Making test cases detailed but not overly complex



## Week 3 - Automation using Playwright

Started working with Playwright for automation testing.

- Initialized Playwright project and understood basic folder structure
  (tests, playwright.config, reports)

- Created first test scripts:
  - Opened a webpage using page.goto()
  - Validated page title
  - Performed simple click actions

- Worked with different locator strategies:
  - text-based locators
  - role-based locators
  - label and placeholder locators
  - understood why locators are important for stability

- Practiced running tests:
  - npx playwright test
  - headed mode for debugging
  - headless mode for faster execution

- Used Playwright codegen to generate basic scripts and studied the output

- Explored reports:
  - HTML report
  - basic understanding of screenshots and traces

- Learned how automation simulates real user interactions

### Challenges
- Initial confusion with Playwright setup and structure
- Difficulty identifying correct locators for some elements
- Tests failing due to incorrect selectors
- Needed time to understand how scripts execute step by step



## Week 4 - Locators, Assertions and Test Stability

Focused on improving automation scripts and making tests more reliable.

- Improved locator usage:
  - started using getByRole, getByText, getByLabel
  - replaced weak selectors with better ones

- Updated existing test scripts to make them more stable

- Implemented assertions:
  - toHaveText for content validation
  - toBeVisible for UI checks
  - toHaveURL for navigation validation

- Understood importance of validation in test cases (not just actions)

- Learned about flaky tests:
  - causes: timing issues, weak locators, dynamic elements
  - observed inconsistent test results

- Worked with Playwright auto-wait behavior
  - understood how Playwright waits for elements internally
  - reduced need for manual waits

- Improved code readability:
  - structured test steps clearly
  - removed unnecessary code

### Challenges
- Selecting the most stable locator among multiple options
- Tests failing randomly due to timing issues
- Understanding flaky behavior and fixing it
- Writing assertions correctly without overcomplicating tests



## Week 5 - Test Structure and Code Organization

Focused on organizing automation code and improving project structure.

- Understood and implemented better folder structure:
  - tests
  - pages
  - helpers
  - test-data
  - manual-test-cases
  - docs

- Started using Page Object Model (POM):
  - created separate page files
  - moved locators and actions into page classes
  - reused functions across tests

- Refactored existing test scripts:
  - reduced code duplication
  - improved readability and maintainability

- Worked with test data:
  - separated test data from test scripts
  - used reusable data inputs

- Created helper functions:
  - common actions (login, navigation, etc.)
  - reused across multiple tests

- Added more structured test cases:
  - covered positive scenarios
  - started thinking about negative scenarios

- Improved overall test organization and clarity

### Challenges
- Understanding Page Object Model structure
- Moving logic from tests into page files correctly
- Managing multiple files and imports
- Avoiding duplication while keeping code simple
- Structuring project in a clean and scalable way
