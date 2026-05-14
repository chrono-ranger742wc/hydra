--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-14 07:10:29.786013277 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6039 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 226 | 862 | 54.20 | 15.48 | 0.74 |
| 5 | 282 | 969 | 59.53 | 17.12 | 0.80 |
| 6 | 337 | 1081 | 70.12 | 20.10 | 0.91 |
| 7 | 393 | 1192 | 87.13 | 24.58 | 1.08 |
| 8 | 448 | 1303 | 89.77 | 25.56 | 1.12 |
| 9 | 504 | 1414 | 90.66 | 26.06 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.40 | 8.39 | 0.49 |
| 3| 2120 | 28.44 | 10.20 | 0.55 |
| 5| 2501 | 32.99 | 12.80 | 0.62 |
| 10| 3198 | 40.65 | 18.27 | 0.75 |
| 38| 7316 | 94.49 | 51.88 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.50 | 7.29 | 0.41 |
| 2| 745 | 24.35 | 8.46 | 0.44 |
| 3| 834 | 24.06 | 9.04 | 0.45 |
| 5| 1229 | 30.13 | 12.07 | 0.53 |
| 10| 2049 | 41.03 | 18.44 | 0.70 |
| 40| 6302 | 91.32 | 52.43 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 744 | 30.27 | 9.86 | 0.50 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1260 | 37.73 | 13.99 | 0.61 |
| 10| 2002 | 44.30 | 19.18 | 0.73 |
| 35| 5883 | 95.06 | 50.10 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.16 | 0.53 |
| 2| 891 | 36.60 | 11.61 | 0.57 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1293 | 42.53 | 15.25 | 0.66 |
| 10| 2049 | 53.97 | 21.79 | 0.83 |
| 28| 4719 | 96.95 | 45.75 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.07 | 0.69 |
| 2| 5984 | 35.80 | 12.04 | 0.79 |
| 3| 6033 | 41.45 | 13.85 | 0.85 |
| 4| 6130 | 53.11 | 17.86 | 0.98 |
| 5| 6383 | 60.62 | 20.36 | 1.07 |
| 6| 6681 | 75.76 | 25.61 | 1.24 |
| 7| 6684 | 79.17 | 26.60 | 1.28 |
| 8| 6967 | 93.88 | 31.65 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 572 | 6177 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2160 | 7122 | 96.88 | 37.08 | 1.51 |

