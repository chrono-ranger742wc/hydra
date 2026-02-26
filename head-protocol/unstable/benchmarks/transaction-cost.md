--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-26 05:46:58.575666802 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 227 | 858 | 48.19 | 13.98 | 0.68 |
| 5 | 283 | 969 | 61.22 | 17.50 | 0.81 |
| 6 | 338 | 1081 | 63.84 | 18.51 | 0.85 |
| 7 | 394 | 1196 | 80.97 | 23.06 | 1.02 |
| 8 | 449 | 1303 | 83.67 | 24.16 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.37 | 7.71 | 0.48 |
| 2| 1975 | 26.47 | 8.98 | 0.52 |
| 3| 2012 | 25.95 | 9.49 | 0.52 |
| 5| 2500 | 33.24 | 12.86 | 0.62 |
| 10| 3096 | 39.84 | 18.03 | 0.74 |
| 40| 7476 | 95.04 | 53.39 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.80 | 7.38 | 0.42 |
| 2| 755 | 24.27 | 8.45 | 0.44 |
| 3| 903 | 25.79 | 9.53 | 0.47 |
| 5| 1219 | 30.05 | 12.05 | 0.53 |
| 10| 2085 | 42.31 | 18.80 | 0.72 |
| 39| 6485 | 96.94 | 53.32 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.47 | 8.46 | 0.46 |
| 2| 839 | 29.19 | 9.60 | 0.49 |
| 3| 1008 | 31.62 | 10.96 | 0.53 |
| 5| 1206 | 36.35 | 13.57 | 0.59 |
| 10| 1941 | 46.61 | 19.79 | 0.76 |
| 37| 6071 | 99.90 | 52.80 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.14 | 11.16 | 0.55 |
| 3| 994 | 38.66 | 12.84 | 0.60 |
| 5| 1261 | 42.60 | 15.27 | 0.66 |
| 10| 2145 | 54.99 | 22.10 | 0.85 |
| 29| 4858 | 97.74 | 46.64 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.08 | 9.09 | 0.69 |
| 2| 5822 | 31.60 | 10.51 | 0.74 |
| 3| 6170 | 45.77 | 15.43 | 0.90 |
| 4| 6099 | 46.95 | 15.67 | 0.91 |
| 5| 6394 | 64.12 | 21.56 | 1.11 |
| 6| 6584 | 69.96 | 23.59 | 1.18 |
| 7| 6530 | 75.38 | 25.29 | 1.23 |
| 8| 6947 | 93.70 | 31.64 | 1.44 |
| 9| 6838 | 94.95 | 31.93 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

