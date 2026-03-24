--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-24 05:48:30.013819741 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.38 | 11.97 | 0.60 |
| 4 | 225 | 858 | 52.36 | 14.96 | 0.72 |
| 5 | 283 | 969 | 56.52 | 16.41 | 0.77 |
| 6 | 339 | 1081 | 73.35 | 20.83 | 0.94 |
| 7 | 394 | 1192 | 86.49 | 24.38 | 1.08 |
| 8 | 448 | 1303 | 85.54 | 24.65 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.76 | 8.76 | 0.51 |
| 3| 2143 | 29.46 | 10.46 | 0.56 |
| 5| 2406 | 32.41 | 12.62 | 0.61 |
| 10| 3115 | 40.68 | 18.27 | 0.75 |
| 40| 7743 | 99.37 | 54.59 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 763 | 23.66 | 8.25 | 0.43 |
| 3| 862 | 24.07 | 9.03 | 0.45 |
| 5| 1314 | 31.68 | 12.52 | 0.55 |
| 10| 1952 | 38.46 | 17.74 | 0.67 |
| 46| 6973 | 98.92 | 58.53 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.50 | 8.46 | 0.46 |
| 2| 853 | 31.69 | 10.29 | 0.52 |
| 3| 921 | 32.72 | 11.23 | 0.54 |
| 5| 1190 | 36.35 | 13.57 | 0.59 |
| 10| 2004 | 47.41 | 20.03 | 0.77 |
| 38| 6117 | 99.67 | 53.36 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 1008 | 38.51 | 12.80 | 0.60 |
| 5| 1216 | 42.19 | 15.14 | 0.65 |
| 10| 1943 | 53.38 | 21.60 | 0.82 |
| 29| 4655 | 96.07 | 46.09 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.08 | 9.08 | 0.69 |
| 2| 6006 | 36.93 | 12.45 | 0.80 |
| 3| 6117 | 44.80 | 15.07 | 0.89 |
| 4| 6269 | 55.00 | 18.47 | 1.00 |
| 5| 6189 | 52.59 | 17.54 | 0.97 |
| 6| 6715 | 72.86 | 24.61 | 1.21 |
| 7| 6664 | 79.69 | 26.84 | 1.28 |
| 8| 6647 | 81.42 | 27.31 | 1.30 |
| 9| 7070 | 96.48 | 32.47 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1136 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

