--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-17 06:27:05.898951729 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.29 | 11.92 | 0.60 |
| 4 | 226 | 858 | 48.50 | 14.11 | 0.68 |
| 5 | 282 | 969 | 64.23 | 18.22 | 0.84 |
| 6 | 337 | 1081 | 71.46 | 20.38 | 0.92 |
| 7 | 395 | 1196 | 82.60 | 23.41 | 1.04 |
| 8 | 450 | 1303 | 90.45 | 25.83 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.29 | 7.69 | 0.48 |
| 2| 1984 | 26.47 | 8.98 | 0.52 |
| 3| 2114 | 28.06 | 10.08 | 0.54 |
| 5| 2366 | 31.44 | 12.35 | 0.60 |
| 10| 3126 | 40.55 | 18.24 | 0.75 |
| 41| 7763 | 99.92 | 55.41 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.77 | 7.36 | 0.42 |
| 2| 747 | 24.27 | 8.45 | 0.44 |
| 3| 861 | 24.07 | 9.03 | 0.45 |
| 5| 1309 | 31.06 | 12.34 | 0.55 |
| 10| 1915 | 38.14 | 17.65 | 0.67 |
| 41| 6656 | 99.84 | 55.47 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 824 | 31.62 | 10.27 | 0.52 |
| 3| 914 | 32.68 | 11.22 | 0.54 |
| 5| 1235 | 34.26 | 13.01 | 0.58 |
| 10| 2006 | 47.63 | 20.10 | 0.77 |
| 35| 5940 | 97.85 | 50.95 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.79 | 10.15 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 999 | 38.55 | 12.81 | 0.60 |
| 5| 1321 | 43.28 | 15.47 | 0.67 |
| 10| 2108 | 54.57 | 21.97 | 0.84 |
| 29| 4943 | 98.98 | 47.01 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.05 | 9.08 | 0.69 |
| 2| 5964 | 35.91 | 12.05 | 0.79 |
| 3| 6082 | 44.78 | 15.08 | 0.89 |
| 4| 6288 | 56.50 | 19.07 | 1.02 |
| 5| 6366 | 63.87 | 21.53 | 1.10 |
| 6| 6558 | 74.44 | 25.11 | 1.22 |
| 7| 6558 | 75.46 | 25.26 | 1.23 |
| 8| 6772 | 86.00 | 28.91 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2217 | 7156 | 99.12 | 37.95 | 1.54 |

