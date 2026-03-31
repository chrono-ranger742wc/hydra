--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-31 06:08:34.910079484 UTC |
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
| 1| 5834 | 11.12 | 3.55 | 0.52 |
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7648 | 28.81 | 9.07 | 0.79 |
| 43| 14286 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 43.72 | 12.52 | 0.63 |
| 4 | 228 | 858 | 50.54 | 14.55 | 0.70 |
| 5 | 282 | 969 | 64.53 | 18.29 | 0.85 |
| 6 | 340 | 1081 | 66.24 | 19.10 | 0.87 |
| 7 | 394 | 1192 | 80.11 | 22.85 | 1.01 |
| 8 | 452 | 1303 | 80.44 | 23.28 | 1.03 |
| 9 | 504 | 1414 | 96.42 | 27.56 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1943 | 25.80 | 8.77 | 0.51 |
| 3| 2086 | 27.32 | 9.86 | 0.53 |
| 5| 2361 | 30.96 | 12.23 | 0.59 |
| 10| 3246 | 43.14 | 18.95 | 0.78 |
| 39| 7415 | 95.41 | 52.83 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.81 | 7.37 | 0.42 |
| 2| 855 | 25.14 | 8.70 | 0.45 |
| 3| 838 | 24.13 | 9.06 | 0.45 |
| 5| 1164 | 28.81 | 11.71 | 0.52 |
| 10| 2018 | 39.65 | 18.07 | 0.69 |
| 41| 6638 | 99.13 | 55.26 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 29.13 | 8.90 | 0.48 |
| 2| 817 | 29.18 | 9.60 | 0.49 |
| 3| 1026 | 31.58 | 10.95 | 0.53 |
| 5| 1361 | 36.32 | 13.64 | 0.60 |
| 10| 1928 | 46.05 | 19.62 | 0.75 |
| 36| 5834 | 97.23 | 51.37 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 1012 | 38.55 | 12.81 | 0.60 |
| 5| 1278 | 42.65 | 15.28 | 0.66 |
| 10| 2067 | 54.78 | 22.02 | 0.84 |
| 29| 4895 | 97.48 | 46.54 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.07 | 0.69 |
| 2| 6027 | 37.12 | 12.50 | 0.81 |
| 3| 6160 | 45.88 | 15.46 | 0.90 |
| 4| 6291 | 54.77 | 18.47 | 1.00 |
| 5| 6450 | 61.75 | 20.77 | 1.08 |
| 6| 6400 | 65.04 | 21.73 | 1.11 |
| 7| 6848 | 85.83 | 28.99 | 1.35 |
| 8| 6868 | 92.00 | 30.97 | 1.42 |
| 9| 6998 | 98.60 | 33.26 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6173 | 40.13 | 14.67 | 0.85 |
| 10 | 30 | 1709 | 6856 | 79.34 | 30.22 | 1.31 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2160 | 7122 | 96.44 | 36.92 | 1.51 |

