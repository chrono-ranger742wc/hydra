--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-12 04:38:04.355949353 UTC |
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
| 2| 6042 | 13.08 | 4.16 | 0.55 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14283 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 227 | 862 | 50.58 | 14.53 | 0.70 |
| 5 | 282 | 969 | 55.81 | 16.17 | 0.76 |
| 6 | 340 | 1081 | 71.90 | 20.56 | 0.93 |
| 7 | 392 | 1196 | 80.95 | 23.06 | 1.02 |
| 8 | 448 | 1307 | 89.52 | 25.51 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.81 | 8.49 | 0.49 |
| 3| 2090 | 27.28 | 9.85 | 0.53 |
| 5| 2320 | 30.18 | 12.00 | 0.58 |
| 10| 3259 | 41.60 | 18.54 | 0.76 |
| 41| 7747 | 99.05 | 55.17 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.80 | 7.36 | 0.42 |
| 2| 816 | 25.57 | 8.80 | 0.46 |
| 3| 878 | 25.09 | 9.31 | 0.46 |
| 5| 1273 | 31.27 | 12.39 | 0.55 |
| 10| 1910 | 37.99 | 17.62 | 0.67 |
| 42| 6797 | 98.91 | 55.87 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 29.13 | 8.90 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1243 | 36.98 | 13.76 | 0.60 |
| 10| 1956 | 46.88 | 19.86 | 0.76 |
| 36| 6160 | 98.61 | 51.85 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.16 | 0.53 |
| 2| 886 | 36.52 | 11.59 | 0.57 |
| 3| 1035 | 39.22 | 13.02 | 0.61 |
| 5| 1264 | 42.57 | 15.26 | 0.66 |
| 10| 2008 | 54.06 | 21.81 | 0.83 |
| 29| 4766 | 97.00 | 46.38 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 5979 | 37.17 | 12.52 | 0.80 |
| 3| 5974 | 40.35 | 13.45 | 0.84 |
| 4| 6294 | 54.67 | 18.42 | 1.00 |
| 5| 6381 | 63.39 | 21.37 | 1.10 |
| 6| 6605 | 76.87 | 26.04 | 1.25 |
| 7| 6783 | 81.17 | 27.32 | 1.30 |
| 8| 7033 | 94.34 | 31.91 | 1.45 |
| 9| 6677 | 87.69 | 29.33 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.34 | 6.91 | 0.62 |
| 10 | 20 | 1138 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2217 | 7156 | 97.61 | 37.43 | 1.52 |

