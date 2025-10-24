# Security Policy

## Supported Versions

As VSCode+ primarily provides configurations, extensions recommendations, and documentation, security concerns are relatively limited. However, we take security seriously.

| Repository Type | Supported |
| --------------- | --------- |
| Latest configurations | ✅ |
| Documentation | ✅ |
| Archived repositories | ❌ |

## Reporting a Vulnerability

If you discover a security vulnerability within any VSCode+ repository, please report it responsibly:

### What to Report

- Security issues in recommended extensions (we'll update recommendations)
- Malicious code in configuration files
- Vulnerabilities in dev container configurations
- Scripts that could execute harmful commands
- Documentation that could lead to security issues

### How to Report

**Please DO NOT open a public issue for security vulnerabilities.**

Instead:

1. **Email**: Send details to [INSERT SECURITY EMAIL]
2. **Subject**: Start with "SECURITY:" followed by a brief description
3. **Include**:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if you have one)
   - Your contact information

### What to Expect

- **Acknowledgment**: Within 48 hours
- **Assessment**: Within 5 business days
- **Updates**: Regular communication on status
- **Resolution**: Fix or mitigation as quickly as possible
- **Credit**: Public acknowledgment (if desired) after the fix

## Security Best Practices

When using VSCode+ configurations:

### Extension Safety

- ✅ Review extensions before installing
- ✅ Check extension publisher and ratings
- ✅ Keep extensions updated
- ✅ Remove unused extensions
- ❌ Don't install from unknown sources

### Configuration Safety

- ✅ Review settings before applying
- ✅ Understand what each setting does
- ✅ Test in a safe environment first
- ✅ Keep backups of your settings
- ❌ Don't blindly copy-paste configurations

### Dev Container Safety

- ✅ Review Dockerfile and devcontainer.json
- ✅ Use official base images when possible
- ✅ Keep containers updated
- ✅ Limit container permissions
- ❌ Don't run containers with unnecessary privileges

### Script Safety

- ✅ Review scripts before executing
- ✅ Understand what commands will run
- ✅ Run with appropriate permissions
- ✅ Use version control
- ❌ Don't run scripts from untrusted sources

## Dependency Security

We strive to:

- Recommend extensions from verified publishers
- Keep documentation updated with latest security practices
- Monitor for security issues in recommended tools
- Update configurations when security issues are discovered
- Provide clear warnings for potentially risky configurations

## Disclosure Policy

- Security issues will be disclosed after a fix is available
- We'll credit researchers who report issues (with permission)
- Critical vulnerabilities will be announced across all channels
- We'll maintain a security advisory for significant issues

## Comments on This Policy

If you have suggestions for improving this policy, please open an issue or contact the maintainers.

---

**Last Updated**: October 23, 2025
