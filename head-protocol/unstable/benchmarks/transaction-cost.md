--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-08 11:34:49.524163027 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 751 | 43.99 | 12.61 | 0.63 |
| 4 | 224 | 862 | 50.69 | 14.56 | 0.70 |
| 5 | 282 | 969 | 62.74 | 17.92 | 0.83 |
| 6 | 342 | 1085 | 72.58 | 20.61 | 0.93 |
| 7 | 394 | 1192 | 84.06 | 23.75 | 1.05 |
| 8 | 450 | 1303 | 92.80 | 26.45 | 1.15 |
| 9 | 504 | 1414 | 96.12 | 27.48 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.88 | 8.79 | 0.51 |
| 3| 2021 | 25.98 | 9.50 | 0.52 |
| 5| 2420 | 32.03 | 12.53 | 0.61 |
| 10| 3046 | 38.56 | 17.68 | 0.72 |
| 38| 7491 | 99.30 | 53.25 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.81 | 7.37 | 0.42 |
| 2| 699 | 22.62 | 7.97 | 0.42 |
| 3| 970 | 26.92 | 9.85 | 0.48 |
| 5| 1355 | 32.39 | 12.70 | 0.56 |
| 10| 1935 | 39.51 | 18.04 | 0.68 |
| 41| 6669 | 97.35 | 54.78 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.46 | 8.69 | 0.47 |
| 2| 800 | 30.94 | 10.07 | 0.51 |
| 3| 872 | 32.08 | 11.03 | 0.53 |
| 5| 1135 | 35.67 | 13.36 | 0.58 |
| 10| 2215 | 50.48 | 20.96 | 0.81 |
| 38| 6068 | 98.10 | 52.93 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 901 | 36.56 | 11.60 | 0.57 |
| 3| 987 | 38.66 | 12.84 | 0.60 |
| 5| 1330 | 43.32 | 15.48 | 0.67 |
| 10| 2094 | 55.11 | 22.13 | 0.85 |
| 29| 4891 | 99.47 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5844 | 27.05 | 9.08 | 0.69 |
| 2| 5920 | 34.76 | 11.63 | 0.78 |
| 3| 5922 | 37.08 | 12.31 | 0.80 |
| 4| 6314 | 55.19 | 18.69 | 1.01 |
| 5| 6480 | 65.24 | 22.05 | 1.12 |
| 6| 6720 | 74.55 | 25.22 | 1.23 |
| 7| 6720 | 79.90 | 26.85 | 1.28 |
| 8| 7055 | 96.90 | 32.82 | 1.48 |
| 9| 6935 | 94.93 | 31.87 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.05 | 37.58 | 1.53 |

