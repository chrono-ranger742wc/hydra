--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-25 05:31:41.692380534 UTC |
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
| 1| 5837 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.00 | 9.14 | 0.79 |
| 43| 14279 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 41.22 | 11.92 | 0.60 |
| 4 | 225 | 858 | 52.37 | 14.96 | 0.72 |
| 5 | 281 | 969 | 61.02 | 17.45 | 0.81 |
| 6 | 337 | 1081 | 68.10 | 19.54 | 0.89 |
| 7 | 393 | 1192 | 79.08 | 22.69 | 1.01 |
| 8 | 452 | 1303 | 95.97 | 27.00 | 1.18 |
| 9 | 506 | 1414 | 93.43 | 26.84 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1994 | 26.84 | 9.06 | 0.52 |
| 3| 2018 | 26.36 | 9.59 | 0.52 |
| 5| 2278 | 29.41 | 11.78 | 0.57 |
| 10| 3186 | 40.85 | 18.32 | 0.75 |
| 40| 7603 | 97.92 | 54.19 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 965 | 26.93 | 9.85 | 0.48 |
| 5| 1165 | 28.08 | 11.49 | 0.51 |
| 10| 2035 | 39.43 | 18.00 | 0.69 |
| 39| 6491 | 96.67 | 53.26 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.50 | 8.46 | 0.46 |
| 2| 838 | 31.58 | 10.27 | 0.52 |
| 3| 938 | 32.64 | 11.21 | 0.54 |
| 5| 1168 | 33.51 | 12.79 | 0.56 |
| 10| 2125 | 46.18 | 19.76 | 0.76 |
| 35| 5800 | 95.09 | 50.13 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 838 | 35.85 | 11.38 | 0.56 |
| 3| 952 | 37.84 | 12.60 | 0.59 |
| 5| 1258 | 42.72 | 15.30 | 0.66 |
| 10| 2079 | 54.92 | 22.06 | 0.84 |
| 30| 4940 | 98.85 | 47.58 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5828 | 26.92 | 9.04 | 0.69 |
| 2| 5969 | 37.05 | 12.49 | 0.80 |
| 3| 6109 | 44.63 | 15.01 | 0.89 |
| 4| 6238 | 53.51 | 18.00 | 0.99 |
| 5| 6470 | 65.17 | 22.01 | 1.12 |
| 6| 6574 | 70.00 | 23.58 | 1.18 |
| 7| 6743 | 80.99 | 27.37 | 1.30 |
| 8| 6977 | 92.28 | 31.05 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7160 | 98.68 | 37.80 | 1.54 |

