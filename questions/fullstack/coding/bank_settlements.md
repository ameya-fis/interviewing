
## Bank Settlements
Banks engage in transactions with each other multiple times a day. A bank can pay another
bank or receive payments from another bank. The system reconciles all transactions over the
day and determines the minimum number of payments that need to be made between banks to
balance the transactions. Write a program that implements this reconciliation algorithm.
Ex: A transaction is given as A,B,10 means Bank A must pay Bank B the amount 10. Assume the
5 transactions take place during the day:
- A,B,10
- B,A,15
- A,C,25
- C,B,20
- C,A,5

If C has to pay B and B has to pay A, we can reduce the number of money movements by C
directly paying A some amount involving B thereby reducing one money movement. On
reconciliation, the final balances (and hence the actual money movement) is reduced to:
- A,C,20
- C,B,15
--- 

## Rubric
### Scoring (Each scored 1-3)
* Understanding the problem and algorithm walkthrough
* Data structure usage and appropriateness
* Problem solving
* Coding fluency
* Correctness

### Rating
* Score >= 12 => High
* 9 >= Score < 12 => Solid
* <9 => Low