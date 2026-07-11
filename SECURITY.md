# Security Policy

## 🔒 Supported Versions

| Version | Supported |
|---------|-----------|
| Latest  | ✅ Yes    |
| < Latest| ❌ No     |

## 🛡️ Reporting a Vulnerability

**Do NOT create a public GitHub issue for security vulnerabilities.**

Please email: **CaputoDav@gmail.com**

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

### Response Timeline

| Timeframe | Action |
|-----------|--------|
| 24 hours | Acknowledgment |
| 72 hours | Initial assessment |
| 7 days | Status update |
| 30 days | Resolution target |

## 🔐 Security Best Practices

### For Users

1. **Never commit credentials** to version control
2. **Use environment variables** for Jamf API credentials
3. **Keep dependencies updated**
4. **Run with minimum required privileges**

### Script Security

```bash
# ❌ Bad - Hardcoded credentials
JAMF_USER="admin"
JAMF_PASS="password123"

# ✅ Good - Environment variables
JAMF_USER="${JAMF_API_USER}"
JAMF_PASS="${JAMF_API_PASSWORD}"
```

## ✅ Security Checklist

- [ ] Jamf API credentials stored securely
- [ ] Script run with `sudo` only when necessary
- [ ] Logs reviewed for sensitive data exposure
- [ ] Test on a single non-production machine before wide deployment

---

Thank you for helping keep this project secure! 🙏
