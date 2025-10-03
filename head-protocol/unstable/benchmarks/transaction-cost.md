--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-03 04:38:19.60710268 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 858 | 53.88 | 15.35 | 0.73 |
| 5 | 284 | 969 | 58.18 | 16.83 | 0.78 |
| 6 | 341 | 1081 | 75.12 | 21.22 | 0.96 |
| 7 | 394 | 1192 | 81.96 | 23.20 | 1.03 |
| 8 | 451 | 1303 | 96.16 | 27.04 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.40 | 8.40 | 0.49 |
| 3| 2105 | 28.05 | 10.08 | 0.54 |
| 5| 2384 | 31.53 | 12.37 | 0.60 |
| 10| 3269 | 43.34 | 19.02 | 0.78 |
| 39| 7353 | 94.70 | 52.64 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.77 | 7.36 | 0.42 |
| 2| 766 | 24.28 | 8.45 | 0.44 |
| 3| 915 | 25.10 | 9.32 | 0.46 |
| 5| 1266 | 30.19 | 12.08 | 0.54 |
| 10| 1818 | 35.67 | 16.93 | 0.64 |
| 39| 6438 | 96.23 | 53.13 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.47 | 8.46 | 0.46 |
| 2| 850 | 31.69 | 10.29 | 0.52 |
| 3| 872 | 31.97 | 11.01 | 0.53 |
| 5| 1269 | 35.01 | 13.24 | 0.58 |
| 10| 1968 | 44.22 | 19.16 | 0.73 |
| 36| 5851 | 96.43 | 51.17 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 868 | 36.60 | 11.61 | 0.57 |
| 3| 942 | 37.95 | 12.63 | 0.59 |
| 5| 1257 | 42.49 | 15.24 | 0.66 |
| 10| 1957 | 53.50 | 21.65 | 0.82 |
| 28| 4737 | 96.24 | 45.53 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 26.92 | 9.04 | 0.69 |
| 2| 5956 | 35.96 | 12.08 | 0.79 |
| 3| 6029 | 43.88 | 14.69 | 0.88 |
| 4| 6294 | 54.92 | 18.51 | 1.00 |
| 5| 6371 | 59.47 | 19.99 | 1.06 |
| 6| 6393 | 68.23 | 22.89 | 1.15 |
| 7| 6707 | 79.46 | 26.71 | 1.28 |
| 8| 6877 | 91.18 | 30.66 | 1.41 |
| 9| 7029 | 99.23 | 33.36 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

