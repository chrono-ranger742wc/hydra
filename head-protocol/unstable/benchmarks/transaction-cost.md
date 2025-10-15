--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-15 04:39:23.167792351 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7647 | 29.30 | 9.24 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 226 | 862 | 51.13 | 14.72 | 0.71 |
| 5 | 284 | 969 | 62.48 | 17.77 | 0.83 |
| 6 | 338 | 1081 | 69.25 | 19.78 | 0.90 |
| 7 | 394 | 1192 | 74.71 | 21.56 | 0.96 |
| 8 | 448 | 1303 | 79.95 | 23.21 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.29 | 7.69 | 0.48 |
| 2| 1987 | 27.00 | 9.10 | 0.52 |
| 3| 2070 | 26.95 | 9.77 | 0.53 |
| 5| 2420 | 32.03 | 12.53 | 0.61 |
| 10| 3095 | 40.04 | 18.08 | 0.74 |
| 40| 7663 | 97.97 | 54.22 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.57 | 7.32 | 0.41 |
| 2| 747 | 24.35 | 8.48 | 0.44 |
| 3| 956 | 26.68 | 9.79 | 0.48 |
| 5| 1203 | 29.19 | 11.80 | 0.52 |
| 10| 2026 | 40.36 | 18.28 | 0.70 |
| 42| 6740 | 99.47 | 56.00 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.13 | 8.90 | 0.48 |
| 2| 817 | 29.22 | 9.61 | 0.49 |
| 3| 868 | 32.08 | 11.03 | 0.53 |
| 5| 1243 | 37.06 | 13.78 | 0.60 |
| 10| 2053 | 48.49 | 20.36 | 0.78 |
| 36| 5815 | 95.75 | 50.93 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 854 | 36.52 | 11.59 | 0.57 |
| 3| 1094 | 39.26 | 13.03 | 0.61 |
| 5| 1225 | 41.78 | 15.02 | 0.65 |
| 10| 2035 | 53.91 | 21.77 | 0.83 |
| 31| 4939 | 98.96 | 48.21 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5841 | 27.08 | 9.09 | 0.69 |
| 2| 5952 | 37.05 | 12.48 | 0.80 |
| 3| 6081 | 42.64 | 14.31 | 0.87 |
| 4| 6150 | 50.68 | 16.98 | 0.95 |
| 5| 6470 | 64.77 | 21.88 | 1.12 |
| 6| 6578 | 73.87 | 24.91 | 1.22 |
| 7| 6824 | 84.51 | 28.50 | 1.34 |
| 8| 6862 | 92.20 | 31.11 | 1.42 |
| 9| 7082 | 99.96 | 33.74 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.99 | 7.82 | 0.65 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

