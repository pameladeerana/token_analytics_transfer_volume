# Token Analytics: Transfer Volume 

## Description
ERC-20 transfer volume on a 7-day dataset, Nov 5 - Nov 11, 2026 PHT. It ranks tokens with unique addresses by transfer count and value, counts transfers per hour, and tallies how many different tokens had a transfer in that period. It reflects ERC-20 token activity in the network.

## 1. Parts / Statements

**1. ERC-20 Transfer Volume and Count by Token **
Groups token with unique contract address to show total transfer count and value.

**2. Hourly Transfer Buckets**
Counts how many transfers happened in each hour

**3. Count Contracts Emitting Transfer Events**
Counts how many different tokens had at least one transfer by counting distinct contract address.

## 2. Workflow

1. Explored token transfers table on Dune, on EVM (Ethereum Network), and picked the weekly dataset on Nov 5 - Nov 11, 2026.
2. Queried dataset for 3 parts (assisted with WizardsCamp and AI for automation of queries).
3. Made visualizations and built final dashboard.

## 3. Files

- **README.md** - Project overview.
- **Dune Queries and Results**:
  - Data Source: https://dune.com/queries/9117502
  - Part 1 - ERC-20 Transfer Volume and Count by Token: https://dune.com/queries/9117745/13171051
  - Part 2 - Hourly Transfer Buckets: https://dune.com/queries/9118321/13169970
  - Part 3 - Count Contracts Emitting Transfer Events: https://dune.com/queries/9118510/13170133
- **Dune Dashboard**: https://dune.com/pameladeerana/token-analytics-transfer-volume

## 4. Data Coverage

- **Date:** November 5 - November 11, 2026 PHT
- **Blocktime Range:** 2026-11-04 16:00:00 to 2026-11-11 16:00:00 UTC (from query_9117502) 

## 5. Tools

- Dune Analytics
- WizardCamp
- LLM Meta AI

## Author

Pamela Dee Elegio Rana
