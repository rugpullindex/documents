# Rug Pull Index Handbook

The RPI Handbook is a method to document processes within the Rug Pull Index
organization. Its purpose is to allow contributors to quickly get up to speed
with how things are done around here. Other companies have handbooks too.
Notable examples are Valve (Steam) and GitLab.

## What It Means To Work For The Public Good

Rug Pull Index has repeatedly received funds from the [oceanDAO](https://oceanprotocol.com). In all our proposals, our main rethoric was along the following lines: "We're creating value for the Ocean Protocol and hence we're allowing ourselves to regularly raise funds from the DAO."

Living this rethoric yields some practical requirements that influences our work directly. An example:

We try to reduce information asymmetry and we strive to discuss all matters not subject to exposing sensitive information (e.g. PII, etc.) in public channels to allow everyone to become part of a conversation.

We do so as we believe in the existence of the swarm intelligence. We acknowledge that innovation stems from an organic discovery process fueled through the collective and not the articifial production of an individuum.

We believe that continuity, originality and commitment are the drivers of value and innocation.

We have an incomplete but ripening set of values that we regularly reflect our actions upon. We value authenticity, responsibility and fairness. They shall guide our work. 

## How to get an offer approved to start working on RPI

To start getting paid for your work on RPI you will need to create a one page proposal outlining the work you intend to do, the amount of time it will take you and your hourly rate in USD. 

All work will be paid retroactively in USDC either in stages, upon partial completion of your project, or in full upon completion.

### Expenses

If you intend to incur outside expenditure for your project that you wish to be reimbursed for, this will need to be estimated and the amount approved in advance. A receipt for expenditure will need to be provided in order to receive reimbursements. 

### Deciding what should be in your proposal

In some instances you will have clear deliverables as set by the RPI team (e.g. tasks or chunks of work that the RPI team have already provided an outline for). When this is the case, your proposal should outline how you intend to achieve these outcomes and the amount of time you need to complete them. 

In other instances you will be proposing something new. For these proposals we recommend discussing your ideas and/or getting feedback from the RPI team on Discord first. This will help to ensure your intentions and the needs of the RPI project are aligned. 

### Writing Your Proposal

Your proposal should be a short, concise (roughly 1 page) summary of the work you intend to do and the impact &/or reasons why the work you are proposing will be valuable to RPI.

* Try to keep proposals targeted and specific. Upon successful completion of one proposal you can always submit a second.
* Try to break down larger chunks of work into smaller, manageable pieces which add value. 
* Every proposal, once complete, should have added value to RPI in some way.
* If the proposal does not add enough value relative to the cost it will not be funded. This is to ensure we have a positive ROI for all proposals approved.
* Proposals with a large scope and open ended deliverables are unlikely to be funded.

### Estimating your time

Once you have broken down your deliverables into appropriately sized chunks, and clearly summarised the work &/or value you intend to provide it should be relatively easy to estimate how much time you will need to complete the task. 

Add an estimate to each task and calculate the overall time estimate. This, along with your hourly rate will be used to calculate the total cost of your proposal. This total cost and your proposed deliverables will need to be approved before you start working. 

Once approved, this amount (total cost) will be set aside for you to complete your deliverables. 

### Keeping up to date with delivery

Once you have received approval for your project and begin working, it’s important to keep track of the time you spend. If at any stage it’s looking like you will need to adjust your estimates, or change direction from the original plan, please check in with the team for further approvals before going ahead and committing extra hours.

Any additional hours/work you do that wasn’t approved will not automatically be funded. We know that things change as you get deeper into a project and sometimes other factors outside your control will impact your deliverables. That’s ok, but what is important is that you communicate these changes clearly with the team as and when they arise. 

### Getting Paid

If your proposal has been approved, you have completed your tasks to the agreed standard and you now wish to get paid, please create an invoice using [Request](https://invoicing.request.network/) and make sure to address it to tim@daubenschuetz.de.

Please follow the instructions [here](https://support.request.network/getting-started-guide) to set up your Request account and create your first invoice!

IMPORTANT NOTE: Allow for up to 14 days for your invoice to be paid.

**Each grant request must include the details below:**

* Email address
* Invoice date
* Your country
* Description of grant reason
* Grant amount (USDC)
* Payment details - crypto-wallet address

**Please address the invoice to:**

Tim Daubenschütz
Badstr. 38
13357 Berlin
Germany
tim@daubenschuetz.de

### I want to submit a work proposal, what should I do now?

We can't guarantee there will always be funding available for proposals so the best thing to do is jump on [Discord](https://discord.gg/hBQVJY9Me6) and get to know more about the product. Any requests for proposals will be submitted on Discord. 

**All proposals should be submitted via email to: tim@daubenschuetz.de**

We look forward to hearing from you and good luck!

The RPI team.



## Fund raising

### Calculating the statistical funding error in the OceanDAO

In the OceanDAO, funds have to be either requested in USD or OCEAN. Since
there's a big gap in time between the day of the proposal, and when winners
receive their OCEANs, fiat prices (OCEAN/USD and OCEAN/EUR) can greatly vary.

To reduce the funding error of RPI, since a few rounds, we've started to
calculate a statistical funding error in USD that we apply to each of our
proposal calculuations. Our intention behind this is to make our funding
requests more accurate and create efficiency.

Exemplarily, we show the above mentioned calculation for RPI's R11 OceanDAO
proposal:

|Round|USD requested|OCEAN received|receive date|USD swapped|swap date|USD delta|USD error|
|---|---|---|---|---|---|---|---|
|[R6](https://port.oceanprotocol.com/t/rugpullindex-com-proposal-r6/650)|9360|13000|2021-06-08|7546.43|2021-06-09|-1813.57|-1813.57|
|[R7](https://port.oceanprotocol.com/c/oceandao/round-7/64)|10080|22400|2021-07-21|8390.49|2021-07-22|-1689.51|-1751.54|
|[R8](https://port.oceanprotocol.com/t/rugpullindex-com-round-8-proposal/801?u=timdaub)|10276.61|19391.00|2021-08-16|15742.78|2021-08-17|5466.17|654.36|
|[R10](https://port.oceanprotocol.com/t/rugpullindex-com-improving-data-trading-safety/970?u=timdaub)|16536.65|21933|2021-10-15|17475.51|2021-10-18|938.86|725.48|

As can be seen, all we do is compare the fiat value of OCEANs we've originally
requested, with those that we have received. For that to work in a fair way,
we're trying to sell our OCEANs for USDC as soon as we can.

For e.g. R10, we calculate the error rate of Round 11 as follows:

`(-1813.57-1689.51+5466.17+938.86)/4 = 725.48`

Simply put, we take all `USD delta`s and form an average (divide by 4) that we
use as our statistical funding error. This funding error, we then either
subtract or add to the amount of funds we were originally requesting.

In the above case, it looks as if we've received 725.48 USD too much in each of
the last four rounds. Hence, to move the error towards zero, in Round 11 we'd
subtract 725.48 USD from our requested amount.
