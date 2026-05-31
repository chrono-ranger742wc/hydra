--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-31 08:24:08.764869415 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6638 | 19.17 | 6.07 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 747 | 42.68 | 12.31 | 0.62 |
| 4 | 226 | 858 | 54.04 | 15.41 | 0.74 |
| 5 | 281 | 969 | 56.75 | 16.55 | 0.77 |
| 6 | 338 | 1081 | 73.99 | 21.03 | 0.95 |
| 7 | 394 | 1192 | 82.01 | 23.30 | 1.03 |
| 8 | 450 | 1303 | 89.56 | 25.46 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.29 | 7.69 | 0.48 |
| 2| 1994 | 26.96 | 9.10 | 0.52 |
| 3| 2111 | 27.94 | 10.05 | 0.54 |
| 5| 2363 | 30.83 | 12.18 | 0.59 |
| 10| 3035 | 38.47 | 17.66 | 0.72 |
| 40| 7761 | 99.18 | 54.54 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.84 | 7.39 | 0.41 |
| 2| 850 | 25.49 | 8.79 | 0.46 |
| 3| 946 | 26.90 | 9.86 | 0.48 |
| 5| 1321 | 33.63 | 13.03 | 0.57 |
| 10| 1888 | 38.47 | 17.74 | 0.67 |
| 41| 6578 | 98.08 | 54.98 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.54 | 8.47 | 0.46 |
| 2| 895 | 29.90 | 9.82 | 0.50 |
| 3| 1026 | 31.87 | 11.04 | 0.53 |
| 5| 1218 | 37.06 | 13.79 | 0.60 |
| 10| 2099 | 47.77 | 20.16 | 0.77 |
| 35| 5870 | 94.86 | 50.09 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.92 | 11.40 | 0.56 |
| 3| 947 | 37.91 | 12.62 | 0.59 |
| 5| 1348 | 43.31 | 15.48 | 0.67 |
| 10| 2024 | 54.17 | 21.84 | 0.83 |
| 29| 5010 | 99.44 | 47.18 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.08 | 9.09 | 0.69 |
| 2| 5947 | 35.92 | 12.07 | 0.79 |
| 3| 6159 | 45.70 | 15.47 | 0.90 |
| 4| 6340 | 56.31 | 19.00 | 1.02 |
| 5| 6278 | 57.65 | 19.39 | 1.03 |
| 6| 6531 | 71.07 | 23.95 | 1.18 |
| 7| 6709 | 81.28 | 27.35 | 1.30 |
| 8| 6745 | 90.70 | 30.43 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2221 | 7161 | 98.68 | 37.80 | 1.54 |

