--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-25 05:49:06.082108528 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.86 | 4.71 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.49 | 9.31 | 0.79 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 169 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 226 | 858 | 53.80 | 15.36 | 0.73 |
| 5 | 282 | 969 | 56.38 | 16.31 | 0.77 |
| 6 | 339 | 1081 | 67.78 | 19.42 | 0.89 |
| 7 | 395 | 1192 | 74.89 | 21.65 | 0.96 |
| 8 | 451 | 1303 | 92.56 | 26.33 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.40 | 8.39 | 0.49 |
| 3| 2053 | 27.39 | 9.88 | 0.53 |
| 5| 2394 | 31.18 | 12.28 | 0.60 |
| 10| 3119 | 39.59 | 17.97 | 0.74 |
| 39| 7558 | 96.83 | 53.23 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 759 | 24.35 | 8.46 | 0.44 |
| 3| 857 | 24.07 | 9.03 | 0.45 |
| 5| 1194 | 28.99 | 11.76 | 0.52 |
| 10| 2016 | 39.77 | 18.11 | 0.69 |
| 42| 6575 | 97.76 | 55.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 914 | 32.64 | 11.21 | 0.54 |
| 5| 1242 | 36.99 | 13.77 | 0.60 |
| 10| 1934 | 43.33 | 18.90 | 0.72 |
| 36| 5929 | 97.18 | 51.35 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.83 | 10.15 | 0.53 |
| 2| 853 | 36.64 | 11.62 | 0.57 |
| 3| 1029 | 39.34 | 13.05 | 0.61 |
| 5| 1260 | 42.68 | 15.29 | 0.66 |
| 10| 2161 | 55.51 | 22.26 | 0.85 |
| 29| 4910 | 98.93 | 47.00 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 6001 | 37.00 | 12.48 | 0.80 |
| 3| 6110 | 44.51 | 14.99 | 0.89 |
| 4| 6202 | 54.28 | 18.24 | 0.99 |
| 5| 6398 | 61.50 | 20.67 | 1.08 |
| 6| 6617 | 71.78 | 24.13 | 1.20 |
| 7| 6690 | 84.17 | 28.40 | 1.33 |
| 8| 7024 | 96.31 | 32.63 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

