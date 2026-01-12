# Contributing to Jamf DLP Migration

Thank you for your interest in contributing! 🎉

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/Jamf-DLP-Migration.git`
3. **Create** a branch: `git checkout -b feature/your-feature`
4. **Make** your changes
5. **Test** thoroughly
6. **Commit**: `git commit -m 'Add feature'`
7. **Push**: `git push origin feature/your-feature`
8. **Open** a Pull Request

## 📋 Guidelines

### Code Style

- Use meaningful variable names
- Add comments for complex logic
- Follow shell script best practices
- Use `shellcheck` for linting

### Commit Messages

```
type(scope): description

[optional body]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

### Testing

Before submitting:

```bash
# Run shellcheck
shellcheck migrate_to_dlp.sh

# Test in dry-run mode
DRY_RUN=true sudo ./migrate_to_dlp.sh
```

## 🐛 Bug Reports

Please include:
- macOS version
- Jamf Pro version
- Error messages
- Steps to reproduce
- Log output

## 💡 Feature Requests

Open an issue with:
- Clear description
- Use case
- Expected behavior

## 📝 Pull Request Process

1. Update documentation if needed
2. Add tests for new features
3. Ensure all tests pass
4. Request review from maintainers

---

Thank you for contributing! 🙏
