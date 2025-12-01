--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-01 06:02:07.064332228 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10088 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 41.35 | 11.98 | 0.60 |
| 4 | 228 | 858 | 49.53 | 14.31 | 0.69 |
| 5 | 283 | 969 | 64.64 | 18.32 | 0.85 |
| 6 | 342 | 1081 | 73.45 | 20.85 | 0.94 |
| 7 | 395 | 1196 | 72.88 | 21.17 | 0.94 |
| 8 | 450 | 1303 | 87.37 | 24.94 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.29 | 7.69 | 0.48 |
| 2| 1971 | 26.55 | 9.00 | 0.52 |
| 3| 2123 | 28.47 | 10.18 | 0.55 |
| 5| 2399 | 31.34 | 12.32 | 0.60 |
| 10| 3087 | 39.59 | 17.97 | 0.74 |
| 38| 7543 | 97.36 | 52.70 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.54 | 7.30 | 0.41 |
| 2| 775 | 24.00 | 8.40 | 0.44 |
| 3| 853 | 24.11 | 9.04 | 0.45 |
| 5| 1242 | 29.14 | 11.80 | 0.53 |
| 10| 2026 | 38.42 | 17.72 | 0.68 |
| 40| 6477 | 96.83 | 53.99 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 816 | 29.19 | 9.60 | 0.49 |
| 3| 903 | 30.19 | 10.53 | 0.51 |
| 5| 1267 | 35.12 | 13.27 | 0.59 |
| 10| 1971 | 44.26 | 19.17 | 0.73 |
| 35| 5684 | 98.79 | 51.07 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.87 | 10.16 | 0.53 |
| 2| 901 | 36.56 | 11.60 | 0.57 |
| 3| 1001 | 38.59 | 12.82 | 0.60 |
| 5| 1343 | 44.11 | 15.72 | 0.68 |
| 10| 2074 | 55.47 | 22.24 | 0.85 |
| 30| 4989 | 98.82 | 47.57 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.09 | 9.08 | 0.69 |
| 2| 5902 | 34.87 | 11.69 | 0.78 |
| 3| 6159 | 46.92 | 15.89 | 0.91 |
| 4| 6260 | 53.89 | 18.11 | 0.99 |
| 5| 6404 | 61.62 | 20.74 | 1.08 |
| 6| 6617 | 71.96 | 24.28 | 1.20 |
| 7| 6556 | 79.59 | 26.74 | 1.27 |
| 8| 6808 | 89.16 | 29.94 | 1.39 |
| 9| 6843 | 99.91 | 33.60 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 283 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 61.31 | 22.98 | 1.10 |
| 10 | 30 | 1709 | 6855 | 80.16 | 30.50 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

