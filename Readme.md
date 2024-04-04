## Refactoring Exercise: Improving the `FundingRaised` Class

This exercise focuses on refactoring the `FundingRaised` class in a provided Java project. The goal is to improve the code's readability, maintainability, and overall quality without altering its external behavior. The exercise is adapted from [GitHub - lamchau/refactoring-exercise](https://github.com/lamchau/refactoring-exercise).

### Setup Instructions

1. **Install Maven**: Ensure Maven is installed on your system. It's a build automation tool used primarily for Java projects. Installation instructions can be found on the [official Maven website](https://maven.apache.org/install.html).

2. **Build the Project**:
   - Open a terminal or command prompt.
   - Navigate to the project's root directory.
   - Run `mvn package` to compile the project and package the compiled code into a distributable format (e.g., a JAR file).

3. **Run Tests**:
   - In the project's root directory, execute `mvn test` to run the unit tests. Ensure all tests pass before and after your refactoring.

### Refactoring Tasks

Your main objectives are to:

- **Eliminate Duplicated Code**: Identify and remove redundant code blocks, using methods or classes to encapsulate repeating logic where possible.

- **Improve Names**: Review and enhance the naming of methods, variables, and classes to clearly reflect their purpose or the data they handle.

- **Enhance Readability and Maintainability**: Apply best coding practices to make the code easier to read and maintain. This includes breaking down large methods into smaller, focused functions, using meaningful constants instead of magic numbers, and improving the code's structural organization.

### Ensuring Success

- **Maintain Original Functionality**: It's crucial that your refactoring does not change the program's behavior. Use the provided unit tests as a safeguard, running `mvn test` after each refactoring step to confirm all tests still pass.

- **Commit Changes Frequently**: If using version control (recommended), make regular commits. This practice helps in tracking your progress and simplifies reverting changes if needed.

Refactoring is an iterative process. Review your changes, run tests, and be prepared to refactor further if necessary. This exercise will deepen your understanding of how to systematically improve code quality.
