--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-24 08:13:14.769330564 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.99 | 4.13 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 751 | 41.23 | 11.93 | 0.60 |
| 4 | 227 | 858 | 52.74 | 15.13 | 0.72 |
| 5 | 281 | 969 | 64.38 | 18.29 | 0.84 |
| 6 | 339 | 1081 | 69.56 | 19.89 | 0.90 |
| 7 | 394 | 1192 | 83.49 | 23.75 | 1.05 |
| 8 | 450 | 1303 | 81.14 | 23.60 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.80 | 8.49 | 0.49 |
| 3| 2076 | 26.98 | 9.78 | 0.53 |
| 5| 2321 | 30.00 | 11.96 | 0.58 |
| 10| 3069 | 39.70 | 18.00 | 0.74 |
| 39| 7580 | 97.95 | 53.51 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 793 | 23.59 | 8.23 | 0.44 |
| 3| 912 | 25.10 | 9.32 | 0.46 |
| 5| 1142 | 28.14 | 11.51 | 0.51 |
| 10| 2029 | 40.23 | 18.25 | 0.70 |
| 40| 6549 | 98.54 | 54.42 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 988 | 33.43 | 11.45 | 0.55 |
| 5| 1169 | 33.70 | 12.84 | 0.57 |
| 10| 2202 | 49.61 | 20.72 | 0.80 |
| 36| 6101 | 99.45 | 52.06 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 1022 | 38.51 | 12.80 | 0.60 |
| 5| 1223 | 41.86 | 15.04 | 0.65 |
| 10| 1920 | 52.75 | 21.40 | 0.82 |
| 28| 4877 | 97.33 | 45.88 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 26.92 | 9.04 | 0.69 |
| 2| 6007 | 37.05 | 12.48 | 0.80 |
| 3| 6083 | 45.08 | 15.14 | 0.89 |
| 4| 6217 | 51.59 | 17.36 | 0.97 |
| 5| 6518 | 65.29 | 22.04 | 1.12 |
| 6| 6493 | 69.39 | 23.30 | 1.16 |
| 7| 6967 | 87.40 | 29.73 | 1.38 |
| 8| 6891 | 93.28 | 31.49 | 1.43 |
| 9| 6809 | 89.59 | 29.90 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.88 | 14.58 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7158 | 98.68 | 37.80 | 1.53 |

