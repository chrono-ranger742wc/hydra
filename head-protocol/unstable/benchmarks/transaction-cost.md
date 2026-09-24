--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-24 09:35:19.77046939 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 43.91 | 12.57 | 0.63 |
| 4 | 228 | 858 | 52.32 | 14.97 | 0.72 |
| 5 | 283 | 969 | 57.94 | 16.75 | 0.78 |
| 6 | 340 | 1081 | 67.82 | 19.51 | 0.89 |
| 7 | 395 | 1192 | 72.70 | 21.12 | 0.94 |
| 8 | 450 | 1303 | 85.89 | 24.69 | 1.08 |
| 10 | 560 | 1525 | 96.92 | 28.07 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.77 | 8.48 | 0.49 |
| 3| 2117 | 28.23 | 10.12 | 0.54 |
| 5| 2385 | 31.19 | 12.29 | 0.60 |
| 10| 3167 | 41.39 | 18.47 | 0.76 |
| 40| 7503 | 96.16 | 53.65 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.30 | 0.41 |
| 2| 774 | 24.32 | 8.46 | 0.44 |
| 3| 892 | 25.85 | 9.57 | 0.47 |
| 5| 1273 | 29.99 | 12.03 | 0.54 |
| 10| 2043 | 40.68 | 18.37 | 0.70 |
| 43| 6738 | 99.76 | 56.77 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 877 | 31.62 | 10.27 | 0.52 |
| 3| 1005 | 31.58 | 10.95 | 0.53 |
| 5| 1327 | 35.65 | 13.44 | 0.59 |
| 10| 2077 | 48.01 | 20.22 | 0.78 |
| 34| 5585 | 97.36 | 49.99 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.60 | 11.61 | 0.57 |
| 3| 1052 | 38.88 | 12.91 | 0.60 |
| 5| 1292 | 42.72 | 15.30 | 0.66 |
| 10| 2037 | 54.21 | 21.85 | 0.84 |
| 29| 5026 | 99.66 | 47.22 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.04 | 9.10 | 0.69 |
| 2| 5957 | 35.93 | 12.07 | 0.79 |
| 3| 6113 | 45.65 | 15.40 | 0.90 |
| 4| 6227 | 54.05 | 18.16 | 0.99 |
| 5| 6265 | 58.54 | 19.57 | 1.04 |
| 6| 6473 | 69.53 | 23.38 | 1.17 |
| 7| 6683 | 79.83 | 26.88 | 1.28 |
| 8| 6845 | 90.36 | 30.46 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

