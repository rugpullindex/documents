# Rug Pull Index Handbook

The RPI Handbook is a method to document processes within the Rug Pull Index
organization. Its purpose is to allow contributors to quickly get up to speed
with how things are done around here. Other company's have handbooks too.
Notable examples are Valve (Steam) and GitLab.

## Financials

### Methodology to Request Funds in the OCEANDAO

In the OCEANDAO, funds have to be requested in
[OCEAN](https://www.coingecko.com/en/coins/ocean-protocol). At RPI, we have a
specific methodology for requesting funds. We prioritize stability and
risk-reduction over potential gains in the market. This means that we have an
interest in converting non-stable assets (e.g.  OCEAN) into fiat-stable assets
(e.g. USDC). We do this, as we'd like to guarantee contributor's priorly
confirmed budgets.

Calculating the budget for a new OCEANDAO round is done as follows:

- For all contributors, we check if they've submitted a new offer that quotes a
  total budget in OCEAN. If they have, we add it to our round's budget.
- In case a contributor hasn't submitted a separate offer but still requests
  funds in a round, we take the contributor's average monthly salary in OCEAN
  and add it to the rounds budget (pro tip: you can compute a contributor's
  average monthly salary by looking into the latest cash-basis accounting
  statement).
- For all contributors that have fiat expenses (e.g. running a web server), we
  ask them to declare them in OCEAN and we then add them to the round's budget.
- Finally, we for all previous rounds were RPI had declare a "funds required"
  field in the OCEANDAO proposal, we find an average error value between what
  was original required in a stable currency and what ended up being exchanged
  after winning the proposal (see example below).

Note that all quotes from all contributors must use a mutually agreed upon
exchange rate between the non-stable asset and the stable asset (e.g. we take
the OCEAN/USDC price 3 days before the proposal deadline).

#### Example Calculation

Assume the following:

- It's OCEANDAO round 1337 (short: R1337).
- Contributor Tim isn't submitting a separate offer but is requesting his
  average monthly salary for R1337.
- Contributor Scott is submitting an offer and requests 1800 USD total budget.
- Contributor Tim submits 200 EUR in expenses (server cost).
- The latest [cash-basis accounting is from
  2021-07-21](https://drive.google.com/file/d/1rYoYKCt0Ri7aXp3pZnyRzHPw2C3JniO0/view?usp=sharing).

Here's what the person creating the budget now has to do:

1. Go to a website like
   [Coingecko](https://www.coingecko.com/en/coins/ocean-protocol) and determine
   a fixed exchange rate for OCEAN/EUR and OCEAN/USD. In our case, for today
   2021-07-31 OCEAN/EUR = 0.40 and OCEAN/USD = 0.48.
2. Then for all contributors' quotes, ask them to resubmit them in OCEAN given
   the fixed exchange rates in OCEAN/EUR and OCEAN/USD.

Executing steps (1) and (2), we get the following list

|position|OCEAN value|EUR value|USD value|
|---|---|---|---|
|Salary Scott|3750|-|1800|
|Expenses Tim|500|-|200|

But then, for Tim we also need to check his average monthly salary. So we take
all positions from the expenses table (EUR) of the cash-basis-accounting
document : 6362.95+9472.47+8940.10+10133.22=34908.74 and divide it by the
number of months (six): 34908.74/6 = 5818.12 EUR. We then convert this value to
OCEAN using our fixed exchange rate. 5818.12 EUR/0.4 OCEAN/EUR = 14545.3 OCEAN.
Our new table now looks as follows:

|position|OCEAN value|EUR value|USD value|
|---|---|---|---|
|Salary Scott|1042|-|500|
|Expenses Tim|500|-|200|
|Salary Tim|14545.3|5818.12|-|

Finally, we want to compute an error value for all previous proposals. For
that, we have to know all previous proposal's targeted stable value as well as
their OCEAN value. For the "EUR value swapped", we can again look into the
cash-basis-accounting statement.

|round|EUR value|OCEAN value requested|USD value swapped|swap date|EUR/USD at swap date|EUR value swapped|EUR error|
|---|---|---|---|---|---|---|---|
|[R6](https://port.oceanprotocol.com/t/rugpullindex-com-proposal-r6/650)|7000|13000|7546.43|2021-06-09|1.22|6185.59|814.41|
|[R7](https://port.oceanprotocol.com/c/oceandao/round-7/64)|8512|22400|8390.49|2021-07-22|1.18|7110.58|1401.42|

Hence, the average stable value that occurs between the time a proposal is
submitted to the time it has been won and converted to a stable currency is
currently: (814.41 EUR+1401.42 EUR)/2=1107.91 EUR.

To conclude our budget, we add it in OCEAN as well and sum up the OCEAN column.

|position|OCEAN value|EUR value|USD value|
|---|---|---|---|
|Salary Scott|1042|-|500|
|Expenses Tim|500|-|200|
|Salary Tim|14545.3|5818.12|-|
|Average error|2769.77|1107.91|-|
|**SUM**|18856.07|7542.42|-|

We hence publish the total value, along with the OCEAN/EUR and OCEAN/USD
exchange rate in the proposal.
