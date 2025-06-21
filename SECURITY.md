# 🔐 Security Policy

## Supported Versions

We actively support the following versions of the Tactical Breach Wizards Offline Setup Assistant:

| Version | Supported          |
| ------- | ------------------ |
| 2.1.x   | ✅ Yes             |
| 2.0.x   | ✅ Yes             |
| 1.9.x   | ⚠️ Limited Support |
| < 1.9   | ❌ No              |

## 🛡️ Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them responsibly through one of these channels:

### 📧 Email
Send a detailed report to: **security@tbw-offline.com**

### 🔒 GitHub Security Advisory
Use GitHub's private vulnerability reporting feature:
1. Go to the [Security tab](https://github.com/Tactical-Breach-Wizards-Offline-Free/tactical-breach-wizards-offline-setup-assistant/security)
2. Click "Report a vulnerability"
3. Fill out the form with details

### 💬 Encrypted Communication
For sensitive reports, you can use our PGP key:
```
-----BEGIN PGP PUBLIC KEY BLOCK-----
[Our PGP key would be here in a real implementation]
-----END PGP PUBLIC KEY BLOCK-----
```

## 📋 What to Include

When reporting a security vulnerability, please include:

### Required Information
- **Description**: Clear description of the vulnerability
- **Impact**: Potential impact and attack scenarios
- **Reproduction**: Steps to reproduce the issue
- **Environment**: OS, version, and configuration details
- **Evidence**: Screenshots, logs, or proof of concept (if safe)

### Optional but Helpful
- **Severity Assessment**: Your estimation of severity
- **Suggested Fix**: If you have ideas for remediation
- **References**: Related CVEs or security advisories

## ⏱️ Response Timeline

We take security seriously and will respond promptly:

| Timeline | Action |
|----------|--------|
| **24 hours** | Initial acknowledgment of your report |
| **3 days** | Preliminary assessment and severity rating |
| **7 days** | Detailed investigation and response plan |
| **30 days** | Security fix released (target, may vary by complexity) |

## 🔄 Disclosure Process

We follow responsible disclosure practices:

1. **Private Disclosure**: You report the vulnerability privately
2. **Investigation**: We investigate and develop a fix
3. **Patch Development**: We create and test the security fix
4. **Coordinated Release**: We release the fix and public advisory
5. **Public Disclosure**: Details are shared publicly after fix is available

## 🏆 Security Researcher Recognition

We believe in recognizing security researchers who help us improve:

### Hall of Fame
Researchers who report valid vulnerabilities will be:
- Listed in our Security Hall of Fame (with permission)
- Credited in release notes and security advisories
- Invited to our private security discussion channel

### Bounty Program
While we don't currently offer monetary rewards, we provide:
- **Recognition**: Public acknowledgment of your contribution
- **Swag**: Exclusive project merchandise
- **Access**: Early access to new features and beta versions
- **References**: Professional references for your security work

## 🛡️ Security Best Practices

### For Users
- **Keep Updated**: Always use the latest version
- **Verify Downloads**: Check file hashes and signatures
- **Secure Storage**: Store the setup assistant in a secure location
- **Permissions**: Run with minimal necessary permissions
- **Antivirus**: Keep your antivirus software updated

### For Developers
- **Code Review**: All code changes require security review
- **Dependencies**: Regularly audit and update dependencies
- **Testing**: Include security testing in our CI/CD pipeline
- **Secrets**: Never commit secrets or sensitive data
- **Access Control**: Follow principle of least privilege

## 🔒 Security Features

### Built-in Security
- **Code Signing**: All releases are digitally signed
- **Checksum Verification**: SHA-256 checksums for all downloads
- **Sandboxing**: Assistant runs in restricted environment
- **No Network Access**: Completely offline operation (no data transmission)
- **Permission Minimal**: Requests only necessary system permissions

### Privacy Protection
- **No Telemetry**: We don't collect usage data or analytics
- **Local Storage**: All data stays on your device
- **No Account**: No registration or personal information required
- **Audit Trail**: Clear logs of all system changes made

## 🚨 Known Security Considerations

### Current Limitations
- **Administrative Privileges**: May require elevated permissions for installation
- **File System Access**: Needs access to game directories
- **Registry Access**: May modify system registry on Windows
- **Process Management**: Can launch and manage game processes

### Risk Mitigation
- All file operations are logged and reversible
- Registry changes are backed up before modification
- Process management is limited to game-related executables
- User consent is required for all system modifications

## 📚 Security Resources

### External Resources
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CWE/SANS Top 25](https://cwe.mitre.org/top25/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

### Project-Specific
- [Threat Model](docs/security/threat-model.md) (Internal)
- [Security Architecture](docs/security/architecture.md) (Internal)
- [Incident Response Plan](docs/security/incident-response.md) (Internal)

## 📞 Contact Information

For security-related questions or concerns:

- **Security Team**: security@tbw-offline.com
- **General Contact**: contact@tbw-offline.com
- **Discord**: #security channel in our server (invite-only)

## 🏅 Past Security Advisories

We maintain transparency about past security issues:

### 2024
- **TBW-2024-001** (Medium): Path traversal in extraction process - *Fixed in v2.0.3*
- **TBW-2024-002** (Low): Information disclosure in debug logs - *Fixed in v2.1.0*

### Historical
- No security advisories prior to 2024

---

**Thank you for helping keep our community safe!** 🛡️

Every security report, regardless of severity, helps us build a more secure and trustworthy tool for the gaming community. 