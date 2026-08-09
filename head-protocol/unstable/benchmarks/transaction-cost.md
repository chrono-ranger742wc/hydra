--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-09 05:36:11.366450191 UTC |
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
| 1| 5836 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 227 | 858 | 52.34 | 14.98 | 0.72 |
| 5 | 281 | 969 | 58.36 | 16.85 | 0.79 |
| 6 | 336 | 1081 | 74.74 | 21.13 | 0.95 |
| 7 | 394 | 1192 | 80.90 | 23.04 | 1.02 |
| 8 | 448 | 1303 | 86.25 | 24.92 | 1.08 |
| 9 | 505 | 1414 | 89.45 | 25.89 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.29 | 7.69 | 0.48 |
| 2| 1999 | 27.00 | 9.10 | 0.52 |
| 3| 2134 | 28.39 | 10.16 | 0.55 |
| 5| 2421 | 32.45 | 12.63 | 0.61 |
| 10| 3174 | 40.53 | 18.24 | 0.75 |
| 39| 7620 | 98.49 | 53.66 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.50 | 7.30 | 0.41 |
| 2| 743 | 24.07 | 8.39 | 0.44 |
| 3| 858 | 23.99 | 9.01 | 0.45 |
| 5| 1348 | 32.40 | 12.70 | 0.56 |
| 10| 2098 | 43.03 | 19.00 | 0.73 |
| 42| 6741 | 97.74 | 55.54 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.09 | 8.89 | 0.48 |
| 2| 797 | 30.98 | 10.08 | 0.51 |
| 3| 970 | 30.82 | 10.73 | 0.52 |
| 5| 1232 | 37.02 | 13.78 | 0.60 |
| 10| 2018 | 47.44 | 20.04 | 0.77 |
| 35| 6065 | 98.38 | 51.14 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.16 | 0.53 |
| 2| 855 | 36.60 | 11.61 | 0.57 |
| 3| 1001 | 38.66 | 12.84 | 0.60 |
| 5| 1212 | 41.86 | 15.04 | 0.65 |
| 10| 1911 | 52.40 | 21.30 | 0.81 |
| 28| 4659 | 95.79 | 45.40 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.08 | 9.08 | 0.69 |
| 2| 5917 | 34.75 | 11.63 | 0.78 |
| 3| 6191 | 46.61 | 15.79 | 0.91 |
| 4| 6148 | 50.61 | 16.95 | 0.95 |
| 5| 6503 | 64.41 | 21.81 | 1.11 |
| 6| 6697 | 75.18 | 25.38 | 1.24 |
| 7| 6737 | 81.52 | 27.43 | 1.30 |
| 8| 6829 | 92.91 | 31.32 | 1.43 |
| 9| 6931 | 96.44 | 32.49 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2215 | 7155 | 98.93 | 37.88 | 1.54 |

