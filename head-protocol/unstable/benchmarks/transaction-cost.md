--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-29 05:35:18.142335565 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6042 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 171 | 747 | 42.60 | 12.26 | 0.62 |
| 4 | 225 | 858 | 48.30 | 14.01 | 0.68 |
| 5 | 284 | 969 | 62.97 | 17.92 | 0.83 |
| 6 | 337 | 1081 | 75.31 | 21.34 | 0.96 |
| 7 | 393 | 1192 | 81.62 | 23.12 | 1.03 |
| 8 | 449 | 1303 | 92.08 | 26.12 | 1.14 |
| 9 | 504 | 1414 | 96.89 | 27.73 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1985 | 26.87 | 9.07 | 0.52 |
| 3| 2061 | 27.02 | 9.79 | 0.53 |
| 5| 2361 | 31.34 | 12.32 | 0.60 |
| 10| 3064 | 39.80 | 18.02 | 0.74 |
| 39| 7450 | 95.85 | 52.93 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.54 | 7.31 | 0.41 |
| 2| 771 | 23.54 | 8.22 | 0.43 |
| 3| 963 | 26.92 | 9.85 | 0.48 |
| 5| 1231 | 29.91 | 12.02 | 0.53 |
| 10| 1979 | 38.69 | 17.78 | 0.68 |
| 42| 6657 | 99.58 | 56.04 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 809 | 29.19 | 9.60 | 0.49 |
| 3| 944 | 30.94 | 10.75 | 0.52 |
| 5| 1210 | 34.22 | 13.00 | 0.57 |
| 10| 2188 | 46.89 | 19.98 | 0.77 |
| 38| 6156 | 99.33 | 53.29 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 826 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1275 | 42.72 | 15.30 | 0.66 |
| 10| 2194 | 55.41 | 22.22 | 0.85 |
| 30| 5060 | 99.86 | 47.91 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5894 | 32.64 | 10.91 | 0.75 |
| 3| 5951 | 40.48 | 13.52 | 0.84 |
| 4| 6383 | 55.78 | 18.85 | 1.02 |
| 5| 6560 | 66.73 | 22.65 | 1.14 |
| 6| 6725 | 76.38 | 25.90 | 1.25 |
| 7| 6880 | 85.63 | 28.84 | 1.35 |
| 8| 6798 | 91.98 | 30.94 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1139 | 6514 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7157 | 97.61 | 37.43 | 1.52 |

