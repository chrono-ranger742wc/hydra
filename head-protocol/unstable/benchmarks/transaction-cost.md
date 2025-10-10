--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-10 04:40:26.288994356 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.90 | 5.97 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 41.39 | 11.95 | 0.60 |
| 4 | 226 | 858 | 49.74 | 14.38 | 0.69 |
| 5 | 283 | 969 | 58.25 | 16.85 | 0.79 |
| 6 | 338 | 1081 | 64.62 | 18.74 | 0.86 |
| 7 | 394 | 1192 | 78.89 | 22.56 | 1.00 |
| 8 | 449 | 1303 | 96.76 | 27.29 | 1.19 |
| 9 | 506 | 1414 | 91.36 | 26.35 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2101 | 28.10 | 10.09 | 0.54 |
| 5| 2454 | 32.32 | 12.60 | 0.61 |
| 10| 3162 | 41.63 | 18.54 | 0.76 |
| 41| 7831 | 99.47 | 55.29 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.38 | 0.42 |
| 2| 862 | 25.13 | 8.70 | 0.45 |
| 3| 923 | 26.67 | 9.80 | 0.48 |
| 5| 1224 | 29.66 | 11.96 | 0.53 |
| 10| 1885 | 36.67 | 17.23 | 0.65 |
| 42| 6776 | 99.84 | 56.14 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 828 | 29.26 | 9.62 | 0.49 |
| 3| 907 | 30.26 | 10.55 | 0.51 |
| 5| 1323 | 35.76 | 13.47 | 0.59 |
| 10| 2073 | 48.04 | 20.23 | 0.78 |
| 36| 5917 | 97.06 | 51.32 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.83 | 10.15 | 0.53 |
| 2| 814 | 35.85 | 11.38 | 0.56 |
| 3| 900 | 37.20 | 12.40 | 0.58 |
| 5| 1281 | 42.72 | 15.30 | 0.66 |
| 10| 2032 | 53.98 | 21.79 | 0.83 |
| 28| 4772 | 96.77 | 45.70 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5938 | 35.88 | 12.07 | 0.79 |
| 3| 6141 | 45.54 | 15.38 | 0.90 |
| 4| 6264 | 54.73 | 18.47 | 1.00 |
| 5| 6430 | 64.41 | 21.73 | 1.11 |
| 6| 6397 | 67.75 | 22.66 | 1.14 |
| 7| 6892 | 84.33 | 28.49 | 1.34 |
| 8| 6864 | 93.20 | 31.42 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 81.11 | 30.83 | 1.33 |
| 10 | 38 | 2163 | 7125 | 96.44 | 36.92 | 1.51 |

