--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-17 09:33:45.37696075 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6240 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 751 | 43.99 | 12.61 | 0.63 |
| 4 | 227 | 862 | 48.19 | 13.99 | 0.68 |
| 5 | 284 | 969 | 59.27 | 17.03 | 0.79 |
| 6 | 338 | 1081 | 72.20 | 20.63 | 0.93 |
| 7 | 393 | 1192 | 85.29 | 24.14 | 1.07 |
| 8 | 450 | 1303 | 91.94 | 26.09 | 1.14 |
| 9 | 505 | 1414 | 98.99 | 28.23 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1999 | 26.76 | 9.04 | 0.52 |
| 3| 2080 | 26.91 | 9.76 | 0.53 |
| 5| 2505 | 33.51 | 12.93 | 0.62 |
| 10| 3262 | 42.45 | 18.76 | 0.77 |
| 40| 7608 | 99.99 | 54.73 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.80 | 7.37 | 0.42 |
| 2| 819 | 25.20 | 8.70 | 0.45 |
| 3| 910 | 25.10 | 9.32 | 0.46 |
| 5| 1342 | 33.79 | 13.09 | 0.58 |
| 10| 2120 | 40.42 | 18.28 | 0.70 |
| 39| 6587 | 97.55 | 53.52 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.13 | 8.90 | 0.48 |
| 2| 876 | 29.90 | 9.82 | 0.50 |
| 3| 976 | 33.51 | 11.47 | 0.55 |
| 5| 1227 | 37.06 | 13.79 | 0.60 |
| 10| 2101 | 46.10 | 19.72 | 0.76 |
| 35| 5686 | 98.61 | 51.02 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 887 | 36.60 | 11.61 | 0.57 |
| 3| 971 | 37.91 | 12.62 | 0.59 |
| 5| 1200 | 41.93 | 15.06 | 0.65 |
| 10| 1982 | 53.34 | 21.59 | 0.82 |
| 29| 5048 | 99.49 | 47.16 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.00 | 9.07 | 0.69 |
| 2| 5935 | 36.08 | 12.12 | 0.79 |
| 3| 5995 | 41.63 | 13.95 | 0.85 |
| 4| 6191 | 50.47 | 16.92 | 0.95 |
| 5| 6475 | 63.86 | 21.50 | 1.11 |
| 6| 6579 | 74.34 | 25.14 | 1.22 |
| 7| 6698 | 83.85 | 28.27 | 1.33 |
| 8| 6830 | 85.56 | 28.72 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1141 | 6516 | 58.66 | 22.07 | 1.07 |
| 10 | 38 | 2163 | 7125 | 96.44 | 36.92 | 1.51 |

