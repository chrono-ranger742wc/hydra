--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-15 06:24:37.95558869 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 228 | 858 | 50.87 | 14.60 | 0.70 |
| 5 | 282 | 974 | 57.63 | 16.64 | 0.78 |
| 6 | 337 | 1081 | 74.80 | 21.14 | 0.95 |
| 7 | 395 | 1192 | 82.93 | 23.57 | 1.04 |
| 8 | 452 | 1303 | 81.20 | 23.56 | 1.03 |
| 9 | 506 | 1418 | 95.32 | 27.18 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1922 | 25.55 | 8.72 | 0.50 |
| 3| 2109 | 28.47 | 10.18 | 0.55 |
| 5| 2349 | 30.37 | 12.05 | 0.59 |
| 10| 3162 | 42.12 | 18.66 | 0.76 |
| 41| 7702 | 99.72 | 55.32 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 768 | 23.59 | 8.23 | 0.43 |
| 3| 964 | 27.03 | 9.88 | 0.48 |
| 5| 1252 | 30.79 | 12.27 | 0.54 |
| 10| 1822 | 35.51 | 16.89 | 0.64 |
| 42| 6749 | 99.77 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 804 | 30.98 | 10.08 | 0.51 |
| 3| 985 | 33.36 | 11.43 | 0.55 |
| 5| 1226 | 34.41 | 13.05 | 0.58 |
| 10| 2029 | 47.47 | 20.05 | 0.77 |
| 36| 5865 | 95.14 | 50.78 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 964 | 37.87 | 12.61 | 0.59 |
| 5| 1256 | 42.57 | 15.26 | 0.66 |
| 10| 2026 | 54.25 | 21.87 | 0.84 |
| 29| 4953 | 99.63 | 47.17 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.05 | 9.07 | 0.69 |
| 2| 5992 | 36.93 | 12.47 | 0.80 |
| 3| 6051 | 41.40 | 13.86 | 0.85 |
| 4| 6188 | 51.42 | 17.24 | 0.96 |
| 5| 6432 | 61.34 | 20.66 | 1.08 |
| 6| 6507 | 67.27 | 22.59 | 1.14 |
| 7| 6744 | 83.96 | 28.30 | 1.33 |
| 8| 6859 | 92.72 | 31.31 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2165 | 7127 | 96.00 | 36.77 | 1.50 |

