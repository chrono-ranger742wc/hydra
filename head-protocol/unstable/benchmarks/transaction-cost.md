--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-06 06:56:29.202427662 UTC |
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
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6646 | 18.91 | 5.98 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 169 | 747 | 42.38 | 12.19 | 0.61 |
| 4 | 226 | 858 | 48.19 | 13.98 | 0.68 |
| 5 | 285 | 969 | 56.41 | 16.35 | 0.77 |
| 6 | 338 | 1081 | 71.77 | 20.42 | 0.92 |
| 7 | 396 | 1196 | 82.00 | 23.21 | 1.03 |
| 8 | 448 | 1303 | 84.47 | 24.24 | 1.06 |
| 9 | 506 | 1414 | 93.96 | 26.97 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2085 | 27.06 | 9.80 | 0.53 |
| 5| 2393 | 31.41 | 12.34 | 0.60 |
| 10| 3195 | 40.90 | 18.33 | 0.75 |
| 40| 7525 | 95.08 | 53.39 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.81 | 7.37 | 0.42 |
| 2| 817 | 25.49 | 8.78 | 0.46 |
| 3| 832 | 24.13 | 9.04 | 0.45 |
| 5| 1241 | 29.00 | 11.75 | 0.52 |
| 10| 1955 | 39.42 | 18.01 | 0.68 |
| 40| 6596 | 98.62 | 54.45 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 816 | 29.26 | 9.62 | 0.49 |
| 3| 961 | 33.36 | 11.43 | 0.54 |
| 5| 1214 | 34.30 | 13.02 | 0.57 |
| 10| 1948 | 43.58 | 18.96 | 0.72 |
| 36| 5775 | 99.96 | 52.04 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 893 | 36.56 | 11.60 | 0.57 |
| 3| 951 | 37.88 | 12.61 | 0.59 |
| 5| 1320 | 43.31 | 15.48 | 0.67 |
| 10| 1933 | 52.67 | 21.38 | 0.82 |
| 29| 4679 | 96.09 | 46.08 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5786 | 27.13 | 9.09 | 0.69 |
| 2| 5894 | 32.60 | 10.89 | 0.75 |
| 3| 6130 | 44.83 | 15.05 | 0.89 |
| 4| 6415 | 55.24 | 18.72 | 1.01 |
| 5| 6362 | 62.93 | 21.15 | 1.09 |
| 6| 6650 | 75.67 | 25.49 | 1.24 |
| 7| 6779 | 82.61 | 27.83 | 1.32 |
| 8| 7082 | 91.73 | 31.01 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

