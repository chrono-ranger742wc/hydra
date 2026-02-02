--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-02 05:49:58.332925516 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.64 | 12.49 | 0.63 |
| 4 | 226 | 858 | 49.59 | 14.32 | 0.69 |
| 5 | 282 | 974 | 62.95 | 17.98 | 0.83 |
| 6 | 337 | 1081 | 71.36 | 20.35 | 0.92 |
| 7 | 394 | 1192 | 87.68 | 24.76 | 1.09 |
| 8 | 450 | 1303 | 82.91 | 23.87 | 1.05 |
| 9 | 505 | 1414 | 91.96 | 26.55 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1887 | 24.40 | 8.40 | 0.49 |
| 3| 2065 | 27.39 | 9.88 | 0.53 |
| 5| 2455 | 31.99 | 12.52 | 0.61 |
| 10| 3161 | 40.50 | 18.23 | 0.75 |
| 42| 7821 | 98.82 | 55.77 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.54 | 7.31 | 0.41 |
| 2| 820 | 25.16 | 8.69 | 0.45 |
| 3| 876 | 25.05 | 9.32 | 0.46 |
| 5| 1236 | 30.66 | 12.25 | 0.54 |
| 10| 1996 | 37.82 | 17.55 | 0.67 |
| 41| 6654 | 99.30 | 55.34 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 786 | 30.95 | 10.07 | 0.51 |
| 3| 942 | 32.75 | 11.24 | 0.54 |
| 5| 1314 | 35.72 | 13.46 | 0.59 |
| 10| 2005 | 47.36 | 20.02 | 0.77 |
| 37| 6151 | 99.87 | 52.79 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 879 | 36.60 | 11.61 | 0.57 |
| 3| 959 | 37.95 | 12.63 | 0.59 |
| 5| 1246 | 42.57 | 15.26 | 0.66 |
| 10| 2240 | 57.06 | 22.71 | 0.87 |
| 28| 5013 | 99.00 | 46.43 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 26.92 | 9.04 | 0.69 |
| 2| 5934 | 36.04 | 12.09 | 0.79 |
| 3| 6068 | 43.39 | 14.56 | 0.87 |
| 4| 6222 | 53.95 | 18.15 | 0.99 |
| 5| 6291 | 57.20 | 19.19 | 1.03 |
| 6| 6517 | 72.48 | 24.34 | 1.20 |
| 7| 6736 | 81.63 | 27.52 | 1.30 |
| 8| 6675 | 83.62 | 28.10 | 1.32 |
| 9| 6813 | 93.77 | 31.47 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1134 | 6508 | 60.42 | 22.68 | 1.09 |
| 10 | 40 | 2274 | 7191 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

