--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-25 05:10:59.074902599 UTC |
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
| 1| 5834 | 11.04 | 3.52 | 0.52 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 15.07 | 4.78 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 39.94 | 11.60 | 0.59 |
| 4 | 228 | 858 | 50.81 | 14.59 | 0.70 |
| 5 | 281 | 969 | 59.41 | 17.09 | 0.80 |
| 6 | 337 | 1081 | 75.39 | 21.36 | 0.96 |
| 7 | 394 | 1192 | 82.94 | 23.57 | 1.04 |
| 8 | 452 | 1303 | 84.93 | 24.40 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.39 | 8.68 | 0.50 |
| 3| 2065 | 26.94 | 9.77 | 0.53 |
| 5| 2404 | 31.35 | 12.34 | 0.60 |
| 10| 3139 | 40.57 | 18.24 | 0.75 |
| 40| 7485 | 95.19 | 53.40 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.32 | 0.41 |
| 2| 772 | 23.61 | 8.23 | 0.43 |
| 3| 959 | 26.60 | 9.77 | 0.48 |
| 5| 1186 | 29.07 | 11.78 | 0.52 |
| 10| 2033 | 40.62 | 18.35 | 0.70 |
| 41| 6709 | 97.97 | 54.97 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.13 | 8.90 | 0.48 |
| 2| 820 | 29.15 | 9.59 | 0.49 |
| 3| 940 | 32.69 | 11.22 | 0.54 |
| 5| 1295 | 35.12 | 13.27 | 0.59 |
| 10| 1959 | 46.50 | 19.77 | 0.75 |
| 33| 5575 | 91.38 | 47.77 | 1.48 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 947 | 37.80 | 12.59 | 0.59 |
| 5| 1314 | 43.32 | 15.49 | 0.67 |
| 10| 2045 | 54.16 | 21.83 | 0.84 |
| 29| 4903 | 98.35 | 46.81 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 27.09 | 9.08 | 0.69 |
| 2| 5901 | 34.87 | 11.68 | 0.78 |
| 3| 6092 | 44.69 | 15.01 | 0.89 |
| 4| 6224 | 53.85 | 18.06 | 0.99 |
| 5| 6431 | 64.36 | 21.65 | 1.11 |
| 6| 6552 | 73.50 | 24.76 | 1.21 |
| 7| 6749 | 83.79 | 28.25 | 1.33 |
| 8| 6873 | 92.88 | 31.29 | 1.43 |
| 9| 6911 | 96.16 | 32.28 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 39 | 2217 | 7156 | 98.49 | 37.73 | 1.53 |

