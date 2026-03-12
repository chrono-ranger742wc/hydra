--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-12 05:38:54.538839531 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.88 | 4.72 | 0.58 |
| 5| 6640 | 19.26 | 6.10 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.83 | 12.57 | 0.63 |
| 4 | 226 | 858 | 54.11 | 15.43 | 0.74 |
| 5 | 283 | 969 | 57.98 | 16.70 | 0.78 |
| 6 | 339 | 1081 | 71.55 | 20.40 | 0.92 |
| 7 | 393 | 1192 | 82.97 | 23.58 | 1.04 |
| 8 | 450 | 1303 | 89.69 | 25.55 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1932 | 25.92 | 8.80 | 0.51 |
| 3| 2123 | 27.93 | 10.05 | 0.54 |
| 5| 2419 | 31.88 | 12.49 | 0.60 |
| 10| 3189 | 41.60 | 18.53 | 0.76 |
| 40| 7605 | 99.10 | 54.50 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 776 | 23.55 | 8.22 | 0.43 |
| 3| 902 | 25.72 | 9.52 | 0.47 |
| 5| 1270 | 29.97 | 12.05 | 0.54 |
| 10| 2008 | 40.61 | 18.35 | 0.70 |
| 39| 6108 | 90.27 | 51.45 | 1.52 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.50 | 8.46 | 0.46 |
| 2| 804 | 29.26 | 9.62 | 0.49 |
| 3| 992 | 33.51 | 11.46 | 0.55 |
| 5| 1275 | 34.97 | 13.23 | 0.58 |
| 10| 2013 | 45.13 | 19.42 | 0.74 |
| 35| 5698 | 93.53 | 49.64 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 900 | 37.13 | 12.38 | 0.58 |
| 5| 1358 | 43.99 | 15.69 | 0.68 |
| 10| 1915 | 52.60 | 21.37 | 0.81 |
| 28| 4939 | 98.20 | 46.15 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.16 | 9.13 | 0.69 |
| 2| 6024 | 37.01 | 12.47 | 0.80 |
| 3| 6111 | 44.94 | 15.11 | 0.89 |
| 4| 6356 | 56.37 | 19.01 | 1.02 |
| 5| 6565 | 65.36 | 22.15 | 1.13 |
| 6| 6432 | 70.98 | 23.84 | 1.18 |
| 7| 6799 | 84.30 | 28.54 | 1.34 |
| 8| 6970 | 95.00 | 32.07 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2222 | 7161 | 99.82 | 38.19 | 1.55 |

