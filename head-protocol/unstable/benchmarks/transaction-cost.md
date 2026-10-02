--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-02 10:52:43.96301732 UTC |
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
| 1| 5841 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.92 | 4.11 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.28 | 11.70 | 0.59 |
| 4 | 227 | 858 | 48.46 | 14.08 | 0.68 |
| 5 | 283 | 974 | 64.82 | 18.40 | 0.85 |
| 6 | 339 | 1081 | 74.81 | 21.14 | 0.95 |
| 7 | 393 | 1192 | 74.54 | 21.52 | 0.96 |
| 8 | 449 | 1303 | 89.43 | 25.48 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 23.92 | 7.60 | 0.48 |
| 2| 1951 | 25.39 | 8.68 | 0.50 |
| 3| 2060 | 27.24 | 9.84 | 0.53 |
| 5| 2327 | 30.08 | 11.98 | 0.58 |
| 10| 3151 | 40.70 | 18.28 | 0.75 |
| 42| 7938 | 99.89 | 56.06 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.81 | 7.37 | 0.42 |
| 2| 811 | 25.12 | 8.69 | 0.45 |
| 3| 987 | 27.08 | 9.89 | 0.48 |
| 5| 1151 | 28.03 | 11.47 | 0.51 |
| 10| 2002 | 40.39 | 18.30 | 0.70 |
| 41| 6424 | 96.01 | 54.40 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 740 | 30.23 | 9.85 | 0.50 |
| 3| 1021 | 34.19 | 11.67 | 0.56 |
| 5| 1342 | 36.09 | 13.57 | 0.60 |
| 10| 2077 | 45.49 | 19.55 | 0.75 |
| 37| 6127 | 99.62 | 52.71 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 814 | 35.89 | 11.39 | 0.56 |
| 3| 943 | 37.87 | 12.61 | 0.59 |
| 5| 1273 | 42.72 | 15.30 | 0.66 |
| 10| 2160 | 55.26 | 22.18 | 0.85 |
| 29| 4945 | 98.15 | 46.75 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.09 | 9.10 | 0.69 |
| 2| 5972 | 35.85 | 12.03 | 0.79 |
| 3| 6140 | 46.06 | 15.51 | 0.90 |
| 4| 6170 | 52.91 | 17.74 | 0.98 |
| 5| 6302 | 59.64 | 20.01 | 1.05 |
| 6| 6605 | 73.92 | 24.94 | 1.22 |
| 7| 6705 | 77.41 | 26.03 | 1.26 |
| 8| 6776 | 85.62 | 28.75 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 22.29 | 7.58 | 0.64 |
| 10 | 5 | 284 | 6004 | 29.72 | 10.56 | 0.73 |
| 10 | 20 | 1135 | 6509 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1710 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

