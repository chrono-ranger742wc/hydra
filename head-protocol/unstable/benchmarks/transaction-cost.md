--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-12 07:04:14.195645989 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6646 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 40.36 | 11.74 | 0.59 |
| 4 | 226 | 858 | 52.26 | 14.96 | 0.72 |
| 5 | 283 | 969 | 61.51 | 17.66 | 0.82 |
| 6 | 339 | 1081 | 74.64 | 21.06 | 0.95 |
| 7 | 395 | 1192 | 76.51 | 21.95 | 0.98 |
| 8 | 449 | 1303 | 98.49 | 27.61 | 1.20 |
| 10 | 561 | 1525 | 97.59 | 28.36 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.00 | 7.62 | 0.48 |
| 2| 1949 | 25.88 | 8.79 | 0.51 |
| 3| 2143 | 28.92 | 10.33 | 0.55 |
| 5| 2424 | 32.53 | 12.65 | 0.61 |
| 10| 3163 | 40.65 | 18.26 | 0.75 |
| 41| 7676 | 97.43 | 54.73 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 850 | 25.37 | 8.76 | 0.46 |
| 3| 861 | 24.03 | 9.02 | 0.45 |
| 5| 1267 | 30.17 | 12.08 | 0.54 |
| 10| 2143 | 41.69 | 18.64 | 0.72 |
| 40| 6501 | 98.19 | 54.29 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 789 | 30.98 | 10.08 | 0.51 |
| 3| 935 | 32.79 | 11.25 | 0.54 |
| 5| 1346 | 35.83 | 13.49 | 0.60 |
| 10| 1981 | 47.48 | 20.05 | 0.77 |
| 36| 5889 | 96.24 | 51.09 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.15 | 0.53 |
| 2| 875 | 36.56 | 11.60 | 0.57 |
| 3| 980 | 38.66 | 12.84 | 0.60 |
| 5| 1270 | 42.45 | 15.23 | 0.66 |
| 10| 2024 | 53.75 | 21.73 | 0.83 |
| 29| 4774 | 97.00 | 46.42 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 27.05 | 9.08 | 0.69 |
| 2| 5874 | 32.56 | 10.88 | 0.75 |
| 3| 6137 | 46.00 | 15.52 | 0.90 |
| 4| 6311 | 54.80 | 18.49 | 1.00 |
| 5| 6405 | 64.67 | 21.80 | 1.11 |
| 6| 6545 | 70.96 | 23.83 | 1.18 |
| 7| 6722 | 80.18 | 27.06 | 1.29 |
| 8| 6839 | 88.06 | 29.65 | 1.38 |
| 9| 7003 | 99.20 | 33.44 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1136 | 6510 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

