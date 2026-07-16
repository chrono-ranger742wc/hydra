--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-16 06:50:12.090840806 UTC |
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
| 2| 6038 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.38 | 11.95 | 0.60 |
| 4 | 225 | 858 | 52.10 | 14.90 | 0.72 |
| 5 | 283 | 969 | 59.64 | 17.18 | 0.80 |
| 6 | 337 | 1081 | 72.45 | 20.70 | 0.93 |
| 7 | 393 | 1192 | 85.16 | 24.11 | 1.06 |
| 8 | 450 | 1303 | 92.10 | 26.18 | 1.14 |
| 9 | 505 | 1414 | 88.74 | 25.66 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.37 | 7.71 | 0.48 |
| 2| 1926 | 25.92 | 8.80 | 0.51 |
| 3| 2060 | 27.36 | 9.87 | 0.53 |
| 5| 2450 | 32.54 | 12.65 | 0.61 |
| 10| 3178 | 41.92 | 18.61 | 0.76 |
| 40| 7726 | 99.87 | 54.73 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.32 | 0.41 |
| 2| 766 | 23.65 | 8.25 | 0.43 |
| 3| 1017 | 28.22 | 10.20 | 0.50 |
| 5| 1194 | 29.18 | 11.80 | 0.52 |
| 10| 2012 | 40.90 | 18.40 | 0.70 |
| 41| 6547 | 97.08 | 54.71 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.17 | 8.91 | 0.48 |
| 2| 737 | 30.23 | 9.85 | 0.50 |
| 3| 1017 | 31.58 | 10.95 | 0.53 |
| 5| 1293 | 37.88 | 14.04 | 0.61 |
| 10| 2073 | 45.54 | 19.56 | 0.75 |
| 36| 5624 | 98.40 | 51.55 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.83 | 10.15 | 0.53 |
| 2| 818 | 35.88 | 11.39 | 0.56 |
| 3| 966 | 37.87 | 12.61 | 0.59 |
| 5| 1204 | 41.97 | 15.07 | 0.65 |
| 10| 2046 | 54.21 | 21.85 | 0.84 |
| 28| 4782 | 96.69 | 45.70 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.08 | 9.09 | 0.69 |
| 2| 5971 | 37.09 | 12.49 | 0.80 |
| 3| 6176 | 45.44 | 15.35 | 0.90 |
| 4| 6225 | 53.92 | 18.10 | 0.99 |
| 5| 6296 | 59.95 | 20.12 | 1.06 |
| 6| 6474 | 67.74 | 22.81 | 1.15 |
| 7| 6452 | 70.97 | 23.70 | 1.18 |
| 8| 6884 | 89.05 | 29.99 | 1.39 |
| 9| 7091 | 99.63 | 33.58 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

