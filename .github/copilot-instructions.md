# GitHub Copilot Custom Instructions

## Repository Overview
This repository is for the WG project. When contributing code, follow the guidelines below to maintain consistency and quality.

## Coding Standards

### General Principles
- Write clear, readable, and maintainable code.
- Follow DRY (Don't Repeat Yourself) principles.
- Use meaningful variable and function names that describe their purpose.
- Keep functions small and focused on a single responsibility.
- Add comments only when necessary to explain complex logic or non-obvious decisions.

### Code Style
- Use consistent indentation (prefer spaces over tabs).
- Follow the language-specific style guides for the project.
- Keep line lengths reasonable (typically 80-120 characters).
- Use proper whitespace for readability.

## Security

### Security Best Practices
- Never commit secrets, API keys, passwords, or sensitive credentials to the repository.
- Use environment variables for configuration and secrets.
- Validate and sanitize all external input.
- Use secure communication protocols (HTTPS, TLS).
- Keep dependencies up to date and regularly check for security vulnerabilities.
- Follow the principle of least privilege for access control.
- Implement proper error handling without exposing sensitive information.

### Authentication & Authorization
- Use secure authentication mechanisms.
- Implement proper session management.
- Validate authorization for all protected resources.

## Testing

### Test Requirements
- Write tests for all new functionality.
- Maintain or improve existing test coverage.
- Ensure tests are clear, focused, and test one thing at a time.
- Use descriptive test names that explain what is being tested.
- Include both positive and negative test cases.

### Test Organization
- Keep test files close to the code they test.
- Follow consistent naming conventions for test files.
- Use appropriate testing frameworks for the language.
- Mock external dependencies appropriately.

## Documentation

### Code Documentation
- Document all public APIs and interfaces.
- Add docstrings or JSDoc comments for functions and classes.
- Explain complex algorithms or business logic with inline comments.
- Keep documentation up to date with code changes.

### README and Project Documentation
- Keep the README.md file current and informative.
- Document setup instructions, dependencies, and how to run the project.
- Include examples of usage where appropriate.
- Document any special configuration or environment requirements.

## Version Control

### Git Practices
- Write clear, descriptive commit messages.
- Use the imperative mood in commit messages (e.g., "Add feature" not "Added feature").
- Keep commits focused and atomic.
- Reference issues or tickets in commit messages when applicable.

### Pull Requests
- Ensure all tests pass before submitting a pull request.
- Provide a clear description of changes in the PR.
- Link to relevant issues or tickets.
- Respond to code review feedback promptly.

## Dependencies and Libraries

### Dependency Management
- Only add dependencies when necessary.
- Document why new dependencies are needed.
- Keep dependencies up to date.
- Prefer well-maintained and widely-used libraries.
- Check licenses for compatibility with the project.

## Error Handling

### Error Management
- Handle errors gracefully and appropriately.
- Provide useful error messages for debugging.
- Log errors at appropriate levels.
- Don't catch exceptions unless you can handle them properly.
- Clean up resources in error cases (use try-finally or equivalent).

## Performance

### Optimization Guidelines
- Write clear code first, optimize only when necessary.
- Profile before optimizing to identify actual bottlenecks.
- Document performance-critical sections.
- Consider algorithmic complexity for data structures and algorithms.
- Be mindful of resource usage (memory, CPU, network).

## Accessibility

### Accessibility Standards
- Follow WCAG guidelines for any user-facing content.
- Ensure proper semantic HTML structure.
- Include appropriate ARIA labels when necessary.
- Test with screen readers and keyboard navigation.
- Ensure sufficient color contrast.

## Code Review

### Review Expectations
- Review code thoroughly for logic, style, and potential issues.
- Be constructive and respectful in feedback.
- Ask questions when something is unclear.
- Verify that tests are included and passing.
- Check for security vulnerabilities and performance issues.

## Continuous Integration

### CI/CD Guidelines
- Ensure all CI checks pass before merging.
- Fix broken builds promptly.
- Keep the main branch stable and deployable.
- Run tests locally before pushing.
- Monitor build and test performance.
