--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-23 06:57:22.179987636 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6039 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14283 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 744 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 39.98 | 11.61 | 0.59 |
| 4 | 228 | 858 | 48.00 | 13.91 | 0.68 |
| 5 | 282 | 969 | 56.00 | 16.25 | 0.76 |
| 6 | 339 | 1085 | 72.35 | 20.63 | 0.93 |
| 7 | 394 | 1192 | 78.98 | 22.59 | 1.00 |
| 8 | 449 | 1303 | 98.53 | 27.67 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1929 | 25.76 | 8.76 | 0.51 |
| 3| 2081 | 27.31 | 9.86 | 0.53 |
| 5| 2424 | 32.19 | 12.57 | 0.61 |
| 10| 3102 | 39.93 | 18.05 | 0.74 |
| 40| 7674 | 99.81 | 54.69 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.57 | 7.31 | 0.41 |
| 2| 745 | 24.35 | 8.46 | 0.44 |
| 3| 899 | 25.14 | 9.33 | 0.46 |
| 5| 1166 | 28.15 | 11.50 | 0.51 |
| 10| 1966 | 39.30 | 17.99 | 0.68 |
| 43| 6591 | 96.02 | 55.73 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 968 | 30.94 | 10.75 | 0.52 |
| 5| 1134 | 35.71 | 13.37 | 0.59 |
| 10| 2019 | 47.17 | 19.97 | 0.76 |
| 34| 5890 | 96.15 | 49.81 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 877 | 36.60 | 11.61 | 0.57 |
| 3| 992 | 38.55 | 12.81 | 0.60 |
| 5| 1218 | 41.93 | 15.06 | 0.65 |
| 10| 1942 | 53.34 | 21.59 | 0.82 |
| 29| 4933 | 98.51 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 26.96 | 9.06 | 0.69 |
| 2| 6007 | 37.05 | 12.50 | 0.80 |
| 3| 6024 | 43.75 | 14.65 | 0.87 |
| 4| 6175 | 50.09 | 16.79 | 0.95 |
| 5| 6515 | 66.23 | 22.36 | 1.13 |
| 6| 6571 | 74.77 | 25.21 | 1.23 |
| 7| 6676 | 79.83 | 26.89 | 1.28 |
| 8| 6988 | 91.57 | 30.84 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2165 | 7128 | 97.77 | 37.38 | 1.52 |

