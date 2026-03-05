--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-05 05:39:29.408938613 UTC |
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
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 751 | 43.86 | 12.56 | 0.63 |
| 4 | 227 | 858 | 49.73 | 14.35 | 0.69 |
| 5 | 282 | 969 | 62.80 | 17.91 | 0.83 |
| 6 | 339 | 1081 | 73.22 | 20.80 | 0.94 |
| 7 | 394 | 1192 | 86.30 | 24.33 | 1.08 |
| 8 | 448 | 1303 | 94.40 | 26.72 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1932 | 25.43 | 8.68 | 0.50 |
| 3| 2085 | 27.43 | 9.89 | 0.53 |
| 5| 2454 | 32.25 | 12.58 | 0.61 |
| 10| 3161 | 41.70 | 18.54 | 0.76 |
| 38| 7305 | 94.57 | 51.89 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.77 | 7.36 | 0.42 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 857 | 23.99 | 9.01 | 0.45 |
| 5| 1138 | 28.87 | 11.72 | 0.52 |
| 10| 2066 | 42.00 | 18.71 | 0.72 |
| 40| 6479 | 97.86 | 54.27 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.13 | 8.90 | 0.48 |
| 2| 828 | 29.22 | 9.61 | 0.49 |
| 3| 1046 | 32.32 | 11.18 | 0.54 |
| 5| 1168 | 33.66 | 12.83 | 0.57 |
| 10| 2162 | 46.43 | 19.84 | 0.76 |
| 38| 6064 | 99.10 | 53.18 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.79 | 10.15 | 0.53 |
| 2| 826 | 35.89 | 11.39 | 0.56 |
| 3| 979 | 38.63 | 12.83 | 0.60 |
| 5| 1300 | 43.25 | 15.47 | 0.67 |
| 10| 2013 | 54.21 | 21.85 | 0.83 |
| 29| 4919 | 98.79 | 46.90 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.12 | 9.10 | 0.69 |
| 2| 5866 | 32.54 | 10.86 | 0.75 |
| 3| 6113 | 46.00 | 15.53 | 0.90 |
| 4| 6203 | 53.94 | 18.13 | 0.99 |
| 5| 6494 | 65.44 | 22.06 | 1.12 |
| 6| 6629 | 74.52 | 25.10 | 1.22 |
| 7| 6790 | 84.80 | 28.63 | 1.34 |
| 8| 6789 | 88.20 | 29.64 | 1.38 |
| 9| 6936 | 97.61 | 32.77 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

