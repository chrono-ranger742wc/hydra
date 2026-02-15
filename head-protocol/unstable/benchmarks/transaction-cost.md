--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-15 05:54:46.498992168 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 99.11 | 30.98 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 41.13 | 11.88 | 0.60 |
| 4 | 226 | 862 | 50.97 | 14.65 | 0.71 |
| 5 | 282 | 969 | 62.73 | 17.89 | 0.83 |
| 6 | 339 | 1081 | 67.48 | 19.39 | 0.88 |
| 7 | 394 | 1192 | 72.34 | 20.95 | 0.94 |
| 8 | 448 | 1307 | 94.24 | 26.73 | 1.16 |
| 9 | 506 | 1414 | 94.42 | 27.19 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 23.92 | 7.60 | 0.48 |
| 2| 1885 | 24.85 | 8.50 | 0.50 |
| 3| 2187 | 29.42 | 10.45 | 0.56 |
| 5| 2321 | 29.97 | 11.95 | 0.58 |
| 10| 3291 | 42.68 | 18.84 | 0.78 |
| 39| 7498 | 97.21 | 53.32 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 865 | 25.13 | 8.70 | 0.45 |
| 3| 962 | 26.57 | 9.77 | 0.48 |
| 5| 1261 | 29.16 | 11.79 | 0.53 |
| 10| 2084 | 40.97 | 18.43 | 0.71 |
| 43| 6729 | 98.75 | 56.47 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 871 | 29.97 | 9.84 | 0.50 |
| 3| 911 | 32.64 | 11.21 | 0.53 |
| 5| 1225 | 37.10 | 13.80 | 0.60 |
| 10| 1997 | 46.69 | 19.81 | 0.76 |
| 35| 5732 | 94.59 | 49.98 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 963 | 37.84 | 12.60 | 0.59 |
| 5| 1297 | 43.24 | 15.47 | 0.67 |
| 10| 1957 | 53.38 | 21.60 | 0.82 |
| 30| 4934 | 98.69 | 47.52 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5846 | 27.08 | 9.09 | 0.69 |
| 2| 5894 | 34.91 | 11.68 | 0.78 |
| 3| 6167 | 45.33 | 15.30 | 0.90 |
| 4| 6167 | 50.45 | 16.91 | 0.95 |
| 5| 6323 | 59.63 | 20.00 | 1.05 |
| 6| 6451 | 70.77 | 23.75 | 1.18 |
| 7| 6685 | 77.42 | 25.99 | 1.26 |
| 8| 6687 | 82.06 | 27.61 | 1.31 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 567 | 6171 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.22 | 30.52 | 1.32 |
| 10 | 36 | 2050 | 7058 | 91.64 | 35.07 | 1.45 |

