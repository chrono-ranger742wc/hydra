--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-24 05:46:13.994268081 UTC |
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
| 1| 5836 | 10.93 | 3.49 | 0.52 |
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.84 | 12.56 | 0.63 |
| 4 | 226 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 283 | 969 | 63.76 | 18.07 | 0.84 |
| 6 | 342 | 1081 | 63.87 | 18.48 | 0.85 |
| 7 | 397 | 1192 | 85.33 | 24.19 | 1.07 |
| 8 | 449 | 1303 | 91.94 | 26.04 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.85 | 8.78 | 0.51 |
| 3| 2072 | 27.03 | 9.79 | 0.53 |
| 5| 2449 | 32.44 | 12.63 | 0.61 |
| 10| 3131 | 39.63 | 17.98 | 0.74 |
| 40| 7525 | 96.48 | 53.80 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.57 | 7.31 | 0.41 |
| 2| 701 | 22.62 | 7.95 | 0.42 |
| 3| 910 | 25.83 | 9.54 | 0.47 |
| 5| 1212 | 29.04 | 11.76 | 0.52 |
| 10| 1930 | 37.62 | 17.48 | 0.67 |
| 41| 6556 | 99.27 | 55.27 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.17 | 8.91 | 0.48 |
| 2| 833 | 29.26 | 9.62 | 0.49 |
| 3| 918 | 32.72 | 11.23 | 0.54 |
| 5| 1391 | 38.37 | 14.19 | 0.62 |
| 10| 2128 | 46.77 | 19.93 | 0.77 |
| 36| 6019 | 97.37 | 51.48 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.83 | 10.15 | 0.53 |
| 2| 829 | 35.92 | 11.40 | 0.56 |
| 3| 949 | 37.84 | 12.60 | 0.59 |
| 5| 1273 | 42.64 | 15.28 | 0.66 |
| 10| 2090 | 54.70 | 22.01 | 0.84 |
| 29| 5084 | 99.81 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.08 | 9.08 | 0.69 |
| 2| 5850 | 31.52 | 10.48 | 0.74 |
| 3| 6059 | 45.03 | 15.12 | 0.89 |
| 4| 6175 | 50.29 | 16.86 | 0.95 |
| 5| 6438 | 65.16 | 21.98 | 1.12 |
| 6| 6709 | 75.36 | 25.39 | 1.24 |
| 7| 6820 | 84.89 | 28.72 | 1.34 |
| 8| 6837 | 88.50 | 29.80 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 286 | 6006 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6855 | 79.34 | 30.22 | 1.31 |
| 10 | 38 | 2164 | 7126 | 96.44 | 36.92 | 1.51 |

