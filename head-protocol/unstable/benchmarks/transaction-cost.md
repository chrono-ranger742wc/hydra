--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-19 05:45:56.009211947 UTC |
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
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6646 | 19.17 | 6.07 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10083 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 169 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 225 | 862 | 48.07 | 13.96 | 0.68 |
| 5 | 281 | 969 | 61.83 | 17.64 | 0.82 |
| 6 | 339 | 1081 | 66.29 | 19.22 | 0.87 |
| 7 | 393 | 1192 | 72.82 | 21.15 | 0.94 |
| 8 | 448 | 1303 | 95.79 | 26.91 | 1.18 |
| 10 | 560 | 1525 | 99.65 | 28.67 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 2009 | 26.62 | 9.02 | 0.52 |
| 3| 2015 | 26.24 | 9.56 | 0.52 |
| 5| 2413 | 32.49 | 12.64 | 0.61 |
| 10| 3217 | 41.97 | 18.63 | 0.77 |
| 42| 7731 | 96.07 | 55.02 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 766 | 24.01 | 8.38 | 0.44 |
| 3| 951 | 26.08 | 9.61 | 0.47 |
| 5| 1236 | 29.81 | 12.01 | 0.53 |
| 10| 2104 | 41.76 | 18.66 | 0.71 |
| 40| 6740 | 99.29 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.50 | 8.46 | 0.46 |
| 2| 780 | 30.94 | 10.07 | 0.51 |
| 3| 990 | 33.43 | 11.44 | 0.55 |
| 5| 1304 | 37.85 | 14.02 | 0.61 |
| 10| 2114 | 48.75 | 20.45 | 0.78 |
| 38| 6016 | 98.32 | 52.96 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 981 | 38.59 | 12.82 | 0.60 |
| 5| 1283 | 42.49 | 15.24 | 0.66 |
| 10| 1883 | 52.07 | 21.21 | 0.81 |
| 30| 4882 | 99.62 | 47.77 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.13 | 9.11 | 0.69 |
| 2| 5895 | 34.94 | 11.70 | 0.78 |
| 3| 6022 | 43.98 | 14.71 | 0.88 |
| 4| 6259 | 52.62 | 17.71 | 0.98 |
| 5| 6301 | 61.92 | 20.76 | 1.08 |
| 6| 6692 | 75.84 | 25.64 | 1.24 |
| 7| 6684 | 78.99 | 26.56 | 1.27 |
| 8| 7021 | 95.54 | 32.24 | 1.46 |
| 9| 7030 | 97.86 | 32.98 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6852 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2159 | 7121 | 96.00 | 36.77 | 1.50 |

