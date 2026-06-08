--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-08 09:28:17.730766399 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6645 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.25 | 11.69 | 0.59 |
| 4 | 227 | 858 | 52.78 | 15.16 | 0.72 |
| 5 | 284 | 969 | 64.13 | 18.26 | 0.84 |
| 6 | 338 | 1081 | 66.12 | 19.10 | 0.87 |
| 7 | 394 | 1192 | 84.59 | 23.88 | 1.06 |
| 8 | 448 | 1303 | 79.65 | 23.08 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.00 | 7.62 | 0.48 |
| 2| 1943 | 25.39 | 8.68 | 0.50 |
| 3| 2057 | 27.35 | 9.87 | 0.53 |
| 5| 2445 | 32.44 | 12.63 | 0.61 |
| 10| 3185 | 41.36 | 18.46 | 0.76 |
| 40| 7642 | 99.06 | 54.48 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.80 | 7.37 | 0.42 |
| 2| 804 | 25.20 | 8.70 | 0.45 |
| 3| 903 | 25.03 | 9.30 | 0.46 |
| 5| 1223 | 29.90 | 12.01 | 0.53 |
| 10| 2182 | 42.59 | 18.90 | 0.73 |
| 43| 6846 | 98.78 | 56.53 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.09 | 8.89 | 0.48 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 1055 | 32.33 | 11.18 | 0.54 |
| 5| 1334 | 35.83 | 13.49 | 0.60 |
| 10| 1874 | 45.94 | 19.59 | 0.75 |
| 35| 5981 | 97.26 | 50.78 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.88 | 11.39 | 0.56 |
| 3| 1031 | 38.59 | 12.82 | 0.60 |
| 5| 1351 | 43.28 | 15.47 | 0.67 |
| 10| 2085 | 54.54 | 21.97 | 0.84 |
| 29| 4985 | 99.32 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.05 | 9.07 | 0.69 |
| 2| 6062 | 36.72 | 12.40 | 0.80 |
| 3| 6098 | 44.84 | 15.07 | 0.89 |
| 4| 6160 | 50.70 | 17.02 | 0.95 |
| 5| 6383 | 64.81 | 21.82 | 1.11 |
| 6| 6532 | 69.43 | 23.34 | 1.17 |
| 7| 6792 | 77.32 | 26.15 | 1.26 |
| 8| 7030 | 91.87 | 31.01 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

