--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-31 05:27:50.011662717 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6042 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.90 | 12.57 | 0.63 |
| 4 | 226 | 862 | 48.05 | 13.96 | 0.68 |
| 5 | 283 | 969 | 63.94 | 18.12 | 0.84 |
| 6 | 339 | 1085 | 73.06 | 20.72 | 0.94 |
| 7 | 395 | 1196 | 83.56 | 23.67 | 1.05 |
| 8 | 450 | 1303 | 89.99 | 25.62 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 1957 | 25.84 | 8.78 | 0.51 |
| 3| 2057 | 27.47 | 9.90 | 0.53 |
| 5| 2279 | 29.26 | 11.74 | 0.57 |
| 10| 3252 | 42.70 | 18.84 | 0.77 |
| 38| 7170 | 92.14 | 51.23 | 1.58 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.54 | 7.31 | 0.41 |
| 2| 726 | 22.56 | 7.94 | 0.42 |
| 3| 897 | 25.45 | 9.45 | 0.46 |
| 5| 1312 | 30.99 | 12.32 | 0.55 |
| 10| 2004 | 39.83 | 18.11 | 0.69 |
| 42| 6657 | 96.96 | 55.36 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 820 | 29.26 | 9.62 | 0.49 |
| 3| 995 | 31.65 | 10.97 | 0.53 |
| 5| 1309 | 35.72 | 13.46 | 0.59 |
| 10| 2090 | 48.31 | 20.30 | 0.78 |
| 35| 5606 | 93.96 | 49.73 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.92 | 11.40 | 0.56 |
| 3| 941 | 37.95 | 12.63 | 0.59 |
| 5| 1209 | 41.89 | 15.05 | 0.65 |
| 10| 2025 | 54.09 | 21.83 | 0.83 |
| 29| 4737 | 95.97 | 46.09 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.09 | 9.08 | 0.69 |
| 2| 6017 | 36.93 | 12.44 | 0.80 |
| 3| 6221 | 47.14 | 15.93 | 0.92 |
| 4| 6220 | 53.97 | 18.12 | 0.99 |
| 5| 6395 | 63.71 | 21.44 | 1.10 |
| 6| 6689 | 76.66 | 25.88 | 1.25 |
| 7| 6732 | 82.09 | 27.66 | 1.31 |
| 8| 6980 | 94.35 | 31.88 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1136 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2161 | 7123 | 96.44 | 36.92 | 1.51 |

