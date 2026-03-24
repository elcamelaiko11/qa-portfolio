# Regression Test Suite – Sample Web Application

## Objective
Ensure that core functionalities remain stable after new releases or bug fixes.

## Covered Modules
- Login & Authentication
- User Registration
- Dashboard Navigation
- Profile Management
- Logout Functionality

## Regression Scope Strategy
High priority features are always included in regression cycles.

### Critical Flow Regression
1. User login with valid credentials
2. Navigation to dashboard
3. Update profile information
4. Logout successfully

### Medium Priority Regression
- Forgot password process
- UI layout validation
- Form validations

### Low Priority Regression
- Minor UI cosmetic checks
- Tooltip messages
- Non-blocking warnings

## Regression Execution Plan
- Execute regression before every production release
- Track failed cases and log defects immediately
- Provide regression summary report to stakeholders

## Tools
- Manual testing
- Test case repository
- Bug tracking tool (JIRA sample)

## Entry Criteria
- Build deployed in QA environment
- Smoke testing passed

## Exit Criteria
- No critical defects open
- All high priority test cases passed
