--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-06 08:53:24.794364998 UTC |
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
| 1| 5838 | 10.85 | 3.45 | 0.52 |
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.97 | 4.75 | 0.58 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.31 | 9.25 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.35 | 12.18 | 0.61 |
| 4 | 227 | 858 | 52.64 | 15.08 | 0.72 |
| 5 | 283 | 969 | 56.56 | 16.42 | 0.77 |
| 6 | 337 | 1081 | 71.31 | 20.31 | 0.92 |
| 7 | 395 | 1192 | 86.59 | 24.40 | 1.08 |
| 8 | 448 | 1303 | 94.33 | 26.66 | 1.16 |
| 9 | 505 | 1414 | 95.02 | 27.34 | 1.18 |
| 10 | 560 | 1525 | 96.93 | 28.02 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.43 | 8.68 | 0.50 |
| 3| 2067 | 27.47 | 9.90 | 0.53 |
| 5| 2350 | 30.22 | 12.01 | 0.58 |
| 10| 3193 | 42.32 | 18.73 | 0.77 |
| 40| 7330 | 93.33 | 52.90 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.54 | 7.30 | 0.41 |
| 2| 737 | 23.65 | 8.25 | 0.43 |
| 3| 895 | 25.03 | 9.30 | 0.46 |
| 5| 1161 | 27.97 | 11.46 | 0.51 |
| 10| 1983 | 38.98 | 17.89 | 0.68 |
| 41| 6440 | 94.61 | 54.00 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 867 | 29.94 | 9.83 | 0.50 |
| 3| 971 | 33.40 | 11.43 | 0.55 |
| 5| 1281 | 34.97 | 13.23 | 0.58 |
| 10| 2012 | 45.02 | 19.40 | 0.74 |
| 36| 6041 | 98.13 | 51.67 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.15 | 0.53 |
| 2| 804 | 35.88 | 11.39 | 0.56 |
| 3| 1010 | 38.58 | 12.82 | 0.60 |
| 5| 1269 | 42.49 | 15.24 | 0.66 |
| 10| 2074 | 54.72 | 22.01 | 0.84 |
| 29| 4879 | 97.96 | 46.66 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.05 | 9.08 | 0.69 |
| 2| 5979 | 37.13 | 12.52 | 0.80 |
| 3| 6128 | 45.99 | 15.47 | 0.90 |
| 4| 6299 | 55.11 | 18.58 | 1.01 |
| 5| 6421 | 62.61 | 21.10 | 1.09 |
| 6| 6636 | 75.21 | 25.38 | 1.23 |
| 7| 6834 | 84.47 | 28.53 | 1.34 |
| 8| 7058 | 94.90 | 32.03 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1705 | 6851 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

