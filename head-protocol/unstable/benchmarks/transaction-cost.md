--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-26 08:11:40.911453531 UTC |
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
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 29.64 | 9.36 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 226 | 862 | 47.94 | 13.93 | 0.68 |
| 5 | 280 | 969 | 59.33 | 17.02 | 0.79 |
| 6 | 338 | 1085 | 72.85 | 20.64 | 0.94 |
| 7 | 396 | 1192 | 81.17 | 23.15 | 1.03 |
| 8 | 450 | 1307 | 96.50 | 27.18 | 1.18 |
| 9 | 505 | 1418 | 95.39 | 27.43 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 23.92 | 7.60 | 0.48 |
| 2| 1993 | 26.62 | 9.02 | 0.52 |
| 3| 2104 | 28.39 | 10.16 | 0.55 |
| 5| 2458 | 31.95 | 12.51 | 0.61 |
| 10| 3204 | 41.17 | 18.41 | 0.76 |
| 42| 7885 | 99.76 | 56.05 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.80 | 7.37 | 0.41 |
| 2| 695 | 22.62 | 7.97 | 0.42 |
| 3| 1018 | 27.64 | 10.08 | 0.49 |
| 5| 1173 | 28.54 | 11.65 | 0.52 |
| 10| 2015 | 40.85 | 18.39 | 0.70 |
| 38| 6322 | 96.34 | 52.44 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 876 | 32.08 | 11.03 | 0.53 |
| 5| 1275 | 35.05 | 13.25 | 0.59 |
| 10| 2076 | 48.11 | 20.25 | 0.78 |
| 37| 6161 | 99.33 | 52.69 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 1032 | 38.59 | 12.82 | 0.60 |
| 5| 1346 | 43.27 | 15.47 | 0.67 |
| 10| 2116 | 55.25 | 22.18 | 0.85 |
| 29| 4884 | 97.74 | 46.62 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 26.92 | 9.05 | 0.69 |
| 2| 5897 | 34.80 | 11.66 | 0.77 |
| 3| 6096 | 42.57 | 14.28 | 0.87 |
| 4| 6126 | 49.38 | 16.50 | 0.94 |
| 5| 6478 | 64.73 | 21.81 | 1.12 |
| 6| 6491 | 71.90 | 24.14 | 1.19 |
| 7| 6568 | 76.65 | 25.77 | 1.24 |
| 8| 7005 | 93.56 | 31.56 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 567 | 6171 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

