--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 06:01:59.18917801 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 639 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 43.63 | 12.50 | 0.63 |
| 4 | 228 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 285 | 974 | 57.59 | 16.63 | 0.78 |
| 6 | 336 | 1081 | 64.26 | 18.69 | 0.85 |
| 7 | 393 | 1192 | 76.03 | 21.83 | 0.97 |
| 8 | 451 | 1303 | 96.59 | 27.29 | 1.18 |
| 9 | 506 | 1414 | 97.63 | 27.73 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1929 | 25.92 | 8.80 | 0.51 |
| 3| 2150 | 28.31 | 10.14 | 0.55 |
| 5| 2343 | 30.04 | 11.97 | 0.58 |
| 10| 3060 | 40.01 | 18.07 | 0.74 |
| 37| 7166 | 90.96 | 50.27 | 1.56 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 795 | 23.59 | 8.23 | 0.44 |
| 3| 897 | 25.72 | 9.52 | 0.47 |
| 5| 1300 | 31.06 | 12.34 | 0.55 |
| 10| 1981 | 39.78 | 18.10 | 0.69 |
| 40| 6541 | 98.94 | 54.55 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.51 | 9.39 | 0.48 |
| 3| 1028 | 31.58 | 10.95 | 0.53 |
| 5| 1252 | 35.12 | 13.27 | 0.58 |
| 10| 2092 | 48.34 | 20.31 | 0.78 |
| 34| 5371 | 89.40 | 47.80 | 1.45 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.89 | 11.39 | 0.56 |
| 3| 942 | 37.84 | 12.60 | 0.59 |
| 5| 1326 | 43.43 | 15.51 | 0.67 |
| 10| 2098 | 54.38 | 21.91 | 0.84 |
| 29| 4735 | 95.98 | 46.11 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 26.97 | 9.06 | 0.69 |
| 2| 5946 | 35.96 | 12.09 | 0.79 |
| 3| 6024 | 43.98 | 14.72 | 0.88 |
| 4| 6246 | 55.14 | 18.60 | 1.00 |
| 5| 6208 | 54.84 | 18.28 | 1.00 |
| 6| 6716 | 72.23 | 24.37 | 1.20 |
| 7| 6806 | 81.97 | 27.63 | 1.31 |
| 8| 6864 | 94.01 | 31.77 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.82 | 6.63 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.44 | 36.92 | 1.51 |

