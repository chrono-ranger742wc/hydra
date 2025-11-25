--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-25 05:37:33.64796687 UTC |
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
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 112 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.16 | 11.66 | 0.59 |
| 4 | 226 | 858 | 53.74 | 15.29 | 0.73 |
| 5 | 282 | 969 | 55.86 | 16.18 | 0.76 |
| 6 | 338 | 1081 | 66.08 | 19.05 | 0.87 |
| 7 | 395 | 1196 | 80.55 | 22.91 | 1.02 |
| 8 | 449 | 1303 | 85.32 | 24.60 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.80 | 8.49 | 0.49 |
| 3| 2115 | 27.97 | 10.06 | 0.54 |
| 5| 2487 | 32.98 | 12.80 | 0.62 |
| 10| 3238 | 42.82 | 18.87 | 0.77 |
| 40| 7668 | 98.47 | 54.35 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.57 | 7.33 | 0.41 |
| 2| 833 | 25.45 | 8.77 | 0.46 |
| 3| 896 | 25.55 | 9.49 | 0.46 |
| 5| 1235 | 30.25 | 12.11 | 0.54 |
| 10| 2026 | 38.98 | 17.90 | 0.68 |
| 41| 6567 | 97.39 | 54.76 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 918 | 32.69 | 11.22 | 0.54 |
| 5| 1257 | 37.06 | 13.79 | 0.60 |
| 10| 1900 | 46.02 | 19.61 | 0.75 |
| 35| 5815 | 95.96 | 50.36 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.87 | 10.16 | 0.53 |
| 2| 863 | 36.56 | 11.60 | 0.57 |
| 3| 1023 | 38.62 | 12.83 | 0.60 |
| 5| 1267 | 42.68 | 15.29 | 0.66 |
| 10| 2151 | 55.65 | 22.30 | 0.86 |
| 29| 4934 | 98.80 | 46.96 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 27.00 | 9.08 | 0.69 |
| 2| 5897 | 32.49 | 10.87 | 0.75 |
| 3| 6115 | 45.95 | 15.47 | 0.90 |
| 4| 6244 | 51.02 | 17.15 | 0.96 |
| 5| 6388 | 61.15 | 20.59 | 1.07 |
| 6| 6449 | 65.86 | 22.10 | 1.13 |
| 7| 6592 | 76.13 | 25.60 | 1.24 |
| 8| 7067 | 96.35 | 32.65 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.44 | 14.43 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.24 | 37.65 | 1.53 |

