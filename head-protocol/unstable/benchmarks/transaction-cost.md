--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-01 08:47:06.3444367 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 751 | 43.92 | 12.57 | 0.63 |
| 4 | 226 | 858 | 51.00 | 14.66 | 0.71 |
| 5 | 283 | 969 | 56.42 | 16.35 | 0.77 |
| 6 | 338 | 1085 | 63.94 | 18.54 | 0.85 |
| 7 | 396 | 1192 | 85.79 | 24.20 | 1.07 |
| 8 | 449 | 1303 | 96.59 | 27.20 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1928 | 25.76 | 8.76 | 0.51 |
| 3| 2060 | 27.23 | 9.84 | 0.53 |
| 5| 2458 | 32.04 | 12.53 | 0.61 |
| 10| 3155 | 41.16 | 18.39 | 0.75 |
| 41| 7772 | 99.96 | 55.44 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.54 | 7.31 | 0.41 |
| 2| 793 | 23.51 | 8.21 | 0.43 |
| 3| 980 | 26.84 | 9.83 | 0.48 |
| 5| 1261 | 30.72 | 12.25 | 0.54 |
| 10| 2204 | 44.87 | 19.50 | 0.75 |
| 39| 6312 | 93.07 | 52.25 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 878 | 31.66 | 10.29 | 0.52 |
| 3| 1021 | 31.54 | 10.94 | 0.53 |
| 5| 1269 | 35.01 | 13.24 | 0.58 |
| 10| 2062 | 48.26 | 20.29 | 0.78 |
| 35| 5790 | 99.68 | 51.34 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 810 | 35.81 | 11.37 | 0.56 |
| 3| 941 | 37.80 | 12.59 | 0.59 |
| 5| 1313 | 43.25 | 15.47 | 0.67 |
| 10| 2018 | 53.50 | 21.65 | 0.83 |
| 29| 5037 | 99.55 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.16 | 9.13 | 0.69 |
| 2| 5984 | 35.87 | 12.06 | 0.79 |
| 3| 6141 | 46.01 | 15.52 | 0.90 |
| 4| 6321 | 56.05 | 18.90 | 1.02 |
| 5| 6343 | 59.32 | 19.89 | 1.05 |
| 6| 6617 | 73.63 | 24.87 | 1.22 |
| 7| 6846 | 85.82 | 28.98 | 1.35 |
| 8| 6882 | 91.61 | 30.84 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.88 | 14.58 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2158 | 7120 | 96.88 | 37.08 | 1.51 |

