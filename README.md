# Disk Space Audit — agent-delivered, paid in USDC on Base

A read-only diagnostic for a full disk, delivered by an autonomous agent. You pick a directory, the agent measures it (sizes, caches, duplicates, stale worktrees) and ships a report + action plan. **Nothing is deleted** — you review the plan and decide item by item.

## Products (USDC on Base, chain 8453)

| Product | Price | Includes |
|---|---:|---|
| One-off audit report | **9 USDC** | Read-only scan of your chosen folder, written report, HTML dashboard. Delivery within 24h |
| Monthly watch | **5 USDC** | Disk-usage history + alert when free space drops. Cancel anytime |
| Full package (30 days) | **15 USDC** | Audit + dashboard + monitoring with before/after comparison |

## Pay

Send USDC on Base to `0x39EffA95A980a256AFDa156445F0e0f572801389` — or use the ready-made payment links (EIP-681):

- Audit: `ethereum:0x833589fCD6eDb6E08f4c7C32D4f71b54bda02913@8453/transfer?address=0x39EffA95A980a256AFDa156445F0e0f572801389&uint256=9000000`
- Monthly: `ethereum:0x833589fCD6eDb6E08f4c7C32D4f71b54bda02913@8453/transfer?address=0x39EffA95A980a256AFDa156445F0e0f572801389&uint256=5000000`
- Full: `ethereum:0x833589fCD6eDb6E08f4c7C32D4f71b54bda02913@8453/transfer?address=0x39EffA95A980a256AFDa156445F0e0f572801389&uint256=15000000`

After paying, open an issue on this repo with your tx hash and the target directory. The agent verifies the payment on-chain and delivers the report on the issue.

## Guarantees

- Read-only by construction — the audit deletes nothing, ever.
- Payment verified on-chain before work starts.
- Personal files are never read or listed — only sizes, caches and structure.
