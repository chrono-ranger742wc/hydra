--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-09 05:07:30.055090976 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6037 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6646 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10033 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 227 | 858 | 51.10 | 14.71 | 0.71 |
| 5 | 283 | 969 | 59.80 | 17.22 | 0.80 |
| 6 | 339 | 1081 | 73.71 | 20.92 | 0.94 |
| 7 | 394 | 1192 | 80.03 | 22.74 | 1.01 |
| 8 | 450 | 1307 | 93.51 | 26.50 | 1.15 |
| 9 | 506 | 1414 | 89.27 | 25.90 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 1953 | 25.76 | 8.76 | 0.51 |
| 3| 2087 | 27.43 | 9.89 | 0.54 |
| 5| 2415 | 32.44 | 12.63 | 0.61 |
| 10| 3037 | 39.12 | 17.82 | 0.73 |
| 39| 7371 | 95.56 | 52.86 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 947 | 26.61 | 9.77 | 0.48 |
| 5| 1375 | 32.47 | 12.72 | 0.56 |
| 10| 1996 | 39.54 | 18.04 | 0.69 |
| 42| 6619 | 97.55 | 55.48 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.17 | 8.91 | 0.48 |
| 2| 844 | 29.26 | 9.62 | 0.49 |
| 3| 933 | 32.72 | 11.23 | 0.54 |
| 5| 1317 | 37.77 | 14.00 | 0.61 |
| 10| 2142 | 46.24 | 19.78 | 0.76 |
| 37| 6063 | 99.09 | 52.57 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 33.15 | 9.95 | 0.52 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1228 | 41.82 | 15.03 | 0.65 |
| 10| 2029 | 54.13 | 21.83 | 0.83 |
| 29| 5004 | 99.25 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5826 | 31.48 | 10.47 | 0.74 |
| 3| 6137 | 44.47 | 14.98 | 0.89 |
| 4| 6282 | 55.38 | 18.76 | 1.01 |
| 5| 6158 | 55.33 | 18.46 | 1.00 |
| 6| 6640 | 74.55 | 25.30 | 1.23 |
| 7| 6901 | 84.63 | 28.59 | 1.34 |
| 8| 6857 | 92.89 | 31.30 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2221 | 7161 | 99.12 | 37.95 | 1.54 |

