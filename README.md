# Cursor Secure Coding Rules - OWASP ASVS

A comprehensive collection of secure coding rules based on the OWASP Application Security Verification Standard (ASVS), implemented as MDC (Markdown Code) files for Cursor.

## What is OWASP ASVS?

The [OWASP Application Security Verification Standard (ASVS)](https://owasp.org/www-project-application-security-verification-standard/) is a framework of security requirements and controls that defines increasing levels of application security verification. It helps developers build secure software by providing:

- A basis for testing application security controls
- Guidance for security control requirements
- A standard that different organizations can adopt

## Project Structure

This repository contains MDC rules organized by ASVS security level and category:

```
.cursor/rules/owasp-asvs/
├── level-1/         # Essential security requirements (minimal)
│   ├── input-validation.mdc
│   ├── authentication.mdc
│   ├── session-management.mdc
│   ├── access-control.mdc
│   ├── cryptography.mdc
│   └── ...
│
└── level-2/         # Standard security requirements (comprehensive)
    ├── input-validation.mdc
    ├── authentication.mdc
    ├── session-management.mdc
    ├── access-control.mdc
    ├── cryptography.mdc
    └── ...
```

## Security Levels

This repository implements two ASVS security levels:

**Level 1 (L1)**: Essential security requirements that can be verified without access to source code. Suitable for all applications.

**Level 2 (L2)**: Standard security requirements for applications that contain sensitive data. Includes everything from L1 plus more comprehensive defensive techniques.

## Language Support

Each rule includes code examples for:
- JavaScript
- Python

## How to Use

1. Clone this repository
2. Copy the `.cursor` directory to your project's root folder
3. Cursor will automatically use these secure coding rules when coding in your project

## Contributors

This project was created to promote secure coding practices and help developers build more secure applications.

## License

MIT
