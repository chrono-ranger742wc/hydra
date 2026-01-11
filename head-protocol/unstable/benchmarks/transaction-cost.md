--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-11 05:15:49.26029408 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.38 | 12.20 | 0.61 |
| 4 | 227 | 858 | 53.87 | 15.34 | 0.73 |
| 5 | 282 | 969 | 62.18 | 17.69 | 0.82 |
| 6 | 340 | 1081 | 70.12 | 20.06 | 0.91 |
| 7 | 394 | 1196 | 80.92 | 23.09 | 1.02 |
| 8 | 450 | 1303 | 91.75 | 25.99 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1976 | 26.39 | 8.96 | 0.51 |
| 3| 2113 | 28.46 | 10.18 | 0.55 |
| 5| 2332 | 30.42 | 12.06 | 0.59 |
| 10| 3265 | 42.37 | 18.76 | 0.77 |
| 38| 7254 | 93.81 | 51.67 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.57 | 7.31 | 0.41 |
| 2| 745 | 23.58 | 8.24 | 0.43 |
| 3| 952 | 26.64 | 9.78 | 0.48 |
| 5| 1138 | 28.57 | 11.64 | 0.52 |
| 10| 2043 | 39.47 | 18.01 | 0.69 |
| 42| 6593 | 97.06 | 55.35 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 712 | 27.54 | 8.47 | 0.47 |
| 2| 870 | 31.62 | 10.27 | 0.52 |
| 3| 906 | 30.15 | 10.52 | 0.51 |
| 5| 1237 | 37.02 | 13.78 | 0.60 |
| 10| 2071 | 45.61 | 19.58 | 0.75 |
| 35| 5722 | 94.61 | 50.01 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 804 | 35.85 | 11.38 | 0.56 |
| 3| 983 | 38.66 | 12.84 | 0.60 |
| 5| 1251 | 42.65 | 15.28 | 0.66 |
| 10| 2069 | 54.74 | 22.02 | 0.84 |
| 29| 5079 | 99.70 | 47.24 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 26.92 | 9.05 | 0.69 |
| 2| 5936 | 35.80 | 12.02 | 0.79 |
| 3| 6032 | 41.39 | 13.87 | 0.85 |
| 4| 6306 | 55.82 | 18.87 | 1.01 |
| 5| 6388 | 60.08 | 20.18 | 1.06 |
| 6| 6674 | 74.60 | 25.13 | 1.23 |
| 7| 6753 | 83.77 | 28.23 | 1.33 |
| 8| 6902 | 91.97 | 31.02 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.42 | 5.80 | 0.59 |
| 10 | 10 | 571 | 6176 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

