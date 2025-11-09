--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-09 05:32:00.695913003 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 225 | 858 | 47.93 | 13.90 | 0.68 |
| 5 | 284 | 969 | 57.98 | 16.75 | 0.78 |
| 6 | 338 | 1081 | 70.24 | 20.17 | 0.91 |
| 7 | 393 | 1192 | 80.38 | 22.87 | 1.02 |
| 8 | 451 | 1307 | 96.10 | 27.08 | 1.18 |
| 9 | 504 | 1414 | 97.89 | 27.85 | 1.20 |
| 10 | 560 | 1525 | 97.39 | 28.25 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 2015 | 26.47 | 8.98 | 0.52 |
| 3| 2156 | 29.38 | 10.44 | 0.56 |
| 5| 2547 | 34.31 | 13.16 | 0.63 |
| 10| 3061 | 39.73 | 18.00 | 0.74 |
| 41| 7707 | 98.78 | 55.07 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.84 | 7.37 | 0.42 |
| 2| 704 | 22.62 | 7.97 | 0.42 |
| 3| 1016 | 28.29 | 10.22 | 0.50 |
| 5| 1155 | 28.69 | 11.68 | 0.52 |
| 10| 2032 | 42.30 | 18.80 | 0.72 |
| 40| 6517 | 96.70 | 53.93 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 968 | 33.43 | 11.45 | 0.55 |
| 5| 1234 | 34.29 | 13.02 | 0.58 |
| 10| 2008 | 45.13 | 19.42 | 0.74 |
| 35| 5984 | 98.62 | 51.14 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 998 | 38.55 | 12.81 | 0.60 |
| 5| 1225 | 41.86 | 15.04 | 0.65 |
| 10| 1927 | 52.52 | 21.35 | 0.81 |
| 30| 4933 | 99.80 | 47.87 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.92 | 9.04 | 0.69 |
| 2| 5946 | 35.88 | 12.06 | 0.79 |
| 3| 6133 | 45.45 | 15.33 | 0.90 |
| 4| 6303 | 54.79 | 18.46 | 1.00 |
| 5| 6505 | 65.02 | 21.96 | 1.12 |
| 6| 6685 | 76.77 | 26.03 | 1.25 |
| 7| 6759 | 82.91 | 27.99 | 1.32 |
| 8| 6901 | 90.53 | 30.60 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 570 | 6175 | 40.13 | 14.67 | 0.85 |
| 10 | 30 | 1706 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7161 | 98.05 | 37.58 | 1.53 |

