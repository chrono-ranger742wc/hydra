--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-29 05:33:23.773576332 UTC |
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
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 40.29 | 11.71 | 0.59 |
| 4 | 227 | 858 | 51.02 | 14.66 | 0.71 |
| 5 | 282 | 969 | 59.27 | 17.06 | 0.79 |
| 6 | 337 | 1081 | 70.54 | 20.24 | 0.91 |
| 7 | 395 | 1196 | 86.80 | 24.45 | 1.08 |
| 8 | 449 | 1303 | 93.86 | 26.50 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 23.92 | 7.60 | 0.48 |
| 2| 1982 | 26.76 | 9.04 | 0.52 |
| 3| 2059 | 27.47 | 9.90 | 0.53 |
| 5| 2371 | 31.42 | 12.34 | 0.60 |
| 10| 3239 | 41.54 | 18.52 | 0.76 |
| 40| 7826 | 99.54 | 54.65 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.53 | 7.30 | 0.41 |
| 2| 858 | 24.97 | 8.65 | 0.45 |
| 3| 910 | 25.03 | 9.30 | 0.46 |
| 5| 1208 | 29.16 | 11.79 | 0.52 |
| 10| 2054 | 41.00 | 18.46 | 0.71 |
| 43| 6682 | 97.45 | 56.12 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 782 | 30.98 | 10.08 | 0.51 |
| 3| 1019 | 31.65 | 10.97 | 0.53 |
| 5| 1350 | 38.45 | 14.21 | 0.62 |
| 10| 2223 | 47.01 | 20.01 | 0.77 |
| 36| 5713 | 93.96 | 50.39 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 885 | 36.52 | 11.59 | 0.57 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1203 | 41.86 | 15.04 | 0.65 |
| 10| 2034 | 53.86 | 21.76 | 0.83 |
| 29| 4902 | 98.91 | 46.99 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.13 | 9.11 | 0.69 |
| 2| 6008 | 37.01 | 12.47 | 0.80 |
| 3| 6045 | 43.56 | 14.62 | 0.87 |
| 4| 6302 | 54.96 | 18.52 | 1.01 |
| 5| 6396 | 64.04 | 21.61 | 1.10 |
| 6| 6562 | 73.91 | 24.89 | 1.22 |
| 7| 6468 | 70.72 | 23.62 | 1.18 |
| 8| 6795 | 90.11 | 30.25 | 1.40 |
| 9| 7127 | 99.52 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1134 | 6508 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

