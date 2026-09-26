--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-26 09:44:37.149143466 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 43.92 | 12.57 | 0.63 |
| 4 | 227 | 858 | 50.89 | 14.63 | 0.70 |
| 5 | 284 | 969 | 62.46 | 17.79 | 0.83 |
| 6 | 337 | 1085 | 71.30 | 20.30 | 0.92 |
| 7 | 395 | 1192 | 86.63 | 24.37 | 1.08 |
| 8 | 452 | 1307 | 86.52 | 24.78 | 1.09 |
| 9 | 506 | 1414 | 91.19 | 26.36 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.00 | 7.62 | 0.48 |
| 2| 1926 | 25.39 | 8.67 | 0.50 |
| 3| 2106 | 28.10 | 10.09 | 0.54 |
| 5| 2377 | 30.93 | 12.22 | 0.59 |
| 10| 3260 | 43.05 | 18.93 | 0.78 |
| 38| 7562 | 99.77 | 53.36 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 769 | 23.98 | 8.37 | 0.44 |
| 3| 934 | 26.16 | 9.61 | 0.47 |
| 5| 1269 | 30.83 | 12.28 | 0.54 |
| 10| 2153 | 43.39 | 19.13 | 0.73 |
| 41| 6564 | 95.74 | 54.36 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.51 | 8.47 | 0.46 |
| 2| 820 | 29.19 | 9.60 | 0.49 |
| 3| 944 | 30.86 | 10.73 | 0.52 |
| 5| 1330 | 35.83 | 13.49 | 0.60 |
| 10| 2165 | 46.53 | 19.87 | 0.76 |
| 35| 6001 | 96.66 | 50.63 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.83 | 10.16 | 0.53 |
| 2| 855 | 36.14 | 11.47 | 0.56 |
| 3| 1004 | 38.63 | 12.83 | 0.60 |
| 5| 1213 | 41.93 | 15.06 | 0.65 |
| 10| 2055 | 54.09 | 21.82 | 0.83 |
| 28| 4604 | 94.53 | 45.03 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5908 | 32.64 | 10.90 | 0.75 |
| 3| 6074 | 44.92 | 15.11 | 0.89 |
| 4| 6107 | 49.11 | 16.45 | 0.93 |
| 5| 6435 | 63.82 | 21.50 | 1.10 |
| 6| 6440 | 69.55 | 23.34 | 1.16 |
| 7| 6854 | 84.15 | 28.41 | 1.34 |
| 8| 6850 | 92.57 | 31.19 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2216 | 7155 | 98.05 | 37.58 | 1.53 |

