--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-26 06:03:56.044872168 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 42.65 | 12.27 | 0.62 |
| 4 | 226 | 858 | 53.23 | 15.17 | 0.73 |
| 5 | 282 | 969 | 55.81 | 16.17 | 0.76 |
| 6 | 338 | 1081 | 66.64 | 19.27 | 0.88 |
| 7 | 394 | 1192 | 78.17 | 22.34 | 1.00 |
| 8 | 448 | 1303 | 86.32 | 24.68 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1937 | 25.76 | 8.76 | 0.51 |
| 3| 2142 | 28.31 | 10.14 | 0.55 |
| 5| 2427 | 32.27 | 12.59 | 0.61 |
| 10| 3198 | 42.38 | 18.73 | 0.77 |
| 40| 7616 | 97.70 | 54.09 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.80 | 7.38 | 0.41 |
| 2| 803 | 25.16 | 8.70 | 0.45 |
| 3| 924 | 26.90 | 9.85 | 0.48 |
| 5| 1335 | 32.35 | 12.69 | 0.56 |
| 10| 2005 | 40.93 | 18.43 | 0.70 |
| 42| 6659 | 97.99 | 55.64 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.09 | 8.89 | 0.48 |
| 2| 826 | 29.22 | 9.61 | 0.49 |
| 3| 992 | 31.69 | 10.98 | 0.53 |
| 5| 1306 | 37.69 | 13.98 | 0.61 |
| 10| 2129 | 46.28 | 19.79 | 0.76 |
| 34| 5582 | 97.39 | 49.97 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.16 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 984 | 38.51 | 12.80 | 0.60 |
| 5| 1157 | 41.26 | 14.85 | 0.64 |
| 10| 2021 | 53.50 | 21.63 | 0.83 |
| 29| 4983 | 99.35 | 47.08 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 26.92 | 9.04 | 0.69 |
| 2| 5893 | 34.87 | 11.69 | 0.78 |
| 3| 6091 | 45.00 | 15.10 | 0.89 |
| 4| 6366 | 56.92 | 19.24 | 1.03 |
| 5| 6412 | 63.72 | 21.43 | 1.10 |
| 6| 6539 | 73.85 | 24.85 | 1.21 |
| 7| 6571 | 77.65 | 26.03 | 1.25 |
| 8| 6846 | 91.57 | 30.76 | 1.41 |
| 9| 6970 | 99.13 | 33.31 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

