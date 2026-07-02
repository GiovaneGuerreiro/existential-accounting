# Existential Accounting
This is just an idea, not a manifesto. Feel free to use it as you wish.

"The existence precedes the essence" - Sartre

Cash and cash equivalents are the only things that exist. Goods and other assets may exist in the real world, but they're not measurable, therefore, I reject their subjective value.

**Anarcho Bookkeeping**: There is no hierarchy, the accounts just exist.

The bookkeeping is a graph, the accounts are nodes and the records/transactions are directed edges (origin is credit and destination is debit).

When money flows from or to a node that is not an account or payable/receivable, it is the void. Ex: You bought a vehicle:

`cash -> void, {value: 25000.00, date: "2026-01-01", description: "Vehicle purchase"}`

Payables and receivables are nodes, not just edges to an account, since accounts store values that exist. The edge that creates it still store a value, but it's just for reference. Example, You bought goods for retail:

`supplier xpto invoice xxxxxxx -> void, {value: 2264.91, date: "2026-01-02", description: "75497 candies", "due date": "2026-01-12"}`

When you pay it:

`cash -> supplier xpto invoice xxxxxxx, {value: 2264.91, date: "2026-01-10", description: "done"}`

**The Non-Accrual Basis**: It is an agnostic approach. Since we don't consider payables and receivables until they're paid or received (which renders them useless for bookkeeping purpose after that), we don't accrue them. This is an honest acceptance of the human incompetence to predict the unpredictable future or to estimate the subjective value of the material world. In Portuguese, we can call it "Regime de Incompetência".

**Results**: The results are simply the sum of the account values compared to the previous period, influenced only by income, expenses, receivables received and payables paid. There is no fictitious profit or loss.
