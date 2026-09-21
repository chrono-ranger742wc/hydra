--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-21 10:10:38.040980048 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.88 | 5.97 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 40.10 | 11.64 | 0.59 |
| 4 | 225 | 858 | 50.88 | 14.60 | 0.70 |
| 5 | 285 | 969 | 56.03 | 16.26 | 0.76 |
| 6 | 337 | 1081 | 66.41 | 19.14 | 0.87 |
| 7 | 392 | 1192 | 84.01 | 23.74 | 1.05 |
| 8 | 448 | 1303 | 89.57 | 25.47 | 1.11 |
| 9 | 504 | 1414 | 88.59 | 25.63 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.37 | 7.71 | 0.48 |
| 2| 2003 | 26.38 | 8.96 | 0.52 |
| 3| 2059 | 27.39 | 9.88 | 0.53 |
| 5| 2284 | 29.37 | 11.77 | 0.57 |
| 10| 3302 | 42.47 | 18.78 | 0.77 |
| 39| 7702 | 99.26 | 53.94 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.54 | 7.30 | 0.41 |
| 2| 774 | 24.32 | 8.46 | 0.44 |
| 3| 943 | 26.16 | 9.61 | 0.47 |
| 5| 1177 | 28.77 | 11.70 | 0.52 |
| 10| 2030 | 39.62 | 18.05 | 0.69 |
| 41| 6629 | 98.51 | 55.11 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 783 | 30.90 | 10.06 | 0.51 |
| 3| 948 | 30.98 | 10.76 | 0.52 |
| 5| 1239 | 37.14 | 13.81 | 0.60 |
| 10| 1976 | 47.44 | 20.04 | 0.76 |
| 37| 6025 | 97.90 | 52.22 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.83 | 10.15 | 0.53 |
| 2| 815 | 35.92 | 11.40 | 0.56 |
| 3| 960 | 37.95 | 12.63 | 0.59 |
| 5| 1278 | 42.68 | 15.29 | 0.66 |
| 10| 1984 | 53.42 | 21.61 | 0.82 |
| 28| 4766 | 96.13 | 45.56 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.11 | 0.69 |
| 2| 5916 | 34.87 | 11.67 | 0.78 |
| 3| 6018 | 41.32 | 13.82 | 0.85 |
| 4| 6223 | 51.26 | 17.24 | 0.96 |
| 5| 6345 | 62.89 | 21.14 | 1.09 |
| 6| 6490 | 68.53 | 22.96 | 1.16 |
| 7| 6790 | 80.27 | 27.07 | 1.29 |
| 8| 6775 | 85.66 | 28.73 | 1.35 |
| 9| 7030 | 99.88 | 33.64 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 567 | 6172 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

