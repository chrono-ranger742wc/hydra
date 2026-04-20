--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-20 06:38:20.200409658 UTC |
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
| 2| 6037 | 13.18 | 4.20 | 0.55 |
| 3| 6238 | 14.78 | 4.68 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 168 | 747 | 43.55 | 12.48 | 0.62 |
| 4 | 227 | 858 | 48.27 | 14.00 | 0.68 |
| 5 | 281 | 969 | 58.43 | 16.87 | 0.79 |
| 6 | 337 | 1081 | 69.72 | 19.96 | 0.90 |
| 7 | 395 | 1192 | 76.39 | 21.92 | 0.98 |
| 8 | 449 | 1303 | 90.44 | 25.88 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 2005 | 26.54 | 9.00 | 0.52 |
| 3| 2210 | 29.01 | 10.35 | 0.56 |
| 5| 2375 | 31.20 | 12.29 | 0.60 |
| 10| 3146 | 40.52 | 18.23 | 0.75 |
| 43| 7886 | 97.90 | 56.19 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.80 | 7.37 | 0.42 |
| 2| 702 | 22.62 | 7.95 | 0.42 |
| 3| 904 | 25.14 | 9.33 | 0.46 |
| 5| 1205 | 30.01 | 12.04 | 0.53 |
| 10| 1961 | 38.31 | 17.69 | 0.67 |
| 40| 6496 | 97.01 | 54.02 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 838 | 29.22 | 9.61 | 0.49 |
| 3| 962 | 33.31 | 11.41 | 0.54 |
| 5| 1257 | 36.91 | 13.75 | 0.60 |
| 10| 1988 | 44.00 | 19.10 | 0.73 |
| 36| 6179 | 99.77 | 52.18 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 33.83 | 10.16 | 0.53 |
| 2| 868 | 36.56 | 11.60 | 0.57 |
| 3| 955 | 37.95 | 12.63 | 0.59 |
| 5| 1256 | 42.57 | 15.26 | 0.66 |
| 10| 2177 | 55.52 | 22.25 | 0.86 |
| 29| 4789 | 97.43 | 46.53 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.09 | 9.10 | 0.69 |
| 2| 5920 | 35.81 | 12.02 | 0.79 |
| 3| 5899 | 37.04 | 12.29 | 0.80 |
| 4| 6208 | 53.69 | 18.06 | 0.99 |
| 5| 6598 | 65.73 | 22.28 | 1.13 |
| 6| 6686 | 75.71 | 25.55 | 1.24 |
| 7| 6612 | 77.80 | 26.04 | 1.26 |
| 8| 6908 | 94.52 | 31.99 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

