# Chapter 2 — Staying safe with USDT

On-chain payments are fast and final. That finality is a feature — no one can claw back a legitimate payment — but it also means mistakes and scams are unforgiving. Here's how to stay safe.

## The top risks, ranked

### 1. Wrong-network sends
The single most common way people lose USDT. Sending on the wrong network (e.g., ERC20 to a wallet expecting TRC20) can make funds unrecoverable. **Always confirm and select the matching network** — see [Chapter 1](01-networks.md).

### 2. Wrong or tampered address
- **Copy-paste or scan** addresses — never type them by hand.
- Beware **clipboard-hijacking malware** that swaps a copied address for an attacker's. Verify the first and last several characters after pasting.
- For a new counterparty or a large payment, **send a small test amount first**, confirm receipt, then send the rest.

### 3. Phishing and fake support
- No legitimate service will ask for your **seed phrase / recovery phrase**. Anyone who does is trying to steal your wallet.
- Check URLs carefully; bookmark the real sites you use.
- Be skeptical of "support" that DMs you first.

### 4. Losing your keys
- Your **seed phrase is your money.** Back it up offline, never in a screenshot or cloud note.
- Use a **hardware wallet** for larger balances.
- Consider separating a small "spending" wallet from a larger "savings" wallet.

## A pre-payment checklist

Before sending or sharing an address for a payment:

- [ ] Network confirmed in writing (TRC20 / ERC20 / BEP20)
- [ ] Correct network selected in the wallet/exchange
- [ ] Address copied by paste or QR — not typed
- [ ] First/last characters of the address visually verified
- [ ] Test amount sent for new addresses or large sums
- [ ] Counterparty verified as legitimate
- [ ] Record kept (amount, network, tx hash, date)

## If something goes wrong

- **Wrong network / wrong address:** on-chain transfers are irreversible. If the receiving side is an exchange or custodial service, contact their support immediately — recovery is sometimes possible but never guaranteed. For self-custody to a truly wrong address, funds are typically unrecoverable.
- **Suspected phishing:** move funds to a fresh wallet with a new seed if you believe your seed is compromised.

## Why a review step helps

A human review before a payout is a cheap insurance policy against the two costliest mistakes — wrong network and wrong address. Platforms like [**PayrollFlow**](https://payrollflow.io) review each withdrawal before funds are sent for exactly this reason, and show the chosen network clearly so TRC20/ERC20/BEP20 don't get mixed up.

---

Next → **[Chapter 3: cashing out](03-cashing-out.md)**

_Educational content, not financial or security advice._
