--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-18 05:56:51.49680549 UTC |
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
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14285 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.51 | 12.00 | 0.60 |
| 4 | 228 | 858 | 49.87 | 14.41 | 0.69 |
| 5 | 281 | 969 | 62.96 | 17.92 | 0.83 |
| 6 | 337 | 1081 | 66.42 | 19.21 | 0.87 |
| 7 | 394 | 1192 | 82.42 | 23.36 | 1.04 |
| 8 | 450 | 1303 | 83.35 | 24.08 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2017 | 25.87 | 9.47 | 0.52 |
| 5| 2277 | 29.30 | 11.75 | 0.57 |
| 10| 3095 | 39.74 | 18.00 | 0.74 |
| 39| 7649 | 99.89 | 54.04 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.31 | 0.41 |
| 2| 826 | 25.49 | 8.79 | 0.46 |
| 3| 949 | 26.09 | 9.60 | 0.47 |
| 5| 1161 | 28.08 | 11.49 | 0.51 |
| 10| 1953 | 37.52 | 17.46 | 0.67 |
| 42| 6796 | 99.74 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 806 | 29.22 | 9.61 | 0.49 |
| 3| 948 | 30.87 | 10.74 | 0.52 |
| 5| 1169 | 33.58 | 12.81 | 0.57 |
| 10| 2211 | 46.18 | 19.76 | 0.76 |
| 35| 6009 | 96.71 | 50.61 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.87 | 10.16 | 0.53 |
| 2| 810 | 35.88 | 11.39 | 0.56 |
| 3| 899 | 37.13 | 12.38 | 0.58 |
| 5| 1203 | 41.89 | 15.05 | 0.65 |
| 10| 2071 | 54.92 | 22.06 | 0.84 |
| 29| 4959 | 98.75 | 46.95 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.05 | 9.07 | 0.69 |
| 2| 5917 | 35.92 | 12.06 | 0.79 |
| 3| 6085 | 44.59 | 15.01 | 0.89 |
| 4| 6295 | 54.48 | 18.40 | 1.00 |
| 5| 6365 | 61.33 | 20.66 | 1.07 |
| 6| 6561 | 70.80 | 23.88 | 1.18 |
| 7| 6802 | 83.38 | 28.06 | 1.33 |
| 8| 7022 | 93.92 | 31.70 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 571 | 6175 | 41.02 | 14.97 | 0.86 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2217 | 7157 | 99.82 | 38.19 | 1.55 |

