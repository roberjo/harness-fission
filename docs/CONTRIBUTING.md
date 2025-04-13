# Contributing Guidelines

## 🤝 Welcome!

Thank you for considering contributing to our Harness pipeline framework. This document outlines the process and guidelines for contributing.

## 📋 Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Follow best practices
- Document your changes

## 🔄 Development Workflow

### 1. Setting Up Development Environment

```bash
# Clone the repository
git clone <repository-url>
cd harness-fission

# Create a new branch
git checkout -b feature/your-feature-name
```

### 2. Making Changes

#### Pipeline Changes
- Follow the template structure
- Test in development first
- Update documentation
- Add security checks

#### Documentation Changes
- Follow markdown standards
- Include examples
- Update table of contents
- Check links

### 3. Testing

1. **Local Testing**
   - Validate YAML syntax
   - Test template rendering
   - Check variable references

2. **Pipeline Testing**
   - Run in development environment
   - Verify all steps execute
   - Check security scans
   - Validate load tests

### 4. Submitting Changes

1. **Prepare Your Commit**
   ```bash
   git add .
   git commit -m "feat: description of your changes"
   ```

2. **Create Pull Request**
   - Use the PR template
   - Link related issues
   - Add screenshots if relevant
   - Tag reviewers

## 📝 Style Guide

### Commit Messages

Follow conventional commits:
- `feat:` New features
- `fix:` Bug fixes
- `docs:` Documentation
- `chore:` Maintenance
- `test:` Test updates

### YAML Style

```yaml
# Good
steps:
  - name: Clear Step Name
    identifier: unique_identifier
    type: Step_Type
    spec:
      property: value

# Bad
steps:
- name: unclear
  identifier: id1
  type: type1
  spec:
    prop: val
```

### Documentation Style

- Use clear headings
- Include code examples
- Add emojis for visibility
- Keep content concise

## 🔍 Review Process

### Pull Request Reviews

1. **Automated Checks**
   - YAML validation
   - Documentation links
   - Security scanning

2. **Manual Review**
   - Code review
   - Documentation review
   - Security review

### Approval Requirements

| Environment | Reviewers | Notes |
|-------------|-----------|--------|
| Development | 1 | Technical review |
| Production | 2 | Technical + Security |

## 🐛 Issue Reporting

### Bug Reports

Include:
- Description
- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details

### Feature Requests

Include:
- Use case
- Proposed solution
- Alternative approaches
- Benefits

## 📚 Resources

- [Harness Documentation](https://docs.harness.io)
- [Terraform Docs](https://www.terraform.io/docs)
- [JMeter Documentation](https://jmeter.apache.org/docs)
- [WIZ Documentation](https://docs.wiz.io)

## 🔄 Release Process

1. **Version Bumping**
   - Update version numbers
   - Update changelog
   - Tag release

2. **Documentation Updates**
   - Update version references
   - Add release notes
   - Update examples

3. **Testing**
   - Full pipeline test
   - Security validation
   - Performance validation

## ❓ Getting Help

- Create an issue
- Join our Slack channel
- Check documentation
- Contact maintainers

---

Thank you for contributing! 🙏