--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-17 04:59:26.667814224 UTC |
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
| 1| 5837 | 10.69 | 3.40 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 168 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 226 | 858 | 48.17 | 14.00 | 0.68 |
| 5 | 284 | 969 | 64.05 | 18.14 | 0.84 |
| 6 | 337 | 1081 | 71.52 | 20.43 | 0.92 |
| 7 | 393 | 1192 | 80.43 | 22.93 | 1.02 |
| 8 | 449 | 1303 | 97.05 | 27.41 | 1.19 |
| 9 | 504 | 1418 | 91.09 | 26.52 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 1949 | 25.43 | 8.68 | 0.50 |
| 3| 2059 | 26.86 | 9.75 | 0.53 |
| 5| 2318 | 30.26 | 12.02 | 0.58 |
| 10| 3227 | 42.69 | 18.84 | 0.77 |
| 39| 7533 | 97.79 | 53.49 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 781 | 23.51 | 8.21 | 0.43 |
| 3| 872 | 25.13 | 9.33 | 0.46 |
| 5| 1277 | 31.23 | 12.38 | 0.55 |
| 10| 1971 | 39.62 | 18.08 | 0.69 |
| 41| 6582 | 95.82 | 54.33 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.51 | 8.47 | 0.46 |
| 2| 775 | 28.55 | 9.40 | 0.48 |
| 3| 964 | 33.36 | 11.43 | 0.54 |
| 5| 1303 | 34.94 | 13.22 | 0.59 |
| 10| 1997 | 47.56 | 20.07 | 0.77 |
| 37| 6080 | 99.93 | 52.84 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 937 | 37.84 | 12.60 | 0.59 |
| 5| 1342 | 43.58 | 15.57 | 0.67 |
| 10| 2106 | 54.90 | 22.08 | 0.85 |
| 29| 4967 | 99.52 | 47.16 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 27.08 | 9.08 | 0.69 |
| 2| 5893 | 34.87 | 11.67 | 0.78 |
| 3| 5993 | 41.36 | 13.86 | 0.85 |
| 4| 6317 | 55.15 | 18.58 | 1.01 |
| 5| 6439 | 64.22 | 21.57 | 1.11 |
| 6| 6512 | 70.35 | 23.64 | 1.18 |
| 7| 6667 | 82.28 | 27.72 | 1.31 |
| 8| 7062 | 96.40 | 32.62 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 286 | 6006 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

