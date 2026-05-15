--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-15 07:19:22.339177571 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6238 | 14.76 | 4.67 | 0.58 |
| 5| 6638 | 19.08 | 6.04 | 0.64 |
| 10| 7650 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 227 | 858 | 53.69 | 15.30 | 0.73 |
| 5 | 282 | 969 | 56.02 | 16.25 | 0.76 |
| 6 | 337 | 1081 | 64.50 | 18.72 | 0.85 |
| 7 | 392 | 1192 | 82.51 | 23.43 | 1.04 |
| 8 | 451 | 1303 | 92.05 | 26.11 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1998 | 26.76 | 9.04 | 0.52 |
| 3| 2130 | 28.31 | 10.14 | 0.55 |
| 5| 2395 | 31.49 | 12.36 | 0.60 |
| 10| 3107 | 39.02 | 17.81 | 0.73 |
| 41| 7760 | 99.76 | 55.37 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.84 | 7.38 | 0.41 |
| 2| 755 | 23.58 | 8.22 | 0.43 |
| 3| 945 | 26.71 | 9.81 | 0.48 |
| 5| 1327 | 31.18 | 12.36 | 0.55 |
| 10| 1961 | 38.45 | 17.74 | 0.68 |
| 42| 6709 | 96.92 | 55.33 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.50 | 8.46 | 0.46 |
| 2| 805 | 30.98 | 10.08 | 0.51 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1257 | 34.89 | 13.21 | 0.58 |
| 10| 2252 | 47.71 | 20.22 | 0.78 |
| 34| 5614 | 98.81 | 50.41 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 849 | 36.60 | 11.61 | 0.57 |
| 3| 900 | 37.16 | 12.39 | 0.58 |
| 5| 1308 | 43.35 | 15.49 | 0.67 |
| 10| 2041 | 54.10 | 21.82 | 0.83 |
| 28| 5091 | 99.39 | 46.51 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 5968 | 35.92 | 12.05 | 0.79 |
| 3| 6020 | 43.87 | 14.70 | 0.88 |
| 4| 6170 | 50.28 | 16.86 | 0.95 |
| 5| 6343 | 59.27 | 19.87 | 1.05 |
| 6| 6603 | 74.32 | 25.07 | 1.22 |
| 7| 6672 | 82.38 | 27.73 | 1.31 |
| 8| 6826 | 92.75 | 31.29 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 99.38 | 38.04 | 1.54 |

