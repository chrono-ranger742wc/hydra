--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-27 05:35:29.145040973 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 747 | 41.51 | 12.02 | 0.61 |
| 4 | 227 | 858 | 47.88 | 13.89 | 0.67 |
| 5 | 284 | 974 | 62.79 | 17.85 | 0.83 |
| 6 | 339 | 1081 | 73.11 | 20.70 | 0.94 |
| 7 | 392 | 1192 | 74.38 | 21.44 | 0.96 |
| 8 | 449 | 1303 | 80.23 | 23.23 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1937 | 25.47 | 8.69 | 0.50 |
| 3| 2087 | 26.94 | 9.77 | 0.53 |
| 5| 2375 | 30.88 | 12.21 | 0.59 |
| 10| 3018 | 38.70 | 17.71 | 0.72 |
| 38| 7558 | 98.44 | 53.02 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.50 | 7.30 | 0.41 |
| 2| 778 | 23.59 | 8.23 | 0.43 |
| 3| 919 | 25.76 | 9.53 | 0.47 |
| 5| 1237 | 30.13 | 12.06 | 0.54 |
| 10| 1904 | 36.29 | 17.12 | 0.65 |
| 40| 6345 | 94.59 | 53.31 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 854 | 29.97 | 9.84 | 0.50 |
| 3| 868 | 32.08 | 11.03 | 0.53 |
| 5| 1257 | 35.05 | 13.25 | 0.58 |
| 10| 2060 | 48.34 | 20.30 | 0.78 |
| 37| 6058 | 98.19 | 52.33 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 809 | 35.81 | 11.37 | 0.56 |
| 3| 942 | 37.88 | 12.61 | 0.59 |
| 5| 1266 | 42.53 | 15.25 | 0.66 |
| 10| 1959 | 53.49 | 21.63 | 0.82 |
| 28| 4597 | 93.39 | 44.70 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 26.97 | 9.07 | 0.69 |
| 2| 5950 | 35.93 | 12.06 | 0.79 |
| 3| 6071 | 44.80 | 15.09 | 0.89 |
| 4| 6334 | 55.91 | 18.85 | 1.02 |
| 5| 6222 | 54.75 | 18.23 | 1.00 |
| 6| 6439 | 65.76 | 22.02 | 1.12 |
| 7| 6829 | 85.24 | 28.82 | 1.35 |
| 8| 6986 | 94.75 | 31.96 | 1.45 |
| 9| 6856 | 95.61 | 32.26 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

