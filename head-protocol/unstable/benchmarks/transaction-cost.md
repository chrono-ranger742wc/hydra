--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-28 05:22:04.95865531 UTC |
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
| 1| 5836 | 10.76 | 3.42 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 227 | 862 | 50.83 | 14.62 | 0.70 |
| 5 | 282 | 969 | 57.53 | 16.58 | 0.78 |
| 6 | 339 | 1081 | 70.51 | 20.19 | 0.91 |
| 7 | 394 | 1192 | 82.94 | 23.53 | 1.04 |
| 8 | 450 | 1307 | 87.50 | 25.07 | 1.10 |
| 9 | 505 | 1414 | 88.59 | 25.73 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 27.32 | 9.86 | 0.53 |
| 5| 2330 | 30.34 | 12.04 | 0.58 |
| 10| 3157 | 41.16 | 18.41 | 0.75 |
| 39| 7651 | 98.82 | 53.77 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.31 | 0.41 |
| 2| 836 | 25.17 | 8.71 | 0.45 |
| 3| 969 | 26.84 | 9.83 | 0.48 |
| 5| 1188 | 28.66 | 11.68 | 0.52 |
| 10| 2150 | 43.73 | 19.21 | 0.74 |
| 42| 6826 | 99.93 | 56.18 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 29.17 | 8.91 | 0.48 |
| 2| 836 | 29.26 | 9.62 | 0.49 |
| 3| 1015 | 31.54 | 10.94 | 0.53 |
| 5| 1236 | 36.95 | 13.76 | 0.60 |
| 10| 2190 | 46.93 | 19.99 | 0.77 |
| 36| 5974 | 97.61 | 51.53 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 828 | 35.92 | 11.40 | 0.56 |
| 3| 972 | 37.91 | 12.62 | 0.59 |
| 5| 1246 | 42.45 | 15.23 | 0.66 |
| 10| 1943 | 53.12 | 21.53 | 0.82 |
| 29| 4853 | 97.73 | 46.66 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 27.05 | 9.08 | 0.69 |
| 2| 5919 | 35.88 | 12.03 | 0.79 |
| 3| 6125 | 45.57 | 15.38 | 0.90 |
| 4| 6254 | 55.09 | 18.55 | 1.00 |
| 5| 6493 | 64.85 | 21.86 | 1.12 |
| 6| 6629 | 75.61 | 25.55 | 1.24 |
| 7| 6786 | 81.63 | 27.58 | 1.31 |
| 8| 6865 | 93.32 | 31.46 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1137 | 6511 | 60.17 | 22.59 | 1.09 |
| 10 | 39 | 2217 | 7157 | 99.12 | 37.95 | 1.54 |

