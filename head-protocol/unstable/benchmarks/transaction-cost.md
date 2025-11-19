--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-19 05:34:24.283416767 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.49 | 12.21 | 0.61 |
| 4 | 227 | 858 | 53.49 | 15.25 | 0.73 |
| 5 | 283 | 969 | 63.96 | 18.15 | 0.84 |
| 6 | 336 | 1081 | 69.42 | 19.85 | 0.90 |
| 7 | 392 | 1192 | 86.61 | 24.41 | 1.08 |
| 8 | 451 | 1303 | 94.20 | 26.68 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1974 | 26.91 | 9.08 | 0.52 |
| 3| 2101 | 27.94 | 10.05 | 0.54 |
| 5| 2359 | 31.49 | 12.36 | 0.60 |
| 10| 3130 | 40.82 | 18.31 | 0.75 |
| 42| 7753 | 98.15 | 55.57 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.80 | 7.37 | 0.42 |
| 2| 780 | 23.56 | 8.22 | 0.43 |
| 3| 933 | 26.86 | 9.84 | 0.48 |
| 5| 1346 | 32.52 | 12.73 | 0.56 |
| 10| 1948 | 38.61 | 17.77 | 0.68 |
| 40| 6564 | 98.17 | 54.34 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 848 | 29.22 | 9.61 | 0.49 |
| 3| 936 | 32.69 | 11.22 | 0.54 |
| 5| 1325 | 38.11 | 14.10 | 0.62 |
| 10| 2076 | 48.00 | 20.22 | 0.78 |
| 35| 5663 | 97.93 | 50.83 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.79 | 10.15 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 1033 | 38.51 | 12.80 | 0.60 |
| 5| 1271 | 42.64 | 15.28 | 0.66 |
| 10| 2048 | 54.73 | 22.01 | 0.84 |
| 30| 4934 | 99.65 | 47.76 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.13 | 9.09 | 0.69 |
| 2| 5878 | 34.99 | 11.71 | 0.78 |
| 3| 6070 | 42.22 | 14.20 | 0.86 |
| 4| 6358 | 55.71 | 18.82 | 1.02 |
| 5| 6452 | 63.90 | 21.52 | 1.11 |
| 6| 6603 | 72.91 | 24.54 | 1.21 |
| 7| 7047 | 87.08 | 29.57 | 1.38 |
| 8| 6887 | 86.90 | 29.38 | 1.37 |
| 9| 7069 | 97.84 | 32.96 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1141 | 6516 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

