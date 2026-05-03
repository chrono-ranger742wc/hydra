--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-03 06:50:22.011072009 UTC |
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
| 1| 5836 | 10.86 | 3.46 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 41.51 | 12.02 | 0.61 |
| 4 | 226 | 858 | 51.09 | 14.70 | 0.71 |
| 5 | 283 | 969 | 60.53 | 17.30 | 0.81 |
| 6 | 339 | 1081 | 70.13 | 20.06 | 0.91 |
| 7 | 393 | 1192 | 84.23 | 23.83 | 1.06 |
| 8 | 450 | 1303 | 96.89 | 27.37 | 1.19 |
| 9 | 505 | 1414 | 98.62 | 28.08 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 23.92 | 7.60 | 0.48 |
| 2| 1884 | 24.77 | 8.48 | 0.49 |
| 3| 2141 | 28.39 | 10.16 | 0.55 |
| 5| 2396 | 31.52 | 12.37 | 0.60 |
| 10| 3110 | 40.08 | 18.09 | 0.74 |
| 39| 7695 | 97.63 | 53.48 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.37 | 0.42 |
| 2| 799 | 25.48 | 8.77 | 0.45 |
| 3| 853 | 24.03 | 9.02 | 0.45 |
| 5| 1240 | 29.73 | 11.99 | 0.53 |
| 10| 2032 | 39.88 | 18.13 | 0.69 |
| 43| 6811 | 98.84 | 56.52 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.20 | 9.84 | 0.50 |
| 3| 1076 | 32.28 | 11.17 | 0.54 |
| 5| 1249 | 37.10 | 13.80 | 0.60 |
| 10| 1975 | 47.63 | 20.09 | 0.77 |
| 38| 6099 | 98.67 | 53.07 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.15 | 0.53 |
| 2| 845 | 36.52 | 11.59 | 0.57 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1267 | 42.53 | 15.25 | 0.66 |
| 10| 2053 | 54.89 | 22.05 | 0.84 |
| 29| 4789 | 97.46 | 46.55 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 26.97 | 9.05 | 0.69 |
| 2| 5912 | 35.81 | 12.03 | 0.79 |
| 3| 6116 | 44.71 | 15.05 | 0.89 |
| 4| 6080 | 49.59 | 16.58 | 0.94 |
| 5| 6577 | 65.45 | 22.15 | 1.13 |
| 6| 6791 | 76.69 | 26.06 | 1.26 |
| 7| 6834 | 84.72 | 28.57 | 1.34 |
| 8| 6881 | 90.87 | 30.67 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.42 | 10.80 | 0.74 |
| 10 | 10 | 567 | 6171 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2166 | 7128 | 96.44 | 36.92 | 1.51 |

