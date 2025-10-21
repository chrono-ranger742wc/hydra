--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-21 05:31:52.988421041 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.78 | 4.06 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 43.75 | 12.51 | 0.63 |
| 4 | 226 | 858 | 47.91 | 13.89 | 0.68 |
| 5 | 283 | 969 | 59.30 | 17.10 | 0.80 |
| 6 | 338 | 1085 | 72.26 | 20.65 | 0.93 |
| 7 | 395 | 1192 | 86.62 | 24.37 | 1.08 |
| 8 | 450 | 1307 | 96.81 | 27.25 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.39 | 8.68 | 0.50 |
| 3| 2063 | 27.27 | 9.85 | 0.53 |
| 5| 2400 | 31.34 | 12.32 | 0.60 |
| 10| 3036 | 38.33 | 17.62 | 0.72 |
| 40| 7519 | 94.72 | 53.32 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 701 | 22.62 | 7.95 | 0.42 |
| 3| 874 | 25.16 | 9.33 | 0.46 |
| 5| 1307 | 31.08 | 12.34 | 0.55 |
| 10| 1889 | 37.72 | 17.52 | 0.66 |
| 42| 6705 | 98.47 | 55.73 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.13 | 8.90 | 0.48 |
| 2| 775 | 30.98 | 10.08 | 0.51 |
| 3| 939 | 32.76 | 11.24 | 0.54 |
| 5| 1240 | 34.41 | 13.05 | 0.58 |
| 10| 2028 | 44.90 | 19.37 | 0.74 |
| 37| 5925 | 96.27 | 51.73 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 822 | 35.81 | 11.37 | 0.56 |
| 3| 997 | 38.59 | 12.82 | 0.60 |
| 5| 1199 | 41.86 | 15.04 | 0.65 |
| 10| 1881 | 51.78 | 21.12 | 0.80 |
| 28| 4858 | 97.49 | 45.92 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.05 | 9.07 | 0.69 |
| 2| 5875 | 34.91 | 11.70 | 0.78 |
| 3| 6156 | 46.00 | 15.48 | 0.90 |
| 4| 6331 | 55.78 | 18.84 | 1.02 |
| 5| 6331 | 61.16 | 20.52 | 1.07 |
| 6| 6522 | 73.69 | 24.84 | 1.21 |
| 7| 6578 | 78.68 | 26.41 | 1.27 |
| 8| 6911 | 89.36 | 30.16 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 38 | 2159 | 7121 | 96.00 | 36.77 | 1.50 |

