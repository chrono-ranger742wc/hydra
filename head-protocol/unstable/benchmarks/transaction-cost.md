--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-30 10:19:51.192106132 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 751 | 41.24 | 11.91 | 0.60 |
| 4 | 226 | 858 | 49.57 | 14.32 | 0.69 |
| 5 | 283 | 974 | 57.81 | 16.68 | 0.78 |
| 6 | 337 | 1085 | 65.91 | 19.05 | 0.87 |
| 7 | 394 | 1192 | 84.34 | 23.82 | 1.06 |
| 8 | 449 | 1307 | 86.73 | 24.78 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2057 | 27.06 | 9.80 | 0.53 |
| 5| 2279 | 29.38 | 11.77 | 0.57 |
| 10| 2992 | 37.80 | 17.46 | 0.71 |
| 40| 7407 | 94.57 | 53.25 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.81 | 7.37 | 0.42 |
| 2| 768 | 24.31 | 8.45 | 0.44 |
| 3| 872 | 25.51 | 9.46 | 0.46 |
| 5| 1166 | 28.03 | 11.47 | 0.51 |
| 10| 1941 | 39.82 | 18.11 | 0.69 |
| 42| 6487 | 97.03 | 55.32 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 772 | 30.94 | 10.07 | 0.51 |
| 3| 1003 | 31.61 | 10.96 | 0.53 |
| 5| 1302 | 37.54 | 13.94 | 0.61 |
| 10| 2034 | 44.90 | 19.37 | 0.74 |
| 35| 5770 | 94.67 | 49.98 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.64 | 11.62 | 0.57 |
| 3| 1083 | 39.30 | 13.04 | 0.61 |
| 5| 1273 | 42.64 | 15.28 | 0.66 |
| 10| 2037 | 54.81 | 22.03 | 0.84 |
| 29| 4790 | 98.12 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.16 | 9.10 | 0.69 |
| 2| 5939 | 35.77 | 12.03 | 0.79 |
| 3| 6139 | 45.70 | 15.41 | 0.90 |
| 4| 6330 | 55.97 | 18.92 | 1.02 |
| 5| 6246 | 58.15 | 19.46 | 1.04 |
| 6| 6505 | 70.87 | 23.84 | 1.18 |
| 7| 6695 | 79.55 | 26.77 | 1.28 |
| 8| 6844 | 92.17 | 31.06 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1135 | 6509 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2221 | 7161 | 98.24 | 37.65 | 1.53 |

