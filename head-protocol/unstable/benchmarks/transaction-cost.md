--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-02 09:09:25.699856775 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 735 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.34 | 9.90 | 0.53 |
| 3 | 171 | 747 | 41.19 | 11.92 | 0.60 |
| 4 | 226 | 858 | 49.73 | 14.35 | 0.69 |
| 5 | 283 | 974 | 57.97 | 16.72 | 0.78 |
| 6 | 339 | 1081 | 75.43 | 21.33 | 0.96 |
| 7 | 394 | 1192 | 86.00 | 24.21 | 1.07 |
| 8 | 451 | 1303 | 94.29 | 26.65 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.29 | 7.69 | 0.48 |
| 2| 1992 | 26.92 | 9.08 | 0.52 |
| 3| 2065 | 27.31 | 9.86 | 0.53 |
| 5| 2446 | 32.27 | 12.59 | 0.61 |
| 10| 3190 | 41.73 | 18.57 | 0.76 |
| 38| 7397 | 96.25 | 52.38 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.84 | 7.39 | 0.41 |
| 2| 804 | 25.13 | 8.69 | 0.45 |
| 3| 1034 | 28.09 | 10.18 | 0.50 |
| 5| 1382 | 32.44 | 12.72 | 0.56 |
| 10| 2027 | 41.76 | 18.66 | 0.71 |
| 41| 6643 | 97.65 | 54.87 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 29.17 | 8.91 | 0.48 |
| 2| 859 | 31.62 | 10.28 | 0.52 |
| 3| 1074 | 32.29 | 11.17 | 0.54 |
| 5| 1368 | 36.40 | 13.66 | 0.60 |
| 10| 2026 | 44.93 | 19.37 | 0.74 |
| 37| 6122 | 98.82 | 52.49 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 955 | 37.84 | 12.60 | 0.59 |
| 5| 1269 | 42.61 | 15.27 | 0.66 |
| 10| 2050 | 54.43 | 21.92 | 0.84 |
| 30| 4714 | 96.04 | 46.71 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5946 | 35.95 | 12.10 | 0.79 |
| 3| 6109 | 44.58 | 15.00 | 0.89 |
| 4| 6373 | 57.00 | 19.30 | 1.03 |
| 5| 6368 | 64.11 | 21.61 | 1.10 |
| 6| 6422 | 71.48 | 23.97 | 1.18 |
| 7| 6624 | 78.14 | 26.27 | 1.26 |
| 8| 6853 | 88.32 | 29.78 | 1.38 |
| 9| 6919 | 95.40 | 32.10 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5868 | 21.66 | 7.36 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

