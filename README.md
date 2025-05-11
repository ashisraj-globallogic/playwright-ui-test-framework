# playwright-ui-test-framework
This project is a Functional UI Test Automation Framework built using Playwright and TypeScript. It is designed to provide a robust, scalable, and maintainable solution for automating end-to-end UI testing for web applications. The framework includes features for test execution, reporting, and code quality enforcement, ensuring high-quality test automation.

## Key Features:

### Playwright Integration:

1. Utilizes Playwright for fast and reliable end-to-end testing.
2. Supports cross-browser testing (Chromium, Firefox, WebKit).
3. Includes support for headless and headed browser modes.

### TypeScript Support:

1. Leverages TypeScript for type safety and better code maintainability.
2. Includes TypeScript configuration for seamless development.

### Page Object Model (POM):

1. Implements the Page Object Model design pattern for better test structure and reusability.
2. Encapsulates page-specific actions and locators in dedicated classes.
  
### Session Management:

1. Supports saving and reusing session storage for faster test execution.
2. Includes functionality for handling cookies and storage state.

### Allure Reporting:

1. Generates detailed test execution reports with Allure.
2. Provides insights into test results, including screenshots and logs.

### Code Quality Tools:

1. Integrates ESLint and Prettier for enforcing coding standards and formatting.
2. Includes configuration for TypeScript-specific linting and Playwright best practices.

### Pre-Commit Hooks:

1. Uses Husky and lint-staged to ensure code quality before committing changes.
2. Automatically runs linters and formatters on staged files.

### Test Tags and Filtering:

1. Supports tagging tests (e.g., @smoke, @regression, @sanity) for selective execution.
2. Allows running specific test suites based on tags.

### Reusable Components:

1. Encapsulates common actions (e.g., login, navigation) in reusable methods.
2. Includes modular and extensible test utilities.

### Cross-Environment Support:

1. Configurable for different environments (e.g., staging, production).
2. Supports environment-specific test data and configurations.

## Functionalities:

### Login and Authentication:

1. Automates login flows with session reuse.
2. Validates authentication and logout functionality.

### Inventory Management:

1. Tests adding and removing items from the cart.
2. Verifies cart functionality and item counts.

### UI Validations:

1. Ensures the visibility and correctness of UI elements.
2. Validates page titles, buttons, and other visual components.

## Error Handling:

1. Includes robust error handling and retry mechanisms.
2. Captures screenshots and logs for failed tests.

This framework is designed to accelerate the development and execution of UI tests, ensuring high test coverage and reliability for web applications.
