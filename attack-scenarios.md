# Attack Scenarios

## Scenario 1 - SQL Injection

If user input is not properly validated or parameterized, an attacker may attempt to inject SQL through form fields such as request title or description.

### Impact

- unauthorized data access
- data modification
- data deletion

## Scenario 2 - Broken Access Control

A user may attempt to access pages or data intended for staff or managers.

### Impact

- unauthorized viewing of requests
- privilege misuse
- exposure of sensitive data

## Scenario 3 - Malicious File Upload

If the system accepts attachments, an attacker may try to upload unsafe or unexpected file types.

### Impact

- malware delivery
- storage abuse
- server-side processing risk

## Scenario 4 - Weak Authentication

If passwords are weak or authentication is poorly implemented, accounts may be compromised.

### Impact

- unauthorized access
- impersonation
- request tampering

## Scenario 5 - Denial of Service

An attacker may flood the application with excessive requests or malformed input.

### Impact

- service disruption
- degraded performance
- reduced availability
