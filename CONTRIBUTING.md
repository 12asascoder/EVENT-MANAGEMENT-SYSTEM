# Contributing to EventFlow Pro

Thank you for your interest in contributing to EventFlow Pro! This document provides guidelines and information for contributors.

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/EVENT-MANAGEMENT-SYSTEM.git
   cd EVENT-MANAGEMENT-SYSTEM
   ```
3. **Add upstream remote**:
   ```bash
   git remote add upstream https://github.com/12asascoder/EVENT-MANAGEMENT-SYSTEM.git
   ```

## 🔄 Development Workflow

1. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** and test thoroughly

3. **Commit your changes**:
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

4. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request** on GitHub

## 📝 Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `test:` - Adding or updating tests
- `chore:` - Maintenance tasks

Examples:
- `feat: add QR code scanner for mobile devices`
- `fix: resolve authentication token expiration issue`
- `docs: update API documentation for events endpoint`

## 🧪 Testing

Before submitting a PR, please ensure:

1. **Backend tests pass**:
   ```bash
   cd backend
   npm test
   ```

2. **Frontend builds successfully**:
   ```bash
   cd frontend
   npm run build
   ```

3. **Linting passes**:
   ```bash
   npm run lint
   ```

## 📋 Pull Request Guidelines

### Before Submitting:
- [ ] Code follows the project's style guidelines
- [ ] Self-review of your code has been performed
- [ ] Comments have been added to hard-to-understand areas
- [ ] Documentation has been updated accordingly
- [ ] Tests have been added/updated for new functionality
- [ ] All tests pass locally

### PR Description Template:
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
Describe the tests you ran to verify your changes

## Screenshots (if applicable)
Add screenshots to help explain your changes

## Checklist
- [ ] My code follows the style guidelines
- [ ] I have performed a self-review
- [ ] I have commented my code
- [ ] I have made corresponding changes to documentation
- [ ] My changes generate no new warnings
```

## 🐛 Reporting Bugs

When reporting bugs, please include:

1. **Environment details**:
   - OS and version
   - Node.js version
   - Browser (for frontend issues)

2. **Steps to reproduce**:
   - Clear, numbered steps
   - Expected vs actual behavior

3. **Additional context**:
   - Screenshots if applicable
   - Error messages/logs
   - Any relevant configuration

## 💡 Suggesting Features

Feature requests are welcome! Please provide:

1. **Clear description** of the feature
2. **Use case** - why would this be useful?
3. **Proposed implementation** (if you have ideas)
4. **Additional context** or examples

## 🏗️ Development Setup

### Prerequisites:
- Node.js 18+
- MongoDB 6+
- Git

### Environment Variables:
Copy `env.example` to `.env` and configure:
```env
MONGODB_URI=mongodb://localhost:27017/arnav-events
JWT_SECRET=your-secret-key
PORT=5001
NODE_ENV=development
```

### Running Locally:
```bash
# Backend
cd backend && npm install && npm run dev

# Frontend (in another terminal)
cd frontend && npm install && npm run dev
```

## 📞 Getting Help

- **Issues**: Use GitHub Issues for bug reports and feature requests
- **Discussions**: Use GitHub Discussions for questions and general discussion
- **Email**: Contact [arnavpuggal@example.com](mailto:arnavpuggal@example.com)

## 📜 Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) Code of Conduct. By participating, you agree to uphold this code.

## 🙏 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

Thank you for contributing to EventFlow Pro! 🎉
