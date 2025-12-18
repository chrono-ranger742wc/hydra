--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-18 05:42:18.986375325 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.34 | 3.90 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.64 | 12.50 | 0.63 |
| 4 | 227 | 858 | 52.04 | 14.88 | 0.72 |
| 5 | 283 | 969 | 56.07 | 16.24 | 0.76 |
| 6 | 340 | 1081 | 72.08 | 20.53 | 0.93 |
| 7 | 394 | 1192 | 86.87 | 24.47 | 1.08 |
| 8 | 451 | 1307 | 99.17 | 27.92 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1943 | 25.84 | 8.78 | 0.51 |
| 3| 2021 | 25.91 | 9.48 | 0.52 |
| 5| 2428 | 32.36 | 12.61 | 0.61 |
| 10| 3203 | 41.84 | 18.61 | 0.76 |
| 39| 7521 | 97.99 | 53.49 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.50 | 7.29 | 0.41 |
| 2| 812 | 25.14 | 8.69 | 0.45 |
| 3| 830 | 24.09 | 9.04 | 0.45 |
| 5| 1229 | 29.12 | 11.78 | 0.52 |
| 10| 1994 | 38.65 | 17.78 | 0.68 |
| 43| 6764 | 98.71 | 56.49 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.22 | 9.61 | 0.49 |
| 3| 1012 | 31.57 | 10.95 | 0.53 |
| 5| 1317 | 37.78 | 14.00 | 0.61 |
| 10| 2116 | 48.98 | 20.50 | 0.79 |
| 36| 5782 | 95.62 | 50.88 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 836 | 35.89 | 11.39 | 0.56 |
| 3| 1011 | 38.47 | 12.79 | 0.60 |
| 5| 1396 | 43.87 | 15.66 | 0.68 |
| 10| 1978 | 53.42 | 21.61 | 0.82 |
| 29| 4800 | 97.72 | 46.60 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.13 | 9.11 | 0.69 |
| 2| 5945 | 35.91 | 12.07 | 0.79 |
| 3| 6126 | 45.57 | 15.39 | 0.90 |
| 4| 6175 | 52.89 | 17.72 | 0.98 |
| 5| 6408 | 63.27 | 21.34 | 1.10 |
| 6| 6642 | 73.64 | 24.90 | 1.22 |
| 7| 6663 | 82.35 | 27.72 | 1.31 |
| 8| 6735 | 88.53 | 29.80 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 286 | 6006 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 81.81 | 31.06 | 1.34 |
| 10 | 39 | 2219 | 7158 | 99.12 | 37.95 | 1.54 |

