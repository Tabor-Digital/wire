# Security policy

## Reporting a vulnerability

Please do not open a public issue for a security problem.

Use GitHub's private reporting: open the **Security** tab of this repository and choose **Report a vulnerability**.

Include the WIRE version, your Windows version, what you found, and steps to reproduce it.

[TODO: owner adds a private contact such as an email address, as a second way to report]

## Supported versions

Only the latest release is supported. WIRE is a young product (version 0.1.0).

## Scope

WIRE runs locally. Its HTTP API listens only on `127.0.0.1` and requires a token. Plugins are Python code that run inside WIRE with your Windows user's permissions and are disabled by default. Reports about third-party software such as Virtual Audio Cable should go to that software's author.
