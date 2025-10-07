--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-07 04:39:11.573844571 UTC |
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
| 1| 5837 | 10.86 | 3.46 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.33 | 12.17 | 0.61 |
| 4 | 226 | 858 | 49.58 | 14.32 | 0.69 |
| 5 | 282 | 969 | 55.75 | 16.22 | 0.76 |
| 6 | 339 | 1081 | 73.50 | 20.87 | 0.94 |
| 7 | 393 | 1192 | 74.48 | 21.46 | 0.96 |
| 8 | 449 | 1303 | 83.16 | 23.98 | 1.05 |
| 9 | 505 | 1418 | 93.60 | 26.88 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.29 | 7.69 | 0.48 |
| 2| 1942 | 25.55 | 8.72 | 0.51 |
| 3| 2086 | 27.32 | 9.86 | 0.53 |
| 5| 2326 | 30.04 | 11.97 | 0.58 |
| 10| 3115 | 40.16 | 18.11 | 0.74 |
| 40| 7749 | 98.93 | 54.52 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 739 | 24.35 | 8.48 | 0.44 |
| 3| 976 | 28.35 | 10.24 | 0.50 |
| 5| 1380 | 32.85 | 12.85 | 0.57 |
| 10| 1894 | 36.65 | 17.23 | 0.65 |
| 42| 6640 | 97.76 | 55.53 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.13 | 8.90 | 0.48 |
| 2| 822 | 29.26 | 9.62 | 0.49 |
| 3| 997 | 31.69 | 10.98 | 0.53 |
| 5| 1273 | 35.08 | 13.26 | 0.59 |
| 10| 1968 | 44.26 | 19.19 | 0.73 |
| 39| 6100 | 99.24 | 53.85 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 814 | 35.88 | 11.39 | 0.56 |
| 3| 953 | 37.91 | 12.62 | 0.59 |
| 5| 1310 | 43.28 | 15.47 | 0.67 |
| 10| 2079 | 54.58 | 21.96 | 0.84 |
| 29| 4953 | 99.83 | 47.24 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 26.97 | 9.05 | 0.69 |
| 2| 5896 | 32.48 | 10.86 | 0.75 |
| 3| 6117 | 44.53 | 14.97 | 0.89 |
| 4| 6300 | 55.05 | 18.52 | 1.01 |
| 5| 6399 | 64.26 | 21.67 | 1.11 |
| 6| 6556 | 74.08 | 25.00 | 1.22 |
| 7| 6725 | 80.51 | 27.13 | 1.29 |
| 8| 6809 | 82.44 | 27.74 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

