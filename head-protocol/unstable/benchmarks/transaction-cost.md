--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-04 05:51:00.565581718 UTC |
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
| 1| 5834 | 10.93 | 3.49 | 0.52 |
| 2| 6035 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.79 | 4.69 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 228 | 862 | 49.41 | 14.28 | 0.69 |
| 5 | 283 | 969 | 61.18 | 17.49 | 0.81 |
| 6 | 337 | 1085 | 66.31 | 19.11 | 0.87 |
| 7 | 392 | 1192 | 72.40 | 20.96 | 0.94 |
| 8 | 453 | 1303 | 84.76 | 24.36 | 1.07 |
| 9 | 506 | 1418 | 88.65 | 25.75 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.37 | 7.71 | 0.48 |
| 2| 1957 | 25.55 | 8.71 | 0.51 |
| 3| 2090 | 27.27 | 9.85 | 0.53 |
| 5| 2361 | 31.53 | 12.37 | 0.60 |
| 10| 3131 | 39.78 | 18.03 | 0.74 |
| 40| 7633 | 98.28 | 54.31 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.57 | 7.32 | 0.41 |
| 2| 730 | 22.52 | 7.93 | 0.42 |
| 3| 970 | 26.90 | 9.85 | 0.48 |
| 5| 1159 | 28.08 | 11.49 | 0.51 |
| 10| 1896 | 36.47 | 17.17 | 0.65 |
| 42| 6733 | 99.58 | 56.07 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.83 | 8.26 | 0.45 |
| 2| 843 | 29.22 | 9.61 | 0.49 |
| 3| 963 | 33.47 | 11.45 | 0.55 |
| 5| 1163 | 33.51 | 12.79 | 0.56 |
| 10| 1945 | 46.83 | 19.85 | 0.76 |
| 36| 5934 | 96.55 | 51.21 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 959 | 37.95 | 12.63 | 0.59 |
| 5| 1231 | 41.82 | 15.03 | 0.65 |
| 10| 2074 | 54.50 | 21.96 | 0.84 |
| 29| 4965 | 99.74 | 47.24 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 26.96 | 9.06 | 0.69 |
| 2| 5920 | 34.79 | 11.64 | 0.78 |
| 3| 6225 | 46.61 | 15.77 | 0.91 |
| 4| 6264 | 55.20 | 18.56 | 1.01 |
| 5| 6370 | 60.49 | 20.30 | 1.07 |
| 6| 6637 | 74.37 | 25.07 | 1.22 |
| 7| 6743 | 80.68 | 27.21 | 1.29 |
| 8| 6847 | 87.61 | 29.46 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 570 | 6175 | 37.74 | 13.85 | 0.83 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7159 | 99.82 | 38.19 | 1.55 |

