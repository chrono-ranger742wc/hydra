--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-20 05:10:31.170334117 UTC |
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
| 1| 5840 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 635 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 751 | 39.86 | 11.58 | 0.59 |
| 4 | 227 | 858 | 48.42 | 14.07 | 0.68 |
| 5 | 284 | 974 | 60.85 | 17.38 | 0.81 |
| 6 | 337 | 1081 | 66.07 | 19.05 | 0.87 |
| 7 | 394 | 1192 | 76.12 | 21.85 | 0.98 |
| 8 | 452 | 1303 | 92.23 | 26.21 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 23.92 | 7.60 | 0.48 |
| 2| 1945 | 25.47 | 8.70 | 0.50 |
| 3| 2146 | 28.27 | 10.13 | 0.55 |
| 5| 2322 | 30.49 | 12.08 | 0.59 |
| 10| 3129 | 41.01 | 18.36 | 0.75 |
| 40| 7776 | 99.85 | 54.71 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.84 | 7.38 | 0.41 |
| 2| 812 | 25.48 | 8.78 | 0.46 |
| 3| 948 | 26.97 | 9.86 | 0.48 |
| 5| 1296 | 32.11 | 12.63 | 0.56 |
| 10| 2064 | 40.59 | 18.33 | 0.70 |
| 40| 6602 | 99.75 | 54.80 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.13 | 8.90 | 0.48 |
| 2| 819 | 29.26 | 9.62 | 0.49 |
| 3| 981 | 33.47 | 11.46 | 0.55 |
| 5| 1238 | 34.29 | 13.02 | 0.58 |
| 10| 1790 | 44.74 | 19.21 | 0.73 |
| 35| 6005 | 97.13 | 50.75 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 811 | 35.85 | 11.38 | 0.56 |
| 3| 999 | 38.66 | 12.84 | 0.60 |
| 5| 1208 | 41.89 | 15.05 | 0.65 |
| 10| 2127 | 55.36 | 22.21 | 0.85 |
| 28| 4700 | 95.33 | 45.30 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.08 | 9.08 | 0.69 |
| 2| 5923 | 36.00 | 12.10 | 0.79 |
| 3| 6203 | 47.09 | 15.88 | 0.92 |
| 4| 6163 | 50.64 | 16.97 | 0.95 |
| 5| 6263 | 55.75 | 18.63 | 1.01 |
| 6| 6473 | 69.43 | 23.34 | 1.16 |
| 7| 6775 | 83.53 | 28.10 | 1.33 |
| 8| 6894 | 89.41 | 30.09 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2219 | 7159 | 97.61 | 37.43 | 1.52 |

