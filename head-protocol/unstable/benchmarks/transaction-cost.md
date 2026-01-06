--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-06 05:52:27.376822624 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.55 | 9.33 | 0.79 |
| 43| 14282 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 228 | 858 | 49.87 | 14.41 | 0.69 |
| 5 | 283 | 974 | 55.92 | 16.20 | 0.76 |
| 6 | 339 | 1081 | 66.19 | 19.09 | 0.87 |
| 7 | 394 | 1192 | 83.27 | 23.66 | 1.05 |
| 8 | 449 | 1303 | 92.46 | 26.31 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.43 | 8.40 | 0.49 |
| 3| 2060 | 27.23 | 9.84 | 0.53 |
| 5| 2366 | 31.16 | 12.28 | 0.59 |
| 10| 3083 | 40.08 | 18.09 | 0.74 |
| 39| 7571 | 97.27 | 53.35 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.37 | 0.41 |
| 2| 804 | 25.53 | 8.79 | 0.46 |
| 3| 982 | 28.15 | 10.20 | 0.49 |
| 5| 1100 | 27.07 | 11.21 | 0.50 |
| 10| 1913 | 37.44 | 17.44 | 0.66 |
| 41| 6563 | 96.20 | 54.42 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 29.13 | 8.90 | 0.48 |
| 2| 782 | 30.91 | 10.06 | 0.51 |
| 3| 964 | 33.39 | 11.43 | 0.54 |
| 5| 1222 | 34.37 | 13.04 | 0.58 |
| 10| 1934 | 46.61 | 19.79 | 0.75 |
| 35| 5632 | 92.70 | 49.40 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 801 | 35.85 | 11.38 | 0.56 |
| 3| 1032 | 39.34 | 13.05 | 0.61 |
| 5| 1331 | 43.39 | 15.50 | 0.67 |
| 10| 2059 | 54.66 | 22.00 | 0.84 |
| 29| 4884 | 97.84 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.16 | 9.12 | 0.69 |
| 2| 5901 | 34.94 | 11.69 | 0.78 |
| 3| 6171 | 45.58 | 15.39 | 0.90 |
| 4| 6216 | 51.63 | 17.34 | 0.97 |
| 5| 6407 | 63.66 | 21.44 | 1.10 |
| 6| 6434 | 67.01 | 22.48 | 1.14 |
| 7| 6619 | 78.17 | 26.23 | 1.26 |
| 8| 6832 | 93.65 | 31.55 | 1.43 |
| 9| 6735 | 90.07 | 30.21 | 1.39 |
| 10| 6860 | 93.48 | 31.31 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |

