--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-30 02:27:47.547968408 UTC |
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
| 2| 6037 | 12.80 | 4.07 | 0.55 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 41.24 | 11.93 | 0.60 |
| 4 | 227 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 283 | 969 | 57.64 | 16.64 | 0.78 |
| 6 | 337 | 1081 | 74.95 | 21.21 | 0.96 |
| 7 | 392 | 1192 | 87.32 | 24.67 | 1.09 |
| 8 | 451 | 1303 | 99.02 | 27.88 | 1.21 |
| 9 | 504 | 1414 | 96.26 | 27.63 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.00 | 7.62 | 0.48 |
| 2| 1883 | 24.77 | 8.48 | 0.49 |
| 3| 2151 | 28.47 | 10.18 | 0.55 |
| 5| 2464 | 33.24 | 12.86 | 0.62 |
| 10| 3161 | 42.04 | 18.64 | 0.76 |
| 41| 7685 | 98.59 | 55.03 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.80 | 7.37 | 0.42 |
| 2| 815 | 25.43 | 8.77 | 0.45 |
| 3| 950 | 27.00 | 9.87 | 0.48 |
| 5| 1210 | 29.06 | 11.77 | 0.52 |
| 10| 1996 | 38.62 | 17.77 | 0.68 |
| 39| 6459 | 98.39 | 53.70 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.13 | 8.90 | 0.48 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 953 | 30.94 | 10.75 | 0.52 |
| 5| 1390 | 38.37 | 14.19 | 0.62 |
| 10| 2090 | 45.51 | 19.56 | 0.75 |
| 34| 5592 | 92.37 | 48.66 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 33.83 | 10.16 | 0.53 |
| 2| 816 | 35.85 | 11.38 | 0.56 |
| 3| 1046 | 38.51 | 12.80 | 0.60 |
| 5| 1246 | 42.64 | 15.28 | 0.66 |
| 10| 2187 | 56.40 | 22.52 | 0.86 |
| 30| 4970 | 99.71 | 47.84 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5867 | 32.61 | 10.89 | 0.75 |
| 3| 6019 | 41.40 | 13.86 | 0.85 |
| 4| 6274 | 54.97 | 18.50 | 1.00 |
| 5| 6329 | 63.36 | 21.26 | 1.09 |
| 6| 6575 | 74.56 | 25.10 | 1.22 |
| 7| 6706 | 77.61 | 26.18 | 1.26 |
| 8| 6995 | 95.22 | 32.22 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 21.66 | 7.36 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.37 | 14.06 | 0.83 |
| 10 | 39 | 2221 | 7160 | 98.68 | 37.80 | 1.54 |

