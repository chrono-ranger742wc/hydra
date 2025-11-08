--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-08 05:31:32.872738587 UTC |
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
| 2| 6038 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.97 | 4.75 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 43.90 | 12.57 | 0.63 |
| 4 | 227 | 858 | 50.52 | 14.54 | 0.70 |
| 5 | 282 | 969 | 57.57 | 16.63 | 0.78 |
| 6 | 339 | 1081 | 74.03 | 21.04 | 0.95 |
| 7 | 396 | 1196 | 82.74 | 23.48 | 1.04 |
| 8 | 449 | 1307 | 81.53 | 23.70 | 1.04 |
| 9 | 507 | 1414 | 90.55 | 26.09 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.55 | 8.71 | 0.50 |
| 3| 2127 | 27.98 | 10.06 | 0.54 |
| 5| 2342 | 30.26 | 12.02 | 0.58 |
| 10| 3168 | 40.81 | 18.31 | 0.75 |
| 38| 7175 | 91.34 | 51.03 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.32 | 0.41 |
| 2| 763 | 23.58 | 8.22 | 0.43 |
| 3| 881 | 25.12 | 9.32 | 0.46 |
| 5| 1140 | 28.11 | 11.49 | 0.51 |
| 10| 1954 | 39.37 | 18.00 | 0.68 |
| 42| 6752 | 98.51 | 55.78 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 768 | 28.55 | 9.40 | 0.48 |
| 3| 917 | 32.64 | 11.21 | 0.54 |
| 5| 1134 | 35.71 | 13.37 | 0.59 |
| 10| 1959 | 46.73 | 19.83 | 0.76 |
| 34| 5468 | 96.51 | 49.74 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 840 | 36.60 | 11.61 | 0.57 |
| 3| 992 | 38.63 | 12.83 | 0.60 |
| 5| 1258 | 43.02 | 15.39 | 0.66 |
| 10| 2128 | 55.37 | 22.21 | 0.85 |
| 29| 4706 | 96.69 | 46.28 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 26.97 | 9.06 | 0.69 |
| 2| 5955 | 35.80 | 12.02 | 0.79 |
| 3| 6154 | 45.49 | 15.37 | 0.90 |
| 4| 6356 | 56.02 | 18.91 | 1.02 |
| 5| 6498 | 65.09 | 21.95 | 1.12 |
| 6| 6554 | 70.57 | 23.84 | 1.18 |
| 7| 6733 | 82.54 | 27.76 | 1.31 |
| 8| 7011 | 96.72 | 32.69 | 1.48 |
| 9| 6698 | 88.55 | 29.58 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1708 | 6855 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2162 | 7125 | 95.30 | 36.54 | 1.50 |

