--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-10 08:41:03.145283047 UTC |
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
| 1| 5834 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 39.81 | 11.57 | 0.59 |
| 4 | 227 | 858 | 54.11 | 15.43 | 0.74 |
| 5 | 283 | 969 | 56.02 | 16.25 | 0.76 |
| 6 | 338 | 1081 | 66.17 | 19.08 | 0.87 |
| 7 | 395 | 1192 | 80.90 | 23.09 | 1.02 |
| 8 | 450 | 1307 | 83.19 | 24.04 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1916 | 25.55 | 8.71 | 0.50 |
| 3| 2117 | 28.13 | 10.10 | 0.54 |
| 5| 2321 | 30.38 | 12.05 | 0.58 |
| 10| 3240 | 43.41 | 19.02 | 0.78 |
| 39| 7419 | 96.26 | 53.05 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.50 | 7.29 | 0.41 |
| 2| 772 | 23.59 | 8.23 | 0.43 |
| 3| 858 | 24.03 | 9.02 | 0.45 |
| 5| 1151 | 28.57 | 11.65 | 0.52 |
| 10| 1860 | 36.85 | 17.29 | 0.65 |
| 40| 6372 | 94.70 | 53.34 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.42 | 8.68 | 0.47 |
| 2| 841 | 31.70 | 10.30 | 0.52 |
| 3| 944 | 30.90 | 10.74 | 0.52 |
| 5| 1219 | 36.95 | 13.76 | 0.60 |
| 10| 1946 | 46.66 | 19.81 | 0.76 |
| 37| 6085 | 99.00 | 52.53 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 803 | 35.88 | 11.39 | 0.56 |
| 3| 900 | 37.16 | 12.39 | 0.58 |
| 5| 1382 | 43.88 | 15.66 | 0.68 |
| 10| 2030 | 54.96 | 22.07 | 0.84 |
| 29| 5013 | 99.57 | 47.18 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 26.96 | 9.06 | 0.69 |
| 2| 5917 | 34.79 | 11.64 | 0.78 |
| 3| 6025 | 41.33 | 13.82 | 0.85 |
| 4| 6269 | 55.18 | 18.57 | 1.01 |
| 5| 6360 | 62.90 | 21.13 | 1.09 |
| 6| 6599 | 74.21 | 25.04 | 1.22 |
| 7| 6720 | 82.81 | 27.90 | 1.32 |
| 8| 6931 | 90.42 | 30.49 | 1.41 |
| 9| 6985 | 98.55 | 33.17 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 567 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

