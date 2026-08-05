--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-05 06:59:58.271564357 UTC |
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
| 1| 5840 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 225 | 858 | 49.42 | 14.25 | 0.69 |
| 5 | 285 | 969 | 62.68 | 17.88 | 0.83 |
| 6 | 337 | 1081 | 72.02 | 20.52 | 0.93 |
| 7 | 393 | 1192 | 76.37 | 21.87 | 0.98 |
| 8 | 448 | 1303 | 92.03 | 26.11 | 1.14 |
| 9 | 506 | 1414 | 90.66 | 26.30 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 1933 | 25.47 | 8.70 | 0.50 |
| 3| 2115 | 27.89 | 10.04 | 0.54 |
| 5| 2494 | 33.31 | 12.88 | 0.62 |
| 10| 3178 | 41.74 | 18.57 | 0.76 |
| 41| 7695 | 97.87 | 54.85 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.77 | 7.36 | 0.42 |
| 2| 730 | 22.52 | 7.93 | 0.42 |
| 3| 830 | 24.13 | 9.06 | 0.45 |
| 5| 1163 | 28.00 | 11.48 | 0.51 |
| 10| 1888 | 36.58 | 17.21 | 0.65 |
| 42| 6700 | 98.35 | 55.71 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.47 | 8.46 | 0.46 |
| 2| 834 | 31.58 | 10.26 | 0.52 |
| 3| 1050 | 34.18 | 11.67 | 0.56 |
| 5| 1396 | 39.01 | 14.39 | 0.63 |
| 10| 2046 | 45.00 | 19.39 | 0.74 |
| 35| 5873 | 96.42 | 50.53 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 713 | 33.83 | 10.16 | 0.53 |
| 2| 838 | 35.85 | 11.38 | 0.56 |
| 3| 945 | 37.80 | 12.59 | 0.59 |
| 5| 1361 | 43.25 | 15.47 | 0.67 |
| 10| 2134 | 55.26 | 22.18 | 0.85 |
| 29| 4990 | 99.10 | 47.06 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.13 | 9.10 | 0.69 |
| 2| 5997 | 37.05 | 12.48 | 0.80 |
| 3| 6093 | 45.00 | 15.12 | 0.89 |
| 4| 5928 | 39.35 | 12.91 | 0.82 |
| 5| 6421 | 63.86 | 21.54 | 1.10 |
| 6| 6641 | 74.35 | 25.08 | 1.22 |
| 7| 6730 | 83.09 | 27.98 | 1.32 |
| 8| 6837 | 86.51 | 29.13 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |

