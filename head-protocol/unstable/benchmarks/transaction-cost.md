--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-17 09:47:37.453699116 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6242 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 227 | 862 | 49.43 | 14.26 | 0.69 |
| 5 | 283 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 337 | 1081 | 64.59 | 18.74 | 0.85 |
| 7 | 395 | 1192 | 82.50 | 23.42 | 1.04 |
| 8 | 449 | 1303 | 93.94 | 26.61 | 1.16 |
| 9 | 505 | 1414 | 96.65 | 27.62 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.85 | 8.50 | 0.50 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2409 | 32.25 | 12.58 | 0.61 |
| 10| 3171 | 42.07 | 18.65 | 0.76 |
| 39| 7510 | 96.84 | 53.20 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.38 | 0.42 |
| 2| 817 | 25.47 | 8.79 | 0.46 |
| 3| 991 | 26.87 | 9.84 | 0.48 |
| 5| 1182 | 29.22 | 11.80 | 0.52 |
| 10| 1931 | 39.76 | 18.09 | 0.69 |
| 41| 6632 | 96.06 | 54.44 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 784 | 30.94 | 10.07 | 0.51 |
| 3| 1017 | 31.57 | 10.95 | 0.53 |
| 5| 1246 | 36.98 | 13.76 | 0.60 |
| 10| 2184 | 48.76 | 20.45 | 0.79 |
| 37| 6130 | 99.54 | 52.72 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 877 | 36.64 | 11.62 | 0.57 |
| 3| 959 | 37.88 | 12.61 | 0.59 |
| 5| 1268 | 42.65 | 15.28 | 0.66 |
| 10| 2032 | 54.06 | 21.81 | 0.83 |
| 29| 4969 | 99.73 | 47.20 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 27.08 | 9.09 | 0.69 |
| 2| 5894 | 34.87 | 11.67 | 0.78 |
| 3| 6087 | 42.33 | 14.20 | 0.86 |
| 4| 6319 | 55.99 | 18.87 | 1.02 |
| 5| 6508 | 66.73 | 22.65 | 1.14 |
| 6| 6597 | 74.75 | 25.17 | 1.23 |
| 7| 6702 | 81.74 | 27.43 | 1.30 |
| 8| 6784 | 89.36 | 30.07 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1140 | 6515 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

