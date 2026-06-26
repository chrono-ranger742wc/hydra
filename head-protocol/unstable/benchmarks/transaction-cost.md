--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-26 08:23:12.902107174 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6645 | 18.83 | 5.95 | 0.64 |
| 10| 7650 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 228 | 858 | 50.02 | 14.48 | 0.70 |
| 5 | 282 | 969 | 59.10 | 16.96 | 0.79 |
| 6 | 339 | 1081 | 72.85 | 20.64 | 0.94 |
| 7 | 394 | 1192 | 73.12 | 21.23 | 0.95 |
| 8 | 452 | 1303 | 93.88 | 26.55 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1745 | 23.30 | 7.41 | 0.47 |
| 2| 1955 | 25.84 | 8.78 | 0.51 |
| 3| 2073 | 27.35 | 9.87 | 0.53 |
| 5| 2345 | 30.33 | 12.04 | 0.59 |
| 10| 3185 | 40.70 | 18.28 | 0.75 |
| 38| 7151 | 91.36 | 51.03 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.54 | 7.31 | 0.41 |
| 2| 836 | 25.57 | 8.80 | 0.46 |
| 3| 936 | 26.16 | 9.61 | 0.47 |
| 5| 1280 | 30.79 | 12.27 | 0.54 |
| 10| 1975 | 39.38 | 17.99 | 0.69 |
| 39| 6348 | 96.08 | 53.10 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 847 | 29.97 | 9.84 | 0.50 |
| 3| 972 | 30.94 | 10.75 | 0.52 |
| 5| 1321 | 35.69 | 13.45 | 0.59 |
| 10| 1954 | 43.96 | 19.09 | 0.73 |
| 36| 6034 | 97.94 | 51.59 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1354 | 44.11 | 15.72 | 0.68 |
| 10| 1964 | 53.38 | 21.60 | 0.82 |
| 30| 4914 | 99.11 | 47.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.13 | 9.10 | 0.69 |
| 2| 5933 | 36.04 | 12.12 | 0.79 |
| 3| 6073 | 44.76 | 15.03 | 0.89 |
| 4| 6077 | 49.71 | 16.64 | 0.94 |
| 5| 6220 | 55.35 | 18.53 | 1.00 |
| 6| 6573 | 74.28 | 24.96 | 1.22 |
| 7| 6688 | 84.05 | 28.33 | 1.33 |
| 8| 7067 | 95.48 | 32.33 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 283 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1706 | 6852 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

