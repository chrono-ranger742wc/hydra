--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-07 06:10:29.520571408 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.97 | 4.75 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 640 | 32.34 | 9.42 | 0.51 |
| 3 | 171 | 747 | 40.25 | 11.70 | 0.59 |
| 4 | 228 | 858 | 52.31 | 14.95 | 0.72 |
| 5 | 283 | 969 | 62.11 | 17.74 | 0.82 |
| 6 | 341 | 1081 | 75.69 | 21.43 | 0.96 |
| 7 | 393 | 1192 | 72.43 | 21.05 | 0.94 |
| 8 | 449 | 1303 | 95.77 | 26.95 | 1.18 |
| 9 | 505 | 1418 | 93.53 | 26.87 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.43 | 8.68 | 0.50 |
| 3| 2054 | 26.90 | 9.76 | 0.53 |
| 5| 2407 | 31.05 | 12.25 | 0.60 |
| 10| 3162 | 40.89 | 18.32 | 0.75 |
| 38| 7223 | 92.91 | 51.47 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 704 | 22.62 | 7.97 | 0.42 |
| 3| 903 | 25.14 | 9.33 | 0.46 |
| 5| 1164 | 28.12 | 11.50 | 0.51 |
| 10| 1910 | 37.68 | 17.50 | 0.66 |
| 39| 6557 | 99.44 | 54.04 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.54 | 8.47 | 0.46 |
| 2| 816 | 29.22 | 9.61 | 0.49 |
| 3| 978 | 33.36 | 11.43 | 0.55 |
| 5| 1400 | 36.38 | 13.66 | 0.60 |
| 10| 1985 | 47.69 | 20.12 | 0.77 |
| 35| 5776 | 99.87 | 51.36 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.15 | 0.53 |
| 2| 836 | 35.89 | 11.39 | 0.56 |
| 3| 900 | 37.13 | 12.38 | 0.58 |
| 5| 1276 | 42.65 | 15.28 | 0.66 |
| 10| 2062 | 54.70 | 22.01 | 0.84 |
| 30| 4982 | 99.66 | 47.82 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.00 | 9.08 | 0.69 |
| 2| 5886 | 32.60 | 10.91 | 0.75 |
| 3| 6140 | 45.60 | 15.40 | 0.90 |
| 4| 6264 | 54.77 | 18.45 | 1.00 |
| 5| 6436 | 62.39 | 21.07 | 1.09 |
| 6| 6395 | 68.96 | 23.15 | 1.16 |
| 7| 6730 | 83.58 | 28.20 | 1.32 |
| 8| 6933 | 91.26 | 30.71 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.56 | 6.54 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 286 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.32 | 14.73 | 0.85 |
| 10 | 20 | 1138 | 6512 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2223 | 7163 | 99.38 | 38.04 | 1.54 |

