--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-30 07:10:29.007304335 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6038 | 12.32 | 3.89 | 0.54 |
| 3| 6243 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.31 | 11.95 | 0.60 |
| 4 | 226 | 858 | 51.45 | 14.82 | 0.71 |
| 5 | 283 | 974 | 57.52 | 16.58 | 0.78 |
| 6 | 338 | 1081 | 65.73 | 18.97 | 0.87 |
| 7 | 394 | 1192 | 77.74 | 22.24 | 0.99 |
| 8 | 450 | 1303 | 87.58 | 24.99 | 1.10 |
| 9 | 506 | 1418 | 91.26 | 26.27 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2058 | 26.87 | 9.75 | 0.53 |
| 5| 2461 | 32.19 | 12.57 | 0.61 |
| 10| 3089 | 39.78 | 18.02 | 0.74 |
| 41| 7632 | 97.06 | 54.58 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 743 | 24.00 | 8.39 | 0.44 |
| 3| 1004 | 28.29 | 10.22 | 0.50 |
| 5| 1231 | 29.04 | 11.76 | 0.52 |
| 10| 1986 | 38.75 | 17.80 | 0.68 |
| 41| 6534 | 96.78 | 54.64 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.17 | 8.91 | 0.48 |
| 2| 740 | 30.20 | 9.84 | 0.50 |
| 3| 872 | 31.97 | 11.01 | 0.53 |
| 5| 1322 | 35.76 | 13.47 | 0.59 |
| 10| 2229 | 46.72 | 19.94 | 0.77 |
| 38| 6116 | 99.98 | 53.45 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 971 | 37.95 | 12.63 | 0.59 |
| 5| 1422 | 44.82 | 15.94 | 0.69 |
| 10| 2029 | 53.72 | 21.70 | 0.83 |
| 29| 4982 | 99.10 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.04 | 9.09 | 0.69 |
| 2| 5870 | 34.95 | 11.71 | 0.78 |
| 3| 6147 | 45.80 | 15.47 | 0.90 |
| 4| 6196 | 51.91 | 17.47 | 0.97 |
| 5| 6308 | 59.27 | 19.83 | 1.05 |
| 6| 6576 | 73.39 | 24.66 | 1.21 |
| 7| 6643 | 82.33 | 27.70 | 1.31 |
| 8| 6926 | 89.45 | 30.13 | 1.39 |
| 9| 6962 | 95.52 | 32.06 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.71 | 7.04 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

