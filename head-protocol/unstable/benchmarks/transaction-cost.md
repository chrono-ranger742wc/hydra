--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-30 05:45:32.697361625 UTC |
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
| 1| 5837 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7648 | 29.02 | 9.14 | 0.79 |
| 43| 14283 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 39.85 | 11.58 | 0.59 |
| 4 | 226 | 858 | 48.18 | 14.01 | 0.68 |
| 5 | 281 | 974 | 59.51 | 17.06 | 0.80 |
| 6 | 339 | 1081 | 69.11 | 19.77 | 0.90 |
| 7 | 393 | 1192 | 72.92 | 21.14 | 0.94 |
| 8 | 448 | 1303 | 84.52 | 24.25 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1971 | 26.96 | 9.09 | 0.52 |
| 3| 2014 | 26.36 | 9.59 | 0.52 |
| 5| 2402 | 30.96 | 12.23 | 0.59 |
| 10| 3205 | 41.63 | 18.54 | 0.76 |
| 40| 7604 | 98.11 | 54.27 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.53 | 7.29 | 0.41 |
| 2| 781 | 24.05 | 8.39 | 0.44 |
| 3| 929 | 25.14 | 9.33 | 0.46 |
| 5| 1233 | 30.42 | 12.16 | 0.54 |
| 10| 1884 | 37.37 | 17.43 | 0.66 |
| 43| 6875 | 99.76 | 56.78 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 775 | 28.55 | 9.40 | 0.48 |
| 3| 872 | 32.09 | 11.03 | 0.53 |
| 5| 1322 | 35.71 | 13.45 | 0.59 |
| 10| 2150 | 46.17 | 19.76 | 0.76 |
| 37| 5826 | 95.62 | 51.48 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.79 | 10.15 | 0.53 |
| 2| 891 | 36.64 | 11.62 | 0.57 |
| 3| 899 | 37.20 | 12.40 | 0.58 |
| 5| 1392 | 43.80 | 15.64 | 0.68 |
| 10| 2098 | 54.57 | 21.97 | 0.84 |
| 29| 4795 | 96.07 | 46.13 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 6014 | 36.85 | 12.42 | 0.80 |
| 3| 6066 | 44.53 | 15.00 | 0.89 |
| 4| 6268 | 54.07 | 18.17 | 0.99 |
| 5| 6520 | 64.60 | 21.79 | 1.12 |
| 6| 6541 | 71.76 | 24.13 | 1.19 |
| 7| 6679 | 82.30 | 27.73 | 1.31 |
| 8| 6824 | 89.35 | 29.98 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.76 | 14.88 | 0.86 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

