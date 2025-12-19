--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-19 05:39:42.292023988 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6243 | 15.16 | 4.82 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.34 | 9.42 | 0.51 |
| 3 | 169 | 747 | 43.51 | 12.45 | 0.62 |
| 4 | 225 | 858 | 49.53 | 14.28 | 0.69 |
| 5 | 284 | 969 | 62.22 | 17.77 | 0.82 |
| 6 | 338 | 1081 | 73.71 | 20.99 | 0.94 |
| 7 | 395 | 1192 | 77.42 | 22.30 | 0.99 |
| 8 | 449 | 1303 | 94.68 | 26.79 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1945 | 25.80 | 8.77 | 0.51 |
| 3| 2126 | 28.30 | 10.14 | 0.55 |
| 5| 2322 | 29.97 | 11.95 | 0.58 |
| 10| 3169 | 41.57 | 18.51 | 0.76 |
| 39| 7489 | 95.18 | 52.77 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.39 | 0.42 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 939 | 26.12 | 9.60 | 0.47 |
| 5| 1120 | 26.94 | 11.17 | 0.50 |
| 10| 2042 | 41.78 | 18.67 | 0.71 |
| 41| 6464 | 94.74 | 54.07 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.13 | 8.90 | 0.48 |
| 2| 775 | 30.94 | 10.07 | 0.51 |
| 3| 1068 | 32.40 | 11.20 | 0.54 |
| 5| 1383 | 36.80 | 13.78 | 0.61 |
| 10| 2110 | 45.68 | 19.60 | 0.75 |
| 38| 6115 | 99.73 | 53.35 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 838 | 35.89 | 11.39 | 0.56 |
| 3| 945 | 37.87 | 12.61 | 0.59 |
| 5| 1267 | 42.57 | 15.26 | 0.66 |
| 10| 1932 | 53.01 | 21.49 | 0.82 |
| 29| 4884 | 97.25 | 46.48 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.09 | 0.69 |
| 2| 5975 | 35.99 | 12.10 | 0.79 |
| 3| 6091 | 44.93 | 15.07 | 0.89 |
| 4| 6330 | 55.98 | 18.86 | 1.02 |
| 5| 6442 | 64.77 | 21.80 | 1.11 |
| 6| 6532 | 72.87 | 24.49 | 1.20 |
| 7| 6739 | 81.31 | 27.47 | 1.30 |
| 8| 6892 | 92.11 | 30.97 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.46 | 10.47 | 0.73 |
| 10 | 10 | 568 | 6172 | 38.37 | 14.06 | 0.83 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1703 | 6850 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2160 | 7122 | 96.44 | 36.92 | 1.51 |

