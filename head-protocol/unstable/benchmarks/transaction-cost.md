--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-27 07:24:53.994891006 UTC |
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
| 1| 5837 | 10.64 | 3.38 | 0.52 |
| 2| 6041 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 15.24 | 4.85 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 751 | 42.64 | 12.27 | 0.62 |
| 4 | 226 | 862 | 51.24 | 14.77 | 0.71 |
| 5 | 281 | 974 | 62.78 | 17.90 | 0.83 |
| 6 | 336 | 1081 | 68.11 | 19.62 | 0.89 |
| 7 | 393 | 1192 | 73.92 | 21.32 | 0.95 |
| 8 | 451 | 1303 | 83.15 | 24.03 | 1.05 |
| 9 | 507 | 1414 | 87.67 | 25.40 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1940 | 25.76 | 8.76 | 0.51 |
| 3| 2086 | 27.39 | 9.88 | 0.53 |
| 5| 2421 | 32.28 | 12.59 | 0.61 |
| 10| 3328 | 44.13 | 19.23 | 0.79 |
| 39| 7645 | 98.73 | 53.77 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.84 | 7.39 | 0.42 |
| 2| 797 | 24.05 | 8.40 | 0.44 |
| 3| 1048 | 27.88 | 10.13 | 0.49 |
| 5| 1242 | 29.91 | 12.02 | 0.53 |
| 10| 1883 | 36.48 | 17.17 | 0.65 |
| 42| 6699 | 99.86 | 56.10 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.50 | 8.46 | 0.46 |
| 2| 782 | 30.91 | 10.06 | 0.51 |
| 3| 959 | 30.86 | 10.73 | 0.52 |
| 5| 1234 | 34.26 | 13.02 | 0.58 |
| 10| 2039 | 47.81 | 20.17 | 0.77 |
| 37| 6041 | 99.72 | 52.73 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.92 | 11.40 | 0.56 |
| 3| 992 | 38.58 | 12.82 | 0.60 |
| 5| 1220 | 41.82 | 15.03 | 0.65 |
| 10| 1962 | 53.23 | 21.56 | 0.82 |
| 30| 4919 | 98.93 | 47.58 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.08 | 9.08 | 0.69 |
| 2| 5954 | 35.84 | 12.04 | 0.79 |
| 3| 6090 | 45.05 | 15.12 | 0.89 |
| 4| 6172 | 53.16 | 17.84 | 0.98 |
| 5| 6462 | 65.09 | 21.96 | 1.12 |
| 6| 6611 | 73.01 | 24.63 | 1.21 |
| 7| 6874 | 85.36 | 28.81 | 1.35 |
| 8| 6814 | 88.53 | 29.73 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2223 | 7162 | 98.49 | 37.73 | 1.53 |

