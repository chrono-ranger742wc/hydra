--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-24 06:11:45.912946642 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.21 | 11.69 | 0.59 |
| 4 | 227 | 862 | 51.28 | 14.78 | 0.71 |
| 5 | 282 | 969 | 60.05 | 17.28 | 0.80 |
| 6 | 337 | 1081 | 73.55 | 20.92 | 0.94 |
| 7 | 394 | 1192 | 74.43 | 21.45 | 0.96 |
| 8 | 451 | 1303 | 82.01 | 23.75 | 1.04 |
| 9 | 505 | 1414 | 92.55 | 26.70 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.00 | 7.62 | 0.48 |
| 2| 1885 | 24.85 | 8.50 | 0.50 |
| 3| 2195 | 29.47 | 10.46 | 0.56 |
| 5| 2427 | 31.95 | 12.49 | 0.61 |
| 10| 3218 | 42.01 | 18.64 | 0.77 |
| 40| 7704 | 98.88 | 54.47 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.80 | 7.36 | 0.42 |
| 2| 750 | 24.04 | 8.38 | 0.44 |
| 3| 880 | 25.51 | 9.46 | 0.46 |
| 5| 1186 | 29.97 | 12.04 | 0.53 |
| 10| 1997 | 39.28 | 17.97 | 0.69 |
| 42| 6795 | 99.80 | 56.13 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.79 | 8.25 | 0.45 |
| 2| 833 | 31.62 | 10.28 | 0.52 |
| 3| 920 | 32.72 | 11.23 | 0.54 |
| 5| 1253 | 35.12 | 13.27 | 0.58 |
| 10| 2085 | 47.69 | 20.12 | 0.77 |
| 37| 6175 | 99.67 | 52.79 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 817 | 35.89 | 11.39 | 0.56 |
| 3| 1005 | 38.59 | 12.82 | 0.60 |
| 5| 1211 | 41.89 | 15.05 | 0.65 |
| 10| 2104 | 55.17 | 22.16 | 0.85 |
| 30| 4794 | 97.43 | 47.13 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.08 | 9.08 | 0.69 |
| 2| 5895 | 34.87 | 11.67 | 0.78 |
| 3| 6115 | 45.69 | 15.44 | 0.90 |
| 4| 6236 | 54.24 | 18.23 | 0.99 |
| 5| 6395 | 60.23 | 20.31 | 1.06 |
| 6| 6539 | 71.29 | 24.02 | 1.19 |
| 7| 6528 | 77.81 | 26.08 | 1.25 |
| 8| 6909 | 90.67 | 30.53 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1710 | 6857 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

