--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-03 07:58:16.193467197 UTC |
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
| 1| 5840 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.44 | 12.22 | 0.61 |
| 4 | 228 | 862 | 49.73 | 14.36 | 0.69 |
| 5 | 284 | 969 | 63.30 | 18.06 | 0.83 |
| 6 | 338 | 1081 | 67.62 | 19.42 | 0.88 |
| 7 | 395 | 1192 | 76.75 | 22.09 | 0.98 |
| 8 | 450 | 1303 | 99.35 | 27.96 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.88 | 8.79 | 0.51 |
| 3| 2069 | 27.39 | 9.88 | 0.53 |
| 5| 2474 | 33.52 | 12.93 | 0.62 |
| 10| 3217 | 41.74 | 18.57 | 0.76 |
| 39| 7378 | 95.25 | 52.78 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.80 | 7.37 | 0.42 |
| 2| 707 | 22.58 | 7.96 | 0.42 |
| 3| 988 | 26.64 | 9.79 | 0.48 |
| 5| 1200 | 29.81 | 12.01 | 0.53 |
| 10| 2010 | 38.88 | 17.87 | 0.68 |
| 39| 6440 | 98.45 | 53.75 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 29.09 | 8.89 | 0.48 |
| 2| 794 | 30.98 | 10.08 | 0.51 |
| 3| 1032 | 31.61 | 10.96 | 0.53 |
| 5| 1306 | 37.98 | 14.07 | 0.62 |
| 10| 1975 | 47.21 | 19.97 | 0.76 |
| 35| 5823 | 96.97 | 50.69 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 808 | 35.89 | 11.39 | 0.56 |
| 3| 1029 | 38.55 | 12.81 | 0.60 |
| 5| 1246 | 42.61 | 15.27 | 0.66 |
| 10| 2120 | 55.40 | 22.22 | 0.85 |
| 29| 4819 | 97.81 | 46.60 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.00 | 9.06 | 0.69 |
| 2| 5944 | 35.93 | 12.06 | 0.79 |
| 3| 6157 | 46.03 | 15.50 | 0.90 |
| 4| 6201 | 52.71 | 17.69 | 0.98 |
| 5| 6457 | 64.84 | 21.96 | 1.12 |
| 6| 6434 | 63.35 | 21.24 | 1.10 |
| 7| 6669 | 83.81 | 28.29 | 1.32 |
| 8| 6777 | 88.52 | 29.79 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

