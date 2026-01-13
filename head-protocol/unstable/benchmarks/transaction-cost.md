--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-13 05:07:42.300772411 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.88 | 9.10 | 0.79 |
| 43| 14279 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 42.38 | 12.19 | 0.61 |
| 4 | 226 | 862 | 53.21 | 15.16 | 0.73 |
| 5 | 281 | 969 | 58.12 | 16.82 | 0.78 |
| 6 | 340 | 1081 | 66.41 | 19.25 | 0.87 |
| 7 | 393 | 1192 | 86.88 | 24.43 | 1.08 |
| 8 | 449 | 1307 | 85.22 | 24.47 | 1.07 |
| 9 | 507 | 1414 | 92.68 | 26.89 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1923 | 25.39 | 8.68 | 0.50 |
| 3| 2074 | 26.98 | 9.78 | 0.53 |
| 5| 2381 | 31.61 | 12.39 | 0.60 |
| 10| 3283 | 42.70 | 18.84 | 0.78 |
| 41| 7558 | 95.75 | 54.24 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.54 | 7.31 | 0.41 |
| 2| 770 | 23.98 | 8.37 | 0.44 |
| 3| 904 | 25.85 | 9.55 | 0.47 |
| 5| 1215 | 29.19 | 11.80 | 0.52 |
| 10| 1944 | 38.05 | 17.61 | 0.67 |
| 43| 6700 | 97.66 | 56.19 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.13 | 8.90 | 0.48 |
| 2| 891 | 29.90 | 9.82 | 0.50 |
| 3| 960 | 30.90 | 10.74 | 0.52 |
| 5| 1397 | 36.20 | 13.61 | 0.60 |
| 10| 1979 | 44.19 | 19.15 | 0.73 |
| 36| 5558 | 92.45 | 49.93 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 853 | 36.48 | 11.58 | 0.57 |
| 3| 971 | 37.87 | 12.61 | 0.59 |
| 5| 1273 | 42.53 | 15.25 | 0.66 |
| 10| 2149 | 55.37 | 22.21 | 0.85 |
| 30| 5028 | 99.67 | 47.83 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 5950 | 35.80 | 12.02 | 0.79 |
| 3| 5926 | 36.85 | 12.22 | 0.80 |
| 4| 6267 | 51.18 | 17.19 | 0.96 |
| 5| 6411 | 64.05 | 21.59 | 1.11 |
| 6| 6363 | 65.34 | 21.91 | 1.12 |
| 7| 6660 | 78.11 | 26.28 | 1.26 |
| 8| 6792 | 88.78 | 29.88 | 1.38 |
| 9| 6890 | 99.51 | 33.58 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 61.31 | 22.98 | 1.10 |
| 10 | 30 | 1710 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.86 | 37.86 | 1.54 |

