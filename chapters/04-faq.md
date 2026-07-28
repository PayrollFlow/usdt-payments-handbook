# Chapter 4 — USDT payments FAQ

### Is USDT the same as US dollars?
No. USDT (Tether) is a stablecoin designed to stay worth about one US dollar. It tracks the dollar closely but is a separate asset issued on blockchains.

### Which network is cheapest — TRC20, ERC20, or BEP20?
**TRC20 (Tron)** is usually the cheapest, followed by **BEP20 (BNB Smart Chain)**. **ERC20 (Ethereum)** costs more and varies with network congestion. See [Chapter 1](01-networks.md).

### What happens if I send USDT on the wrong network?
It can be **permanently lost**. Always confirm the network with the counterparty and select the matching network before sending. If the receiving side is a custodial exchange, contact support immediately — recovery is sometimes possible but never guaranteed.

### Can BEP20 and ERC20 use the same address?
They can *look* identical because both use `0x…` addresses (both are EVM chains), but the **network you send on is what matters**. Never assume — select the correct network explicitly.

### Do I pay a percentage fee to receive USDT?
Not for a plain on-chain transfer. You pay a **network (gas) fee** to move the tokens (in TRX/BNB/ETH, not USDT). Services and exchanges may add their own fees — check their current pricing.

### How long does a USDT transfer take?
Usually seconds to a couple of minutes, depending on the network and congestion. Wait for on-chain confirmations before treating a payment as final.

### Is getting paid in USDT taxable?
In most places, yes — it's income, typically reported in your local currency at the value on the date received. Keep records (invoice, tx hash, date, amount). This is not tax advice; check your local rules.

### Do I need a hardware wallet?
Not to get started, but it's strongly recommended for larger balances. At minimum, back up your seed phrase offline and never share it.

### What's the safest way to receive a large payment?
Confirm the network, share a copy-pasted/scanned address, and ask the sender to send a **small test amount first**. Confirm receipt, then have them send the balance.

### How does PayrollFlow handle USDT payouts?
[PayrollFlow](https://payrollflow.io) lets you withdraw your balance to USDT on **TRC20, ERC20, or BEP20** (or a local bank). Each withdrawal is **reviewed before funds are sent** — a check against wrong-address and wrong-network mistakes — and typically completes within a few hours. 👉 **[Get started](https://app.payrollflow.io)**

---

Back to the **[handbook home](../README.md)**.

_Educational content, not financial, legal, or tax advice._
