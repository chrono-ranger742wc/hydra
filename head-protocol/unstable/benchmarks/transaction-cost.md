--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-03 09:25:43.195309594 UTC |
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
| 1| 5834 | 11.12 | 3.55 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.49 | 12.21 | 0.61 |
| 4 | 226 | 858 | 53.94 | 15.36 | 0.73 |
| 5 | 282 | 969 | 57.78 | 16.71 | 0.78 |
| 6 | 341 | 1081 | 73.24 | 20.73 | 0.94 |
| 7 | 394 | 1192 | 73.26 | 21.31 | 0.95 |
| 8 | 451 | 1303 | 98.73 | 27.71 | 1.20 |
| 9 | 506 | 1418 | 91.82 | 26.46 | 1.15 |
| 10 | 560 | 1525 | 99.91 | 28.85 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.40 | 8.40 | 0.49 |
| 3| 2137 | 28.10 | 10.09 | 0.54 |
| 5| 2432 | 32.60 | 12.67 | 0.61 |
| 10| 3173 | 41.86 | 18.60 | 0.76 |
| 41| 7688 | 98.79 | 55.08 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.37 | 0.42 |
| 2| 792 | 24.32 | 8.46 | 0.44 |
| 3| 906 | 25.52 | 9.47 | 0.46 |
| 5| 1272 | 30.19 | 12.08 | 0.54 |
| 10| 1989 | 38.48 | 17.73 | 0.68 |
| 41| 6722 | 99.39 | 55.36 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 986 | 31.61 | 10.96 | 0.53 |
| 5| 1289 | 34.93 | 13.22 | 0.58 |
| 10| 1953 | 46.80 | 19.84 | 0.76 |
| 33| 5404 | 95.80 | 48.87 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 852 | 36.52 | 11.59 | 0.57 |
| 3| 942 | 37.95 | 12.63 | 0.59 |
| 5| 1221 | 42.01 | 15.08 | 0.65 |
| 10| 2090 | 54.77 | 22.02 | 0.84 |
| 29| 5019 | 99.62 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 27.05 | 9.08 | 0.69 |
| 2| 5901 | 34.83 | 11.65 | 0.78 |
| 3| 6120 | 44.68 | 15.01 | 0.89 |
| 4| 6253 | 54.53 | 18.39 | 1.00 |
| 5| 6399 | 61.67 | 20.77 | 1.08 |
| 6| 6564 | 70.57 | 23.72 | 1.18 |
| 7| 6596 | 79.09 | 26.66 | 1.27 |
| 8| 7078 | 95.36 | 32.27 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 27.14 | 9.67 | 0.70 |
| 10 | 10 | 570 | 6175 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |
| 10 | 35 | 1992 | 7023 | 89.85 | 34.35 | 1.43 |

