--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-28 05:12:32.161473998 UTC |
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
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.70 | 12.54 | 0.63 |
| 4 | 227 | 862 | 49.25 | 14.24 | 0.69 |
| 5 | 281 | 969 | 59.47 | 17.05 | 0.80 |
| 6 | 339 | 1081 | 75.28 | 21.26 | 0.96 |
| 7 | 392 | 1192 | 72.67 | 21.07 | 0.94 |
| 8 | 450 | 1303 | 89.95 | 25.61 | 1.12 |
| 9 | 505 | 1414 | 98.25 | 27.99 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2173 | 29.54 | 10.48 | 0.56 |
| 5| 2426 | 32.52 | 12.65 | 0.61 |
| 10| 3215 | 41.78 | 18.58 | 0.76 |
| 39| 7535 | 99.92 | 54.05 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 22.77 | 7.37 | 0.42 |
| 2| 777 | 23.66 | 8.26 | 0.44 |
| 3| 971 | 26.93 | 9.86 | 0.48 |
| 5| 1289 | 32.18 | 12.65 | 0.56 |
| 10| 2146 | 43.63 | 19.15 | 0.74 |
| 40| 6497 | 94.68 | 53.39 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.47 | 8.46 | 0.46 |
| 2| 871 | 29.97 | 9.84 | 0.50 |
| 3| 977 | 33.51 | 11.47 | 0.55 |
| 5| 1253 | 34.85 | 13.20 | 0.58 |
| 10| 1891 | 45.83 | 19.56 | 0.74 |
| 36| 6003 | 97.15 | 51.39 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 709 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.14 | 11.16 | 0.55 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1199 | 42.01 | 15.08 | 0.65 |
| 10| 1955 | 53.19 | 21.55 | 0.82 |
| 29| 5002 | 99.80 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5897 | 34.80 | 11.66 | 0.77 |
| 3| 6155 | 46.08 | 15.54 | 0.91 |
| 4| 6298 | 55.15 | 18.55 | 1.01 |
| 5| 6394 | 63.68 | 21.46 | 1.10 |
| 6| 6687 | 73.62 | 24.85 | 1.22 |
| 7| 6927 | 85.03 | 28.78 | 1.35 |
| 8| 6750 | 87.13 | 29.22 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 567 | 6172 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.05 | 37.58 | 1.53 |

