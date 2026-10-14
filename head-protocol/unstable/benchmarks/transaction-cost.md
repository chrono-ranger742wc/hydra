--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-14 09:37:11.44596744 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.19 | 6.08 | 0.64 |
| 10| 7651 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 913 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 226 | 858 | 48.31 | 14.01 | 0.68 |
| 5 | 282 | 969 | 64.55 | 18.36 | 0.85 |
| 6 | 338 | 1081 | 68.35 | 19.64 | 0.89 |
| 7 | 394 | 1192 | 76.43 | 21.89 | 0.98 |
| 8 | 450 | 1303 | 92.21 | 26.20 | 1.14 |
| 10 | 560 | 1525 | 97.80 | 28.24 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1947 | 25.52 | 8.71 | 0.50 |
| 3| 2112 | 28.13 | 10.10 | 0.54 |
| 5| 2376 | 30.89 | 12.21 | 0.59 |
| 10| 3247 | 42.61 | 18.82 | 0.77 |
| 39| 7591 | 99.01 | 53.81 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 703 | 22.58 | 7.96 | 0.42 |
| 3| 925 | 25.79 | 9.54 | 0.47 |
| 5| 1209 | 29.06 | 11.76 | 0.52 |
| 10| 2082 | 39.75 | 18.08 | 0.69 |
| 39| 6639 | 99.65 | 54.09 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 29.13 | 8.90 | 0.48 |
| 2| 842 | 29.26 | 9.62 | 0.49 |
| 3| 872 | 32.05 | 11.02 | 0.53 |
| 5| 1391 | 36.43 | 13.67 | 0.60 |
| 10| 2252 | 51.08 | 21.14 | 0.81 |
| 36| 5935 | 97.63 | 51.51 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 973 | 37.87 | 12.61 | 0.59 |
| 5| 1271 | 42.45 | 15.23 | 0.66 |
| 10| 2011 | 53.53 | 21.64 | 0.83 |
| 29| 4907 | 98.88 | 46.97 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.09 | 9.08 | 0.69 |
| 2| 5897 | 34.95 | 11.69 | 0.78 |
| 3| 6142 | 46.06 | 15.54 | 0.90 |
| 4| 6124 | 49.32 | 16.47 | 0.94 |
| 5| 6506 | 65.40 | 22.07 | 1.12 |
| 6| 6681 | 75.14 | 25.43 | 1.23 |
| 7| 6716 | 81.32 | 27.36 | 1.30 |
| 8| 6895 | 92.32 | 31.16 | 1.42 |
| 9| 6939 | 99.19 | 33.38 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

