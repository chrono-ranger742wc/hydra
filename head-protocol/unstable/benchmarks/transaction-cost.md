--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-23 05:34:04.424994723 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 227 | 858 | 50.65 | 14.55 | 0.70 |
| 5 | 283 | 969 | 62.59 | 17.83 | 0.83 |
| 6 | 339 | 1081 | 73.34 | 20.87 | 0.94 |
| 7 | 393 | 1196 | 80.56 | 22.92 | 1.02 |
| 8 | 448 | 1303 | 98.33 | 27.57 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1879 | 24.77 | 8.48 | 0.49 |
| 3| 2147 | 28.85 | 10.31 | 0.55 |
| 5| 2445 | 32.15 | 12.56 | 0.61 |
| 10| 3228 | 41.99 | 18.63 | 0.77 |
| 40| 7627 | 99.60 | 54.63 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 22.77 | 7.37 | 0.42 |
| 2| 774 | 24.32 | 8.46 | 0.44 |
| 3| 992 | 27.68 | 10.08 | 0.49 |
| 5| 1167 | 28.07 | 11.48 | 0.51 |
| 10| 2009 | 41.10 | 18.46 | 0.70 |
| 42| 6929 | 99.51 | 56.08 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.51 | 8.47 | 0.46 |
| 2| 847 | 31.62 | 10.28 | 0.52 |
| 3| 1028 | 34.06 | 11.64 | 0.55 |
| 5| 1212 | 34.26 | 13.01 | 0.57 |
| 10| 2112 | 48.89 | 20.48 | 0.79 |
| 34| 5916 | 96.96 | 50.03 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.16 | 0.53 |
| 2| 832 | 35.92 | 11.40 | 0.56 |
| 3| 954 | 37.87 | 12.61 | 0.59 |
| 5| 1346 | 43.65 | 15.58 | 0.67 |
| 10| 1858 | 51.89 | 21.15 | 0.80 |
| 30| 5036 | 99.49 | 47.80 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 26.96 | 9.05 | 0.69 |
| 2| 5895 | 32.65 | 10.91 | 0.75 |
| 3| 6100 | 44.61 | 15.01 | 0.89 |
| 4| 6261 | 54.89 | 18.51 | 1.00 |
| 5| 6477 | 62.43 | 21.06 | 1.09 |
| 6| 6627 | 73.25 | 24.71 | 1.21 |
| 7| 6758 | 82.84 | 27.94 | 1.32 |
| 8| 6973 | 93.22 | 31.45 | 1.44 |
| 9| 6852 | 98.16 | 32.98 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

