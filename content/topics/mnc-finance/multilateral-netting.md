---
title: Multilateral Netting
---

> Technique for reducing transaction costs when many subsidiaries trade with each other. Mid-priority MC topic.

## The problem

When N subsidiaries trade with each other, the volume of cross-currency money flows generates large FX commissions and transfer fees. Every individual payment is a separate currency conversion + bank fee.

## Bilateral netting (the simple case)

Two subsidiaries:
- A owes B \$6M
- B owes A \$4M

Instead of two payments, **A pays B just \$2M** (the net). One transaction instead of two.

## Multilateral netting (the N-way generalization)

With N subsidiaries, build a **payment matrix**: row = payer, column = payee, cell = amount owed. Net everyone's positions across the whole matrix.

The result is a much smaller set of net payments — only the largest debtors send money to only the largest creditors.

## Worked example (book)

4 Asian subsidiaries with gross inter-subsidiary flows totaling **\$43M**.

After multilateral netting → **\$5M** in net flows. Transaction cost savings: **\$380,000 (~90% reduction)**.

## Why this matters

Each cross-currency transfer costs:
- FX commission (bid-ask spread)
- Wire transfer fee
- Internal accounting work

Reducing \$43M of gross flows to \$5M of net flows scales the cost down proportionally.

## See also

- [[centralized-depositories|Centralized depositories]] — different cost-saving technique
- [[moving-money|Moving money across borders]]
