--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-12 06:11:11.652035931 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6645 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.25 | 11.70 | 0.59 |
| 4 | 226 | 858 | 52.29 | 14.99 | 0.72 |
| 5 | 283 | 969 | 57.79 | 16.68 | 0.78 |
| 6 | 338 | 1081 | 73.44 | 20.86 | 0.94 |
| 7 | 395 | 1196 | 78.96 | 22.58 | 1.00 |
| 8 | 448 | 1307 | 85.86 | 24.68 | 1.08 |
| 9 | 504 | 1414 | 90.16 | 26.29 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1985 | 26.38 | 8.96 | 0.52 |
| 3| 2090 | 27.39 | 9.88 | 0.53 |
| 5| 2413 | 32.00 | 12.52 | 0.61 |
| 10| 3036 | 39.00 | 17.79 | 0.73 |
| 40| 7511 | 96.83 | 53.87 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 777 | 23.98 | 8.37 | 0.44 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1129 | 27.01 | 11.19 | 0.50 |
| 10| 1961 | 39.86 | 18.11 | 0.69 |
| 43| 6834 | 98.45 | 56.42 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 740 | 30.19 | 9.84 | 0.50 |
| 3| 963 | 33.47 | 11.46 | 0.55 |
| 5| 1191 | 36.39 | 13.58 | 0.59 |
| 10| 2191 | 49.58 | 20.69 | 0.80 |
| 36| 6255 | 99.91 | 52.21 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.87 | 10.16 | 0.53 |
| 2| 881 | 36.52 | 11.59 | 0.57 |
| 3| 1021 | 38.62 | 12.83 | 0.60 |
| 5| 1312 | 43.39 | 15.50 | 0.67 |
| 10| 2081 | 54.88 | 22.05 | 0.84 |
| 29| 4800 | 96.23 | 46.19 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 26.97 | 9.05 | 0.69 |
| 2| 5946 | 35.92 | 12.07 | 0.79 |
| 3| 6049 | 41.36 | 13.86 | 0.85 |
| 4| 6258 | 55.01 | 18.54 | 1.00 |
| 5| 6531 | 65.19 | 21.98 | 1.12 |
| 6| 6610 | 73.23 | 24.67 | 1.21 |
| 7| 6386 | 67.07 | 22.38 | 1.13 |
| 8| 6853 | 89.43 | 30.08 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 283 | 6002 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 568 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 30 | 1706 | 6852 | 78.90 | 30.07 | 1.31 |
| 10 | 39 | 2223 | 7162 | 97.61 | 37.43 | 1.52 |

