--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-16 04:39:13.698741233 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 751 | 42.34 | 12.19 | 0.61 |
| 4 | 227 | 858 | 49.23 | 14.21 | 0.69 |
| 5 | 283 | 969 | 64.17 | 18.20 | 0.84 |
| 6 | 338 | 1081 | 64.19 | 18.67 | 0.85 |
| 7 | 396 | 1192 | 84.96 | 24.02 | 1.06 |
| 8 | 448 | 1303 | 93.24 | 26.34 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.00 | 7.62 | 0.48 |
| 2| 1884 | 24.80 | 8.49 | 0.49 |
| 3| 2116 | 28.05 | 10.08 | 0.54 |
| 5| 2323 | 30.37 | 12.05 | 0.58 |
| 10| 3141 | 41.07 | 18.37 | 0.75 |
| 41| 7613 | 98.73 | 55.06 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 770 | 23.98 | 8.37 | 0.44 |
| 3| 1043 | 28.25 | 10.22 | 0.50 |
| 5| 1165 | 28.04 | 11.48 | 0.51 |
| 10| 1989 | 40.03 | 18.18 | 0.69 |
| 41| 6510 | 95.08 | 54.16 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.83 | 8.26 | 0.45 |
| 2| 896 | 29.93 | 9.83 | 0.50 |
| 3| 1008 | 34.11 | 11.65 | 0.55 |
| 5| 1240 | 37.10 | 13.79 | 0.60 |
| 10| 2198 | 50.32 | 20.92 | 0.80 |
| 36| 5812 | 95.65 | 50.94 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 835 | 35.92 | 11.40 | 0.56 |
| 3| 965 | 37.91 | 12.62 | 0.59 |
| 5| 1268 | 42.68 | 15.29 | 0.66 |
| 10| 2034 | 53.99 | 21.79 | 0.83 |
| 29| 4827 | 97.67 | 46.61 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.09 | 9.09 | 0.69 |
| 2| 5917 | 35.96 | 12.07 | 0.79 |
| 3| 6139 | 44.94 | 15.10 | 0.89 |
| 4| 6198 | 51.11 | 17.17 | 0.96 |
| 5| 6497 | 64.63 | 21.83 | 1.12 |
| 6| 6501 | 71.57 | 24.10 | 1.19 |
| 7| 6603 | 79.30 | 26.65 | 1.27 |
| 8| 6917 | 94.76 | 31.95 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 20 | 1140 | 6515 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2163 | 7125 | 96.44 | 36.92 | 1.51 |

