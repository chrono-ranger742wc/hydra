--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-20 08:23:46.454297616 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 41.28 | 11.92 | 0.60 |
| 4 | 226 | 858 | 48.18 | 14.01 | 0.68 |
| 5 | 284 | 969 | 63.05 | 17.97 | 0.83 |
| 6 | 338 | 1081 | 68.89 | 19.85 | 0.90 |
| 7 | 395 | 1192 | 76.59 | 21.97 | 0.98 |
| 8 | 450 | 1303 | 91.48 | 26.02 | 1.13 |
| 9 | 505 | 1414 | 98.89 | 28.15 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1921 | 25.55 | 8.71 | 0.50 |
| 3| 2092 | 27.28 | 9.85 | 0.53 |
| 5| 2383 | 31.13 | 12.27 | 0.60 |
| 10| 3124 | 40.56 | 18.24 | 0.75 |
| 38| 7280 | 93.84 | 51.70 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.53 | 7.30 | 0.41 |
| 2| 781 | 23.63 | 8.24 | 0.44 |
| 3| 948 | 26.95 | 9.86 | 0.48 |
| 5| 1231 | 29.55 | 11.93 | 0.53 |
| 10| 2070 | 41.71 | 18.64 | 0.71 |
| 40| 6292 | 92.39 | 52.75 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 949 | 30.82 | 10.73 | 0.52 |
| 5| 1325 | 35.65 | 13.44 | 0.59 |
| 10| 1922 | 43.65 | 19.00 | 0.72 |
| 37| 6088 | 98.11 | 52.32 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1204 | 41.97 | 15.07 | 0.65 |
| 10| 1972 | 53.42 | 21.61 | 0.82 |
| 29| 4909 | 97.67 | 46.61 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 26.92 | 9.04 | 0.69 |
| 2| 6007 | 36.89 | 12.45 | 0.80 |
| 3| 6039 | 41.28 | 13.83 | 0.85 |
| 4| 6284 | 52.53 | 17.70 | 0.98 |
| 5| 6373 | 63.02 | 21.18 | 1.09 |
| 6| 6559 | 74.00 | 24.91 | 1.22 |
| 7| 6655 | 75.88 | 25.50 | 1.24 |
| 8| 7022 | 94.27 | 31.91 | 1.45 |
| 9| 7075 | 99.94 | 33.72 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.42 | 5.80 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

