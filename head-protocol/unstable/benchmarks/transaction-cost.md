--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-07 05:25:10.752756876 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6242 | 14.84 | 4.71 | 0.58 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 168 | 747 | 42.38 | 12.19 | 0.61 |
| 4 | 228 | 858 | 53.38 | 15.23 | 0.73 |
| 5 | 284 | 969 | 63.23 | 18.02 | 0.83 |
| 6 | 337 | 1081 | 68.16 | 19.56 | 0.89 |
| 7 | 394 | 1196 | 86.87 | 24.56 | 1.08 |
| 8 | 448 | 1303 | 86.97 | 24.84 | 1.09 |
| 9 | 506 | 1414 | 88.72 | 25.71 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2148 | 28.17 | 10.11 | 0.55 |
| 5| 2510 | 33.34 | 12.89 | 0.62 |
| 10| 3023 | 38.48 | 17.66 | 0.72 |
| 38| 7392 | 94.51 | 51.90 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.77 | 7.36 | 0.42 |
| 2| 699 | 22.62 | 7.97 | 0.42 |
| 3| 964 | 27.10 | 9.90 | 0.48 |
| 5| 1214 | 30.10 | 12.06 | 0.53 |
| 10| 2081 | 39.64 | 18.06 | 0.69 |
| 40| 6527 | 96.97 | 54.02 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 820 | 31.69 | 10.29 | 0.52 |
| 3| 952 | 30.82 | 10.73 | 0.52 |
| 5| 1248 | 35.12 | 13.27 | 0.58 |
| 10| 2210 | 47.04 | 20.02 | 0.77 |
| 34| 5587 | 93.09 | 48.86 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.83 | 10.16 | 0.53 |
| 2| 866 | 36.56 | 11.60 | 0.57 |
| 3| 960 | 37.87 | 12.61 | 0.59 |
| 5| 1251 | 42.65 | 15.28 | 0.66 |
| 10| 2243 | 56.87 | 22.66 | 0.87 |
| 29| 5038 | 99.71 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.00 | 9.06 | 0.69 |
| 2| 6013 | 37.05 | 12.50 | 0.80 |
| 3| 6190 | 45.86 | 15.44 | 0.90 |
| 4| 6143 | 50.49 | 16.93 | 0.95 |
| 5| 6435 | 63.92 | 21.56 | 1.11 |
| 6| 6427 | 66.10 | 22.13 | 1.13 |
| 7| 6769 | 85.05 | 28.74 | 1.34 |
| 8| 6969 | 90.81 | 30.61 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

