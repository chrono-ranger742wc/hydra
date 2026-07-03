--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-03 07:51:51.116549818 UTC |
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
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 43.99 | 12.61 | 0.63 |
| 4 | 226 | 858 | 47.77 | 13.86 | 0.67 |
| 5 | 282 | 969 | 62.27 | 17.75 | 0.82 |
| 6 | 337 | 1081 | 75.72 | 21.48 | 0.96 |
| 7 | 392 | 1192 | 84.63 | 23.89 | 1.06 |
| 8 | 448 | 1307 | 94.10 | 26.60 | 1.16 |
| 10 | 560 | 1529 | 97.44 | 28.27 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 23.92 | 7.60 | 0.48 |
| 2| 2025 | 26.50 | 8.98 | 0.52 |
| 3| 2129 | 28.39 | 10.16 | 0.55 |
| 5| 2507 | 33.64 | 12.96 | 0.63 |
| 10| 3024 | 39.12 | 17.82 | 0.73 |
| 38| 7460 | 98.93 | 53.11 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.81 | 7.37 | 0.42 |
| 2| 768 | 24.08 | 8.40 | 0.44 |
| 3| 872 | 25.09 | 9.32 | 0.46 |
| 5| 1263 | 31.22 | 12.39 | 0.55 |
| 10| 1932 | 37.53 | 17.46 | 0.66 |
| 39| 6649 | 99.30 | 54.02 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 841 | 29.22 | 9.61 | 0.49 |
| 3| 1003 | 33.47 | 11.46 | 0.55 |
| 5| 1255 | 37.10 | 13.80 | 0.60 |
| 10| 2081 | 45.77 | 19.62 | 0.75 |
| 37| 5876 | 96.87 | 51.89 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.83 | 10.15 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 999 | 38.59 | 12.82 | 0.60 |
| 5| 1248 | 42.53 | 15.25 | 0.66 |
| 10| 2147 | 55.67 | 22.29 | 0.86 |
| 29| 4981 | 99.62 | 47.23 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5842 | 27.08 | 9.09 | 0.69 |
| 2| 6001 | 37.01 | 12.47 | 0.80 |
| 3| 6068 | 44.74 | 15.05 | 0.89 |
| 4| 6180 | 50.05 | 16.77 | 0.95 |
| 5| 6416 | 61.55 | 20.74 | 1.08 |
| 6| 6638 | 76.09 | 25.74 | 1.24 |
| 7| 6738 | 82.73 | 27.90 | 1.32 |
| 8| 7013 | 92.03 | 31.08 | 1.43 |
| 9| 6923 | 97.93 | 32.90 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2215 | 7154 | 97.61 | 37.43 | 1.52 |

