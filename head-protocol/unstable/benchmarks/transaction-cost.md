--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-01 11:18:02.240902614 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.99 | 4.13 | 0.55 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.26 | 6.10 | 0.64 |
| 10| 7650 | 29.26 | 9.23 | 0.79 |
| 43| 14283 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 42.44 | 12.23 | 0.61 |
| 4 | 227 | 858 | 49.70 | 14.35 | 0.69 |
| 5 | 283 | 969 | 57.15 | 16.55 | 0.77 |
| 6 | 338 | 1085 | 71.88 | 20.48 | 0.93 |
| 7 | 394 | 1192 | 80.47 | 22.89 | 1.02 |
| 8 | 449 | 1303 | 90.07 | 25.69 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.80 | 8.77 | 0.51 |
| 3| 2078 | 26.87 | 9.75 | 0.53 |
| 5| 2433 | 32.41 | 12.62 | 0.61 |
| 10| 3049 | 39.15 | 17.84 | 0.73 |
| 40| 7598 | 97.90 | 54.16 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.50 | 7.30 | 0.41 |
| 2| 772 | 23.58 | 8.23 | 0.43 |
| 3| 881 | 25.82 | 9.54 | 0.47 |
| 5| 1192 | 29.73 | 11.97 | 0.53 |
| 10| 1945 | 37.40 | 17.43 | 0.66 |
| 41| 6870 | 98.66 | 55.20 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.09 | 8.89 | 0.48 |
| 2| 817 | 29.26 | 9.62 | 0.49 |
| 3| 910 | 30.23 | 10.54 | 0.51 |
| 5| 1260 | 35.04 | 13.25 | 0.58 |
| 10| 2220 | 46.72 | 19.94 | 0.77 |
| 36| 5770 | 93.88 | 50.42 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.16 | 0.53 |
| 2| 819 | 35.88 | 11.39 | 0.56 |
| 3| 988 | 38.66 | 12.84 | 0.60 |
| 5| 1254 | 42.68 | 15.29 | 0.66 |
| 10| 2031 | 54.12 | 21.84 | 0.83 |
| 30| 4949 | 99.36 | 47.73 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.13 | 9.11 | 0.69 |
| 2| 5954 | 35.92 | 12.05 | 0.79 |
| 3| 6023 | 41.54 | 13.93 | 0.85 |
| 4| 6299 | 52.35 | 17.64 | 0.98 |
| 5| 6354 | 62.92 | 21.18 | 1.09 |
| 6| 6535 | 73.32 | 24.69 | 1.21 |
| 7| 6733 | 81.45 | 27.45 | 1.30 |
| 8| 6893 | 88.11 | 29.69 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6002 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

