--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-10 05:01:24.101702463 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 171 | 747 | 43.57 | 12.47 | 0.63 |
| 4 | 226 | 862 | 49.36 | 14.29 | 0.69 |
| 5 | 283 | 969 | 61.21 | 17.53 | 0.81 |
| 6 | 338 | 1081 | 73.49 | 20.90 | 0.94 |
| 7 | 395 | 1192 | 72.10 | 20.89 | 0.94 |
| 8 | 450 | 1303 | 96.58 | 27.20 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 1998 | 26.39 | 8.96 | 0.52 |
| 3| 2018 | 26.24 | 9.56 | 0.52 |
| 5| 2385 | 31.37 | 12.33 | 0.60 |
| 10| 3139 | 40.66 | 18.27 | 0.75 |
| 41| 7612 | 95.49 | 54.17 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.39 | 0.42 |
| 2| 799 | 23.59 | 8.23 | 0.44 |
| 3| 952 | 26.56 | 9.77 | 0.48 |
| 5| 1283 | 31.12 | 12.36 | 0.55 |
| 10| 1951 | 38.68 | 17.79 | 0.68 |
| 40| 6248 | 95.37 | 53.49 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 830 | 29.26 | 9.62 | 0.49 |
| 3| 872 | 32.08 | 11.03 | 0.53 |
| 5| 1270 | 35.05 | 13.25 | 0.58 |
| 10| 2093 | 49.35 | 20.61 | 0.79 |
| 37| 6013 | 97.94 | 52.25 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 803 | 35.92 | 11.40 | 0.56 |
| 3| 1036 | 38.51 | 12.80 | 0.60 |
| 5| 1161 | 41.26 | 14.85 | 0.64 |
| 10| 2112 | 54.70 | 22.01 | 0.84 |
| 30| 4920 | 97.95 | 47.32 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.05 | 9.07 | 0.69 |
| 2| 5889 | 32.59 | 10.90 | 0.75 |
| 3| 5951 | 40.28 | 13.43 | 0.83 |
| 4| 6192 | 51.32 | 17.27 | 0.96 |
| 5| 6368 | 64.55 | 21.71 | 1.11 |
| 6| 6587 | 71.17 | 23.95 | 1.19 |
| 7| 6715 | 77.50 | 26.03 | 1.26 |
| 8| 7000 | 94.90 | 32.15 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 79.53 | 30.29 | 1.31 |
| 10 | 37 | 2106 | 7091 | 93.95 | 35.96 | 1.48 |

