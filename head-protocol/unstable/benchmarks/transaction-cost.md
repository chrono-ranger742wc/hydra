--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-14 06:10:34.650840907 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.35 | 9.90 | 0.53 |
| 3 | 171 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 227 | 858 | 53.83 | 15.36 | 0.73 |
| 5 | 282 | 969 | 62.93 | 17.88 | 0.83 |
| 6 | 339 | 1081 | 69.83 | 19.96 | 0.91 |
| 7 | 394 | 1192 | 74.46 | 21.54 | 0.96 |
| 8 | 449 | 1303 | 97.89 | 27.41 | 1.20 |
| 9 | 507 | 1414 | 92.94 | 26.77 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.00 | 7.62 | 0.48 |
| 2| 1949 | 25.88 | 8.79 | 0.51 |
| 3| 2121 | 28.51 | 10.19 | 0.55 |
| 5| 2465 | 32.37 | 12.61 | 0.61 |
| 10| 3223 | 42.90 | 18.89 | 0.77 |
| 38| 7470 | 95.78 | 52.27 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 698 | 22.55 | 7.94 | 0.42 |
| 3| 884 | 25.74 | 9.54 | 0.47 |
| 5| 1187 | 29.58 | 11.94 | 0.53 |
| 10| 2130 | 40.80 | 18.38 | 0.71 |
| 43| 6725 | 97.98 | 56.26 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.17 | 8.91 | 0.48 |
| 2| 840 | 31.58 | 10.27 | 0.52 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1339 | 35.72 | 13.46 | 0.59 |
| 10| 2078 | 48.08 | 20.24 | 0.78 |
| 36| 5933 | 95.55 | 50.91 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.85 | 11.38 | 0.56 |
| 3| 942 | 37.87 | 12.61 | 0.59 |
| 5| 1200 | 42.01 | 15.08 | 0.65 |
| 10| 2025 | 53.83 | 21.75 | 0.83 |
| 28| 5006 | 99.11 | 46.40 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.00 | 9.07 | 0.69 |
| 2| 5964 | 36.07 | 12.11 | 0.79 |
| 3| 6096 | 44.62 | 15.02 | 0.89 |
| 4| 6375 | 57.55 | 19.49 | 1.04 |
| 5| 6402 | 61.43 | 20.67 | 1.08 |
| 6| 6512 | 70.46 | 23.75 | 1.18 |
| 7| 6664 | 82.99 | 27.93 | 1.32 |
| 8| 6991 | 90.11 | 30.42 | 1.41 |
| 9| 7060 | 96.75 | 32.62 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2161 | 7123 | 96.44 | 36.92 | 1.51 |

