--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-29 06:07:40.372868227 UTC |
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
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 40.32 | 11.73 | 0.59 |
| 4 | 226 | 862 | 51.04 | 14.67 | 0.71 |
| 5 | 283 | 969 | 60.66 | 17.33 | 0.81 |
| 6 | 337 | 1081 | 68.01 | 19.52 | 0.89 |
| 7 | 393 | 1192 | 76.63 | 22.02 | 0.98 |
| 8 | 451 | 1303 | 87.76 | 25.18 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2101 | 28.39 | 10.16 | 0.55 |
| 5| 2411 | 32.44 | 12.63 | 0.61 |
| 10| 3176 | 41.99 | 18.63 | 0.76 |
| 39| 7753 | 99.65 | 54.04 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.81 | 7.37 | 0.42 |
| 2| 741 | 23.61 | 8.24 | 0.43 |
| 3| 925 | 26.63 | 9.79 | 0.48 |
| 5| 1312 | 31.00 | 12.32 | 0.55 |
| 10| 2171 | 42.85 | 18.96 | 0.73 |
| 40| 6704 | 99.48 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 877 | 29.86 | 9.81 | 0.50 |
| 3| 937 | 32.72 | 11.23 | 0.54 |
| 5| 1226 | 37.03 | 13.78 | 0.60 |
| 10| 2047 | 48.04 | 20.23 | 0.77 |
| 35| 5938 | 97.59 | 50.90 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 819 | 35.92 | 11.40 | 0.56 |
| 3| 1005 | 38.55 | 12.81 | 0.60 |
| 5| 1286 | 42.72 | 15.30 | 0.66 |
| 10| 1983 | 53.45 | 21.62 | 0.83 |
| 29| 4987 | 99.89 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.13 | 9.11 | 0.69 |
| 2| 5990 | 37.13 | 12.50 | 0.80 |
| 3| 6041 | 41.46 | 13.89 | 0.85 |
| 4| 6183 | 53.98 | 18.13 | 0.99 |
| 5| 6335 | 60.39 | 20.25 | 1.06 |
| 6| 6365 | 64.69 | 21.65 | 1.11 |
| 7| 6631 | 81.58 | 27.41 | 1.30 |
| 8| 6706 | 87.82 | 29.49 | 1.37 |
| 9| 6682 | 86.31 | 28.90 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.96 | 7.01 | 0.63 |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

