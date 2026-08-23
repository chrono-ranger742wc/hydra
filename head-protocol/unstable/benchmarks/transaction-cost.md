--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-23 05:10:20.045537605 UTC |
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
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7651 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 526 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 40.13 | 11.66 | 0.59 |
| 4 | 226 | 858 | 52.40 | 15.00 | 0.72 |
| 5 | 284 | 969 | 56.60 | 16.43 | 0.77 |
| 6 | 338 | 1081 | 67.07 | 19.25 | 0.88 |
| 7 | 396 | 1192 | 80.13 | 22.77 | 1.01 |
| 8 | 450 | 1303 | 87.04 | 24.91 | 1.09 |
| 9 | 506 | 1414 | 89.49 | 26.01 | 1.12 |
| 10 | 561 | 1529 | 97.00 | 28.09 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 24.37 | 7.71 | 0.48 |
| 2| 1970 | 26.38 | 8.96 | 0.51 |
| 3| 2018 | 25.87 | 9.47 | 0.52 |
| 5| 2429 | 32.15 | 12.56 | 0.61 |
| 10| 3057 | 38.59 | 17.69 | 0.72 |
| 39| 7454 | 96.85 | 53.19 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.57 | 7.32 | 0.41 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 959 | 27.00 | 9.87 | 0.48 |
| 5| 1268 | 31.10 | 12.35 | 0.55 |
| 10| 1919 | 38.88 | 17.85 | 0.68 |
| 42| 6782 | 99.71 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 816 | 29.26 | 9.62 | 0.49 |
| 3| 872 | 31.97 | 11.01 | 0.53 |
| 5| 1316 | 35.83 | 13.49 | 0.59 |
| 10| 2048 | 47.89 | 20.19 | 0.77 |
| 36| 6088 | 97.36 | 51.45 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 1024 | 38.55 | 12.81 | 0.60 |
| 5| 1207 | 41.86 | 15.04 | 0.65 |
| 10| 2081 | 54.81 | 22.03 | 0.84 |
| 29| 4793 | 97.14 | 46.45 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.12 | 9.10 | 0.69 |
| 2| 5947 | 35.96 | 12.08 | 0.79 |
| 3| 6024 | 41.45 | 13.86 | 0.85 |
| 4| 6341 | 56.35 | 19.01 | 1.02 |
| 5| 6351 | 60.24 | 20.28 | 1.06 |
| 6| 6651 | 74.41 | 25.16 | 1.23 |
| 7| 6617 | 75.62 | 25.38 | 1.24 |
| 8| 6969 | 93.54 | 31.57 | 1.44 |
| 9| 6942 | 97.62 | 32.87 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

