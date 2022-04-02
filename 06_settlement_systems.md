# Settlement systems

How does money move inside the banking system?

1. Two accounts in the same bank
  * Occurs using the bank's internal system
  * No credit or counterparty risk for the bank
  * No liquidity impact for the bank

2. Corresponding baks
Bank A debits customer account and credits bank B's account. Bank B credits
customer account and debits bank A's account.
  * Not practical for all banks to have correspodent relationships
  * Credit/counterparty risk

3. Settlement systems
Banks maintain accounts at the settlement system. The system can be a private
company or Central Bank.

Settling with the Central Bank has advantages:
* No counterparty/credit risk
* Provision of credit/overdraft as needed
* Low costs

**Clearing**: The activities related with transfer of information relating to
payments and related activities (confirmation, error resolution, etc.)

**Settlement**: The actual transfer of funds. Final settlement is irrevocable

## Kinds of settlement systems

1. Real time gross settlement systems (RTGS)
  * Each transaction proceeds as it happens
  * Reduces intra-day credit risk
  * Increases liquidity needs and subsequently cost of liquidity

2. Net settlement systems
  * Transactions netted at the end of the day, so only the net amount is settled
  * Reduces liquidity needs
  * Increases intra-day credit risk

3. Hybrid systems
  * Near real-time but looking for opportunities to reduce liquidity needs
  * Netting queued orders
  * Prioritization of orders
  * Delaying orders above certain liquidity limits

**Fedwire** is the oldest RTGS system operated by the Federal Reserve. It first
began operations in 1918 using Morse code over telegraph lines! Computerized by
the early 1970s.

The Federal Reserve banks act as the RTGS ledger by debiting/crediting the individual
participants' accounts at their respective regional Federal Reserve banks.

Primary uses:
* Operations relating to the Central Bank
* Settlement for other payment systems
* High-value financial transactions
* Settlement of real estate transactions
* ...

**SEPA** (Single Euro Payment Area) is the most important initiative for bank transfers
in the Euro area. Through PSD/PSD2, it has been working towards a common market for
payments.

The goal of SEPA is to standardize national systems and have them adopt a common set of
protocols so that it becomes as easy to transfer money across member states as it is within
a member state. SEPA guarantees a time to settlement and disallows higher charges for cross-
border transfers than for domestic transfers.

Not a payment system in itself. More like a series of protocols, directives, and deadlines
for interoperability and fee pricing. Large third-party clearing and settlment systems
became compliant with SEPA.

### Continuous linked settlements

Fairly recent development in settlement systems: a bank specialized in foreign exchange
settlement. FX transactions were viewed as a source of systemic risk because:
* FX flows are very large
* FX could not be settled simultaneously by Central Bank RTGS so there was credit risk
in FX settlement.

Continuous linked settlements (CLS) works as follows:
* Collects all trades for the day and performs multilateral netting across institutions
* Holds accounts at the RTGS for each currency it supports
* During a window when all relevant RTGS are open, it nets the member multi-currency accounts
at CLS that have been funded via RTGS

In other words, it is a net, multi-currency, multilateral settlement system, itself settled to
national RTGS.

## SWIFT messaging

The Society for Worldwide Interbank Financial Telecommunications is a member owned cooperative
operating with many institutions across many countries. Not a payment system, simply a messaging
system that is used by other payment systems to pass along the relevant information as it relates
to a transaction.

About 30M messages exchanged per day on average, of which ~49% are the funds.
