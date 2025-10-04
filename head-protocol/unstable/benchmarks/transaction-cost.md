--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-04 04:37:41.567043217 UTC |
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
| 2| 6035 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 170 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 227 | 858 | 48.17 | 14.00 | 0.68 |
| 5 | 282 | 974 | 57.41 | 16.55 | 0.78 |
| 6 | 339 | 1081 | 64.29 | 18.67 | 0.85 |
| 7 | 395 | 1192 | 76.22 | 21.96 | 0.98 |
| 8 | 450 | 1307 | 98.16 | 27.52 | 1.20 |
| 9 | 504 | 1414 | 94.24 | 27.09 | 1.17 |
| 10 | 560 | 1525 | 96.79 | 28.10 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.40 | 8.39 | 0.49 |
| 3| 2110 | 28.13 | 10.10 | 0.54 |
| 5| 2278 | 29.04 | 11.69 | 0.57 |
| 10| 3121 | 40.78 | 18.30 | 0.75 |
| 42| 7734 | 99.41 | 55.91 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.77 | 7.36 | 0.41 |
| 2| 835 | 25.41 | 8.76 | 0.46 |
| 3| 957 | 26.20 | 9.63 | 0.47 |
| 5| 1226 | 30.05 | 12.07 | 0.53 |
| 10| 1994 | 39.18 | 17.94 | 0.68 |
| 43| 6774 | 98.68 | 56.49 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.51 | 8.47 | 0.46 |
| 2| 774 | 28.51 | 9.39 | 0.48 |
| 3| 1031 | 31.50 | 10.93 | 0.53 |
| 5| 1342 | 38.49 | 14.22 | 0.62 |
| 10| 2151 | 46.24 | 19.78 | 0.76 |
| 35| 6042 | 98.25 | 51.09 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 900 | 37.16 | 12.39 | 0.58 |
| 5| 1249 | 42.57 | 15.26 | 0.66 |
| 10| 1913 | 52.75 | 21.40 | 0.81 |
| 30| 4897 | 99.23 | 47.64 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.07 | 0.69 |
| 2| 5870 | 32.69 | 10.93 | 0.75 |
| 3| 6169 | 46.79 | 15.84 | 0.91 |
| 4| 6230 | 55.15 | 18.61 | 1.00 |
| 5| 6346 | 59.38 | 19.87 | 1.05 |
| 6| 6598 | 71.63 | 24.21 | 1.19 |
| 7| 6658 | 81.62 | 27.48 | 1.30 |
| 8| 6934 | 89.53 | 30.17 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 569 | 6174 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1711 | 6857 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.42 | 37.71 | 1.53 |

