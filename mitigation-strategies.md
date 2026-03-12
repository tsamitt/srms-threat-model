# Mitigation Strategies

## Prevent SQL Injection

- use prepared statements
- use parameterized queries
- validate and sanitize input
- avoid dynamic SQL where possible

## Enforce Access Control

- implement role-based access control
- verify authorization on the server side
- restrict direct access to protected resources

## Secure File Uploads

- restrict allowed file types
- validate file size
- scan uploaded files where possible
- store uploads securely

## Improve Authentication

- require strong passwords
- hash and salt stored passwords
- consider multi-factor authentication
- implement secure session handling

## Protect Availability

- rate limit requests
- monitor unusual traffic
- validate input sizes
- deploy logging and alerting

## Conclusion

Threat modeling helps improve application security by identifying likely attack paths before deployment and guiding the design of safer systems.
