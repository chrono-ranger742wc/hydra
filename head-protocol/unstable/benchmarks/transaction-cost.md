--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-25 05:20:04.828310233 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.07 | 11.87 | 0.60 |
| 4 | 226 | 858 | 52.47 | 15.03 | 0.72 |
| 5 | 283 | 974 | 57.63 | 16.67 | 0.78 |
| 6 | 339 | 1081 | 64.06 | 18.61 | 0.85 |
| 7 | 394 | 1192 | 82.89 | 23.52 | 1.04 |
| 8 | 451 | 1303 | 99.03 | 27.83 | 1.21 |
| 9 | 506 | 1414 | 90.54 | 26.22 | 1.13 |
| 10 | 560 | 1525 | 98.99 | 28.77 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.37 | 7.71 | 0.48 |
| 2| 1919 | 25.92 | 8.80 | 0.51 |
| 3| 2013 | 26.32 | 9.58 | 0.52 |
| 5| 2332 | 30.45 | 12.07 | 0.59 |
| 10| 3224 | 42.12 | 18.66 | 0.77 |
| 41| 7634 | 96.68 | 54.52 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.84 | 7.38 | 0.42 |
| 2| 730 | 22.60 | 7.95 | 0.42 |
| 3| 909 | 25.14 | 9.33 | 0.46 |
| 5| 1230 | 29.59 | 11.94 | 0.53 |
| 10| 2085 | 42.84 | 18.96 | 0.72 |
| 40| 6403 | 97.89 | 54.22 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 837 | 29.22 | 9.61 | 0.49 |
| 3| 903 | 30.26 | 10.55 | 0.51 |
| 5| 1280 | 37.70 | 13.98 | 0.61 |
| 10| 2086 | 48.79 | 20.46 | 0.78 |
| 36| 5752 | 99.63 | 51.95 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.15 | 0.53 |
| 2| 833 | 35.92 | 11.40 | 0.56 |
| 3| 1054 | 39.26 | 13.03 | 0.61 |
| 5| 1268 | 42.68 | 15.29 | 0.66 |
| 10| 1903 | 52.71 | 21.39 | 0.81 |
| 29| 4957 | 99.41 | 47.10 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.04 | 9.09 | 0.69 |
| 2| 5987 | 36.81 | 12.41 | 0.80 |
| 3| 6184 | 46.02 | 15.50 | 0.91 |
| 4| 6176 | 50.35 | 16.92 | 0.95 |
| 5| 6265 | 59.19 | 19.91 | 1.05 |
| 6| 6597 | 73.15 | 24.66 | 1.21 |
| 7| 6766 | 83.46 | 28.13 | 1.33 |
| 8| 6851 | 88.32 | 29.81 | 1.38 |
| 9| 6888 | 93.67 | 31.46 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6174 | 37.29 | 13.69 | 0.82 |
| 10 | 20 | 1138 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1705 | 6851 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2221 | 7161 | 99.38 | 38.04 | 1.54 |

