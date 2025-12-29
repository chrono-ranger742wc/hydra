--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-29 06:00:07.277921168 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 751 | 41.38 | 11.97 | 0.60 |
| 4 | 227 | 862 | 51.11 | 14.71 | 0.71 |
| 5 | 283 | 969 | 57.71 | 16.63 | 0.78 |
| 6 | 338 | 1081 | 71.44 | 20.34 | 0.92 |
| 7 | 393 | 1196 | 74.62 | 21.54 | 0.96 |
| 8 | 450 | 1303 | 87.95 | 25.23 | 1.10 |
| 9 | 505 | 1414 | 98.46 | 27.99 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.29 | 7.69 | 0.48 |
| 2| 1949 | 25.39 | 8.68 | 0.50 |
| 3| 2164 | 29.47 | 10.46 | 0.56 |
| 5| 2423 | 32.41 | 12.62 | 0.61 |
| 10| 3104 | 40.90 | 18.33 | 0.75 |
| 41| 7619 | 98.35 | 54.93 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 22.57 | 7.32 | 0.41 |
| 2| 811 | 25.49 | 8.78 | 0.46 |
| 3| 835 | 24.13 | 9.06 | 0.45 |
| 5| 1249 | 30.10 | 12.07 | 0.54 |
| 10| 2053 | 41.11 | 18.49 | 0.71 |
| 41| 6755 | 99.85 | 55.52 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 844 | 31.66 | 10.29 | 0.52 |
| 3| 973 | 30.94 | 10.75 | 0.52 |
| 5| 1276 | 35.08 | 13.26 | 0.59 |
| 10| 1977 | 47.29 | 20.00 | 0.76 |
| 35| 6030 | 97.05 | 50.73 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.92 | 11.40 | 0.56 |
| 3| 1007 | 38.58 | 12.82 | 0.60 |
| 5| 1234 | 41.97 | 15.07 | 0.65 |
| 10| 1938 | 52.64 | 21.38 | 0.81 |
| 29| 4926 | 99.04 | 46.99 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 26.96 | 9.06 | 0.69 |
| 2| 5974 | 35.83 | 12.05 | 0.79 |
| 3| 6163 | 45.93 | 15.47 | 0.90 |
| 4| 6096 | 49.66 | 16.58 | 0.94 |
| 5| 6370 | 63.74 | 21.47 | 1.10 |
| 6| 6447 | 68.58 | 22.98 | 1.15 |
| 7| 6751 | 83.56 | 28.14 | 1.33 |
| 8| 6892 | 93.34 | 31.49 | 1.43 |
| 9| 6923 | 96.52 | 32.41 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 565 | 6169 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2221 | 7160 | 99.56 | 38.10 | 1.54 |

