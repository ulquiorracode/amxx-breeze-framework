# Contribution Guide

Thank you for your interest in Breeze Framework! We welcome any help and contributions to the project.

## Development Process

1. Fork the repository
2. Create a branch for your feature (`git checkout -b feature/amazing-feature`)
3. Make your changes and test them
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push the branch to your fork (`git push origin feature/amazing-feature`)
6. Create a Pull Request

## Project Structure

```
amxx-breeze-framework/
├── .github/                    # GitHub Actions configuration and templates
├── amxmodx/                    # AMXX files
│   ├── scripting/              # AMXX scripts
│   │   ├── include/            # Include files
│   │   │   └── breeze/         # Framework files
│   │   │       ├── core.inc    # Framework core
│   │   │       ├── plugin.inc  # Basic plugin functionality
│   │   │       └── ...         # Other components
│   │   └── plugins/            # Example plugins
├── docs/                       # Documentation
└── tests/                      # Tests
```

## Code Style

- Indentation: 4 spaces
- Braces: same line
- Function names: CamelCase
- Global variables: g_prefixedCamelCase
- Local variables: camelCase
- Constants: UPPERCASE_WITH_UNDERSCORES
- Macros: UPPERCASE_WITH_UNDERSCORES

## Pull Request Rules

1. Ensure your code follows the project's code style
2. Update README.md if necessary
3. Update documentation if necessary
4. Write a clear description of your changes

## Bug Reports

Bug reports help us improve the framework. When submitting a report, please follow the template and provide:

1. Framework version
2. Steps to reproduce the bug
3. Expected behavior
4. Actual behavior
5. Screenshots or logs (if applicable)

## Feature Requests

If you have ideas for improving the framework, please create an issue with the feature request template. Describe your idea, its benefits, and possible implementation approaches. 