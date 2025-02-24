Test Cases for Website TestingObjectiveThe objective of these test cases is to validate the functionality, performance, and user experience of the website https://www.demoblaze.com/. These tests ensure that all features work as expected and meet the required standards.

Test Case DetailsTest Scope: Covers core functionalities including navigation, form validation, responsiveness, and performance.

Test Environment: Web browser testing on different devices and resolutions.

Test Scenarios:

UI/UX validation

Functional correctness

Load and performance testing

Security checks

Test ResultsThe following test cases were executed, and the results were documented. The tests that failed are listed below:

Verify register with a username with emojis

Result: Webpage made the registration successfully when it shouldn't be accepted with emojis.

Verify sign-up with a very long password

Result: A password of more than 128 characters was introduced and permitted. It should have a limit of characters.

Update product quantity

Result: The same item appears as if it were different items, so to change the quantity it must be deleted one by one.

Place order with an empty cart

Result: Webpage opened the form asking for user data to finish the purchase, which should not happen.

How to UseReview the provided test case images.

Analyze the failed tests and report necessary fixes.

Implement changes and re-test if needed.

ContactFor any queries or clarifications, reach out to the test author or project manager.

## Test Case Screenshots

Here are some screenshots of the executed test cases:

- **Test Case 1:** ![Test Case 1](https://github.com/ceruz99/demoBlazeTests/blob/main/screenshots/CartTestCases/TestCase1.JPG)
- **Test Case 2:** [View Screenshot](https://github.com/ceruz99/demoBlazeTests/blob/main/screenshots/CartTestCases/TestCase2.JPG)

