--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-04 09:03:43.987969772 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6236 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.35 | 9.90 | 0.53 |
| 3 | 170 | 747 | 43.55 | 12.48 | 0.62 |
| 4 | 225 | 858 | 51.00 | 14.66 | 0.71 |
| 5 | 280 | 969 | 59.70 | 17.17 | 0.80 |
| 6 | 339 | 1081 | 71.80 | 20.46 | 0.93 |
| 7 | 394 | 1192 | 86.43 | 24.32 | 1.08 |
| 8 | 453 | 1307 | 95.86 | 26.92 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.37 | 7.71 | 0.48 |
| 2| 1954 | 25.43 | 8.68 | 0.50 |
| 3| 2059 | 27.31 | 9.86 | 0.53 |
| 5| 2468 | 32.07 | 12.54 | 0.61 |
| 10| 3150 | 40.60 | 18.25 | 0.75 |
| 39| 7528 | 96.77 | 53.20 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 22.81 | 7.37 | 0.42 |
| 2| 783 | 25.52 | 8.78 | 0.45 |
| 3| 930 | 27.10 | 9.89 | 0.48 |
| 5| 1256 | 31.04 | 12.34 | 0.55 |
| 10| 2100 | 40.49 | 18.31 | 0.70 |
| 40| 6467 | 97.47 | 54.13 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 854 | 29.89 | 9.82 | 0.50 |
| 3| 922 | 32.68 | 11.22 | 0.54 |
| 5| 1257 | 37.02 | 13.77 | 0.60 |
| 10| 2179 | 49.64 | 20.72 | 0.80 |
| 36| 6142 | 98.70 | 51.86 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.85 | 11.38 | 0.56 |
| 3| 1033 | 38.55 | 12.81 | 0.60 |
| 5| 1273 | 42.53 | 15.25 | 0.66 |
| 10| 2155 | 55.92 | 22.39 | 0.86 |
| 29| 4639 | 94.82 | 45.72 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 26.92 | 9.04 | 0.69 |
| 2| 5994 | 36.95 | 12.47 | 0.80 |
| 3| 6112 | 44.97 | 15.10 | 0.89 |
| 4| 6170 | 50.48 | 16.89 | 0.95 |
| 5| 6571 | 65.85 | 22.31 | 1.13 |
| 6| 6610 | 74.56 | 25.12 | 1.22 |
| 7| 6959 | 86.77 | 29.36 | 1.37 |
| 8| 6777 | 87.44 | 29.30 | 1.37 |
| 9| 7182 | 98.85 | 33.42 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 30 | 1705 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2216 | 7155 | 98.49 | 37.73 | 1.53 |

