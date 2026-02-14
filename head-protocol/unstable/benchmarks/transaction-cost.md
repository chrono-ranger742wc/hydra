--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-14 05:42:35.701583755 UTC |
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
| 1| 5841 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.38 | 12.19 | 0.61 |
| 4 | 227 | 862 | 53.81 | 15.31 | 0.73 |
| 5 | 283 | 969 | 61.52 | 17.64 | 0.82 |
| 6 | 340 | 1081 | 68.50 | 19.71 | 0.89 |
| 7 | 395 | 1192 | 80.64 | 22.94 | 1.02 |
| 8 | 449 | 1303 | 82.06 | 23.66 | 1.04 |
| 10 | 560 | 1525 | 97.09 | 28.12 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.93 | 7.32 | 0.47 |
| 2| 1937 | 25.51 | 8.70 | 0.50 |
| 3| 2067 | 27.02 | 9.79 | 0.53 |
| 5| 2528 | 34.23 | 13.14 | 0.63 |
| 10| 3224 | 41.31 | 18.43 | 0.76 |
| 41| 7614 | 96.32 | 54.40 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.50 | 7.29 | 0.41 |
| 2| 821 | 25.12 | 8.69 | 0.45 |
| 3| 1019 | 27.52 | 10.03 | 0.49 |
| 5| 1310 | 30.60 | 12.23 | 0.54 |
| 10| 2018 | 40.11 | 18.20 | 0.69 |
| 41| 6368 | 95.18 | 54.13 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.51 | 8.47 | 0.46 |
| 2| 870 | 29.86 | 9.81 | 0.50 |
| 3| 979 | 33.43 | 11.45 | 0.55 |
| 5| 1232 | 36.99 | 13.77 | 0.60 |
| 10| 2136 | 49.73 | 20.73 | 0.80 |
| 35| 5791 | 94.41 | 49.96 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.16 | 0.53 |
| 2| 908 | 36.60 | 11.61 | 0.57 |
| 3| 949 | 37.95 | 12.63 | 0.59 |
| 5| 1216 | 41.89 | 15.05 | 0.65 |
| 10| 1885 | 52.33 | 21.28 | 0.81 |
| 29| 4966 | 99.08 | 47.02 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.09 | 9.08 | 0.69 |
| 2| 5938 | 35.84 | 12.05 | 0.79 |
| 3| 6038 | 41.33 | 13.83 | 0.85 |
| 4| 6394 | 55.81 | 18.85 | 1.02 |
| 5| 6394 | 61.71 | 20.82 | 1.08 |
| 6| 6588 | 75.09 | 25.29 | 1.23 |
| 7| 6718 | 80.78 | 27.19 | 1.29 |
| 8| 6856 | 92.45 | 31.16 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 56 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2217 | 7156 | 99.82 | 38.19 | 1.55 |

