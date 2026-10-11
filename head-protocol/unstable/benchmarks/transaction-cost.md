--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-11 11:11:29.881083145 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.99 | 4.13 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 28.90 | 9.10 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.62 | 12.26 | 0.62 |
| 4 | 227 | 862 | 48.19 | 13.98 | 0.68 |
| 5 | 282 | 969 | 57.71 | 16.66 | 0.78 |
| 6 | 339 | 1081 | 73.67 | 20.91 | 0.94 |
| 7 | 392 | 1192 | 82.67 | 23.47 | 1.04 |
| 8 | 449 | 1307 | 94.60 | 26.82 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.55 | 8.71 | 0.50 |
| 3| 2073 | 27.39 | 9.88 | 0.53 |
| 5| 2382 | 31.20 | 12.29 | 0.60 |
| 10| 2997 | 37.75 | 17.45 | 0.71 |
| 39| 7420 | 96.97 | 53.22 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.57 | 7.32 | 0.41 |
| 2| 752 | 23.58 | 8.23 | 0.43 |
| 3| 861 | 24.07 | 9.03 | 0.45 |
| 5| 1262 | 30.79 | 12.27 | 0.54 |
| 10| 2039 | 41.19 | 18.48 | 0.71 |
| 41| 6660 | 97.50 | 54.85 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.17 | 8.91 | 0.48 |
| 2| 843 | 31.58 | 10.26 | 0.52 |
| 3| 930 | 32.69 | 11.22 | 0.54 |
| 5| 1309 | 37.62 | 13.96 | 0.61 |
| 10| 1938 | 46.80 | 19.84 | 0.76 |
| 36| 5865 | 95.11 | 50.79 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 863 | 36.60 | 11.61 | 0.57 |
| 3| 956 | 37.91 | 12.62 | 0.59 |
| 5| 1268 | 42.53 | 15.25 | 0.66 |
| 10| 1963 | 53.35 | 21.59 | 0.82 |
| 29| 5045 | 98.78 | 46.96 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.13 | 9.09 | 0.69 |
| 2| 5846 | 31.48 | 10.47 | 0.74 |
| 3| 6093 | 44.93 | 15.10 | 0.89 |
| 4| 6385 | 56.72 | 19.22 | 1.03 |
| 5| 6530 | 65.59 | 22.07 | 1.13 |
| 6| 6513 | 69.80 | 23.43 | 1.17 |
| 7| 6560 | 77.90 | 26.15 | 1.26 |
| 8| 6918 | 93.24 | 31.42 | 1.43 |
| 9| 6899 | 93.17 | 31.28 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1709 | 6855 | 81.30 | 30.89 | 1.33 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

