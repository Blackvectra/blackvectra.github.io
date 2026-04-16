# MTA-STS Policy

This repository hosts the MTA-STS policy for secure email delivery.

## Policy Location
https://mta-sts.yourdomain.com/.well-known/mta-sts.txt

## Configuration
- Version: STSv1
- Mode: enforce
- Mail Provider: Microsoft 365 (Exchange Online)
- TLS Reporting: Enabled via DNS

## Purpose
This policy enforces TLS encryption for inbound SMTP connections and protects against downgrade and man-in-the-middle attacks.

## Standards
- RFC 8461 – SMTP MTA Strict Transport Security (MTA-STS)
- RFC 8460 – SMTP TLS Reporting (TLS-RPT)
