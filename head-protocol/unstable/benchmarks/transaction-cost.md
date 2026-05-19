--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-19 08:32:30.178077364 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.92 | 4.11 | 0.55 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7648 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.45 | 12.22 | 0.61 |
| 4 | 228 | 858 | 53.34 | 15.19 | 0.73 |
| 5 | 282 | 974 | 64.02 | 18.14 | 0.84 |
| 6 | 337 | 1081 | 67.80 | 19.50 | 0.89 |
| 7 | 395 | 1192 | 76.24 | 21.88 | 0.98 |
| 8 | 448 | 1303 | 80.30 | 23.34 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 2027 | 26.63 | 9.02 | 0.52 |
| 3| 2129 | 28.02 | 10.07 | 0.54 |
| 5| 2284 | 29.27 | 11.74 | 0.57 |
| 10| 3276 | 43.08 | 18.96 | 0.78 |
| 40| 7500 | 95.48 | 53.51 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 22.57 | 7.31 | 0.41 |
| 2| 718 | 22.52 | 7.93 | 0.42 |
| 3| 937 | 26.90 | 9.86 | 0.48 |
| 5| 1180 | 28.16 | 11.51 | 0.51 |
| 10| 1959 | 38.68 | 17.79 | 0.68 |
| 42| 6681 | 98.13 | 55.68 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 805 | 29.19 | 9.60 | 0.49 |
| 3| 956 | 33.43 | 11.44 | 0.54 |
| 5| 1284 | 35.00 | 13.24 | 0.59 |
| 10| 2136 | 45.73 | 19.61 | 0.76 |
| 35| 5761 | 94.08 | 49.80 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.85 | 11.38 | 0.56 |
| 3| 948 | 37.80 | 12.59 | 0.59 |
| 5| 1202 | 41.93 | 15.06 | 0.65 |
| 10| 2150 | 55.64 | 22.28 | 0.85 |
| 29| 4661 | 96.14 | 46.11 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5784 | 26.97 | 9.05 | 0.69 |
| 2| 5941 | 36.03 | 12.11 | 0.79 |
| 3| 5976 | 40.47 | 13.49 | 0.84 |
| 4| 6209 | 51.18 | 17.22 | 0.96 |
| 5| 6534 | 65.70 | 22.23 | 1.13 |
| 6| 6474 | 68.31 | 22.94 | 1.15 |
| 7| 6715 | 83.46 | 28.08 | 1.32 |
| 8| 7053 | 96.20 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2273 | 7190 | 99.66 | 38.24 | 1.55 |

