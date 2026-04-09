--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-09 06:12:02.17851729 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 10.36 | 3.28 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 228 | 858 | 47.87 | 13.88 | 0.67 |
| 5 | 282 | 974 | 63.23 | 18.02 | 0.83 |
| 6 | 337 | 1081 | 71.91 | 20.53 | 0.93 |
| 7 | 395 | 1192 | 83.42 | 23.70 | 1.05 |
| 8 | 448 | 1303 | 90.71 | 25.94 | 1.13 |
| 9 | 504 | 1414 | 96.52 | 27.64 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 1948 | 25.47 | 8.70 | 0.50 |
| 3| 2127 | 28.43 | 10.17 | 0.55 |
| 5| 2428 | 32.41 | 12.62 | 0.61 |
| 10| 3165 | 40.61 | 18.26 | 0.75 |
| 41| 7717 | 99.69 | 55.31 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 718 | 22.60 | 7.95 | 0.42 |
| 3| 877 | 25.09 | 9.32 | 0.46 |
| 5| 1167 | 28.12 | 11.50 | 0.51 |
| 10| 1989 | 38.68 | 17.80 | 0.68 |
| 42| 6705 | 99.33 | 55.99 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 794 | 30.94 | 10.07 | 0.51 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1257 | 37.06 | 13.78 | 0.60 |
| 10| 2229 | 47.64 | 20.21 | 0.78 |
| 34| 5624 | 99.48 | 50.60 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 1003 | 38.66 | 12.84 | 0.60 |
| 5| 1208 | 41.89 | 15.05 | 0.65 |
| 10| 2032 | 53.99 | 21.79 | 0.83 |
| 28| 4657 | 95.85 | 45.43 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.97 | 9.07 | 0.69 |
| 2| 5902 | 34.80 | 11.65 | 0.78 |
| 3| 6139 | 45.61 | 15.41 | 0.90 |
| 4| 6258 | 54.79 | 18.43 | 1.00 |
| 5| 6498 | 63.47 | 21.44 | 1.10 |
| 6| 6355 | 64.15 | 21.47 | 1.10 |
| 7| 6635 | 79.38 | 26.65 | 1.28 |
| 8| 7044 | 95.81 | 32.39 | 1.47 |
| 9| 7022 | 95.96 | 32.31 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1136 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2218 | 7158 | 97.61 | 37.43 | 1.52 |

