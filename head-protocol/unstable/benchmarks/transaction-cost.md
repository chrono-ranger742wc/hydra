--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-20 04:42:22.91823073 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 19.27 | 6.11 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.34 | 9.90 | 0.53 |
| 3 | 170 | 747 | 40.01 | 11.63 | 0.59 |
| 4 | 228 | 858 | 52.28 | 14.97 | 0.72 |
| 5 | 282 | 969 | 57.87 | 16.67 | 0.78 |
| 6 | 337 | 1081 | 74.93 | 21.17 | 0.96 |
| 7 | 395 | 1192 | 78.47 | 22.46 | 1.00 |
| 8 | 454 | 1303 | 87.64 | 25.15 | 1.10 |
| 9 | 505 | 1414 | 89.92 | 26.12 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.29 | 7.69 | 0.48 |
| 2| 1968 | 26.92 | 9.08 | 0.52 |
| 3| 2018 | 26.28 | 9.57 | 0.52 |
| 5| 2494 | 33.55 | 12.94 | 0.62 |
| 10| 3291 | 43.57 | 19.09 | 0.78 |
| 38| 7389 | 95.94 | 52.27 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.53 | 7.30 | 0.41 |
| 2| 769 | 23.63 | 8.24 | 0.43 |
| 3| 830 | 24.06 | 9.03 | 0.45 |
| 5| 1245 | 29.87 | 12.01 | 0.53 |
| 10| 2016 | 38.40 | 17.71 | 0.68 |
| 40| 6477 | 94.30 | 53.27 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.09 | 8.89 | 0.48 |
| 2| 816 | 29.19 | 9.60 | 0.49 |
| 3| 932 | 32.76 | 11.24 | 0.54 |
| 5| 1134 | 35.68 | 13.36 | 0.58 |
| 10| 2105 | 45.68 | 19.60 | 0.75 |
| 36| 6155 | 99.38 | 52.03 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.79 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 960 | 37.91 | 12.62 | 0.59 |
| 5| 1348 | 44.07 | 15.71 | 0.68 |
| 10| 2183 | 55.92 | 22.39 | 0.86 |
| 29| 4944 | 98.38 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 27.16 | 9.11 | 0.69 |
| 2| 5970 | 36.07 | 12.12 | 0.79 |
| 3| 5949 | 40.51 | 13.51 | 0.84 |
| 4| 6374 | 55.84 | 18.87 | 1.02 |
| 5| 6450 | 64.65 | 21.80 | 1.11 |
| 6| 6576 | 73.26 | 24.61 | 1.21 |
| 7| 6809 | 85.48 | 28.91 | 1.35 |
| 8| 6889 | 92.88 | 31.34 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7162 | 97.61 | 37.43 | 1.52 |

