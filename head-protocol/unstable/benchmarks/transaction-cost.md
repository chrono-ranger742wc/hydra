--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-16 09:22:12.952714398 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.25 | 12.15 | 0.61 |
| 4 | 227 | 858 | 54.07 | 15.42 | 0.74 |
| 5 | 282 | 974 | 62.30 | 17.72 | 0.82 |
| 6 | 338 | 1081 | 68.10 | 19.58 | 0.89 |
| 7 | 394 | 1192 | 73.90 | 21.36 | 0.95 |
| 8 | 450 | 1303 | 80.05 | 23.19 | 1.02 |
| 9 | 505 | 1418 | 93.83 | 26.94 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.85 | 8.78 | 0.51 |
| 3| 2059 | 26.94 | 9.77 | 0.53 |
| 5| 2333 | 30.45 | 12.07 | 0.59 |
| 10| 3259 | 42.40 | 18.75 | 0.77 |
| 40| 7595 | 97.83 | 54.13 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.84 | 7.37 | 0.41 |
| 2| 752 | 24.35 | 8.47 | 0.44 |
| 3| 831 | 24.02 | 9.02 | 0.45 |
| 5| 1164 | 28.58 | 11.65 | 0.52 |
| 10| 1981 | 38.70 | 17.79 | 0.68 |
| 41| 6514 | 94.95 | 54.11 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 855 | 31.65 | 10.28 | 0.52 |
| 3| 940 | 32.64 | 11.21 | 0.54 |
| 5| 1232 | 34.33 | 13.03 | 0.58 |
| 10| 2125 | 45.64 | 19.59 | 0.75 |
| 35| 6147 | 99.05 | 51.33 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1263 | 42.53 | 15.25 | 0.66 |
| 10| 2072 | 54.70 | 22.01 | 0.84 |
| 28| 4947 | 99.26 | 46.49 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.12 | 9.10 | 0.69 |
| 2| 5973 | 35.91 | 12.05 | 0.79 |
| 3| 6063 | 44.93 | 15.09 | 0.89 |
| 4| 6267 | 54.69 | 18.46 | 1.00 |
| 5| 6472 | 65.34 | 21.97 | 1.12 |
| 6| 6551 | 69.44 | 23.36 | 1.17 |
| 7| 6829 | 85.17 | 28.82 | 1.35 |
| 8| 7062 | 93.39 | 31.62 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

