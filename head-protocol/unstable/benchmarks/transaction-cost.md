--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-04 09:06:56.781848482 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.72 | 4.03 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.51 | 12.00 | 0.61 |
| 4 | 227 | 858 | 50.83 | 14.62 | 0.70 |
| 5 | 283 | 969 | 61.23 | 17.53 | 0.81 |
| 6 | 340 | 1085 | 75.24 | 21.25 | 0.96 |
| 7 | 393 | 1192 | 82.84 | 23.55 | 1.04 |
| 8 | 451 | 1307 | 92.05 | 26.06 | 1.14 |
| 9 | 509 | 1414 | 98.83 | 28.08 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 23.92 | 7.60 | 0.48 |
| 2| 1960 | 26.92 | 9.09 | 0.52 |
| 3| 2057 | 27.03 | 9.79 | 0.53 |
| 5| 2431 | 32.19 | 12.57 | 0.61 |
| 10| 3130 | 40.74 | 18.29 | 0.75 |
| 40| 7618 | 97.49 | 54.05 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 22.81 | 7.38 | 0.42 |
| 2| 858 | 24.98 | 8.65 | 0.45 |
| 3| 882 | 25.58 | 9.48 | 0.46 |
| 5| 1241 | 29.67 | 11.96 | 0.53 |
| 10| 2007 | 40.96 | 18.42 | 0.70 |
| 44| 6898 | 99.29 | 57.30 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.13 | 8.90 | 0.48 |
| 2| 782 | 30.98 | 10.08 | 0.51 |
| 3| 906 | 30.26 | 10.55 | 0.51 |
| 5| 1181 | 36.38 | 13.58 | 0.59 |
| 10| 2082 | 48.05 | 20.23 | 0.78 |
| 37| 5887 | 96.51 | 51.78 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 886 | 36.48 | 11.58 | 0.57 |
| 3| 992 | 38.59 | 12.82 | 0.60 |
| 5| 1275 | 42.64 | 15.28 | 0.66 |
| 10| 2008 | 53.26 | 21.57 | 0.82 |
| 30| 4810 | 97.82 | 47.23 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 6022 | 36.69 | 12.38 | 0.80 |
| 3| 6072 | 43.51 | 14.60 | 0.87 |
| 4| 6273 | 54.28 | 18.34 | 1.00 |
| 5| 6374 | 60.73 | 20.43 | 1.07 |
| 6| 6681 | 75.01 | 25.36 | 1.23 |
| 7| 6916 | 85.77 | 29.01 | 1.36 |
| 8| 6810 | 91.67 | 30.79 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

