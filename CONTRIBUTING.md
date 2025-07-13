```markdown
# Contributing to Leaf 🍃

Thank you for your interest in contributing to Leaf! This document provides guidelines for contributing.

## Ways to Contribute

- 🐛 **Report bugs** via GitHub Issues
- 💡 **Suggest features** via GitHub Issues  
- 📝 **Improve documentation**
- 🔧 **Submit code improvements**
- 🌍 **Share usage examples**

## Getting Started

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create** a feature branch
4. **Make** your changes
5. **Test** thoroughly
6. **Submit** a pull request

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/leaf-journal.git
cd leaf-journal

# Create test installation
chmod +x leaf
cp leaf ~/bin/leaf-dev  # or another test location

# Test your changes
~/bin/leaf-dev help
```

## Code Style

- Use **bash best practices**
- Add **comments** for complex logic
- Follow **existing patterns** in the codebase
- Test on **multiple systems** if possible

## Feature Ideas

### Planned Features
- [ ] Date-specific entries (`leaf 2025-07-10`)
- [ ] Mood tracking and statistics
- [ ] Export functions (PDF, markdown)
- [ ] Streak counting
- [ ] Template customization

### Feature Requests
Check [Issues](https://github.com/linux-finn/leaf-journal/issues) for requested features or suggest new ones!

## Testing

Before submitting:

```bash
# Test basic functionality
leaf setup
leaf
leaf yesterday
leaf list
leaf find "test"
leaf help

# Test edge cases
leaf invalid-command
leaf find ""
```

## Pull Request Process

1. **Update documentation** if needed
2. **Add yourself** to contributors list
3. **Describe changes** clearly in PR
4. **Reference issues** if applicable

## Bug Reports

Include:
- **Operating system** and version
- **Bash version** (`bash --version`)
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Error messages** (if any)

## Questions?

Open an issue with the `question` label!

## Code of Conduct

Be respectful, inclusive, and constructive. We're all here to build something useful together! 🌟
```
