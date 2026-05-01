--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-01 07:02:39.227888146 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6645 | 18.52 | 5.84 | 0.63 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 635 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.96 | 12.60 | 0.63 |
| 4 | 225 | 858 | 52.10 | 14.90 | 0.72 |
| 5 | 282 | 969 | 62.57 | 17.82 | 0.83 |
| 6 | 337 | 1081 | 69.62 | 19.94 | 0.90 |
| 7 | 394 | 1192 | 86.86 | 24.43 | 1.08 |
| 8 | 450 | 1303 | 82.97 | 23.93 | 1.05 |
| 9 | 507 | 1418 | 94.59 | 27.23 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1928 | 25.47 | 8.70 | 0.50 |
| 3| 2118 | 28.17 | 10.11 | 0.54 |
| 5| 2319 | 29.93 | 11.94 | 0.58 |
| 10| 3046 | 38.69 | 17.71 | 0.72 |
| 40| 7707 | 98.71 | 54.40 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.54 | 7.30 | 0.41 |
| 2| 727 | 22.52 | 7.93 | 0.42 |
| 3| 883 | 25.13 | 9.32 | 0.46 |
| 5| 1292 | 31.06 | 12.34 | 0.55 |
| 10| 1899 | 36.59 | 17.20 | 0.65 |
| 44| 6822 | 99.87 | 57.47 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 855 | 29.86 | 9.81 | 0.50 |
| 3| 978 | 33.36 | 11.43 | 0.55 |
| 5| 1367 | 36.43 | 13.67 | 0.60 |
| 10| 2250 | 50.13 | 20.87 | 0.80 |
| 37| 5940 | 96.55 | 51.82 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.87 | 10.16 | 0.53 |
| 2| 830 | 35.85 | 11.38 | 0.56 |
| 3| 942 | 37.84 | 12.60 | 0.59 |
| 5| 1241 | 42.15 | 15.13 | 0.65 |
| 10| 2027 | 53.91 | 21.77 | 0.83 |
| 29| 4785 | 95.95 | 46.08 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.92 | 9.04 | 0.69 |
| 2| 5893 | 34.84 | 11.67 | 0.78 |
| 3| 5993 | 43.76 | 14.71 | 0.87 |
| 4| 6239 | 53.88 | 18.09 | 0.99 |
| 5| 6473 | 64.90 | 21.90 | 1.12 |
| 6| 6643 | 74.24 | 25.03 | 1.22 |
| 7| 6829 | 84.18 | 28.41 | 1.34 |
| 8| 6898 | 92.49 | 31.18 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 58 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1710 | 6856 | 81.11 | 30.83 | 1.33 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

