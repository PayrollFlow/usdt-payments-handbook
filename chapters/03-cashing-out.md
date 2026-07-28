# Chapter 3 — Cashing out USDT to local currency

Getting paid in USDT is only half the story. At some point you'll want to spend it, which usually means converting to your local currency. Here are the common routes and how to compare them.

## Common cash-out routes

### 1. A reputable exchange
Deposit USDT, sell for your local currency, and withdraw to your bank.
- **Pros:** transparent rates, larger volumes, familiar flow.
- **Watch for:** trading fee + withdrawal fee, and whether the exchange supports your currency and withdrawal method.

### 2. Peer-to-peer (P2P)
Sell directly to a buyer, often via an exchange's P2P marketplace with escrow.
- **Pros:** can beat exchange rates; flexible payment methods.
- **Watch for:** counterparty risk — use escrow, check ratings, and never release before confirming receipt.

### 3. A payout account
Some accounts let you hold a balance and withdraw to USDT or a local bank as you choose.
- **Pros:** one place to collect client payments and cash out.
- **Watch for:** the platform's fee schedule and supported networks.

## Comparing the *effective* rate

Don't compare headline fees — compare what actually lands in your bank:

```
Effective rate = (local currency received) ÷ (USDT sold)
```

Factor in **all** of:
- Exchange/trading fee
- Network fee to move USDT to the exchange (use TRC20/BEP20 to keep this low)
- Withdrawal/off-ramp fee to your bank
- FX spread between USDT→USD→local currency

Sometimes converting locally (P2P) beats an exchange; sometimes the exchange wins. Check both for large amounts.

## Keep the network cheap

When moving USDT *to* an exchange to cash out, send on **TRC20** or **BEP20** to minimize the on-chain fee. Avoid ERC20 for this step unless the exchange only credits ERC20 deposits.

## Records for tax

Getting paid in USDT is still income. Most tax authorities expect you to report it in your local currency at the value on the date received. Keep:

- The invoice
- The transaction hash
- The date and amount
- The rate used when cashing out

A clean record now saves a headache later. *(This is not tax advice — check your local rules.)*

## Where PayrollFlow fits

With [**PayrollFlow**](https://payrollflow.io) you collect client payments in USD or EUR and withdraw to **USDT (TRC20/ERC20/BEP20)** or a local bank — so you can choose the cash-out path that suits you, with a review step before each payout. 👉 **[Get started](https://app.payrollflow.io)**

---

Next → **[Chapter 4: FAQ](04-faq.md)**

_Educational content, not financial or tax advice._
