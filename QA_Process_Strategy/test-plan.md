# Sample Test Plan – Web Application

## Test Objective
The objective of this testing is to validate the core functionalities of the web application including authentication, user registration, dashboard usability and profile management.

## Test Scope
IN SCOPE:
- Login functionality
- Registration process
- Dashboard features
- Profile update

OUT OF SCOPE:
- Payment integration
- Third-party API services
- Performance testing

## Test Approach
Manual functional testing will be performed based on defined test scenarios and user workflows.

## Test Environment
- Browser: Google Chrome
- OS: Windows 10
- Test URL: Sample Test Environment

## Test Types
- Functional Testing
- Regression Testing
- UI Testing
- Smoke Testing

## Entry Criteria
- Requirements finalized
- QA environment ready
- Test data prepared
- Stable build deployed

## Exit Criteria
- All planned test cases executed
- No critical defects open
- Test summary report completed

## Registration Feature Test Cases
| Test Case ID | Scenario | Steps | Expected Result | Priority | Type |
|-------------|---------|------|----------------|---------|------|
| TC006 | Valid Registration | Enter valid user details then click Register | Account created successfully | High | Functional |
| TC007 | Existing Email | Register using already registered email | Error message should appear | High | Negative |
| TC008 | Weak Password | Enter password below required criteria | Validation message should appear | Medium | Validation |
| TC009 | Empty Required Fields | Click register without filling form | Required field errors displayed | Medium | Validation |

## Dashboard Feature Test Cases

| Test Case ID | Scenario | Steps | Expected Result | Priority | Type |
|-------------|---------|------|----------------|---------|------|
| TC010 | Dashboard Load | Login and navigate to dashboard | Dashboard loads successfully | High | Functional |
| TC011 | Widget Display | Check dashboard widgets visibility | All widgets displayed correctly | Medium | UI |
| TC012 | Broken Navigation Link | Click dashboard menu links | Links redirect to correct pages | High | Functional |

## Profile Management Test Cases

| Test Case ID | Scenario | Steps | Expected Result | Priority | Type |
|-------------|---------|------|----------------|---------|------|
| TC013 | Update Profile Info | Edit profile details and save | Profile updated successfully | High | Functional |
| TC014 | Upload Invalid Image | Upload unsupported file format | Error message displayed | Medium | Validation |
| TC015 | Cancel Profile Update | Edit then click cancel | No changes should be saved | Low | Usability |
