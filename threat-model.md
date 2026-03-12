# Threat Model

## System Overview

The Smart Service Request Management System is a web-based application that allows users to submit service requests, staff to manage and update requests, and managers to review reports and performance data.

## Security Goals

- protect request data from unauthorized access
- preserve the integrity of request updates and status changes
- maintain system availability for users and staff
- protect authentication and user role data

## Key Assets

- user accounts
- service request records
- comments and attachments
- role-based permissions
- audit and status history logs

## Threat Areas

Potential threat areas include:

- authentication and login
- user input fields
- file uploads
- role-based access control
- sensitive data exposure
- application availability
