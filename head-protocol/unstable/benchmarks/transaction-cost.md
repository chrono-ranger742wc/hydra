--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-28 05:35:40.710821836 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.26 | 6.10 | 0.64 |
| 10| 7647 | 29.38 | 9.27 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.31 | 11.96 | 0.60 |
| 4 | 227 | 858 | 51.00 | 14.64 | 0.71 |
| 5 | 283 | 969 | 62.84 | 17.92 | 0.83 |
| 6 | 337 | 1081 | 66.07 | 19.05 | 0.87 |
| 7 | 396 | 1192 | 76.20 | 21.83 | 0.98 |
| 8 | 450 | 1303 | 98.47 | 27.60 | 1.20 |
| 9 | 506 | 1414 | 93.66 | 26.90 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1964 | 26.79 | 9.05 | 0.52 |
| 3| 2059 | 27.10 | 9.81 | 0.53 |
| 5| 2394 | 31.15 | 12.28 | 0.60 |
| 10| 3073 | 39.86 | 18.03 | 0.74 |
| 40| 7521 | 96.50 | 53.76 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.80 | 7.37 | 0.42 |
| 2| 817 | 25.13 | 8.69 | 0.45 |
| 3| 861 | 24.11 | 9.04 | 0.45 |
| 5| 1242 | 31.29 | 12.39 | 0.55 |
| 10| 1883 | 37.61 | 17.49 | 0.66 |
| 39| 6386 | 98.87 | 53.80 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.09 | 8.89 | 0.48 |
| 2| 737 | 30.23 | 9.85 | 0.50 |
| 3| 868 | 31.97 | 11.00 | 0.53 |
| 5| 1221 | 34.29 | 13.02 | 0.57 |
| 10| 1971 | 46.62 | 19.80 | 0.76 |
| 36| 6056 | 99.22 | 51.97 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 842 | 35.85 | 11.38 | 0.56 |
| 3| 999 | 38.51 | 12.80 | 0.60 |
| 5| 1260 | 42.57 | 15.26 | 0.66 |
| 10| 1992 | 53.42 | 21.61 | 0.83 |
| 29| 4826 | 97.91 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5975 | 35.75 | 12.01 | 0.79 |
| 3| 6141 | 46.17 | 15.55 | 0.91 |
| 4| 6147 | 49.89 | 16.74 | 0.94 |
| 5| 6368 | 61.82 | 20.75 | 1.08 |
| 6| 6533 | 69.83 | 23.57 | 1.17 |
| 7| 6675 | 78.17 | 26.23 | 1.26 |
| 8| 6766 | 84.59 | 28.43 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 568 | 6173 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6856 | 81.99 | 31.13 | 1.34 |
| 10 | 38 | 2162 | 7124 | 97.33 | 37.23 | 1.52 |

