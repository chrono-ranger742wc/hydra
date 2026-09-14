--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-14 10:10:14.288689857 UTC |
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
| 1| 5841 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6646 | 19.34 | 6.13 | 0.64 |
| 10| 7644 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 40.01 | 11.63 | 0.59 |
| 4 | 226 | 858 | 50.97 | 14.63 | 0.71 |
| 5 | 284 | 969 | 57.72 | 16.66 | 0.78 |
| 6 | 338 | 1085 | 67.74 | 19.41 | 0.89 |
| 7 | 396 | 1192 | 82.34 | 23.34 | 1.04 |
| 8 | 449 | 1303 | 89.64 | 25.58 | 1.12 |
| 9 | 505 | 1414 | 89.23 | 25.89 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 1942 | 25.88 | 8.79 | 0.51 |
| 3| 2078 | 27.02 | 9.79 | 0.53 |
| 5| 2321 | 29.96 | 11.95 | 0.58 |
| 10| 3078 | 40.24 | 18.14 | 0.74 |
| 39| 7579 | 98.50 | 53.68 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.57 | 7.31 | 0.41 |
| 2| 798 | 23.63 | 8.24 | 0.44 |
| 3| 908 | 25.12 | 9.32 | 0.46 |
| 5| 1144 | 28.07 | 11.50 | 0.51 |
| 10| 2026 | 39.10 | 17.90 | 0.68 |
| 42| 6705 | 97.41 | 55.49 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.17 | 8.91 | 0.48 |
| 2| 813 | 29.15 | 9.59 | 0.49 |
| 3| 946 | 32.68 | 11.22 | 0.54 |
| 5| 1238 | 34.26 | 13.02 | 0.58 |
| 10| 1978 | 44.29 | 19.18 | 0.73 |
| 36| 5772 | 95.13 | 50.75 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 802 | 35.81 | 11.37 | 0.56 |
| 3| 965 | 37.91 | 12.62 | 0.59 |
| 5| 1336 | 43.53 | 15.56 | 0.67 |
| 10| 1982 | 53.31 | 21.58 | 0.82 |
| 29| 4947 | 99.13 | 47.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5843 | 27.08 | 9.09 | 0.69 |
| 2| 5921 | 34.91 | 11.68 | 0.78 |
| 3| 6073 | 42.56 | 14.28 | 0.86 |
| 4| 6300 | 54.71 | 18.42 | 1.00 |
| 5| 6416 | 64.51 | 21.67 | 1.11 |
| 6| 6672 | 75.02 | 25.29 | 1.23 |
| 7| 6704 | 79.37 | 26.73 | 1.28 |
| 8| 6922 | 91.30 | 30.84 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7126 | 97.77 | 37.38 | 1.52 |

