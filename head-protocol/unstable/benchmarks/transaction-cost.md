--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-10 10:58:37.356972111 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 39.92 | 11.61 | 0.59 |
| 4 | 226 | 858 | 50.89 | 14.61 | 0.70 |
| 5 | 284 | 969 | 60.90 | 17.45 | 0.81 |
| 6 | 337 | 1081 | 63.85 | 18.48 | 0.85 |
| 7 | 395 | 1192 | 86.68 | 24.43 | 1.08 |
| 8 | 449 | 1303 | 98.57 | 27.67 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.43 | 8.68 | 0.50 |
| 3| 2060 | 26.87 | 9.75 | 0.53 |
| 5| 2407 | 31.26 | 12.30 | 0.60 |
| 10| 3140 | 41.01 | 18.36 | 0.75 |
| 42| 7620 | 96.72 | 55.14 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.37 | 0.42 |
| 2| 837 | 25.10 | 8.68 | 0.45 |
| 3| 942 | 26.57 | 9.76 | 0.48 |
| 5| 1143 | 28.00 | 11.47 | 0.51 |
| 10| 2048 | 40.63 | 18.34 | 0.70 |
| 40| 6520 | 97.85 | 54.25 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 793 | 30.87 | 10.05 | 0.51 |
| 3| 1009 | 31.65 | 10.97 | 0.53 |
| 5| 1252 | 35.08 | 13.26 | 0.58 |
| 10| 1981 | 46.92 | 19.87 | 0.76 |
| 34| 5618 | 97.55 | 50.10 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 861 | 36.56 | 11.60 | 0.57 |
| 3| 895 | 37.16 | 12.39 | 0.58 |
| 5| 1250 | 42.65 | 15.28 | 0.66 |
| 10| 1956 | 53.41 | 21.61 | 0.82 |
| 29| 4913 | 98.36 | 46.82 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.08 | 9.08 | 0.69 |
| 2| 5921 | 34.75 | 11.63 | 0.78 |
| 3| 6100 | 42.29 | 14.22 | 0.86 |
| 4| 6220 | 53.89 | 18.12 | 0.99 |
| 5| 6313 | 59.59 | 19.97 | 1.05 |
| 6| 6599 | 71.30 | 24.02 | 1.19 |
| 7| 6913 | 87.11 | 29.43 | 1.37 |
| 8| 7022 | 94.40 | 31.78 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1134 | 6508 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2280 | 7196 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2164 | 7127 | 96.88 | 37.08 | 1.51 |

