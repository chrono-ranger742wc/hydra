--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-16 05:05:52.032560404 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.84 | 4.71 | 0.58 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.92 | 12.57 | 0.63 |
| 4 | 226 | 862 | 53.63 | 15.27 | 0.73 |
| 5 | 283 | 969 | 61.26 | 17.48 | 0.81 |
| 6 | 338 | 1085 | 66.64 | 19.27 | 0.88 |
| 7 | 393 | 1196 | 83.94 | 23.68 | 1.05 |
| 8 | 451 | 1307 | 96.14 | 27.09 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1983 | 26.55 | 9.00 | 0.52 |
| 3| 2105 | 27.86 | 10.03 | 0.54 |
| 5| 2330 | 30.26 | 12.02 | 0.58 |
| 10| 3256 | 42.05 | 18.67 | 0.77 |
| 37| 7249 | 94.54 | 51.25 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.37 | 0.42 |
| 2| 750 | 23.66 | 8.26 | 0.43 |
| 3| 861 | 24.07 | 9.03 | 0.45 |
| 5| 1141 | 28.14 | 11.50 | 0.51 |
| 10| 2165 | 44.83 | 19.48 | 0.75 |
| 42| 6738 | 99.08 | 55.91 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 830 | 29.26 | 9.62 | 0.49 |
| 3| 959 | 30.82 | 10.73 | 0.52 |
| 5| 1228 | 34.37 | 13.04 | 0.58 |
| 10| 1999 | 44.30 | 19.18 | 0.73 |
| 35| 5783 | 95.05 | 50.12 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 942 | 37.80 | 12.59 | 0.59 |
| 5| 1332 | 43.40 | 15.50 | 0.67 |
| 10| 1927 | 52.82 | 21.42 | 0.82 |
| 30| 4985 | 99.33 | 47.72 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5870 | 34.92 | 11.69 | 0.77 |
| 3| 6024 | 41.48 | 13.89 | 0.85 |
| 4| 6321 | 55.95 | 18.86 | 1.02 |
| 5| 6320 | 59.00 | 19.76 | 1.05 |
| 6| 6512 | 70.92 | 23.90 | 1.18 |
| 7| 6921 | 86.14 | 29.12 | 1.36 |
| 8| 6933 | 91.18 | 30.77 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2163 | 7125 | 95.74 | 36.69 | 1.50 |

