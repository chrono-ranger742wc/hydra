--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-18 08:28:29.170836139 UTC |
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
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 15.16 | 4.82 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 169 | 751 | 40.37 | 11.74 | 0.59 |
| 4 | 226 | 858 | 52.48 | 15.04 | 0.72 |
| 5 | 283 | 969 | 59.58 | 17.14 | 0.80 |
| 6 | 337 | 1085 | 71.76 | 20.42 | 0.92 |
| 7 | 394 | 1192 | 80.97 | 23.06 | 1.02 |
| 8 | 449 | 1307 | 87.83 | 25.10 | 1.10 |
| 9 | 505 | 1414 | 94.13 | 27.07 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 23.92 | 7.60 | 0.48 |
| 2| 1945 | 25.84 | 8.78 | 0.51 |
| 3| 2064 | 26.98 | 9.78 | 0.53 |
| 5| 2327 | 29.97 | 11.95 | 0.58 |
| 10| 3268 | 44.25 | 19.26 | 0.79 |
| 40| 7432 | 94.65 | 53.26 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.57 | 7.30 | 0.41 |
| 2| 819 | 25.40 | 8.78 | 0.45 |
| 3| 972 | 26.06 | 9.59 | 0.47 |
| 5| 1275 | 31.12 | 12.37 | 0.55 |
| 10| 2091 | 41.39 | 18.57 | 0.71 |
| 42| 6689 | 98.66 | 55.78 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 27.54 | 8.47 | 0.46 |
| 2| 823 | 31.62 | 10.27 | 0.52 |
| 3| 1019 | 31.69 | 10.98 | 0.53 |
| 5| 1324 | 35.72 | 13.46 | 0.59 |
| 10| 2096 | 48.86 | 20.47 | 0.78 |
| 36| 5762 | 99.42 | 51.90 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 939 | 37.88 | 12.61 | 0.59 |
| 5| 1301 | 43.28 | 15.47 | 0.67 |
| 10| 1995 | 53.20 | 21.55 | 0.82 |
| 29| 4864 | 98.62 | 46.90 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.00 | 9.07 | 0.69 |
| 2| 5958 | 36.11 | 12.14 | 0.79 |
| 3| 6046 | 41.51 | 13.90 | 0.85 |
| 4| 6316 | 55.73 | 18.85 | 1.01 |
| 5| 6382 | 60.40 | 20.31 | 1.07 |
| 6| 6477 | 65.77 | 22.05 | 1.13 |
| 7| 6693 | 77.62 | 26.11 | 1.26 |
| 8| 6889 | 89.69 | 30.26 | 1.40 |
| 9| 6989 | 95.43 | 32.14 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.26 | 6.78 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1136 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2276 | 7193 | 99.22 | 38.09 | 1.54 |

