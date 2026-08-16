--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-16 05:06:16.253577536 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 15.14 | 4.81 | 0.58 |
| 5| 6638 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 42.46 | 12.22 | 0.61 |
| 4 | 228 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 282 | 969 | 60.87 | 17.38 | 0.81 |
| 6 | 337 | 1081 | 71.57 | 20.44 | 0.92 |
| 7 | 394 | 1192 | 75.01 | 21.68 | 0.96 |
| 8 | 450 | 1307 | 86.87 | 24.82 | 1.09 |
| 9 | 506 | 1418 | 94.08 | 27.00 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1968 | 26.55 | 9.00 | 0.52 |
| 3| 2074 | 27.31 | 9.86 | 0.53 |
| 5| 2373 | 31.52 | 12.37 | 0.60 |
| 10| 3309 | 44.04 | 19.21 | 0.79 |
| 39| 7533 | 96.35 | 53.10 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.53 | 7.29 | 0.41 |
| 2| 790 | 25.43 | 8.77 | 0.45 |
| 3| 838 | 24.02 | 9.03 | 0.45 |
| 5| 1252 | 31.10 | 12.34 | 0.55 |
| 10| 2094 | 43.26 | 19.06 | 0.73 |
| 43| 6615 | 97.40 | 56.16 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.79 | 8.25 | 0.45 |
| 2| 770 | 30.91 | 10.06 | 0.51 |
| 3| 962 | 30.98 | 10.76 | 0.52 |
| 5| 1328 | 35.65 | 13.44 | 0.59 |
| 10| 2154 | 50.04 | 20.84 | 0.80 |
| 36| 6084 | 98.84 | 51.86 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.79 | 10.15 | 0.53 |
| 2| 835 | 35.92 | 11.40 | 0.56 |
| 3| 963 | 37.91 | 12.62 | 0.59 |
| 5| 1317 | 43.36 | 15.49 | 0.67 |
| 10| 2054 | 54.12 | 21.84 | 0.84 |
| 29| 4974 | 99.70 | 47.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5828 | 26.96 | 9.06 | 0.69 |
| 2| 5984 | 37.13 | 12.51 | 0.80 |
| 3| 6117 | 44.72 | 15.06 | 0.89 |
| 4| 6330 | 55.85 | 18.89 | 1.02 |
| 5| 6365 | 60.08 | 20.19 | 1.06 |
| 6| 6679 | 75.37 | 25.51 | 1.24 |
| 7| 6779 | 84.76 | 28.62 | 1.34 |
| 8| 6901 | 91.53 | 30.86 | 1.42 |
| 9| 6916 | 95.16 | 31.90 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 568 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 39 | 2218 | 7157 | 98.93 | 37.88 | 1.54 |

