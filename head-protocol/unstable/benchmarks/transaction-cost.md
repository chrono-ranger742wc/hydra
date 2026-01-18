--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-18 05:08:25.840272241 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 226 | 858 | 49.50 | 14.30 | 0.69 |
| 5 | 282 | 969 | 63.37 | 18.11 | 0.84 |
| 6 | 339 | 1081 | 69.20 | 19.84 | 0.90 |
| 7 | 392 | 1192 | 77.92 | 22.36 | 0.99 |
| 8 | 449 | 1303 | 81.10 | 23.54 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 23.92 | 7.60 | 0.48 |
| 2| 1984 | 27.00 | 9.10 | 0.52 |
| 3| 2015 | 26.02 | 9.51 | 0.52 |
| 5| 2492 | 32.95 | 12.79 | 0.62 |
| 10| 3098 | 39.56 | 17.96 | 0.74 |
| 39| 7608 | 98.45 | 53.67 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.32 | 0.41 |
| 2| 766 | 24.05 | 8.39 | 0.44 |
| 3| 914 | 25.10 | 9.32 | 0.46 |
| 5| 1394 | 32.90 | 12.88 | 0.57 |
| 10| 2143 | 42.26 | 18.81 | 0.72 |
| 39| 6240 | 93.82 | 52.40 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 825 | 31.69 | 10.29 | 0.52 |
| 3| 962 | 30.98 | 10.76 | 0.52 |
| 5| 1231 | 34.26 | 13.01 | 0.58 |
| 10| 1847 | 45.71 | 19.51 | 0.74 |
| 36| 6155 | 98.56 | 51.80 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 873 | 36.60 | 11.61 | 0.57 |
| 3| 899 | 37.24 | 12.41 | 0.58 |
| 5| 1395 | 43.88 | 15.66 | 0.68 |
| 10| 2076 | 54.88 | 22.05 | 0.84 |
| 29| 4756 | 95.80 | 46.04 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 27.05 | 9.08 | 0.69 |
| 2| 5965 | 35.91 | 12.05 | 0.79 |
| 3| 6120 | 46.01 | 15.50 | 0.90 |
| 4| 6272 | 54.05 | 18.16 | 0.99 |
| 5| 6334 | 59.80 | 20.12 | 1.06 |
| 6| 6541 | 72.54 | 24.48 | 1.20 |
| 7| 6656 | 79.20 | 26.62 | 1.27 |
| 8| 6720 | 90.42 | 30.28 | 1.39 |
| 9| 7118 | 99.71 | 33.67 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 283 | 6002 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

