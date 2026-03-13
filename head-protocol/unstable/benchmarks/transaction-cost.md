--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-13 05:36:53.458356965 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.38 | 9.27 | 0.79 |
| 43| 14281 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2166 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 40.27 | 11.70 | 0.59 |
| 4 | 226 | 858 | 52.12 | 14.90 | 0.72 |
| 5 | 282 | 969 | 58.04 | 16.74 | 0.78 |
| 6 | 338 | 1081 | 73.90 | 21.01 | 0.95 |
| 7 | 393 | 1192 | 87.24 | 24.61 | 1.08 |
| 8 | 451 | 1303 | 83.08 | 23.97 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 23.92 | 7.60 | 0.48 |
| 2| 1926 | 25.51 | 8.70 | 0.50 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2421 | 32.52 | 12.65 | 0.61 |
| 10| 3192 | 41.81 | 18.59 | 0.76 |
| 39| 7694 | 99.27 | 53.91 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.50 | 7.30 | 0.41 |
| 2| 751 | 23.54 | 8.22 | 0.43 |
| 3| 955 | 26.09 | 9.60 | 0.47 |
| 5| 1243 | 29.94 | 12.03 | 0.53 |
| 10| 1755 | 34.59 | 16.63 | 0.63 |
| 41| 6689 | 99.53 | 55.37 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.47 | 8.46 | 0.46 |
| 2| 862 | 29.89 | 9.82 | 0.50 |
| 3| 1019 | 31.61 | 10.96 | 0.53 |
| 5| 1333 | 35.64 | 13.44 | 0.59 |
| 10| 2005 | 47.06 | 19.93 | 0.76 |
| 35| 6043 | 98.25 | 51.08 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.79 | 10.15 | 0.53 |
| 2| 815 | 35.85 | 11.38 | 0.56 |
| 3| 900 | 37.16 | 12.39 | 0.58 |
| 5| 1285 | 42.53 | 15.25 | 0.66 |
| 10| 2210 | 56.48 | 22.54 | 0.87 |
| 29| 4904 | 98.29 | 46.78 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 26.96 | 9.06 | 0.69 |
| 2| 6003 | 37.01 | 12.46 | 0.80 |
| 3| 6146 | 45.79 | 15.44 | 0.90 |
| 4| 6170 | 50.41 | 16.87 | 0.95 |
| 5| 6446 | 63.15 | 21.34 | 1.10 |
| 6| 6462 | 66.28 | 22.24 | 1.13 |
| 7| 6799 | 85.25 | 28.75 | 1.35 |
| 8| 6836 | 90.19 | 30.37 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

