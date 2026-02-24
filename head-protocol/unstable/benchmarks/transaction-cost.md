--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-24 05:48:08.817356266 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 227 | 862 | 50.83 | 14.62 | 0.70 |
| 5 | 285 | 969 | 59.16 | 16.97 | 0.79 |
| 6 | 339 | 1081 | 73.23 | 20.77 | 0.94 |
| 7 | 396 | 1196 | 86.75 | 24.44 | 1.08 |
| 8 | 451 | 1303 | 91.14 | 25.84 | 1.13 |
| 10 | 560 | 1525 | 97.22 | 28.21 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.29 | 7.69 | 0.48 |
| 2| 1977 | 26.58 | 9.01 | 0.52 |
| 3| 2084 | 26.87 | 9.75 | 0.53 |
| 5| 2337 | 30.08 | 11.98 | 0.58 |
| 10| 3056 | 38.86 | 17.75 | 0.73 |
| 40| 7746 | 98.33 | 54.30 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.80 | 7.37 | 0.42 |
| 2| 782 | 24.01 | 8.38 | 0.44 |
| 3| 920 | 25.10 | 9.32 | 0.46 |
| 5| 1284 | 31.25 | 12.38 | 0.55 |
| 10| 2087 | 43.05 | 19.01 | 0.73 |
| 41| 6762 | 98.18 | 55.03 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 27.47 | 8.46 | 0.46 |
| 2| 732 | 30.23 | 9.85 | 0.50 |
| 3| 915 | 32.72 | 11.23 | 0.54 |
| 5| 1216 | 37.06 | 13.79 | 0.60 |
| 10| 2053 | 47.96 | 20.21 | 0.77 |
| 36| 5911 | 97.50 | 51.44 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 817 | 35.92 | 11.40 | 0.56 |
| 3| 942 | 37.88 | 12.61 | 0.59 |
| 5| 1279 | 42.45 | 15.23 | 0.66 |
| 10| 2099 | 54.54 | 21.97 | 0.84 |
| 28| 4824 | 97.06 | 45.79 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.93 | 7.56 | 0.64 |
| 2| 5898 | 34.87 | 11.67 | 0.78 |
| 3| 6048 | 41.25 | 13.80 | 0.85 |
| 4| 6144 | 50.51 | 16.90 | 0.95 |
| 5| 6454 | 60.68 | 20.46 | 1.07 |
| 6| 6478 | 72.31 | 24.25 | 1.19 |
| 7| 6816 | 85.92 | 29.02 | 1.35 |
| 8| 6808 | 89.15 | 29.95 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

