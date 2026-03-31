# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability, please report it by opening a GitHub issue or contacting the maintainer directly.

**Please include:**
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

We will respond as quickly as possible and work to address the issue.

## Security Considerations

This ESPHome project uses Bluetooth and MQTT:

- Use authentication for your MQTT broker
- Keep `secrets.yaml` secure and never commit real credentials
- Keep ESPHome and ESP32 firmware updated
- Use encrypted OTA updates
