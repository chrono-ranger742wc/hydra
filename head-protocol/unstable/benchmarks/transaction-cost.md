--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-11 08:04:42.55497705 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.30 | 9.24 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.13 | 11.88 | 0.60 |
| 4 | 226 | 858 | 50.65 | 14.55 | 0.70 |
| 5 | 283 | 969 | 58.00 | 16.79 | 0.78 |
| 6 | 340 | 1081 | 66.18 | 19.08 | 0.87 |
| 7 | 394 | 1192 | 76.38 | 21.96 | 0.98 |
| 8 | 450 | 1303 | 80.28 | 23.29 | 1.02 |
| 9 | 507 | 1414 | 93.82 | 26.99 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.40 | 8.39 | 0.49 |
| 3| 2076 | 27.10 | 9.81 | 0.53 |
| 5| 2418 | 31.88 | 12.49 | 0.60 |
| 10| 3180 | 41.46 | 18.50 | 0.76 |
| 39| 7496 | 97.58 | 53.41 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 22.81 | 7.38 | 0.42 |
| 2| 789 | 23.51 | 8.21 | 0.43 |
| 3| 970 | 28.32 | 10.23 | 0.50 |
| 5| 1266 | 29.94 | 12.01 | 0.53 |
| 10| 1962 | 39.57 | 18.05 | 0.69 |
| 41| 6397 | 92.77 | 53.53 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.13 | 8.90 | 0.48 |
| 2| 891 | 29.97 | 9.84 | 0.50 |
| 3| 937 | 32.69 | 11.22 | 0.54 |
| 5| 1318 | 35.72 | 13.46 | 0.59 |
| 10| 2036 | 44.89 | 19.37 | 0.74 |
| 34| 5590 | 92.05 | 48.59 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 874 | 36.64 | 11.62 | 0.57 |
| 3| 946 | 37.91 | 12.62 | 0.59 |
| 5| 1207 | 41.97 | 15.07 | 0.65 |
| 10| 2098 | 55.14 | 22.13 | 0.85 |
| 29| 4886 | 99.26 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.13 | 9.10 | 0.69 |
| 2| 6035 | 36.81 | 12.41 | 0.80 |
| 3| 6041 | 41.16 | 13.78 | 0.85 |
| 4| 6241 | 51.34 | 17.25 | 0.96 |
| 5| 6311 | 60.84 | 20.45 | 1.07 |
| 6| 6589 | 73.04 | 24.60 | 1.21 |
| 7| 6659 | 79.88 | 26.90 | 1.28 |
| 8| 6845 | 89.43 | 30.04 | 1.39 |
| 9| 6991 | 95.76 | 32.26 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 568 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2218 | 7157 | 96.72 | 37.13 | 1.51 |

