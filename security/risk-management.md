# Risk Management

Borrowing against volatile assets involves risk. Here is how to manage it.

## The Only Risk: Liquidation
If the value of your collateral (Bitcoin) drops significantly, it might no longer be enough to cover your loan. If this happens, the protocol may **Liquidate** a portion of your collateral to pay back the debt.

### How Liquidation Works
1.  **example**: You deposit $10,000 of BTC and borrow $8,000 USDT. (LTV = 80%).
2.  **Market Crash**: Bitcoin drops by 10%. Your collateral is now worth $9,000.
3.  **Unsafe**: The protocol requires a margin of safety. Since $9,000 is too close to the $8,000 debt, the protocol sells some of your BTC to pay back part of the loan.
4.  **Penalty**: You pay a "Liquidation Penalty" (e.g., 5%) on the amount sold. **You lose money.**

## How to Stay Safe
The way to avoid liquidation is simple: **Don't be greedy.**

### 1. Maintain a Low LTV
We recommend keeping your Loan-to-Value (LTV) below **50%**.
*   If you have $10,000 in BTC, borrow only $5,000.
*   This gives you a huge safety buffer. Bitcoin would have to drop by >50% before you are at risk.

### 2. Monitor Your Health
Check the app regularly. If market volatility is high, check your **Health Factor**.

### 3. Top Up or Repay
If you get close to the danger zone, you have two options:
*   **Deposit more collateral**: Add more BTC to increase your safety margin.
*   **Repay part of the loan**: Use some cash to pay down the debt.
