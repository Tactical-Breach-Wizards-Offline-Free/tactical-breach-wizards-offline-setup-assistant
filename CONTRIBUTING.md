# 🤝 Contributing to Tactical Breach Wizards - Offline Setup Assistant

First off, thank you for considering contributing to our project! 🎉 Every contribution helps make the offline gaming experience better for the entire community.

## 🌟 Ways to Contribute

### 🐛 Bug Reports
Found a bug? Help us squash it!
- Use the [Bug Report Template](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/issues/new?template=bug_report.md)
- Include your system specifications
- Provide steps to reproduce the issue
- Attach screenshots or error logs when possible

### 💡 Feature Requests
Have an idea to improve the setup assistant?
- Use the [Feature Request Template](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/issues/new?template=feature_request.md)
- Explain the problem your feature would solve
- Describe your proposed solution
- Consider alternative approaches

### 🔧 Code Contributions
Ready to get your hands dirty with code?
- Check out our [Good First Issue](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/labels/good%20first%20issue) label
- Look for [Help Wanted](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/labels/help%20wanted) issues
- Fork the repository and create a feature branch
- Follow our coding standards and conventions

### 🌍 Translations
Help make the setup assistant accessible worldwide!
- Check existing translations in `/locales/`
- Add new language files following the existing format
- Test the interface with your translations
- Ensure cultural appropriateness and accuracy

### 📝 Documentation
Improve guides, tutorials, and help resources:
- Fix typos or unclear explanations
- Add missing information
- Create new tutorials or guides
- Update outdated screenshots or examples

## 🚀 Getting Started

### Prerequisites
- **Git**: For version control
- **Node.js 16+**: For development dependencies
- **Python 3.8+**: For build scripts
- **Code Editor**: VS Code recommended with our extensions

### Development Setup
1. **Fork and Clone**
   ```bash
   git clone https://github.com/YOUR_USERNAME/tactical-breach-wizards-offline-setup-assistant.git
   cd tactical-breach-wizards-offline-setup-assistant
   ```

2. **Install Dependencies**
   ```bash
   npm install
   pip install -r requirements-dev.txt
   ```

3. **Run Development Environment**
   ```bash
   npm run dev
   ```

4. **Run Tests**
   ```bash
   npm test
   python -m pytest tests/
   ```

## 📋 Development Guidelines

### Code Style
- **JavaScript/TypeScript**: Follow our ESLint configuration
- **Python**: Follow PEP 8 standards
- **Comments**: Write clear, concise comments explaining complex logic
- **Naming**: Use descriptive names for variables and functions

### Commit Messages
Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting changes
- `refactor`: Code refactoring
- `test`: Adding tests
- `chore`: Maintenance tasks

**Examples:**
- `feat(installer): add support for custom installation paths`
- `fix(ui): resolve button alignment issue on macOS`
- `docs(readme): update installation instructions`

### Pull Request Process

1. **Create Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   git checkout -b fix/issue-number-description
   ```

2. **Make Your Changes**
   - Follow coding standards
   - Add tests for new functionality
   - Update documentation as needed
   - Test thoroughly on multiple platforms

3. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add awesome new feature"
   ```

4. **Push and Create PR**
   ```bash
   git push origin feature/your-feature-name
   ```
   - Open a Pull Request on GitHub
   - Use our [PR Template](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/blob/main/.github/PULL_REQUEST_TEMPLATE.md)
   - Link related issues
   - Provide clear description of changes

5. **Code Review Process**
   - Maintainers will review your PR
   - Address any requested changes
   - Ensure CI/CD checks pass
   - PR will be merged after approval

## 🧪 Testing

### Manual Testing
- Test on Windows, macOS, and Linux
- Verify all functionality works offline
- Check UI responsiveness on different screen sizes
- Test with various game installation scenarios

### Automated Testing
- Unit tests: `npm run test:unit`
- Integration tests: `npm run test:integration`
- End-to-end tests: `npm run test:e2e`
- Coverage report: `npm run test:coverage`

### Test Guidelines
- Write tests for new features
- Maintain >80% code coverage
- Test edge cases and error conditions
- Use descriptive test names

## 🏷️ Issue Labels

We use labels to organize and prioritize issues:

- **Type Labels:**
  - `bug` - Something isn't working
  - `enhancement` - New feature or improvement
  - `documentation` - Documentation improvements
  - `question` - General questions

- **Priority Labels:**
  - `priority: high` - Critical issues
  - `priority: medium` - Important improvements
  - `priority: low` - Nice-to-have features

- **Status Labels:**
  - `good first issue` - Good for newcomers
  - `help wanted` - Community contributions welcome
  - `in progress` - Currently being worked on
  - `needs review` - Awaiting code review

## 💬 Communication

### Getting Help
- **Discord**: Join our [community server](https://discord.gg/tactical-breach-wizards)
- **GitHub Discussions**: Use for questions and ideas
- **Issues**: For bugs and feature requests only
- **Email**: `dev@tbw-offline.com` for private matters

### Community Guidelines
- Be respectful and inclusive
- Help others learn and grow
- Share knowledge and experience
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

## 🎯 Contribution Recognition

We value all contributions and recognize them in several ways:

### Hall of Fame
Outstanding contributors are featured in our:
- **README.md** - Special thanks section
- **Contributors Page** - Detailed contribution history
- **Release Notes** - Credit for specific features

### Badges and Rewards
- **Contributor Badge** - For first-time contributors
- **Veteran Badge** - For regular contributors
- **Expert Badge** - For significant contributions
- **Mentor Badge** - For helping other contributors

### Special Roles
Active contributors may be invited to:
- **Beta Testing Team** - Early access to new features
- **Moderation Team** - Help manage community spaces
- **Maintainer Role** - Direct repository access

## 📚 Resources

### Learning Materials
- [Git Tutorial](https://learngitbranching.js.org/) - Interactive Git learning
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) - MDN JavaScript documentation
- [Python Tutorial](https://docs.python.org/3/tutorial/) - Official Python tutorial
- [Electron Docs](https://www.electronjs.org/docs) - Desktop app development

### Development Tools
- **VS Code Extensions:**
  - ESLint - JavaScript linting
  - Prettier - Code formatting
  - GitLens - Enhanced Git integration
  - Thunder Client - API testing

### Project-Specific Documentation
- [Architecture Overview](docs/architecture.md) - System design
- [API Reference](docs/api.md) - Internal APIs
- [Build Process](docs/build.md) - How releases are created
- [Troubleshooting](docs/troubleshooting.md) - Common issues

## 🔄 Release Process

### Versioning
We follow [Semantic Versioning](https://semver.org/):
- **Major (X.0.0)** - Breaking changes
- **Minor (1.X.0)** - New features, backwards compatible
- **Patch (1.1.X)** - Bug fixes

### Release Schedule
- **Patch releases**: As needed for critical bugs
- **Minor releases**: Monthly feature updates
- **Major releases**: Quarterly with significant changes

### Beta Testing
- Beta versions available 1-2 weeks before release
- Community testing via Discord and GitHub
- Feedback incorporated before stable release

---

## 🙏 Thank You!

Every contribution, no matter how small, helps make this project better. We're grateful for:

- **Bug reporters** who help us find issues
- **Feature requesters** who share great ideas
- **Code contributors** who implement improvements
- **Translators** who make the tool accessible
- **Documentarians** who help others understand
- **Community members** who support each other

**Ready to contribute?** Check out our [Good First Issues](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/labels/good%20first%20issue) and join the adventure! 🚀

---

<p align="center">
<strong>Happy Contributing! 🎮✨</strong><br>
Let's make offline gaming accessible for everyone!
</p> 