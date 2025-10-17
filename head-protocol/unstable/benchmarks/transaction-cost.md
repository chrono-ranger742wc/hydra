--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-17 04:38:38.878385985 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6240 | 14.84 | 4.71 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 226 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 283 | 969 | 61.51 | 17.63 | 0.82 |
| 6 | 337 | 1081 | 64.46 | 18.67 | 0.85 |
| 7 | 394 | 1196 | 78.37 | 22.39 | 1.00 |
| 8 | 450 | 1303 | 86.03 | 24.82 | 1.08 |
| 9 | 506 | 1414 | 99.40 | 28.33 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1986 | 26.54 | 9.00 | 0.52 |
| 3| 2101 | 28.35 | 10.15 | 0.54 |
| 5| 2374 | 31.22 | 12.29 | 0.60 |
| 10| 3134 | 40.01 | 18.09 | 0.74 |
| 42| 7797 | 98.19 | 55.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.80 | 7.38 | 0.41 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 905 | 25.01 | 9.30 | 0.46 |
| 5| 1167 | 28.12 | 11.50 | 0.51 |
| 10| 1891 | 37.49 | 17.47 | 0.66 |
| 40| 6368 | 93.93 | 53.19 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.51 | 8.47 | 0.46 |
| 2| 808 | 30.91 | 10.06 | 0.51 |
| 3| 952 | 30.98 | 10.76 | 0.52 |
| 5| 1317 | 38.22 | 14.15 | 0.62 |
| 10| 2049 | 45.09 | 19.43 | 0.74 |
| 37| 5664 | 98.89 | 52.31 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.16 | 0.53 |
| 2| 868 | 36.56 | 11.60 | 0.57 |
| 3| 1069 | 39.38 | 13.06 | 0.61 |
| 5| 1249 | 42.53 | 15.25 | 0.66 |
| 10| 2151 | 56.08 | 22.43 | 0.86 |
| 29| 4881 | 98.59 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5902 | 34.87 | 11.69 | 0.78 |
| 3| 6042 | 41.32 | 13.83 | 0.85 |
| 4| 6252 | 55.54 | 18.78 | 1.01 |
| 5| 6383 | 62.09 | 20.94 | 1.08 |
| 6| 6666 | 75.51 | 25.44 | 1.24 |
| 7| 6589 | 78.58 | 26.39 | 1.27 |
| 8| 6920 | 95.13 | 32.10 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.15 | 7.19 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

