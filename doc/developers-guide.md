# Developer's Manual for Ranger Fusion  360 Add-On

This manual provides the conventions, best practices, and guidelines for contributing to the Ranger Fusion  360 add-on project. It's intended to help developers understand the expectations and maintain a consistent coding style throughout the project.

## Table of Contents
- [Code Style](#code-style)
- [Naming Conventions](#naming-conventions)
- [Commenting](#commenting)
- [Error Handling](#error-handling)
- [Unit Testing](#unit-testing)
- [Performance Considerations](#performance-considerations)
- [Contribution Workflow](#contribution-workflow)

## Code Style
- Follow the C++ Core Guidelines for consistent and high-quality C++ code.
- Use a consistent indentation style (e.g., four spaces or a tab) throughout the codebase.
- Use braces `{}` for all control structures, including single-line statements, for clarity and consistency.

## Naming Conventions
- Use descriptive variable and function names that indicate their purpose.
- Use camelCase for variables and functions (e.g., `myVariable`, `calculateTotal()`).
- Use PascalCase for class names (e.g., `MyClass`).

## Commenting
- Use comments to explain complex or non-obvious sections of code.
- Keep comments concise and relevant to the code they annotate.
- Update comments if the code changes to maintain accuracy.

## Error Handling
- Implement a formal exception handling mechanism to manage unexpected events.
- Use try-catch blocks and provide recovery mechanisms for software or network latency issues.

## Unit Testing
- Write unit tests to verify the functionality of the code.
- Follow the Arrange-Act-Assert (AAA) pattern for structuring tests.
- Ensure that each piece of functionality has corresponding unit tests.

## Performance Considerations
- Optimize code by implementing efficient algorithms.
- Carefully manage resources to prevent memory leaks and excessive resource usage.

## Contribution Workflow
- Clone the repository and create a new branch for your feature or bugfix.
- Commit changes frequently with clear and descriptive commit messages.
- Before submitting a pull request, ensure that all tests pass and the code conforms to the project's coding standards.
- Submit a pull request with a detailed description of the changes made.

## Additional Resources

- **Fusion  360 API Documentation**: [Fusion  360 API Reference](https://help.autodesk.com/view/fusion360/ENU/?guid=GUID-A92A4B10-3781-4925-94C6-47DA85A4F65A) - Comprehensive reference for the Fusion  360 API.
- **Leica API Documentation**: [Leica DISTO API](https://myworld-portal.leica-geosystems.com/s/) - Access the Leica DISTO API documentation for integration with Leica rangefinders.
- **C++ Documentation**: [C++ Standard Library Documentation](http://www.cplusplus.com/reference/) - Official documentation for the C++ standard library.
- **C++ Best Practices**: [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) - Google's C++ style guide for writing readable and maintainable code.
- **Design Patterns**: [Refactoring Guru](https://refactoring.guru/design-patterns) - A collection of design patterns with explanations and examples.

By following these guidelines, contributors can ensure that their code aligns with the project's standards and that the codebase remains consistent and maintainable. This manual is a living document and should be updated as the project evolves and new practices emerge.
