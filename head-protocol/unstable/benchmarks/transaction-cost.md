--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-14 06:43:27.269121348 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14283 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 751 | 41.61 | 12.04 | 0.61 |
| 4 | 227 | 858 | 53.72 | 15.31 | 0.73 |
| 5 | 283 | 969 | 61.37 | 17.57 | 0.82 |
| 6 | 340 | 1081 | 66.08 | 19.06 | 0.87 |
| 7 | 397 | 1192 | 81.05 | 23.08 | 1.02 |
| 8 | 449 | 1303 | 91.63 | 25.96 | 1.14 |
| 9 | 505 | 1414 | 92.23 | 26.62 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1920 | 25.84 | 8.78 | 0.51 |
| 3| 2120 | 28.09 | 10.09 | 0.54 |
| 5| 2415 | 31.22 | 12.29 | 0.60 |
| 10| 3175 | 42.38 | 18.73 | 0.77 |
| 42| 7898 | 99.89 | 56.08 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.39 | 0.42 |
| 2| 856 | 25.37 | 8.76 | 0.46 |
| 3| 998 | 26.63 | 9.78 | 0.48 |
| 5| 1228 | 29.04 | 11.76 | 0.52 |
| 10| 2076 | 40.30 | 18.25 | 0.70 |
| 39| 6426 | 94.88 | 52.75 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 780 | 30.94 | 10.07 | 0.51 |
| 3| 955 | 30.94 | 10.75 | 0.52 |
| 5| 1326 | 35.64 | 13.44 | 0.59 |
| 10| 2085 | 45.23 | 19.47 | 0.75 |
| 35| 5505 | 96.27 | 50.30 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.85 | 11.38 | 0.56 |
| 3| 891 | 37.13 | 12.38 | 0.58 |
| 5| 1245 | 42.56 | 15.26 | 0.66 |
| 10| 1896 | 52.67 | 21.38 | 0.81 |
| 29| 4997 | 99.36 | 47.12 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 5823 | 31.56 | 10.50 | 0.74 |
| 3| 6110 | 46.04 | 15.53 | 0.90 |
| 4| 6248 | 53.69 | 18.07 | 0.99 |
| 5| 6331 | 59.60 | 19.97 | 1.05 |
| 6| 6598 | 73.42 | 24.65 | 1.21 |
| 7| 6549 | 77.84 | 26.11 | 1.26 |
| 8| 6904 | 92.47 | 31.26 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

