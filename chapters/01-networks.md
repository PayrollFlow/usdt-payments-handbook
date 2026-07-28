# Chapter 1 — TRC20 vs ERC20 vs BEP20: choosing a network

USDT (Tether) is not a single thing living in one place. The same "USD-pegged token" is issued on several blockchains, and each version travels on its own network with its own address format and fee. Picking the right one saves money and avoids lost funds.

## The three you'll see most

### TRC20 — USDT on Tron
- **Fee:** the lowest of the three, often just a few cents (and effectively free for senders who stake Tron resources).
- **Speed:** fast, usually seconds to a minute.
- **Why people pick it:** it's the common default for low-cost USDT payouts, widely supported by exchanges and payout platforms.
- **Address format:** starts with `T`.

### BEP20 — USDT on BNB Smart Chain
- **Fee:** low; you pay gas in **BNB**.
- **Speed:** fast.
- **Why people pick it:** popular with Binance and many exchanges; a solid choice when the sender or exchange prefers BNB Chain.
- **Address format:** a `0x…` Ethereum-style address (BNB Smart Chain is EVM-compatible).

### ERC20 — USDT on Ethereum
- **Fee:** higher and **variable** — you pay gas in **ETH**, and it rises when the Ethereum network is busy.
- **Speed:** usually a minute or two, longer when congested.
- **Why people pick it:** the most widely supported version across wallets, exchanges, and DeFi. Choose it when maximum compatibility matters more than fee.
- **Address format:** a `0x…` address.

> **Important:** BEP20 and ERC20 both use `0x…` addresses because both are EVM chains. **The address looking the same does not mean the network is the same.** A BEP20 address and an ERC20 address can even be identical strings — what differs is which network you send on. Always select the correct network explicitly.

## Side-by-side

| | TRC20 | BEP20 | ERC20 |
|---|-------|-------|-------|
| Blockchain | Tron | BNB Smart Chain | Ethereum |
| Gas token | TRX | BNB | ETH |
| Typical fee | Lowest | Low | Higher / variable |
| Address starts with | `T` | `0x` | `0x` |
| Best when | Cost matters most | Sender uses BNB Chain | Maximum support needed |

## How to choose

1. **Match the sender and your cash-out route.** Pick a network *both* sides support and that your exchange or payout platform accepts.
2. **Default to TRC20** for low-cost USDT payments unless there's a reason not to.
3. **Use BEP20** when the counterparty is on BNB Chain / Binance.
4. **Use ERC20** only when it's specifically required — you'll pay more in gas.

## The golden rule (again, because it matters)

**The network must match on both ends.** USDT sent on one network to an address expecting another can be **permanently lost**. Before every payment:

- Confirm the network in writing with the counterparty.
- Select the matching network in your wallet/exchange.
- Copy-paste or scan the address — never type it.
- For a new address or a large amount, send a **small test first**.

---

Next → **[Chapter 2: staying safe](02-safety.md)**

_Educational content, not financial advice. Fees and network behavior change over time._
