# AGENTS.md File Guidelines

**1. DRY (Don't Repeat Yourself)**

*   All code within this repository must be unique and reusable. Avoid duplicating functionality across multiple files.
*   When implementing a common pattern, encapsulate it within a reusable component or class.
*   Document reuse patterns clearly.
*   Refactor to eliminate redundant code.

**2. KISS (Keep It Simple, Stupid)**

*   Prioritize clarity and readability.  Code should be easy to understand and maintain.
*   Minimize complexity.  Strive for straightforward solutions.
*   Avoid unnecessary lines of code.  Refactor to reduce complexity without changing functionality.
*   Use meaningful variable and function names.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  Systems should be open for extension but closed for modification.  New functionality should be added without altering existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on methods it does not use.
*   **Dependency Inversion Principle:** Dependencies should be minimized and replaced with abstractions.

**4. YAGNI (You Aren't Gonna Need It)**

*   Only implement functionality that is absolutely required at a given moment.
*   Avoid adding features or code that isn’t currently needed.
*   Don’t introduce unnecessary complexity.

**5. Test Coverage Requirements**

*   Minimum 80% test coverage is required for all files.
*   Tests should cover all critical logic and edge cases.
*   Each test should be small and focused on verifying a single aspect of the code.
*   Tests should be designed to fail reliably.

**6. File Length Constraint**

*   Each file should be no more than 180 lines of code.
*   Code should be well-structured and easily parsable.
*   Avoid excessively long functions or classes.
*   Code should be readable and understandable.

**7. Code Style & Formatting**

*   Follow PEP 8 style guidelines.
*   Use consistent indentation and spacing.
*   Use meaningful comments where necessary to explain complex logic.
*   Employ code formatting tools (e.g., `black`) for consistent code style.

**8. Development Workflow**

*   Strict adherence to commit message conventions.
*   Code reviews are mandatory before merging.
*   Pull requests should be reviewed by at least one other contributor.
*   Document significant changes and rationale clearly.

**9. Data Model & API Design (Example - Adjust to specific AGENTS.md)**

*   All data models and API endpoints are subject to thorough testing.
*   API endpoints should be well-documented and easy to use.
*   Data structures should be designed for efficient retrieval and manipulation.
*   Error handling should be robust and provide informative error messages.

**10.  Specific File Structure (Example - Adapt as needed)**

*   **data/** –  Data related files (e.g., configuration, data schemas)
*   **logic/** –  Core algorithms and business logic
*   **utils/** –  Reusable utility functions and classes
*   **tests/** –  Unit and integration tests
*   **docs/** –  API documentation (e.g., using Swagger/OpenAPI)

**11.  Code Documentation**

*   Each function and class should have a concise docstring explaining its purpose, parameters, and return values.
*   Use a consistent docstring format (e.g., Google style).

**12.  Automated Code Analysis**

*   Use a static analysis tool (e.g., linters) to ensure code quality and consistency.
*   Automate code formatting and linting.

**13.  Version Control**

*   Use Git for version control.
*   Follow a consistent branching strategy.
*   Commit changes frequently with meaningful messages.

**14.  Dependency Management**

*   Use a dependency management tool (e.g., `pip`, `npm`) to manage external libraries.
*   Keep dependencies up to date.
*   Version control dependencies.