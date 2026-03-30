--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-30 06:23:12.864222227 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6240 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 228 | 858 | 50.84 | 14.62 | 0.70 |
| 5 | 284 | 969 | 64.26 | 18.26 | 0.84 |
| 6 | 340 | 1081 | 69.18 | 19.76 | 0.90 |
| 7 | 395 | 1192 | 86.45 | 24.33 | 1.08 |
| 8 | 453 | 1303 | 87.49 | 24.97 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 1943 | 25.39 | 8.68 | 0.50 |
| 3| 2146 | 29.21 | 10.40 | 0.56 |
| 5| 2322 | 30.08 | 11.98 | 0.58 |
| 10| 3184 | 40.52 | 18.23 | 0.75 |
| 40| 7641 | 97.84 | 54.16 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 22.50 | 7.30 | 0.41 |
| 2| 846 | 25.41 | 8.76 | 0.46 |
| 3| 900 | 25.85 | 9.55 | 0.47 |
| 5| 1214 | 29.03 | 11.76 | 0.52 |
| 10| 2096 | 41.72 | 18.64 | 0.71 |
| 43| 6750 | 98.65 | 56.46 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.79 | 8.25 | 0.45 |
| 2| 813 | 29.18 | 9.60 | 0.49 |
| 3| 1008 | 33.39 | 11.43 | 0.55 |
| 5| 1240 | 37.31 | 13.87 | 0.61 |
| 10| 2015 | 48.27 | 20.28 | 0.78 |
| 36| 6027 | 97.81 | 51.60 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.16 | 0.53 |
| 2| 802 | 35.85 | 11.38 | 0.56 |
| 3| 1109 | 39.38 | 13.06 | 0.61 |
| 5| 1320 | 43.31 | 15.48 | 0.67 |
| 10| 2075 | 55.26 | 22.16 | 0.85 |
| 28| 4785 | 95.99 | 45.49 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.13 | 9.10 | 0.69 |
| 2| 6009 | 37.01 | 12.46 | 0.80 |
| 3| 6049 | 41.40 | 13.84 | 0.85 |
| 4| 6241 | 55.03 | 18.54 | 1.00 |
| 5| 6379 | 62.65 | 21.09 | 1.09 |
| 6| 6505 | 69.32 | 23.25 | 1.16 |
| 7| 6799 | 84.01 | 28.38 | 1.33 |
| 8| 6864 | 88.37 | 29.75 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2224 | 7163 | 98.93 | 37.88 | 1.54 |

