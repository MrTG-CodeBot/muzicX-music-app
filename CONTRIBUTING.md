# Contributing to MuzicX

First off, thank you for considering contributing to MuzicX! It's people like you that make MuzicX such a great tool.

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct: be respectful, constructive, and collaborative.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples**
- **Describe the behavior you observed and what you expected**
- **Include screenshots if applicable**
- **Include your environment details** (OS, Flutter version, app version)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **List any similar features in other apps**

### Pull Requests

1. Fork the repo and create your branch from `main`
2. If you've added code, add tests if applicable
3. Ensure the test suite passes
4. Make sure your code follows the existing style
5. Write a clear commit message
6. Update documentation as needed

## Development Setup

1. **Install Flutter** (3.4.1 or higher)
   ```bash
   flutter --version
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/muzicx.git
   cd muzicx
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Setup Firebase**
   ```bash
   setup_firebase.bat
   ```

5. **Run the app**
   ```bash
   flutter run
   ```

## Coding Guidelines

### Dart Style Guide

- Follow the [official Dart style guide](https://dart.dev/guides/language/effective-dart)
- Use `flutter analyze` to check for issues
- Format your code with `dart format .`

### File Organization

```
lib/
├── models/          # Data models
├── screens/         # UI screens
├── services/        # Business logic & APIs
├── widgets/         # Reusable widgets
├── utils/           # Utility functions
└── themes/          # Theme configurations
```

### Naming Conventions

- **Files**: `snake_case.dart`
- **Classes**: `PascalCase`
- **Variables**: `camelCase`
- **Constants**: `SCREAMING_SNAKE_CASE`
- **Private members**: prefix with `_`

### State Management

- Use `Provider` for app-wide state
- Use `StatefulWidget` for local component state
- Keep state logic separate from UI

### Comments

- Write self-documenting code
- Add comments for complex logic
- Document public APIs with `///`
- Keep comments up-to-date

## Commit Messages

Follow the conventional commits specification:

```
type(scope): subject

body

footer
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting)
- `refactor`: Code refactoring
- `test`: Adding tests
- `chore`: Maintenance tasks

**Example:**
```
feat(player): add sleep timer functionality

- Added duration picker for sleep timer
- Implemented auto-stop playback
- Added settings to persist timer preference

Closes #123
```

## Testing

- Write tests for new features
- Ensure existing tests pass
- Run tests with `flutter test`
- Aim for meaningful test coverage

## Documentation

- Update README.md for significant changes
- Document new features in appropriate files
- Keep inline documentation current
- Update version numbers appropriately

## Branch Naming

- `feature/feature-name` - New features
- `fix/bug-description` - Bug fixes
- `docs/what-changed` - Documentation
- `refactor/what-changed` - Refactoring

## Review Process

1. Maintainers will review your PR
2. Address any requested changes
3. Once approved, your PR will be merged
4. Your contribution will be credited

## Questions?

Feel free to ask questions by:
- Opening an issue with the `question` label
- Joining our Discord community
- Emailing support@muzicx.app

## Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

Thank you for contributing to MuzicX! 🎵
