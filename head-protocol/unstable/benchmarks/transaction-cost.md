--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-06 07:03:51.011814507 UTC |
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
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.77 | 12.52 | 0.63 |
| 4 | 225 | 858 | 54.27 | 15.49 | 0.74 |
| 5 | 284 | 969 | 56.32 | 16.30 | 0.77 |
| 6 | 341 | 1081 | 72.06 | 20.56 | 0.93 |
| 7 | 395 | 1192 | 72.18 | 20.99 | 0.94 |
| 8 | 451 | 1303 | 87.44 | 25.01 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1934 | 25.84 | 8.78 | 0.51 |
| 3| 2089 | 27.02 | 9.79 | 0.53 |
| 5| 2346 | 30.30 | 12.03 | 0.59 |
| 10| 3180 | 40.84 | 18.31 | 0.75 |
| 39| 7454 | 95.98 | 52.96 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.39 | 0.41 |
| 2| 703 | 22.55 | 7.95 | 0.42 |
| 3| 835 | 24.06 | 9.03 | 0.45 |
| 5| 1304 | 31.04 | 12.34 | 0.55 |
| 10| 2032 | 39.76 | 18.09 | 0.69 |
| 40| 6735 | 99.88 | 54.86 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 716 | 27.54 | 8.47 | 0.47 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 948 | 30.82 | 10.73 | 0.52 |
| 5| 1247 | 37.06 | 13.78 | 0.60 |
| 10| 2063 | 48.56 | 20.38 | 0.78 |
| 33| 5988 | 98.28 | 49.82 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 867 | 36.56 | 11.60 | 0.57 |
| 3| 950 | 37.84 | 12.60 | 0.59 |
| 5| 1333 | 43.27 | 15.47 | 0.67 |
| 10| 2112 | 55.55 | 22.26 | 0.85 |
| 30| 4949 | 98.70 | 47.54 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.09 | 9.09 | 0.69 |
| 2| 6045 | 37.05 | 12.49 | 0.81 |
| 3| 6166 | 45.85 | 15.45 | 0.90 |
| 4| 6264 | 55.07 | 18.57 | 1.00 |
| 5| 6494 | 64.33 | 21.74 | 1.11 |
| 6| 6741 | 76.68 | 25.97 | 1.25 |
| 7| 6604 | 75.47 | 25.33 | 1.23 |
| 8| 6930 | 92.34 | 31.13 | 1.43 |
| 9| 6965 | 95.05 | 32.02 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.42 | 10.80 | 0.74 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 37 | 2108 | 7093 | 95.28 | 36.42 | 1.49 |

