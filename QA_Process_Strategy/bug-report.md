# Sample Bug Report

## Bug ID
BUG-001

## Title
Login button becomes unresponsive after multiple invalid password attempts

## Environment
Browser: Google Chrome  
OS: Windows 11  
Build Version: v1.0.3  
Test Environment: UAT  

## Severity
High  

## Priority
Critical  

## Description
When a user enters an incorrect password multiple times, the login button becomes disabled and does not allow further attempts even after entering correct credentials.

## Steps to Reproduce
1. Navigate to the login page  
2. Enter a valid username  
3. Enter an incorrect password  
4. Click Login  
5. Repeat incorrect login attempts 3–5 times  
6. Enter correct password  
7. Click Login  

## Expected Result
User should still be able to login after entering the correct credentials.

## Actual Result
Login button becomes unresponsive and user cannot proceed.

## Attachments
(Screenshots / screen recordings)

## Status
Open

## Reported By
QA Team
