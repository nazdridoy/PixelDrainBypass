# Contributing to PixelDrainBypass

Thank you for your interest in contributing to PixelDrainBypass! This document provides guidelines and instructions for contributing to this project.

## Development Setup

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/PixelDrainBypass.git`
3. Navigate to the project directory: `cd PixelDrainBypass`
4. Open the project in your preferred code editor
5. To test changes, you can use a userscript manager's built-in editor or load the script from your local file

## Code Structure

- `PixelDrainBypass.js` - Main userscript file containing all functionality
- `README.md` - Project documentation

## Code Style Guidelines

- Use consistent indentation (4 spaces)
- Keep the code simple and focused on the core functionality
- Add comments for complex logic
- Maintain the userscript metadata header format

## Pull Request Guidelines

Before submitting a pull request, please make sure that:
  
- Your code follows the project's coding conventions
- You have tested your changes thoroughly in different browsers
- The commit messages are clear and follow conventional commit guidelines as specified in [COMMIT_GUIDELINES.md](COMMIT_GUIDELINES.md)
- You have provided a detailed explanation of the changes in the pull request description

## Submitting Changes

1. Create a new branch: `git checkout -b feature/your-feature-name`
2. Make your changes
3. Test thoroughly
4. Commit with clear messages: `git commit -m "feat: description"`
5. Push to your fork: `git push origin feature/your-feature-name`
6. Open a Pull Request against the main repository

## Testing

Before submitting your changes, please test:

- Functionality in different browsers with different userscript managers (Tampermonkey, Greasemonkey, Violentmonkey)
- Verify that redirection works properly on various PixelDrain links
- Check that the script runs at the appropriate time (document-start)
- Confirm that file IDs are correctly extracted and the redirection URL is properly constructed

## Issue Reporting

When opening an issue, please:

- Use a clear and descriptive title
- Provide a detailed description of the issue, including the environment and steps to reproduce
- Include any relevant screenshots or logs
- Specify your browser, operating system, and userscript manager
- Search the repository for similar issues before creating a new one

## Feature Requests

Feature requests are welcome! To submit a feature request:

- Use a clear and descriptive title
- Provide a detailed description of the proposed feature
- Explain why this feature would be useful to PixelDrainBypass users
- If possible, suggest how it might be implemented

## Questions and Discussions

For questions about the project that aren't bugs or feature requests, please use GitHub Discussions instead of opening an issue. This helps keep the issue tracker focused on bugs and features.

## License

By contributing to this project, you agree that your contributions will be licensed under the same [MIT License](LICENSE) as the project.
