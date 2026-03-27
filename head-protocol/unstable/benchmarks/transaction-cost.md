--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-27 06:07:42.196061323 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14283 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 168 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 227 | 862 | 48.89 | 14.13 | 0.69 |
| 5 | 284 | 969 | 61.52 | 17.61 | 0.82 |
| 6 | 337 | 1081 | 64.18 | 18.56 | 0.85 |
| 7 | 395 | 1192 | 73.62 | 21.20 | 0.95 |
| 8 | 450 | 1307 | 83.27 | 24.11 | 1.05 |
| 9 | 506 | 1418 | 91.27 | 26.32 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.37 | 7.71 | 0.48 |
| 2| 1954 | 25.47 | 8.70 | 0.50 |
| 3| 2131 | 28.47 | 10.18 | 0.55 |
| 5| 2417 | 32.57 | 12.66 | 0.61 |
| 10| 3067 | 38.73 | 17.72 | 0.73 |
| 41| 7724 | 98.31 | 54.96 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 745 | 23.62 | 8.25 | 0.43 |
| 3| 1026 | 27.81 | 10.11 | 0.49 |
| 5| 1264 | 31.13 | 12.35 | 0.55 |
| 10| 2230 | 43.20 | 19.05 | 0.73 |
| 41| 6494 | 94.37 | 53.98 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.09 | 8.89 | 0.48 |
| 2| 766 | 28.51 | 9.39 | 0.48 |
| 3| 952 | 30.98 | 10.76 | 0.52 |
| 5| 1213 | 34.37 | 13.04 | 0.58 |
| 10| 2057 | 45.84 | 19.64 | 0.75 |
| 35| 5802 | 95.00 | 50.09 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.79 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1307 | 43.36 | 15.49 | 0.67 |
| 10| 2192 | 56.01 | 22.41 | 0.86 |
| 29| 5122 | 99.85 | 47.30 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.00 | 9.08 | 0.69 |
| 2| 5968 | 35.91 | 12.06 | 0.79 |
| 3| 5944 | 38.09 | 12.67 | 0.81 |
| 4| 6160 | 50.10 | 16.77 | 0.95 |
| 5| 6470 | 65.20 | 22.00 | 1.12 |
| 6| 6621 | 73.48 | 24.80 | 1.21 |
| 7| 6549 | 74.77 | 25.03 | 1.22 |
| 8| 7165 | 99.01 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.42 | 5.80 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2158 | 7121 | 96.88 | 37.08 | 1.51 |

