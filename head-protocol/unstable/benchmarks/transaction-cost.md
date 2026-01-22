--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-22 05:15:53.972459788 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.97 | 4.75 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7651 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1272 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 170 | 747 | 43.79 | 12.52 | 0.63 |
| 4 | 227 | 858 | 53.30 | 15.21 | 0.73 |
| 5 | 284 | 969 | 55.95 | 16.20 | 0.76 |
| 6 | 338 | 1081 | 73.08 | 20.73 | 0.94 |
| 7 | 393 | 1192 | 83.24 | 23.65 | 1.05 |
| 8 | 452 | 1303 | 81.13 | 23.55 | 1.03 |
| 9 | 505 | 1414 | 98.40 | 28.03 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 1887 | 24.43 | 8.40 | 0.49 |
| 3| 2085 | 27.39 | 9.88 | 0.53 |
| 5| 2436 | 32.19 | 12.57 | 0.61 |
| 10| 3268 | 42.84 | 18.87 | 0.78 |
| 41| 7719 | 98.86 | 55.13 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.77 | 7.36 | 0.42 |
| 2| 840 | 25.53 | 8.80 | 0.46 |
| 3| 966 | 26.06 | 9.59 | 0.47 |
| 5| 1171 | 28.11 | 11.49 | 0.51 |
| 10| 1997 | 38.32 | 17.69 | 0.68 |
| 42| 6720 | 99.30 | 55.99 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.51 | 8.47 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 951 | 30.87 | 10.74 | 0.52 |
| 5| 1295 | 37.81 | 14.01 | 0.61 |
| 10| 2139 | 45.94 | 19.70 | 0.76 |
| 37| 6009 | 99.13 | 52.55 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.79 | 10.15 | 0.53 |
| 2| 832 | 35.92 | 11.40 | 0.56 |
| 3| 950 | 37.91 | 12.62 | 0.59 |
| 5| 1327 | 43.62 | 15.58 | 0.67 |
| 10| 2054 | 53.90 | 21.77 | 0.83 |
| 29| 4964 | 98.79 | 46.94 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5919 | 35.95 | 12.09 | 0.79 |
| 3| 6094 | 44.89 | 15.10 | 0.89 |
| 4| 6051 | 45.99 | 15.31 | 0.90 |
| 5| 6460 | 64.68 | 21.85 | 1.11 |
| 6| 6469 | 67.64 | 22.74 | 1.15 |
| 7| 6684 | 82.61 | 27.81 | 1.31 |
| 8| 6938 | 94.35 | 31.80 | 1.45 |
| 9| 6933 | 97.65 | 32.90 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 286 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

