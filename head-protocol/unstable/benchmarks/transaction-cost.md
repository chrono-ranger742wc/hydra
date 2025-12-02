--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-02 05:40:22.958715768 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6243 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 39.81 | 11.57 | 0.59 |
| 4 | 227 | 858 | 50.87 | 14.60 | 0.70 |
| 5 | 282 | 969 | 64.34 | 18.25 | 0.84 |
| 6 | 338 | 1081 | 68.46 | 19.71 | 0.89 |
| 7 | 394 | 1192 | 73.12 | 21.22 | 0.95 |
| 8 | 449 | 1303 | 85.35 | 24.56 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.37 | 7.71 | 0.48 |
| 2| 1985 | 26.55 | 9.00 | 0.52 |
| 3| 2133 | 28.38 | 10.16 | 0.55 |
| 5| 2406 | 31.18 | 12.28 | 0.60 |
| 10| 3225 | 41.69 | 18.56 | 0.76 |
| 41| 7615 | 98.80 | 55.08 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.54 | 7.30 | 0.41 |
| 2| 838 | 25.29 | 8.74 | 0.45 |
| 3| 861 | 24.11 | 9.04 | 0.45 |
| 5| 1238 | 30.21 | 12.09 | 0.54 |
| 10| 2063 | 42.15 | 18.75 | 0.72 |
| 41| 6614 | 99.37 | 55.28 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.54 | 8.47 | 0.46 |
| 2| 791 | 30.98 | 10.08 | 0.51 |
| 3| 1060 | 32.28 | 11.17 | 0.54 |
| 5| 1247 | 36.95 | 13.76 | 0.60 |
| 10| 2071 | 45.80 | 19.63 | 0.75 |
| 36| 6095 | 98.93 | 51.89 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.87 | 10.16 | 0.53 |
| 2| 882 | 36.64 | 11.62 | 0.57 |
| 3| 999 | 38.55 | 12.81 | 0.60 |
| 5| 1217 | 41.89 | 15.05 | 0.65 |
| 10| 2046 | 53.95 | 21.78 | 0.83 |
| 29| 4826 | 98.05 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.13 | 9.11 | 0.69 |
| 2| 5953 | 35.80 | 12.03 | 0.79 |
| 3| 6053 | 44.69 | 15.05 | 0.89 |
| 4| 6049 | 45.77 | 15.21 | 0.90 |
| 5| 6277 | 55.65 | 18.61 | 1.01 |
| 6| 6503 | 73.19 | 24.70 | 1.21 |
| 7| 6779 | 82.24 | 27.76 | 1.31 |
| 8| 6775 | 84.73 | 28.43 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.68 | 37.80 | 1.53 |

