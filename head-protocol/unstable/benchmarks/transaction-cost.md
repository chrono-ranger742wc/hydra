--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-01 09:46:18.919340637 UTC |
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
| 1| 5838 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 112 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.33 | 12.17 | 0.61 |
| 4 | 225 | 858 | 47.90 | 13.92 | 0.68 |
| 5 | 284 | 969 | 57.55 | 16.59 | 0.78 |
| 6 | 338 | 1081 | 69.76 | 19.94 | 0.91 |
| 7 | 393 | 1192 | 80.09 | 22.84 | 1.01 |
| 8 | 450 | 1303 | 94.80 | 26.87 | 1.17 |
| 9 | 505 | 1414 | 91.26 | 26.27 | 1.14 |
| 10 | 561 | 1525 | 96.96 | 28.08 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.77 | 8.48 | 0.49 |
| 3| 2116 | 27.93 | 10.05 | 0.54 |
| 5| 2350 | 29.97 | 11.95 | 0.58 |
| 10| 3112 | 40.55 | 18.24 | 0.75 |
| 41| 7673 | 98.19 | 54.92 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 1016 | 28.07 | 10.16 | 0.50 |
| 5| 1161 | 27.97 | 11.46 | 0.51 |
| 10| 1957 | 38.15 | 17.66 | 0.67 |
| 40| 6470 | 98.60 | 54.40 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 713 | 27.54 | 8.47 | 0.47 |
| 2| 799 | 30.87 | 10.05 | 0.51 |
| 3| 945 | 30.94 | 10.75 | 0.52 |
| 5| 1273 | 37.67 | 13.98 | 0.61 |
| 10| 2102 | 45.51 | 19.56 | 0.75 |
| 35| 5795 | 95.59 | 50.31 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 876 | 36.56 | 11.60 | 0.57 |
| 3| 942 | 37.80 | 12.59 | 0.59 |
| 5| 1281 | 42.68 | 15.29 | 0.66 |
| 10| 2002 | 54.13 | 21.83 | 0.83 |
| 29| 4751 | 96.50 | 46.24 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.04 | 9.09 | 0.69 |
| 2| 5906 | 32.45 | 10.85 | 0.75 |
| 3| 5974 | 40.28 | 13.43 | 0.84 |
| 4| 6329 | 54.88 | 18.48 | 1.01 |
| 5| 6420 | 64.07 | 21.54 | 1.11 |
| 6| 6450 | 66.07 | 22.13 | 1.13 |
| 7| 6622 | 78.88 | 26.50 | 1.27 |
| 8| 6911 | 89.55 | 30.18 | 1.40 |
| 9| 6818 | 94.98 | 31.89 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 284 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1705 | 6852 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2223 | 7162 | 98.49 | 37.73 | 1.53 |

