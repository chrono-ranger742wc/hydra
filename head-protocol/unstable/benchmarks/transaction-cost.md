--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-14 08:46:57.659176269 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7650 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.62 | 12.25 | 0.62 |
| 4 | 226 | 858 | 53.37 | 15.22 | 0.73 |
| 5 | 283 | 969 | 61.33 | 17.56 | 0.82 |
| 6 | 340 | 1081 | 69.27 | 19.89 | 0.90 |
| 7 | 394 | 1192 | 84.75 | 23.96 | 1.06 |
| 8 | 451 | 1303 | 92.51 | 26.28 | 1.14 |
| 9 | 505 | 1414 | 95.92 | 27.43 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1979 | 26.92 | 9.08 | 0.52 |
| 3| 2068 | 27.10 | 9.81 | 0.53 |
| 5| 2281 | 28.86 | 11.64 | 0.57 |
| 10| 3219 | 42.06 | 18.66 | 0.77 |
| 39| 7584 | 99.21 | 53.86 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.77 | 7.37 | 0.42 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 828 | 24.13 | 9.04 | 0.45 |
| 5| 1140 | 28.11 | 11.49 | 0.51 |
| 10| 1953 | 38.89 | 17.87 | 0.68 |
| 42| 6722 | 96.48 | 55.20 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.51 | 8.47 | 0.46 |
| 2| 769 | 30.90 | 10.06 | 0.51 |
| 3| 898 | 30.15 | 10.52 | 0.51 |
| 5| 1322 | 38.41 | 14.20 | 0.62 |
| 10| 2214 | 47.19 | 20.05 | 0.77 |
| 37| 6065 | 97.64 | 52.17 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 873 | 36.48 | 11.58 | 0.57 |
| 3| 1018 | 38.51 | 12.80 | 0.60 |
| 5| 1262 | 42.97 | 15.38 | 0.66 |
| 10| 1985 | 53.35 | 21.59 | 0.82 |
| 29| 4750 | 97.61 | 46.55 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5946 | 35.93 | 12.06 | 0.79 |
| 3| 6047 | 41.45 | 13.85 | 0.85 |
| 4| 6260 | 53.84 | 18.10 | 0.99 |
| 5| 6351 | 60.85 | 20.44 | 1.07 |
| 6| 6400 | 64.78 | 21.75 | 1.11 |
| 7| 6759 | 81.18 | 27.38 | 1.30 |
| 8| 6836 | 91.84 | 30.98 | 1.42 |
| 9| 6957 | 98.62 | 33.10 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.26 | 6.78 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.21 | 10.04 | 0.71 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2272 | 7188 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

