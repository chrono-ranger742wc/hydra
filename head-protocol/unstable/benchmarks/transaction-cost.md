--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-06 07:25:11.803058325 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6645 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 42.64 | 12.27 | 0.62 |
| 4 | 228 | 858 | 51.98 | 14.92 | 0.72 |
| 5 | 282 | 969 | 62.29 | 17.75 | 0.82 |
| 6 | 337 | 1081 | 70.36 | 20.16 | 0.91 |
| 7 | 395 | 1192 | 83.15 | 23.59 | 1.04 |
| 8 | 451 | 1303 | 80.30 | 23.20 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 1976 | 26.76 | 9.04 | 0.52 |
| 3| 2021 | 25.87 | 9.47 | 0.52 |
| 5| 2416 | 32.16 | 12.56 | 0.61 |
| 10| 3190 | 40.98 | 18.37 | 0.75 |
| 40| 7619 | 98.74 | 54.37 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.81 | 7.37 | 0.42 |
| 2| 852 | 25.44 | 8.77 | 0.46 |
| 3| 858 | 24.03 | 9.02 | 0.45 |
| 5| 1318 | 30.99 | 12.32 | 0.55 |
| 10| 1878 | 37.47 | 17.48 | 0.66 |
| 39| 6478 | 99.30 | 53.98 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 827 | 29.26 | 9.62 | 0.49 |
| 3| 1010 | 31.62 | 10.96 | 0.53 |
| 5| 1379 | 35.68 | 13.45 | 0.60 |
| 10| 2065 | 45.53 | 19.56 | 0.75 |
| 35| 5961 | 97.94 | 50.95 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.87 | 10.16 | 0.53 |
| 2| 864 | 36.60 | 11.61 | 0.57 |
| 3| 900 | 37.20 | 12.40 | 0.58 |
| 5| 1265 | 42.64 | 15.28 | 0.66 |
| 10| 2068 | 54.46 | 21.93 | 0.84 |
| 29| 4873 | 98.27 | 46.78 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.05 | 9.07 | 0.69 |
| 2| 5942 | 35.80 | 12.03 | 0.79 |
| 3| 5978 | 40.43 | 13.50 | 0.84 |
| 4| 6265 | 53.99 | 18.17 | 0.99 |
| 5| 6478 | 66.04 | 22.31 | 1.13 |
| 6| 6468 | 72.65 | 24.45 | 1.20 |
| 7| 6790 | 85.01 | 28.66 | 1.34 |
| 8| 6891 | 92.80 | 31.27 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1704 | 6850 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2216 | 7155 | 98.93 | 37.88 | 1.54 |

