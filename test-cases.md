# Manual Testing: Login Page

## Project Information
- **Project:** Login Page Manual Testing
- **Website:** https://practicetestautomation.com/practice-test-login/
- **Testing Type:** Manual Testing
- **Tester Level:** Beginner

## Test Cases

| Test Case ID | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC001 | Login with valid credentials | Login successful | Logged In Successfully | PASS |
| TC002 | Login with an incorrect password | Login rejected | Your password is invalid! | PASS |
| TC003 | Submit both fields empty | Login rejected | Your username is invalid! | PASS |
| TC004 | Submit with an empty username | Login rejected | Your username is invalid! | PASS |
| TC005 | Submit with an empty password | Login rejected | Your password is invalid! | PASS |
| TC006 | Check password visibility | Password characters hidden | Password characters were hidden | PASS |
| TC007 | Check error message location | Error displayed appropriately | Error appeared on the same page | PASS |
| TC008 | Enter spaces in the username | Login rejected | Your username is invalid! | PASS |
| TC009 | Enter spaces in the password | Login rejected | Your password is invalid! | PASS |
| TC010 | Enter an uppercase username | Result depends on requirements | Your username is invalid! | NEEDS INVESTIGATION |

## Notes
- Tests were performed manually in a web browser.
- Results reflect the observed behavior during testing.
- TC010 requires confirmation of the username case-sensitivity requirement.
- Passing these tests does not prove that the entire application is bug-free.
