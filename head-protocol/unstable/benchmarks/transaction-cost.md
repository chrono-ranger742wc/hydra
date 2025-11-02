--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-02 05:34:29.559604712 UTC |
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
| 1| 5838 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 29.00 | 9.14 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 43.85 | 12.59 | 0.63 |
| 4 | 227 | 858 | 53.98 | 15.37 | 0.73 |
| 5 | 283 | 969 | 58.33 | 16.87 | 0.79 |
| 6 | 338 | 1081 | 64.53 | 18.69 | 0.85 |
| 7 | 392 | 1192 | 80.42 | 22.88 | 1.02 |
| 8 | 448 | 1307 | 98.19 | 27.48 | 1.20 |
| 9 | 504 | 1414 | 96.71 | 27.74 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.29 | 7.69 | 0.48 |
| 2| 1929 | 25.51 | 8.70 | 0.50 |
| 3| 2062 | 27.47 | 9.90 | 0.53 |
| 5| 2423 | 31.95 | 12.51 | 0.61 |
| 10| 3218 | 42.52 | 18.78 | 0.77 |
| 41| 7784 | 99.95 | 55.45 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 818 | 25.49 | 8.78 | 0.46 |
| 3| 857 | 24.07 | 9.03 | 0.45 |
| 5| 1124 | 27.09 | 11.21 | 0.50 |
| 10| 2002 | 38.93 | 17.86 | 0.68 |
| 40| 6404 | 97.48 | 54.13 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 714 | 27.54 | 8.47 | 0.47 |
| 2| 838 | 29.26 | 9.62 | 0.49 |
| 3| 967 | 33.43 | 11.44 | 0.55 |
| 5| 1227 | 34.37 | 13.04 | 0.58 |
| 10| 1995 | 47.40 | 20.03 | 0.77 |
| 36| 6065 | 98.32 | 51.69 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 1034 | 38.59 | 12.82 | 0.60 |
| 5| 1212 | 41.93 | 15.06 | 0.65 |
| 10| 2097 | 55.52 | 22.25 | 0.85 |
| 29| 4874 | 98.69 | 46.92 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.13 | 9.11 | 0.69 |
| 2| 5994 | 37.06 | 12.50 | 0.80 |
| 3| 5977 | 40.61 | 13.56 | 0.84 |
| 4| 6286 | 54.69 | 18.45 | 1.00 |
| 5| 6482 | 62.92 | 21.26 | 1.10 |
| 6| 6462 | 69.19 | 23.27 | 1.16 |
| 7| 6688 | 80.41 | 27.10 | 1.29 |
| 8| 7085 | 95.10 | 32.13 | 1.46 |
| 9| 7093 | 98.16 | 33.18 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1707 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2218 | 7158 | 99.49 | 38.08 | 1.54 |

