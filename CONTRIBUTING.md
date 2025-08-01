# Contributing to Frontier LLM Stack

We love your input! We want to make contributing to Frontier LLM Stack as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## We Develop with Github

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

## We Use [Github Flow](https://guides.github.com/introduction/flow/index.html)

Pull requests are the best way to propose changes to the codebase. We actively welcome your pull requests:

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code follows the existing style.
6. Issue that pull request!

## Any contributions you make will be under the MIT Software License

In short, when you submit code changes, your submissions are understood to be under the same [MIT License](LICENSE) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report bugs using Github's [issues](https://github.com/yourusername/frontier-llm-mac-stack/issues)

We use GitHub issues to track public bugs. Report a bug by [opening a new issue](https://github.com/yourusername/frontier-llm-mac-stack/issues/new); it's that easy!

## Write bug reports with detail, background, and sample code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## Development Process

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/frontier-llm-mac-stack.git
   cd frontier-llm-mac-stack
   ```

2. Create a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and test them
   ```bash
   ./scripts/testing/test-integration.sh
   ```

4. Commit your changes
   ```bash
   git add .
   git commit -m "Add your meaningful commit message"
   ```

5. Push to your fork and submit a pull request

## Code Style

- Use clear, descriptive variable names
- Add comments for complex logic
- Follow existing patterns in the codebase
- Keep scripts modular and reusable

## Testing

Before submitting a PR:

1. Run the integration tests:
   ```bash
   ./scripts/testing/test-integration.sh
   ```

2. Test your changes with both Docker and native installation methods

3. Ensure documentation is updated if needed

## License

By contributing, you agree that your contributions will be licensed under its MIT License.