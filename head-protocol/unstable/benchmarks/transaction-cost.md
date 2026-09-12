--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-12 08:49:43.910776689 UTC |
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
| 1| 5838 | 10.38 | 3.29 | 0.51 |
| 2| 6041 | 12.46 | 3.94 | 0.55 |
| 3| 6242 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.12 | 11.88 | 0.60 |
| 4 | 227 | 862 | 52.49 | 15.04 | 0.72 |
| 5 | 281 | 969 | 59.61 | 17.17 | 0.80 |
| 6 | 341 | 1081 | 69.93 | 19.98 | 0.91 |
| 7 | 393 | 1192 | 72.15 | 20.90 | 0.94 |
| 8 | 448 | 1303 | 88.44 | 25.19 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.85 | 8.50 | 0.50 |
| 3| 2060 | 26.98 | 9.78 | 0.53 |
| 5| 2337 | 29.89 | 11.93 | 0.58 |
| 10| 3139 | 40.76 | 18.29 | 0.75 |
| 39| 7679 | 99.02 | 53.84 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.50 | 7.29 | 0.41 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 990 | 26.09 | 9.60 | 0.47 |
| 5| 1207 | 28.97 | 11.74 | 0.52 |
| 10| 2177 | 44.68 | 19.45 | 0.75 |
| 43| 6863 | 98.14 | 56.36 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.51 | 8.47 | 0.46 |
| 2| 891 | 29.93 | 9.83 | 0.50 |
| 3| 943 | 32.68 | 11.22 | 0.54 |
| 5| 1218 | 36.95 | 13.76 | 0.60 |
| 10| 2057 | 44.90 | 19.37 | 0.74 |
| 36| 5973 | 98.38 | 51.72 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 947 | 37.91 | 12.62 | 0.59 |
| 5| 1296 | 43.36 | 15.49 | 0.67 |
| 10| 2066 | 54.32 | 21.89 | 0.84 |
| 28| 4676 | 95.02 | 45.19 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.13 | 9.10 | 0.69 |
| 2| 5999 | 37.05 | 12.47 | 0.80 |
| 3| 6054 | 43.64 | 14.63 | 0.87 |
| 4| 6331 | 56.41 | 19.03 | 1.02 |
| 5| 6177 | 55.12 | 18.41 | 1.00 |
| 6| 6530 | 69.94 | 23.44 | 1.17 |
| 7| 6625 | 75.35 | 25.23 | 1.23 |
| 8| 6944 | 91.03 | 30.70 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

