Problem Statement:

An investor has $50,000 to allocate among three stocks: Stock A, Stock B, and Stock C. The goal is to maximize the expected return while considering the risk and allocation constraints.

Decision Variables:

Let:
	•	 x_1  = Amount invested in Stock A
	•	 x_2  = Amount invested in Stock B
	•	 x_3  = Amount invested in Stock C

Objective Function (Maximize Return):

The expected annual returns for the stocks are:
	•	Stock A: 8% (0.08)
	•	Stock B: 12% (0.12)
	•	Stock C: 10% (0.10)

Maximize total expected return:


\max Z = 0.08x_1 + 0.12x_2 + 0.10x_3


Constraints:
	1.	Total Investment Constraint (Budget Limit):
The total investment cannot exceed $50,000:

x_1 + x_2 + x_3 \leq 50,000

  2.	Risk Constraint:
Stock B is riskier, so investment in Stock B should not exceed 40% of total investment:

x_2 \leq 0.4(x_1 + x_2 + x_3)

  3.	Minimum Diversification Constraint:
At least $10,000 should be invested in Stock C to ensure diversification:

x_3 \geq 10,000

  4.	Non-Negativity Constraint:
Investment cannot be negative:

x_1, x_2, x_3 \geq 0
