Title: Bonus Calculation Off by 1 EUR (Expected 258 EUR, Actual 259 EUR) in Jugend Bausparen Contract

Description:
When calculating the bonus for the Jugend Bausparen contract, the system returns a bonus of 259 EUR. However, based on the defined rules, the bonus should be calculated as follows:

2025 Bonus: 1.5% of the annual deposit (1,200 EUR) = 18 EUR
2026–2030 Bonus: 4% of the annual deposit (1,200 EUR) for 5 years = 240 EUR
Total Expected Bonus: 18 EUR + 240 EUR = 258 EUR
Steps to Reproduce:

Set up a Jugend Bausparen scenario with monthly deposits of 100 EUR
Check the calculated bonus in the contract summary
Observe that the bonus is displayed as 259 EUR instead of the expected 258 EUR

Expected Result:
The bonus should be calculated as 258 EUR.

Actual Result:
The bonus is calculated and displayed as 259 EUR.

Severity - Minor
Priority - Medium

Title: Bonus exceds the maximum value

Description:
When calculating the bonus for the Jugend Bausparen contract anually with 1300 EUR , the system returns a bonus of 262 EUR.

Steps to Reproduce:

Set up a Jugend Bausparen scenario with anually deposits of 1300 EUR
Check the calculated bonus in the contract summary
Observe that the bonus is displayed as 262 EUR instead of the expected 258 EUR

Expected Result:
The bonus should be calculated as 262 EUR.

Actual Result:
The bonus is calculated and displayed as 258 EUR.

Severity - Minor
Priority - Medium

Title: Entgelt Kontoführung (derzeit) is not described cleaary

Description:
The Entgelt Kontoführung (derzeit) is not described clearly in the documentation. The fee for account management changes in accordance with the salary of the employees of the Raiffeisen Banking Group in accordance with the collective agreement is not very clear.

Steps to Reproduce:

Set up a Jugend Bausparen scenario with monthly deposits of 100 EUR
Check the calculated bonus in the contract summary
Observe The Entgelt Kontoführung (derzeit)

Expected Result:
The Entgelt Kontoführung (derzeit) to be clear described if is anually or for all 6 years and calulated acordingly

Actual Result:
TThe Entgelt Kontoführung (derzeit) is not clear described if is anually or for all 6 years, if is anually should be 6 times bigger

Severity - Major
Priority - Major
