# Unprotected Admin Functionality

## Vulnerability Type
Broken Access Control

## Difficulty
Apprentice

## Platform
PortSwigger Web Security Academy

## Goal
Solve the lab by accessing the admin panel and deleting the user "carlos".

## Root Cause
The application exposed administrative functionality without proper authorization checks.

## Exploitation Steps
1. Browse the application
2. Discover hidden admin functionality
3. Access the admin panel directly
4. Delete the user "carlos"

## Impact
An attacker can gain unauthorized access to administrative functionality and perform privileged actions.

## Prevention
- Enforce server-side authorization checks
- Restrict admin endpoints
- Implement role-based access control
- Disable direct access to sensitive functionality

## What I Learned
This lab helped me understand how exposed administrative endpoints can lead to privilege escalation.
