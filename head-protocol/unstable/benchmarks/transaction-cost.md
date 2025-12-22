--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-22 05:50:57.868996193 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 41.51 | 12.00 | 0.60 |
| 4 | 227 | 858 | 49.63 | 14.35 | 0.69 |
| 5 | 283 | 969 | 64.46 | 18.34 | 0.85 |
| 6 | 339 | 1081 | 69.79 | 19.98 | 0.91 |
| 7 | 395 | 1192 | 73.61 | 21.20 | 0.95 |
| 8 | 449 | 1303 | 85.21 | 24.52 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2084 | 27.35 | 9.87 | 0.53 |
| 5| 2391 | 31.12 | 12.27 | 0.60 |
| 10| 3356 | 43.65 | 19.11 | 0.79 |
| 41| 7683 | 98.41 | 55.00 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.31 | 0.41 |
| 2| 783 | 25.16 | 8.69 | 0.45 |
| 3| 853 | 23.99 | 9.01 | 0.45 |
| 5| 1100 | 27.07 | 11.21 | 0.50 |
| 10| 2015 | 38.82 | 17.83 | 0.68 |
| 40| 6482 | 97.27 | 54.10 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 836 | 29.22 | 9.61 | 0.49 |
| 3| 868 | 32.09 | 11.03 | 0.53 |
| 5| 1259 | 36.95 | 13.76 | 0.60 |
| 10| 1895 | 45.94 | 19.59 | 0.75 |
| 38| 6117 | 98.22 | 52.96 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.15 | 0.53 |
| 2| 865 | 36.52 | 11.59 | 0.57 |
| 3| 899 | 37.24 | 12.41 | 0.58 |
| 5| 1312 | 43.50 | 15.55 | 0.67 |
| 10| 1926 | 52.78 | 21.41 | 0.82 |
| 30| 4896 | 98.50 | 47.47 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5983 | 36.84 | 12.42 | 0.80 |
| 3| 6180 | 45.88 | 15.47 | 0.90 |
| 4| 6212 | 54.08 | 18.21 | 0.99 |
| 5| 6479 | 65.77 | 22.18 | 1.13 |
| 6| 6322 | 65.34 | 21.84 | 1.11 |
| 7| 6786 | 84.04 | 28.31 | 1.33 |
| 8| 6956 | 94.42 | 31.83 | 1.45 |
| 9| 6973 | 99.57 | 33.60 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.53 | 10.50 | 0.73 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

