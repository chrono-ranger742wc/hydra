--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-06 05:33:26.335023786 UTC |
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
| 1| 5836 | 10.26 | 3.25 | 0.51 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.28 | 9.24 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 169 | 747 | 41.07 | 11.87 | 0.60 |
| 4 | 228 | 858 | 48.42 | 14.07 | 0.68 |
| 5 | 283 | 969 | 62.67 | 17.85 | 0.83 |
| 6 | 339 | 1081 | 73.67 | 20.87 | 0.94 |
| 7 | 394 | 1192 | 87.39 | 24.69 | 1.09 |
| 8 | 449 | 1303 | 87.66 | 25.11 | 1.10 |
| 10 | 561 | 1525 | 97.11 | 28.00 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 1954 | 25.39 | 8.68 | 0.50 |
| 3| 2125 | 28.13 | 10.10 | 0.54 |
| 5| 2380 | 30.92 | 12.22 | 0.59 |
| 10| 3068 | 38.55 | 17.68 | 0.72 |
| 42| 7717 | 98.00 | 55.56 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.81 | 7.38 | 0.42 |
| 2| 757 | 24.27 | 8.44 | 0.44 |
| 3| 965 | 26.64 | 9.78 | 0.48 |
| 5| 1180 | 28.16 | 11.51 | 0.51 |
| 10| 1943 | 38.35 | 17.71 | 0.67 |
| 39| 6611 | 97.99 | 53.64 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 841 | 31.66 | 10.29 | 0.52 |
| 3| 923 | 32.68 | 11.22 | 0.54 |
| 5| 1328 | 35.76 | 13.47 | 0.59 |
| 10| 2024 | 48.16 | 20.26 | 0.77 |
| 37| 5994 | 97.46 | 52.09 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 811 | 35.85 | 11.38 | 0.56 |
| 3| 1053 | 39.34 | 13.05 | 0.61 |
| 5| 1157 | 41.26 | 14.85 | 0.64 |
| 10| 1978 | 53.54 | 21.64 | 0.83 |
| 29| 4902 | 98.55 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 27.08 | 9.08 | 0.69 |
| 2| 5920 | 32.64 | 10.90 | 0.75 |
| 3| 6164 | 45.94 | 15.47 | 0.90 |
| 4| 6206 | 51.55 | 17.32 | 0.96 |
| 5| 6314 | 60.39 | 20.28 | 1.06 |
| 6| 6604 | 71.75 | 24.16 | 1.19 |
| 7| 6637 | 80.65 | 27.14 | 1.29 |
| 8| 7029 | 94.48 | 31.97 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1706 | 6852 | 78.71 | 30.00 | 1.30 |
| 10 | 38 | 2163 | 7126 | 95.56 | 36.62 | 1.50 |

