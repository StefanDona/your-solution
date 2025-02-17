Test Cases for Youth Building Savings Tariff
Below is a detailed set of test cases covering both positive and negative scenarios for the Youth Building Savings tariff.

Test Case 1: Tariff Selection Validation
Objective: Ensure the user can select the "Youth Building Savings" tariff successfully.

Preconditions:

User is on the calculator page.
Other tariffs are available for selection.
Steps:

Navigate to the tariff selection section.
Click on the "Choose" button for "Youth Building Savings".
Expected Result:

The tariff is marked as selected.
Other tariffs remain unselected.0

Test Case 2: Monthly Deposit Calculation (Positive Test)
Objective: Validate calculation of total savings for a valid monthly deposit.

Preconditions:

"Youth Building Savings" tariff is selected.
Steps:

Select "monthly" as the deposit frequency.
Enter "100 EUR" as the deposit amount.
Expected Result:

The system correctly displays the total deposits, bonuses, and final savings amount.
The calculated total matches the expected value based on the tariff rules.

Test Case 3: Quarterly Deposit Calculation (Positive Test)
Objective: Verify correct calculations for a quarterly deposit.

Preconditions:

"Youth Building Savings" tariff is selected.
Steps:

Select "quarterly" as the deposit frequency.
Enter "300 EUR" as the deposit amount.

Expected Result:

The total savings calculation reflects quarterly deposits correctly.
The system applies bonuses and fees accordingly.

Test Case 4: Minimum Deposit Value (Boundary Test)
Objective: Verify the system handles the lowest acceptable deposit amount correctly.

Preconditions:

"Youth Building Savings" tariff is selected.
Steps:

Enter the minimum allowed deposit (e.g., "40 EUR").

Expected Result:

The system calculates the savings accurately.
No validation errors occur for the minimum value.

Test Case 5: Maximum Deposit Value (Boundary Test)
Objective: Verify the system processes the highest allowed deposit amount correctly.

Preconditions:

"Youth Building Savings" tariff is selected.
Steps:

Enter the maximum deposit amount (e.g., "13,888 EUR").
Click "Calculate Result".
Expected Result:

The system calculates the savings correctly.
No validation errors occur for the maximum value.

Test Case 6: Invalid Deposit Amount
Objective: Verify that invalid deposit values trigger proper validation messages.

Preconditions:

"Youth Building Savings" tariff is selected.
Steps:

Enter a value under 40 EUR and over 13888 EUR as the deposit amount.

Expected Result:

A pop-up with the corresponding message is displayed
Calculation does not proceed.

Test Case 7: PDF Download Functionality
Objective: Verify that the calculated results can be downloaded as a PDF.

Preconditions:

A valid calculation has been performed.
Steps:

Click on "Download PDF".

Expected Result:

A properly formatted PDF is generated and downloaded.
The content matches the displayed calculation results.

Test Case 9: Cross-Browser Compatibility
Objective: Ensure the calculator functions properly on different browsers.

Steps:

Open the calculator in Chrome, Firefox, Edge, and Safari.
Perform a test calculation with valid inputs.

Expected Result:

The results are consistent across all tested browsers.
The UI renders correctly in each browser.

Test Case 10: Mobile Responsiveness Test
Objective: Verify that the page and calculator are fully functional on mobile devices.

Steps:

Open the calculator on a mobile device.
Enter a valid deposit amount and calculate results.

Expected Result:

The page adjusts properly to the mobile screen.
The calculation results are clearly visible and accessible.
