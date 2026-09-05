--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-05 08:39:02.736487012 UTC |
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
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 19.19 | 6.08 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 40.02 | 11.62 | 0.59 |
| 4 | 225 | 858 | 49.54 | 14.31 | 0.69 |
| 5 | 282 | 969 | 56.17 | 16.29 | 0.76 |
| 6 | 338 | 1081 | 67.60 | 19.42 | 0.88 |
| 7 | 396 | 1192 | 72.85 | 21.12 | 0.94 |
| 8 | 448 | 1303 | 89.09 | 25.40 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2102 | 28.39 | 10.16 | 0.55 |
| 5| 2387 | 30.92 | 12.22 | 0.59 |
| 10| 3289 | 43.14 | 18.95 | 0.78 |
| 41| 7577 | 97.38 | 54.68 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.84 | 7.40 | 0.42 |
| 2| 822 | 25.53 | 8.79 | 0.46 |
| 3| 927 | 26.05 | 9.59 | 0.47 |
| 5| 1188 | 29.07 | 11.76 | 0.52 |
| 10| 1980 | 41.18 | 18.49 | 0.70 |
| 41| 6382 | 93.09 | 53.60 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 781 | 30.98 | 10.08 | 0.51 |
| 3| 965 | 30.87 | 10.74 | 0.52 |
| 5| 1218 | 36.99 | 13.77 | 0.60 |
| 10| 2065 | 48.64 | 20.42 | 0.78 |
| 37| 6027 | 98.23 | 52.32 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 1034 | 38.55 | 12.81 | 0.60 |
| 5| 1161 | 41.26 | 14.85 | 0.64 |
| 10| 2112 | 55.10 | 22.14 | 0.85 |
| 29| 4864 | 96.84 | 46.34 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.08 | 9.09 | 0.69 |
| 2| 5967 | 35.77 | 12.03 | 0.79 |
| 3| 6018 | 43.65 | 14.61 | 0.87 |
| 4| 6386 | 56.11 | 18.93 | 1.02 |
| 5| 6335 | 60.42 | 20.28 | 1.06 |
| 6| 6561 | 73.12 | 24.58 | 1.21 |
| 7| 6808 | 82.85 | 27.99 | 1.32 |
| 8| 6674 | 82.44 | 27.62 | 1.31 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1708 | 6854 | 81.30 | 30.89 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

