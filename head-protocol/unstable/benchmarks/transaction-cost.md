--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-20 05:41:24.319453054 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 226 | 858 | 51.20 | 14.73 | 0.71 |
| 5 | 282 | 969 | 64.28 | 18.26 | 0.84 |
| 6 | 340 | 1081 | 63.76 | 18.46 | 0.85 |
| 7 | 394 | 1192 | 84.19 | 23.78 | 1.05 |
| 8 | 449 | 1303 | 96.01 | 27.06 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1932 | 25.76 | 8.76 | 0.51 |
| 3| 2179 | 29.13 | 10.38 | 0.56 |
| 5| 2381 | 31.36 | 12.33 | 0.60 |
| 10| 3269 | 42.64 | 18.83 | 0.77 |
| 39| 7630 | 98.49 | 53.67 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 828 | 25.17 | 8.71 | 0.45 |
| 3| 977 | 27.99 | 10.16 | 0.49 |
| 5| 1278 | 31.17 | 12.36 | 0.55 |
| 10| 2044 | 39.84 | 18.11 | 0.69 |
| 40| 6475 | 97.30 | 54.08 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 741 | 30.20 | 9.84 | 0.50 |
| 3| 1060 | 32.36 | 11.19 | 0.54 |
| 5| 1247 | 36.95 | 13.76 | 0.60 |
| 10| 2176 | 49.04 | 20.53 | 0.79 |
| 37| 6145 | 99.09 | 52.61 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.81 | 11.37 | 0.56 |
| 3| 987 | 38.63 | 12.83 | 0.60 |
| 5| 1262 | 42.61 | 15.27 | 0.66 |
| 10| 2078 | 54.81 | 22.03 | 0.84 |
| 29| 4892 | 97.55 | 46.59 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 26.92 | 9.04 | 0.69 |
| 2| 5897 | 34.87 | 11.66 | 0.78 |
| 3| 6076 | 43.84 | 14.69 | 0.88 |
| 4| 6155 | 52.91 | 17.77 | 0.98 |
| 5| 6456 | 64.21 | 21.63 | 1.11 |
| 6| 6444 | 68.31 | 22.88 | 1.15 |
| 7| 6777 | 84.23 | 28.41 | 1.33 |
| 8| 6808 | 92.98 | 31.32 | 1.43 |
| 9| 6990 | 97.40 | 32.77 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1708 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2275 | 7191 | 99.22 | 38.09 | 1.54 |

