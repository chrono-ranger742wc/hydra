--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-26 06:30:16.561057322 UTC |
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
| 1| 5834 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.49 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.51 | 12.22 | 0.61 |
| 4 | 227 | 858 | 51.30 | 14.76 | 0.71 |
| 5 | 281 | 969 | 62.28 | 17.72 | 0.82 |
| 6 | 338 | 1081 | 69.80 | 19.95 | 0.91 |
| 7 | 393 | 1192 | 76.01 | 21.82 | 0.97 |
| 8 | 449 | 1307 | 80.55 | 23.36 | 1.03 |
| 9 | 504 | 1414 | 93.64 | 26.89 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1885 | 24.40 | 8.40 | 0.49 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2452 | 32.40 | 12.62 | 0.61 |
| 10| 3253 | 41.74 | 18.57 | 0.76 |
| 40| 7536 | 96.34 | 53.74 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.57 | 7.31 | 0.41 |
| 2| 762 | 24.32 | 8.46 | 0.44 |
| 3| 1043 | 27.77 | 10.09 | 0.49 |
| 5| 1115 | 27.01 | 11.19 | 0.50 |
| 10| 2117 | 41.97 | 18.73 | 0.72 |
| 44| 6830 | 99.15 | 57.27 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.50 | 8.46 | 0.46 |
| 2| 766 | 28.51 | 9.39 | 0.48 |
| 3| 974 | 33.47 | 11.46 | 0.55 |
| 5| 1398 | 38.96 | 14.38 | 0.63 |
| 10| 1975 | 47.22 | 19.99 | 0.76 |
| 34| 5586 | 97.53 | 50.07 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.87 | 10.16 | 0.53 |
| 2| 827 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1340 | 44.03 | 15.70 | 0.68 |
| 10| 2091 | 54.65 | 21.99 | 0.84 |
| 29| 5035 | 99.91 | 47.28 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.13 | 9.10 | 0.69 |
| 2| 5922 | 32.49 | 10.86 | 0.75 |
| 3| 6002 | 41.45 | 13.87 | 0.85 |
| 4| 6149 | 53.01 | 17.79 | 0.98 |
| 5| 6365 | 62.36 | 20.99 | 1.09 |
| 6| 6578 | 73.18 | 24.60 | 1.21 |
| 7| 6829 | 83.59 | 28.25 | 1.33 |
| 8| 6727 | 84.30 | 28.26 | 1.33 |
| 9| 6958 | 98.48 | 33.07 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 284 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

