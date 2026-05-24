--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-24 07:43:40.457590744 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6638 | 18.88 | 5.97 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 751 | 42.38 | 12.20 | 0.61 |
| 4 | 226 | 858 | 48.24 | 14.00 | 0.68 |
| 5 | 282 | 969 | 59.33 | 17.10 | 0.80 |
| 6 | 338 | 1081 | 73.56 | 20.88 | 0.94 |
| 7 | 395 | 1192 | 84.73 | 23.92 | 1.06 |
| 8 | 448 | 1303 | 92.49 | 26.27 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 23.92 | 7.60 | 0.48 |
| 2| 1918 | 25.92 | 8.80 | 0.51 |
| 3| 2113 | 28.06 | 10.08 | 0.54 |
| 5| 2405 | 32.20 | 12.57 | 0.61 |
| 10| 3137 | 40.70 | 18.28 | 0.75 |
| 39| 7552 | 97.45 | 53.42 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 820 | 25.53 | 8.79 | 0.46 |
| 3| 1018 | 28.20 | 10.21 | 0.50 |
| 5| 1214 | 28.99 | 11.74 | 0.52 |
| 10| 2029 | 41.77 | 18.66 | 0.71 |
| 41| 6731 | 98.00 | 54.95 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 868 | 29.90 | 9.82 | 0.50 |
| 3| 982 | 33.43 | 11.44 | 0.55 |
| 5| 1221 | 37.05 | 13.78 | 0.60 |
| 10| 1992 | 47.39 | 20.03 | 0.77 |
| 36| 5982 | 97.66 | 51.50 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 832 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1329 | 43.20 | 15.45 | 0.67 |
| 10| 2128 | 54.62 | 21.99 | 0.84 |
| 28| 4942 | 99.49 | 46.53 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.08 | 9.09 | 0.69 |
| 2| 5898 | 34.91 | 11.69 | 0.78 |
| 3| 6047 | 41.44 | 13.89 | 0.85 |
| 4| 6021 | 43.58 | 14.48 | 0.87 |
| 5| 6320 | 62.91 | 21.23 | 1.09 |
| 6| 6542 | 70.61 | 23.78 | 1.18 |
| 7| 6718 | 80.40 | 27.12 | 1.29 |
| 8| 6716 | 85.05 | 28.53 | 1.34 |
| 9| 6807 | 93.87 | 31.52 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 78.71 | 30.00 | 1.30 |
| 10 | 38 | 2162 | 7124 | 97.33 | 37.23 | 1.52 |

