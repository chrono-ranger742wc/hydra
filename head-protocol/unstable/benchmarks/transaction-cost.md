--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-21 05:34:42.82742132 UTC |
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
| 1| 5836 | 10.93 | 3.49 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.30 | 9.24 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 226 | 858 | 49.43 | 14.26 | 0.69 |
| 5 | 282 | 969 | 64.25 | 18.22 | 0.84 |
| 6 | 339 | 1081 | 75.08 | 21.24 | 0.96 |
| 7 | 395 | 1196 | 83.00 | 23.55 | 1.04 |
| 8 | 448 | 1307 | 94.16 | 26.62 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1943 | 25.39 | 8.68 | 0.50 |
| 3| 2017 | 25.98 | 9.50 | 0.52 |
| 5| 2379 | 30.85 | 12.20 | 0.59 |
| 10| 3066 | 39.59 | 17.97 | 0.73 |
| 39| 7384 | 94.94 | 52.68 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.32 | 0.41 |
| 2| 737 | 24.35 | 8.46 | 0.44 |
| 3| 917 | 25.14 | 9.33 | 0.46 |
| 5| 1209 | 29.07 | 11.77 | 0.52 |
| 10| 1878 | 37.42 | 17.45 | 0.66 |
| 40| 6689 | 99.12 | 54.64 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.50 | 8.46 | 0.46 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 970 | 30.94 | 10.75 | 0.52 |
| 5| 1282 | 35.04 | 13.25 | 0.59 |
| 10| 1917 | 45.98 | 19.60 | 0.75 |
| 36| 6066 | 97.47 | 51.49 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 813 | 35.88 | 11.39 | 0.56 |
| 3| 1060 | 39.22 | 13.02 | 0.61 |
| 5| 1252 | 43.02 | 15.39 | 0.66 |
| 10| 2005 | 54.21 | 21.85 | 0.83 |
| 28| 4637 | 94.27 | 44.96 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.00 | 9.07 | 0.69 |
| 2| 5824 | 31.52 | 10.47 | 0.74 |
| 3| 6045 | 43.84 | 14.70 | 0.88 |
| 4| 6097 | 49.29 | 16.44 | 0.94 |
| 5| 6564 | 64.92 | 21.91 | 1.12 |
| 6| 6610 | 73.16 | 24.63 | 1.21 |
| 7| 6741 | 83.58 | 28.18 | 1.33 |
| 8| 6794 | 89.10 | 29.99 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1703 | 6850 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2277 | 7194 | 99.22 | 38.09 | 1.54 |

