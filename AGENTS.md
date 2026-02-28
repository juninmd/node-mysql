```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines outline the principles and requirements for the development of AI coding agents within this repository.  Adherence to these principles is crucial for creating maintainable, scalable, and reliable agent systems.

## 1. DRY (Don't Repeat Yourself)

*   **Core Logic Reuse:**  All core logic components, algorithms, and data structures should be encapsulated in reusable modules or functions.
*   **Componentization:** Break down complex tasks into smaller, self-contained components that can be easily reused across multiple agents.
*   **Abstraction:** Define abstract interfaces for agents, allowing for flexibility while maintaining consistent behavior.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:** Design components and algorithms with simplicity as the primary goal. Avoid unnecessary features or intricate details.
*   **Clear Intent:** Each component should have a single, well-defined purpose.  Avoid implicit assumptions.
*   **Readability:** Prioritize code that is easily understandable and maintainable – use meaningful variable names and clear formatting.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible through public interfaces, not through modifications to its internal code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without affecting the correctness of the system.
*   **Interface Segregation Principle:** Each interface should have a minimal set of methods required to fulfill its contract.
*   **Dependency Inversion Principle:**  High-level modules should be dependent on low-level modules, and low-level modules should be dependent on interfaces.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Feature Creep:**  Focus on implementing the essential requirements specified in the requirements specification.  Don’t add functionality that isn’t currently needed.
*   **Forward-Looking Considerations:**  Consider potential future needs when designing components, but avoid premature implementation of things that won’t be used.

## 5. Development Guidelines

*   **Code Reviews:** All code must undergo thorough code reviews by at least two developers.
*   **Unit Tests:** All code must be thoroughly tested with comprehensive unit tests.
*   **Test Coverage:**  Target a minimum of 80% test coverage.  Automated tests should cover all core functionality.
*   **Error Handling:** Implement robust error handling mechanisms to gracefully handle unexpected situations.  Log errors effectively.
*   **Logging:** Use a consistent and informative logging strategy to aid in debugging and monitoring.
*   **Version Control:** Employ a robust version control system (e.g., Git) with clear branching strategies.
*   **Documentation:**  Provide clear and concise documentation for all components, functions, and classes.

## 6. File Structure & Constraints

*   **Maximum File Length:** Each file shall not exceed 180 lines of code.
*   **File Organization:**  Organize files into logical categories (e.g., Modules, Components, Data, Tests).
*   **Naming Conventions:** Follow consistent naming conventions (e.g., camelCase for variables and functions).
*   **Comments:** Include comments where necessary to explain complex logic or design decisions.

## 7.  Specific Considerations for AGENTS

*   **Agent State Management:**  Define a clear and robust state management system.
*   **Communication Protocols:** Document the communication protocols used by agents.
*   **Data Structures:** Employ appropriate data structures for efficient agent processing.
*   **Agent Lifecycle Management:**  Consider a lifecycle management system for agents (e.g., initialization, termination, state).

## 8. Testing Framework

*   **Automated Tests:** All tests must be automated and well-documented.
*   **Test-Driven Development:** Use test-driven development practices to ensure code quality.

## 9.  Code Style

*   Use a consistent code style (e.g., PEP 8 for Python).

## 10.  Requirements Specification

*   All development must be driven by a clearly defined requirements specification.

These guidelines are intended to promote a sustainable and high-quality development process.  Any deviation from these principles will be considered a violation of the project's quality standards.
```