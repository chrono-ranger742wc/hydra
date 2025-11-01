--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-01 05:26:26.135020258 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14283 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 226 | 858 | 53.94 | 15.39 | 0.73 |
| 5 | 282 | 969 | 62.85 | 17.95 | 0.83 |
| 6 | 339 | 1081 | 66.37 | 19.13 | 0.87 |
| 7 | 395 | 1192 | 74.05 | 21.40 | 0.96 |
| 8 | 449 | 1303 | 89.17 | 25.42 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 23.92 | 7.60 | 0.48 |
| 2| 1879 | 24.40 | 8.40 | 0.49 |
| 3| 2017 | 25.91 | 9.48 | 0.52 |
| 5| 2375 | 31.34 | 12.32 | 0.60 |
| 10| 3272 | 43.00 | 18.91 | 0.78 |
| 39| 7397 | 94.81 | 52.63 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.77 | 7.36 | 0.41 |
| 2| 697 | 22.58 | 7.94 | 0.42 |
| 3| 924 | 25.10 | 9.32 | 0.46 |
| 5| 1188 | 28.16 | 11.51 | 0.51 |
| 10| 1817 | 35.55 | 16.91 | 0.64 |
| 42| 6668 | 99.02 | 55.91 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.47 | 8.46 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 1011 | 34.03 | 11.63 | 0.55 |
| 5| 1263 | 37.24 | 13.85 | 0.61 |
| 10| 2046 | 47.26 | 20.00 | 0.77 |
| 34| 5894 | 95.48 | 49.64 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 983 | 38.63 | 12.83 | 0.60 |
| 5| 1204 | 41.93 | 15.06 | 0.65 |
| 10| 2033 | 54.81 | 22.03 | 0.84 |
| 29| 4706 | 96.22 | 46.17 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5845 | 31.48 | 10.46 | 0.74 |
| 3| 6095 | 44.67 | 15.04 | 0.89 |
| 4| 6215 | 51.60 | 17.35 | 0.97 |
| 5| 6303 | 60.88 | 20.45 | 1.07 |
| 6| 6578 | 70.87 | 23.84 | 1.18 |
| 7| 6825 | 85.45 | 28.89 | 1.35 |
| 8| 6958 | 92.17 | 31.08 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 567 | 6171 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2223 | 7162 | 97.61 | 37.43 | 1.52 |

