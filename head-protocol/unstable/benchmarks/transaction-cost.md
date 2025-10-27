--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-27 05:42:17.223246312 UTC |
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
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.31 | 9.25 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 751 | 43.63 | 12.50 | 0.63 |
| 4 | 228 | 858 | 48.35 | 14.05 | 0.68 |
| 5 | 283 | 969 | 59.80 | 17.22 | 0.80 |
| 6 | 338 | 1081 | 70.81 | 20.14 | 0.92 |
| 7 | 394 | 1192 | 80.47 | 22.90 | 1.02 |
| 8 | 450 | 1303 | 84.50 | 24.20 | 1.06 |
| 10 | 560 | 1529 | 98.80 | 28.72 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.81 | 8.77 | 0.51 |
| 3| 2059 | 27.39 | 9.88 | 0.53 |
| 5| 2370 | 31.57 | 12.38 | 0.60 |
| 10| 3209 | 41.38 | 18.48 | 0.76 |
| 41| 7683 | 98.97 | 55.16 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.77 | 7.36 | 0.42 |
| 2| 848 | 25.37 | 8.75 | 0.46 |
| 3| 905 | 25.55 | 9.48 | 0.46 |
| 5| 1346 | 32.22 | 12.66 | 0.56 |
| 10| 2031 | 39.86 | 18.13 | 0.69 |
| 41| 6743 | 98.98 | 55.26 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 27.47 | 8.46 | 0.46 |
| 2| 786 | 30.94 | 10.07 | 0.51 |
| 3| 975 | 33.47 | 11.45 | 0.55 |
| 5| 1265 | 37.10 | 13.79 | 0.61 |
| 10| 2019 | 47.47 | 20.05 | 0.77 |
| 34| 5672 | 93.48 | 49.01 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.79 | 10.15 | 0.53 |
| 2| 822 | 35.88 | 11.39 | 0.56 |
| 3| 1000 | 38.59 | 12.82 | 0.60 |
| 5| 1271 | 42.53 | 15.25 | 0.66 |
| 10| 2125 | 55.47 | 22.24 | 0.85 |
| 28| 4970 | 99.75 | 46.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.12 | 9.10 | 0.69 |
| 2| 5914 | 35.93 | 12.04 | 0.79 |
| 3| 6053 | 41.32 | 13.84 | 0.85 |
| 4| 6226 | 54.23 | 18.24 | 0.99 |
| 5| 6362 | 63.16 | 21.27 | 1.09 |
| 6| 6544 | 72.98 | 24.56 | 1.20 |
| 7| 6694 | 81.94 | 27.57 | 1.31 |
| 8| 6977 | 93.25 | 31.41 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2216 | 7156 | 98.93 | 37.88 | 1.54 |

