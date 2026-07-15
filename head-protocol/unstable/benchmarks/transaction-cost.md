--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-15 06:45:55.886177752 UTC |
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
| 2| 6037 | 12.75 | 4.04 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 29.30 | 9.24 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1266 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.51 | 12.00 | 0.61 |
| 4 | 226 | 858 | 50.74 | 14.57 | 0.70 |
| 5 | 281 | 969 | 62.67 | 17.85 | 0.83 |
| 6 | 339 | 1081 | 65.63 | 18.91 | 0.86 |
| 7 | 395 | 1192 | 80.65 | 22.98 | 1.02 |
| 8 | 451 | 1303 | 93.82 | 26.48 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1953 | 25.76 | 8.76 | 0.51 |
| 3| 2070 | 27.31 | 9.86 | 0.53 |
| 5| 2322 | 30.22 | 12.01 | 0.58 |
| 10| 3149 | 40.47 | 18.22 | 0.75 |
| 40| 7717 | 99.77 | 54.67 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.57 | 7.30 | 0.41 |
| 2| 718 | 22.60 | 7.95 | 0.42 |
| 3| 857 | 23.99 | 9.01 | 0.45 |
| 5| 1182 | 27.97 | 11.46 | 0.51 |
| 10| 1879 | 38.17 | 17.66 | 0.67 |
| 42| 6579 | 96.63 | 55.24 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 914 | 32.79 | 11.25 | 0.54 |
| 5| 1314 | 35.61 | 13.43 | 0.59 |
| 10| 2087 | 47.84 | 20.18 | 0.77 |
| 35| 5729 | 93.56 | 49.69 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.81 | 11.37 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1273 | 42.68 | 15.29 | 0.66 |
| 10| 2078 | 54.76 | 22.02 | 0.84 |
| 30| 5061 | 99.84 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5847 | 26.92 | 9.05 | 0.69 |
| 2| 5999 | 36.80 | 12.41 | 0.80 |
| 3| 6118 | 45.77 | 15.43 | 0.90 |
| 4| 6147 | 47.90 | 16.02 | 0.92 |
| 5| 6318 | 59.24 | 19.87 | 1.05 |
| 6| 6549 | 72.88 | 24.49 | 1.20 |
| 7| 6747 | 82.48 | 27.76 | 1.31 |
| 8| 6831 | 92.48 | 31.13 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 19.45 | 6.61 | 0.61 |
| 10 | 10 | 566 | 6171 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1706 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 37 | 2108 | 7093 | 94.39 | 36.12 | 1.49 |

