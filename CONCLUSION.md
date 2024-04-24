# Ticket-101 Code Review (front-end)

## Description

Overall, the modified code enhances clarity, readability, and error handling, making it a significant improvement over the original version.

## Code Review:

1. Clarity and Readability:
- The modified code provides clearer logic by separating cases based on different conditions.
- Each case is well-commented, explaining the condition and the corresponding action taken.
2. Error Handling:
- The modified code handles cases where the applied loan amount is less than, greater than, or equal to the approved loan amount.
- It properly sets the _loanAmountResult and _loanPeriodResult based on these conditions.
- In case no suitable loan amount is found within the selected period, it sets appropriate error messages.
3. Correction:
- The code now correctly displays '12 months' instead of '6 months' in the UI. Which is the right minimum range of loan appliance