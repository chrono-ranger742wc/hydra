--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-28 06:43:43.345877937 UTC |
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
| 2| 6037 | 13.18 | 4.20 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 862 | 53.30 | 15.18 | 0.73 |
| 5 | 282 | 969 | 55.98 | 16.24 | 0.76 |
| 6 | 340 | 1081 | 71.54 | 20.40 | 0.92 |
| 7 | 395 | 1192 | 80.24 | 22.84 | 1.02 |
| 8 | 449 | 1303 | 85.08 | 24.39 | 1.07 |
| 9 | 504 | 1414 | 89.52 | 26.02 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.39 | 8.68 | 0.50 |
| 3| 2063 | 27.35 | 9.87 | 0.53 |
| 5| 2363 | 30.80 | 12.19 | 0.59 |
| 10| 3273 | 43.55 | 19.07 | 0.78 |
| 39| 7487 | 95.89 | 52.93 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.84 | 7.37 | 0.41 |
| 2| 775 | 23.59 | 8.23 | 0.43 |
| 3| 946 | 26.06 | 9.59 | 0.47 |
| 5| 1208 | 30.31 | 12.15 | 0.54 |
| 10| 1965 | 38.74 | 17.81 | 0.68 |
| 41| 6681 | 99.75 | 55.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 910 | 29.90 | 9.82 | 0.50 |
| 3| 983 | 33.51 | 11.47 | 0.55 |
| 5| 1249 | 35.05 | 13.25 | 0.58 |
| 10| 2143 | 46.17 | 19.76 | 0.76 |
| 37| 6191 | 98.82 | 52.54 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 873 | 36.60 | 11.61 | 0.57 |
| 3| 971 | 38.17 | 12.70 | 0.59 |
| 5| 1273 | 42.56 | 15.26 | 0.66 |
| 10| 2055 | 54.78 | 22.02 | 0.84 |
| 29| 4930 | 99.36 | 47.10 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5844 | 27.12 | 9.10 | 0.69 |
| 2| 5960 | 35.96 | 12.06 | 0.79 |
| 3| 6045 | 43.55 | 14.60 | 0.87 |
| 4| 6235 | 53.86 | 18.08 | 0.99 |
| 5| 6522 | 66.47 | 22.42 | 1.14 |
| 6| 6627 | 74.06 | 24.99 | 1.22 |
| 7| 6768 | 82.97 | 27.94 | 1.32 |
| 8| 6737 | 87.65 | 29.44 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 61.75 | 23.13 | 1.10 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.44 | 36.92 | 1.51 |

