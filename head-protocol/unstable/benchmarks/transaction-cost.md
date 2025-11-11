--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-11 05:29:45.130127976 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6243 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 751 | 42.61 | 12.28 | 0.62 |
| 4 | 226 | 858 | 50.79 | 14.61 | 0.70 |
| 5 | 281 | 969 | 61.35 | 17.56 | 0.82 |
| 6 | 339 | 1081 | 68.67 | 19.79 | 0.90 |
| 7 | 394 | 1192 | 82.96 | 23.58 | 1.04 |
| 8 | 451 | 1303 | 94.28 | 26.64 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.29 | 7.69 | 0.48 |
| 2| 1946 | 25.39 | 8.68 | 0.50 |
| 3| 2143 | 28.10 | 10.09 | 0.54 |
| 5| 2382 | 31.34 | 12.32 | 0.60 |
| 10| 3039 | 38.25 | 17.60 | 0.72 |
| 39| 7591 | 98.08 | 53.57 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 789 | 25.13 | 8.70 | 0.45 |
| 3| 944 | 26.17 | 9.62 | 0.47 |
| 5| 1225 | 28.99 | 11.76 | 0.52 |
| 10| 1973 | 38.92 | 17.86 | 0.68 |
| 42| 6844 | 99.60 | 56.08 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 1015 | 34.11 | 11.65 | 0.55 |
| 5| 1256 | 34.89 | 13.21 | 0.58 |
| 10| 1865 | 42.62 | 18.68 | 0.71 |
| 36| 5939 | 96.65 | 51.25 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 1021 | 38.51 | 12.80 | 0.60 |
| 5| 1308 | 43.31 | 15.48 | 0.67 |
| 10| 2018 | 54.29 | 21.86 | 0.84 |
| 30| 4868 | 98.97 | 47.59 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.13 | 9.09 | 0.69 |
| 2| 5884 | 32.45 | 10.84 | 0.75 |
| 3| 6099 | 45.06 | 15.14 | 0.89 |
| 4| 6324 | 55.91 | 18.87 | 1.02 |
| 5| 6343 | 60.21 | 20.27 | 1.06 |
| 6| 6602 | 74.45 | 25.20 | 1.22 |
| 7| 6726 | 84.01 | 28.30 | 1.33 |
| 8| 6976 | 93.02 | 31.42 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 56 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

