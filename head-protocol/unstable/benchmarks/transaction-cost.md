--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-25 08:13:57.16906483 UTC |
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
| 1| 5834 | 10.86 | 3.46 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.60 | 12.49 | 0.63 |
| 4 | 228 | 862 | 49.73 | 14.35 | 0.69 |
| 5 | 282 | 969 | 57.87 | 16.73 | 0.78 |
| 6 | 338 | 1081 | 70.13 | 20.10 | 0.91 |
| 7 | 395 | 1196 | 84.67 | 23.94 | 1.06 |
| 8 | 448 | 1303 | 98.41 | 27.59 | 1.20 |
| 10 | 560 | 1529 | 99.84 | 28.84 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.37 | 7.71 | 0.48 |
| 2| 1980 | 26.83 | 9.06 | 0.52 |
| 3| 2091 | 27.27 | 9.85 | 0.53 |
| 5| 2447 | 32.19 | 12.57 | 0.61 |
| 10| 3245 | 42.91 | 18.89 | 0.78 |
| 43| 7840 | 98.74 | 56.40 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.39 | 0.41 |
| 2| 731 | 23.65 | 8.24 | 0.43 |
| 3| 830 | 24.13 | 9.05 | 0.45 |
| 5| 1339 | 32.11 | 12.64 | 0.56 |
| 10| 2063 | 41.24 | 18.49 | 0.71 |
| 41| 6660 | 97.61 | 54.86 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 828 | 29.22 | 9.61 | 0.49 |
| 3| 869 | 32.01 | 11.01 | 0.53 |
| 5| 1218 | 36.94 | 13.75 | 0.60 |
| 10| 2056 | 47.44 | 20.04 | 0.77 |
| 37| 5988 | 96.65 | 51.87 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 970 | 37.91 | 12.62 | 0.59 |
| 5| 1304 | 43.40 | 15.50 | 0.67 |
| 10| 2044 | 54.06 | 21.81 | 0.83 |
| 29| 4929 | 98.97 | 46.99 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5891 | 34.84 | 11.65 | 0.77 |
| 3| 6073 | 44.85 | 15.08 | 0.89 |
| 4| 6170 | 52.68 | 17.70 | 0.97 |
| 5| 6369 | 61.85 | 20.84 | 1.08 |
| 6| 6694 | 75.91 | 25.66 | 1.24 |
| 7| 6767 | 84.61 | 28.56 | 1.34 |
| 8| 6916 | 92.83 | 31.19 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.67 | 10.88 | 0.74 |
| 10 | 20 | 1140 | 6515 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2163 | 7125 | 97.51 | 37.29 | 1.52 |

