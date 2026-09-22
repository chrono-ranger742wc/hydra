--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-22 09:37:24.888967376 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.55 | 9.33 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.75 | 12.51 | 0.63 |
| 4 | 227 | 858 | 50.90 | 14.61 | 0.70 |
| 5 | 283 | 974 | 59.16 | 16.97 | 0.79 |
| 6 | 340 | 1081 | 73.10 | 20.70 | 0.94 |
| 7 | 394 | 1192 | 76.27 | 21.93 | 0.98 |
| 8 | 449 | 1303 | 85.18 | 24.47 | 1.07 |
| 9 | 506 | 1414 | 96.41 | 27.61 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 23.92 | 7.60 | 0.48 |
| 2| 1959 | 25.39 | 8.68 | 0.50 |
| 3| 2081 | 26.98 | 9.78 | 0.53 |
| 5| 2337 | 30.00 | 11.96 | 0.58 |
| 10| 3216 | 42.27 | 18.70 | 0.77 |
| 40| 7567 | 94.60 | 53.27 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.54 | 7.31 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 926 | 25.83 | 9.55 | 0.47 |
| 5| 1226 | 30.09 | 12.07 | 0.53 |
| 10| 1986 | 39.54 | 18.03 | 0.69 |
| 41| 6657 | 98.63 | 55.14 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 29.17 | 8.91 | 0.48 |
| 2| 847 | 29.97 | 9.84 | 0.50 |
| 3| 950 | 30.90 | 10.74 | 0.52 |
| 5| 1218 | 37.02 | 13.77 | 0.60 |
| 10| 2056 | 45.05 | 19.41 | 0.74 |
| 37| 6069 | 99.17 | 52.58 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.89 | 11.39 | 0.56 |
| 3| 1009 | 38.55 | 12.81 | 0.60 |
| 5| 1297 | 42.60 | 15.27 | 0.66 |
| 10| 1943 | 53.39 | 21.60 | 0.82 |
| 29| 4870 | 97.02 | 46.42 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.13 | 9.09 | 0.69 |
| 2| 5943 | 36.00 | 12.10 | 0.79 |
| 3| 6103 | 44.56 | 14.98 | 0.89 |
| 4| 6341 | 55.71 | 18.81 | 1.02 |
| 5| 6274 | 58.22 | 19.45 | 1.04 |
| 6| 6570 | 70.64 | 23.71 | 1.18 |
| 7| 6916 | 84.54 | 28.53 | 1.34 |
| 8| 6964 | 95.19 | 32.14 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.68 | 6.24 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 37 | 2107 | 7093 | 93.95 | 35.96 | 1.48 |

