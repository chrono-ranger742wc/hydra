--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-20 08:06:32.035733651 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6240 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 168 | 746 | 40.17 | 11.66 | 0.59 |
| 4 | 225 | 858 | 47.80 | 13.92 | 0.67 |
| 5 | 280 | 969 | 56.02 | 16.25 | 0.76 |
| 6 | 339 | 1081 | 68.06 | 19.60 | 0.89 |
| 7 | 396 | 1192 | 72.93 | 21.14 | 0.94 |
| 8 | 450 | 1303 | 81.16 | 23.51 | 1.03 |
| 9 | 506 | 1414 | 89.90 | 26.11 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2091 | 26.86 | 9.75 | 0.53 |
| 5| 2326 | 30.33 | 12.04 | 0.58 |
| 10| 3283 | 44.30 | 19.27 | 0.79 |
| 41| 7755 | 99.39 | 55.24 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 737 | 24.27 | 8.44 | 0.44 |
| 3| 840 | 24.09 | 9.03 | 0.45 |
| 5| 1247 | 31.06 | 12.34 | 0.55 |
| 10| 2032 | 40.42 | 18.29 | 0.70 |
| 43| 6810 | 99.20 | 56.63 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 817 | 29.18 | 9.60 | 0.49 |
| 3| 949 | 30.98 | 10.76 | 0.52 |
| 5| 1225 | 34.33 | 13.03 | 0.58 |
| 10| 2008 | 48.12 | 20.25 | 0.77 |
| 37| 6101 | 98.66 | 52.48 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 1017 | 38.47 | 12.79 | 0.60 |
| 5| 1335 | 43.32 | 15.48 | 0.67 |
| 10| 2085 | 54.77 | 22.02 | 0.84 |
| 29| 4765 | 97.11 | 46.41 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.09 | 9.09 | 0.69 |
| 2| 5850 | 31.48 | 10.46 | 0.74 |
| 3| 6101 | 44.40 | 14.96 | 0.89 |
| 4| 6191 | 50.28 | 16.89 | 0.95 |
| 5| 6278 | 58.03 | 19.43 | 1.04 |
| 6| 6577 | 74.35 | 25.12 | 1.22 |
| 7| 6627 | 78.97 | 26.52 | 1.27 |
| 8| 6856 | 86.31 | 29.03 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1135 | 6509 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2216 | 7156 | 98.49 | 37.73 | 1.53 |

