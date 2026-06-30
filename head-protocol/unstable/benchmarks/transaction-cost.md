--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-30 08:26:41.117095825 UTC |
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
| 2| 6038 | 13.16 | 4.19 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 19.02 | 6.02 | 0.64 |
| 10| 7644 | 29.02 | 9.14 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.35 | 9.42 | 0.51 |
| 3 | 171 | 747 | 41.31 | 11.95 | 0.60 |
| 4 | 226 | 862 | 48.34 | 14.07 | 0.68 |
| 5 | 282 | 969 | 64.57 | 18.36 | 0.85 |
| 6 | 338 | 1081 | 69.81 | 19.99 | 0.91 |
| 7 | 397 | 1196 | 71.87 | 20.83 | 0.93 |
| 8 | 451 | 1303 | 96.36 | 27.09 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.93 | 7.32 | 0.47 |
| 2| 1945 | 25.76 | 8.76 | 0.51 |
| 3| 2059 | 26.90 | 9.76 | 0.53 |
| 5| 2454 | 31.53 | 12.39 | 0.60 |
| 10| 3257 | 43.68 | 19.10 | 0.78 |
| 38| 7379 | 95.29 | 52.11 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.53 | 7.32 | 0.41 |
| 2| 749 | 23.66 | 8.26 | 0.43 |
| 3| 882 | 25.47 | 9.46 | 0.46 |
| 5| 1269 | 31.14 | 12.36 | 0.55 |
| 10| 2001 | 39.19 | 17.93 | 0.68 |
| 43| 6938 | 99.74 | 56.80 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 29.09 | 8.89 | 0.48 |
| 2| 814 | 29.22 | 9.61 | 0.49 |
| 3| 1052 | 34.14 | 11.66 | 0.56 |
| 5| 1345 | 35.56 | 13.42 | 0.59 |
| 10| 1968 | 47.33 | 20.01 | 0.76 |
| 36| 6073 | 99.38 | 52.04 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 1002 | 38.63 | 12.83 | 0.60 |
| 5| 1424 | 43.92 | 15.67 | 0.68 |
| 10| 2065 | 54.02 | 21.80 | 0.83 |
| 30| 4901 | 99.74 | 47.81 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.08 | 9.08 | 0.69 |
| 2| 5959 | 36.03 | 12.12 | 0.79 |
| 3| 6084 | 45.07 | 15.15 | 0.89 |
| 4| 6294 | 52.68 | 17.78 | 0.98 |
| 5| 6510 | 66.75 | 22.56 | 1.14 |
| 6| 6380 | 65.32 | 21.83 | 1.12 |
| 7| 6727 | 83.14 | 28.02 | 1.32 |
| 8| 6906 | 93.65 | 31.51 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1134 | 6508 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7127 | 95.56 | 36.62 | 1.50 |

