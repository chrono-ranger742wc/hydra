--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-07 06:58:40.130991826 UTC |
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
| 1| 5836 | 10.86 | 3.46 | 0.52 |
| 2| 6039 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 19.26 | 6.10 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 751 | 41.19 | 11.92 | 0.60 |
| 4 | 226 | 858 | 53.71 | 15.28 | 0.73 |
| 5 | 283 | 969 | 60.06 | 17.26 | 0.80 |
| 6 | 339 | 1081 | 68.22 | 19.64 | 0.89 |
| 7 | 394 | 1192 | 74.72 | 21.56 | 0.96 |
| 8 | 449 | 1303 | 84.61 | 24.33 | 1.07 |
| 9 | 505 | 1414 | 93.75 | 26.92 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.84 | 8.78 | 0.51 |
| 3| 2123 | 27.33 | 9.89 | 0.54 |
| 5| 2396 | 31.18 | 12.28 | 0.60 |
| 10| 3280 | 43.25 | 19.00 | 0.78 |
| 39| 7293 | 92.60 | 52.03 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.57 | 7.31 | 0.41 |
| 2| 826 | 25.16 | 8.71 | 0.45 |
| 3| 1001 | 26.92 | 9.85 | 0.48 |
| 5| 1256 | 31.04 | 12.33 | 0.55 |
| 10| 1984 | 39.68 | 18.08 | 0.69 |
| 42| 6692 | 97.57 | 55.53 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 840 | 31.66 | 10.29 | 0.52 |
| 3| 1038 | 31.54 | 10.94 | 0.53 |
| 5| 1231 | 34.37 | 13.04 | 0.58 |
| 10| 2210 | 47.03 | 20.01 | 0.77 |
| 37| 5973 | 98.58 | 52.41 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 952 | 37.95 | 12.63 | 0.59 |
| 5| 1267 | 42.64 | 15.28 | 0.66 |
| 10| 2038 | 54.31 | 21.89 | 0.84 |
| 30| 4816 | 97.58 | 47.19 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.05 | 9.07 | 0.69 |
| 2| 6021 | 36.85 | 12.44 | 0.80 |
| 3| 6068 | 43.75 | 14.66 | 0.88 |
| 4| 6305 | 54.83 | 18.46 | 1.00 |
| 5| 6335 | 63.08 | 21.23 | 1.09 |
| 6| 6546 | 72.26 | 24.32 | 1.20 |
| 7| 6877 | 86.81 | 29.40 | 1.37 |
| 8| 6798 | 88.46 | 29.80 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2219 | 7158 | 99.12 | 37.95 | 1.54 |

