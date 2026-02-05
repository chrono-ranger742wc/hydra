--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-05 05:45:56.315688942 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6039 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.90 | 4.72 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 43.84 | 12.55 | 0.63 |
| 4 | 227 | 862 | 48.13 | 13.97 | 0.68 |
| 5 | 283 | 969 | 62.46 | 17.80 | 0.83 |
| 6 | 338 | 1081 | 66.18 | 19.08 | 0.87 |
| 7 | 393 | 1192 | 86.34 | 24.30 | 1.08 |
| 8 | 450 | 1307 | 81.29 | 23.59 | 1.03 |
| 9 | 504 | 1414 | 91.56 | 26.39 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.00 | 7.62 | 0.48 |
| 2| 1933 | 25.88 | 8.79 | 0.51 |
| 3| 2057 | 26.98 | 9.78 | 0.53 |
| 5| 2581 | 34.14 | 13.12 | 0.63 |
| 10| 3092 | 40.31 | 18.16 | 0.74 |
| 40| 7570 | 96.15 | 53.71 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.84 | 7.37 | 0.41 |
| 2| 752 | 24.08 | 8.41 | 0.44 |
| 3| 1039 | 27.92 | 10.14 | 0.49 |
| 5| 1288 | 30.13 | 12.07 | 0.54 |
| 10| 1959 | 39.70 | 18.07 | 0.69 |
| 41| 6651 | 98.58 | 55.12 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 745 | 30.20 | 9.84 | 0.50 |
| 3| 952 | 30.94 | 10.75 | 0.52 |
| 5| 1231 | 34.22 | 13.01 | 0.57 |
| 10| 2065 | 47.97 | 20.21 | 0.77 |
| 36| 5747 | 99.23 | 51.85 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 837 | 35.92 | 11.40 | 0.56 |
| 3| 989 | 38.55 | 12.81 | 0.60 |
| 5| 1247 | 42.53 | 15.25 | 0.66 |
| 10| 1988 | 53.42 | 21.61 | 0.83 |
| 30| 4735 | 96.39 | 46.83 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 26.92 | 9.05 | 0.69 |
| 2| 5945 | 35.99 | 12.10 | 0.79 |
| 3| 6117 | 42.49 | 14.27 | 0.87 |
| 4| 6354 | 55.55 | 18.82 | 1.01 |
| 5| 6585 | 66.93 | 22.68 | 1.14 |
| 6| 6579 | 72.84 | 24.53 | 1.21 |
| 7| 6715 | 83.58 | 28.13 | 1.32 |
| 8| 6806 | 90.80 | 30.57 | 1.40 |
| 9| 6942 | 96.66 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 21.66 | 7.36 | 0.64 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.24 | 37.65 | 1.53 |

