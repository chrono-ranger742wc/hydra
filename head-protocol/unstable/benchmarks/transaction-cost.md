--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-12 05:34:56.743395388 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 168 | 751 | 41.29 | 11.92 | 0.60 |
| 4 | 227 | 862 | 52.19 | 14.94 | 0.72 |
| 5 | 284 | 969 | 60.90 | 17.42 | 0.81 |
| 6 | 340 | 1081 | 73.19 | 20.79 | 0.94 |
| 7 | 394 | 1192 | 73.71 | 21.27 | 0.95 |
| 8 | 449 | 1307 | 97.78 | 27.38 | 1.20 |
| 9 | 506 | 1414 | 96.95 | 27.86 | 1.20 |
| 10 | 561 | 1525 | 97.03 | 28.10 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.47 | 8.41 | 0.49 |
| 3| 2017 | 26.36 | 9.59 | 0.52 |
| 5| 2413 | 32.15 | 12.56 | 0.61 |
| 10| 3096 | 40.15 | 18.11 | 0.74 |
| 42| 7839 | 99.27 | 55.89 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 804 | 25.55 | 8.81 | 0.46 |
| 3| 862 | 24.07 | 9.03 | 0.45 |
| 5| 1214 | 29.69 | 11.96 | 0.53 |
| 10| 2070 | 42.01 | 18.72 | 0.72 |
| 39| 6496 | 98.80 | 53.81 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 834 | 29.22 | 9.61 | 0.49 |
| 3| 918 | 32.76 | 11.24 | 0.54 |
| 5| 1237 | 37.14 | 13.81 | 0.60 |
| 10| 1961 | 44.23 | 19.16 | 0.73 |
| 35| 6080 | 97.89 | 50.96 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 873 | 36.60 | 11.61 | 0.57 |
| 3| 959 | 37.88 | 12.61 | 0.59 |
| 5| 1297 | 43.25 | 15.47 | 0.67 |
| 10| 2063 | 54.51 | 21.96 | 0.84 |
| 28| 5013 | 99.90 | 46.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.13 | 9.10 | 0.69 |
| 2| 5918 | 36.01 | 12.10 | 0.79 |
| 3| 6048 | 41.37 | 13.84 | 0.85 |
| 4| 6406 | 56.86 | 19.27 | 1.03 |
| 5| 6599 | 66.28 | 22.38 | 1.14 |
| 6| 6484 | 73.18 | 24.67 | 1.20 |
| 7| 6845 | 85.28 | 28.84 | 1.35 |
| 8| 6770 | 88.35 | 29.67 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.78 | 30.37 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

