--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 05:17:34.947616853 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.49 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 226 | 858 | 50.97 | 14.63 | 0.71 |
| 5 | 280 | 969 | 64.45 | 18.27 | 0.85 |
| 6 | 339 | 1081 | 69.91 | 20.01 | 0.91 |
| 7 | 397 | 1196 | 85.10 | 24.09 | 1.06 |
| 8 | 451 | 1303 | 94.46 | 26.69 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 26.86 | 9.75 | 0.53 |
| 5| 2353 | 30.49 | 12.08 | 0.59 |
| 10| 3202 | 41.88 | 18.60 | 0.76 |
| 42| 7829 | 99.80 | 56.04 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.84 | 7.39 | 0.42 |
| 2| 807 | 25.40 | 8.76 | 0.45 |
| 3| 983 | 26.68 | 9.79 | 0.48 |
| 5| 1211 | 29.54 | 11.94 | 0.53 |
| 10| 1986 | 38.34 | 17.70 | 0.68 |
| 41| 6747 | 99.71 | 55.44 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 824 | 29.26 | 9.62 | 0.49 |
| 3| 968 | 33.51 | 11.47 | 0.55 |
| 5| 1339 | 38.56 | 14.24 | 0.62 |
| 10| 2008 | 44.44 | 19.23 | 0.74 |
| 36| 6000 | 97.89 | 51.56 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 871 | 36.56 | 11.60 | 0.57 |
| 3| 1029 | 38.66 | 12.84 | 0.60 |
| 5| 1161 | 41.29 | 14.86 | 0.64 |
| 10| 2131 | 54.92 | 22.06 | 0.85 |
| 30| 4765 | 96.74 | 46.95 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.04 | 9.09 | 0.69 |
| 2| 5850 | 31.44 | 10.45 | 0.74 |
| 3| 6084 | 42.61 | 14.31 | 0.87 |
| 4| 6173 | 52.69 | 17.65 | 0.97 |
| 5| 6450 | 63.98 | 21.55 | 1.11 |
| 6| 6651 | 74.50 | 25.10 | 1.23 |
| 7| 6686 | 80.31 | 27.04 | 1.29 |
| 8| 6931 | 94.12 | 31.71 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.83 | 10.26 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2277 | 7193 | 99.84 | 38.30 | 1.55 |
| 10 | 39 | 2219 | 7158 | 99.56 | 38.10 | 1.54 |

