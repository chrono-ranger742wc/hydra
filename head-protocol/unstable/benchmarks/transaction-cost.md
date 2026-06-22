--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-22 10:19:51.853463664 UTC |
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
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.83 | 12.57 | 0.63 |
| 4 | 226 | 858 | 49.73 | 14.35 | 0.69 |
| 5 | 281 | 969 | 60.70 | 17.37 | 0.81 |
| 6 | 339 | 1085 | 73.58 | 20.92 | 0.94 |
| 7 | 393 | 1192 | 72.54 | 21.12 | 0.94 |
| 8 | 449 | 1303 | 96.82 | 27.26 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1994 | 27.00 | 9.10 | 0.52 |
| 3| 2059 | 27.39 | 9.88 | 0.53 |
| 5| 2327 | 29.96 | 11.95 | 0.58 |
| 10| 3179 | 42.11 | 18.66 | 0.76 |
| 39| 7582 | 97.94 | 53.54 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 978 | 28.35 | 10.23 | 0.50 |
| 5| 1253 | 29.59 | 11.94 | 0.53 |
| 10| 1880 | 37.35 | 17.43 | 0.66 |
| 41| 6737 | 99.57 | 55.43 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 910 | 29.90 | 9.82 | 0.50 |
| 3| 1005 | 31.57 | 10.95 | 0.53 |
| 5| 1190 | 36.38 | 13.58 | 0.59 |
| 10| 1907 | 43.37 | 18.91 | 0.72 |
| 36| 5804 | 95.00 | 50.72 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 812 | 35.92 | 11.40 | 0.56 |
| 3| 1008 | 38.51 | 12.80 | 0.60 |
| 5| 1246 | 42.61 | 15.27 | 0.66 |
| 10| 1917 | 52.44 | 21.33 | 0.81 |
| 29| 4853 | 98.08 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.13 | 9.12 | 0.69 |
| 2| 5901 | 34.91 | 11.68 | 0.78 |
| 3| 6156 | 46.97 | 15.87 | 0.92 |
| 4| 6226 | 51.37 | 17.27 | 0.96 |
| 5| 6392 | 60.50 | 20.32 | 1.07 |
| 6| 6554 | 74.43 | 25.15 | 1.22 |
| 7| 6888 | 85.42 | 28.99 | 1.35 |
| 8| 6855 | 88.80 | 29.88 | 1.38 |
| 9| 6778 | 91.52 | 30.72 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

