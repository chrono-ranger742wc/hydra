--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-13 05:37:48.360938084 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 19.27 | 6.11 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.09 | 11.66 | 0.59 |
| 4 | 225 | 858 | 47.89 | 13.89 | 0.68 |
| 5 | 283 | 969 | 64.13 | 18.23 | 0.84 |
| 6 | 340 | 1081 | 71.20 | 20.24 | 0.92 |
| 7 | 394 | 1192 | 76.39 | 21.92 | 0.98 |
| 8 | 451 | 1303 | 87.70 | 25.07 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.29 | 7.69 | 0.48 |
| 2| 1997 | 26.92 | 9.09 | 0.52 |
| 3| 2112 | 28.39 | 10.16 | 0.55 |
| 5| 2383 | 31.04 | 12.25 | 0.59 |
| 10| 3152 | 41.00 | 18.35 | 0.75 |
| 41| 7674 | 98.69 | 55.04 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 774 | 24.01 | 8.38 | 0.44 |
| 3| 974 | 27.04 | 9.88 | 0.48 |
| 5| 1187 | 30.09 | 12.07 | 0.53 |
| 10| 1997 | 39.31 | 17.98 | 0.69 |
| 39| 6444 | 98.04 | 53.62 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 866 | 29.94 | 9.83 | 0.50 |
| 3| 948 | 30.98 | 10.76 | 0.52 |
| 5| 1297 | 37.65 | 13.97 | 0.61 |
| 10| 2129 | 46.39 | 19.82 | 0.76 |
| 36| 5867 | 95.53 | 50.91 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1220 | 41.93 | 15.06 | 0.65 |
| 10| 2047 | 53.94 | 21.78 | 0.83 |
| 29| 4866 | 98.17 | 46.73 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5797 | 27.00 | 9.07 | 0.69 |
| 2| 5929 | 36.04 | 12.13 | 0.79 |
| 3| 6139 | 46.01 | 15.52 | 0.90 |
| 4| 6216 | 53.72 | 18.03 | 0.99 |
| 5| 6388 | 64.05 | 21.58 | 1.10 |
| 6| 6578 | 73.15 | 24.59 | 1.21 |
| 7| 6722 | 82.13 | 27.65 | 1.31 |
| 8| 7083 | 93.32 | 31.54 | 1.44 |
| 9| 6929 | 94.18 | 31.66 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2163 | 7126 | 96.44 | 36.92 | 1.51 |

