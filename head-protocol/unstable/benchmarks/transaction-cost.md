--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-12 05:44:41.454691336 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.35 | 9.42 | 0.51 |
| 3 | 169 | 747 | 42.48 | 12.24 | 0.61 |
| 4 | 228 | 858 | 48.04 | 13.92 | 0.68 |
| 5 | 281 | 969 | 56.13 | 16.31 | 0.76 |
| 6 | 339 | 1081 | 65.53 | 18.88 | 0.86 |
| 7 | 395 | 1192 | 80.31 | 22.82 | 1.02 |
| 8 | 449 | 1303 | 88.47 | 25.36 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 23.92 | 7.60 | 0.48 |
| 2| 1946 | 25.51 | 8.70 | 0.50 |
| 3| 2074 | 26.98 | 9.78 | 0.53 |
| 5| 2404 | 32.07 | 12.54 | 0.61 |
| 10| 3019 | 38.59 | 17.69 | 0.72 |
| 40| 7465 | 94.64 | 53.27 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.57 | 7.30 | 0.41 |
| 2| 784 | 24.25 | 8.44 | 0.44 |
| 3| 874 | 25.13 | 9.34 | 0.46 |
| 5| 1308 | 30.19 | 12.08 | 0.54 |
| 10| 2149 | 42.17 | 18.78 | 0.72 |
| 41| 6521 | 96.96 | 54.70 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 785 | 30.87 | 10.05 | 0.51 |
| 3| 928 | 32.75 | 11.24 | 0.54 |
| 5| 1344 | 35.68 | 13.45 | 0.59 |
| 10| 2016 | 47.48 | 20.05 | 0.77 |
| 35| 5924 | 97.06 | 50.71 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 823 | 35.92 | 11.40 | 0.56 |
| 3| 1010 | 38.55 | 12.81 | 0.60 |
| 5| 1245 | 42.61 | 15.27 | 0.66 |
| 10| 1901 | 52.53 | 21.35 | 0.81 |
| 29| 4800 | 96.84 | 46.34 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.13 | 9.09 | 0.69 |
| 2| 6016 | 37.04 | 12.51 | 0.80 |
| 3| 6026 | 43.87 | 14.73 | 0.88 |
| 4| 6305 | 55.05 | 18.51 | 1.01 |
| 5| 6359 | 63.23 | 21.24 | 1.09 |
| 6| 6488 | 69.64 | 23.33 | 1.17 |
| 7| 6698 | 79.35 | 26.67 | 1.28 |
| 8| 7023 | 95.02 | 32.16 | 1.46 |
| 9| 6945 | 96.40 | 32.47 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2222 | 7161 | 98.68 | 37.80 | 1.54 |

