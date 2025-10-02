--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-02 04:36:23.686521577 UTC |
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
| 1| 5836 | 10.72 | 3.41 | 0.52 |
| 2| 6039 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 228 | 858 | 49.57 | 14.32 | 0.69 |
| 5 | 284 | 969 | 63.51 | 18.14 | 0.84 |
| 6 | 339 | 1081 | 67.67 | 19.43 | 0.88 |
| 7 | 394 | 1192 | 78.24 | 22.40 | 1.00 |
| 8 | 449 | 1303 | 86.48 | 24.67 | 1.08 |
| 10 | 560 | 1529 | 98.78 | 28.51 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.37 | 7.71 | 0.48 |
| 2| 1940 | 25.47 | 8.70 | 0.50 |
| 3| 2120 | 28.17 | 10.11 | 0.54 |
| 5| 2336 | 30.26 | 12.02 | 0.58 |
| 10| 3319 | 43.24 | 19.00 | 0.78 |
| 40| 7681 | 98.19 | 54.29 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.80 | 7.36 | 0.41 |
| 2| 701 | 22.55 | 7.93 | 0.42 |
| 3| 876 | 25.05 | 9.32 | 0.46 |
| 5| 1262 | 30.57 | 12.21 | 0.54 |
| 10| 1870 | 36.69 | 17.24 | 0.65 |
| 41| 6642 | 98.45 | 55.11 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 775 | 28.47 | 9.38 | 0.48 |
| 3| 960 | 30.90 | 10.74 | 0.52 |
| 5| 1260 | 37.58 | 13.96 | 0.61 |
| 10| 2063 | 45.30 | 19.51 | 0.75 |
| 34| 5800 | 99.61 | 50.73 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 880 | 36.60 | 11.61 | 0.57 |
| 3| 1001 | 38.59 | 12.82 | 0.60 |
| 5| 1296 | 43.36 | 15.49 | 0.67 |
| 10| 1928 | 52.49 | 21.34 | 0.81 |
| 29| 4775 | 96.34 | 46.20 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.07 | 0.69 |
| 2| 5976 | 35.80 | 12.04 | 0.79 |
| 3| 6105 | 44.77 | 15.06 | 0.89 |
| 4| 6174 | 50.07 | 16.79 | 0.95 |
| 5| 6298 | 58.34 | 19.59 | 1.04 |
| 6| 6627 | 70.51 | 23.75 | 1.18 |
| 7| 6780 | 83.86 | 28.26 | 1.33 |
| 8| 6750 | 87.29 | 29.26 | 1.36 |
| 9| 6956 | 94.16 | 31.67 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2222 | 7162 | 99.38 | 38.04 | 1.54 |

