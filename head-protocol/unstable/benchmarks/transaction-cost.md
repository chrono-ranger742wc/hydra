--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-23 05:51:16.226232792 UTC |
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
| 2| 6035 | 12.42 | 3.93 | 0.54 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7651 | 28.80 | 9.07 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 43.49 | 12.45 | 0.62 |
| 4 | 226 | 858 | 50.87 | 14.62 | 0.70 |
| 5 | 281 | 974 | 62.54 | 17.81 | 0.83 |
| 6 | 336 | 1081 | 66.27 | 19.17 | 0.87 |
| 7 | 394 | 1192 | 84.57 | 23.88 | 1.06 |
| 8 | 450 | 1303 | 80.83 | 23.43 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1887 | 24.77 | 8.48 | 0.49 |
| 3| 2158 | 28.40 | 10.19 | 0.55 |
| 5| 2414 | 32.03 | 12.53 | 0.61 |
| 10| 3259 | 42.30 | 18.71 | 0.77 |
| 39| 7490 | 97.15 | 53.31 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 840 | 25.57 | 8.80 | 0.46 |
| 3| 888 | 25.58 | 9.50 | 0.46 |
| 5| 1237 | 29.12 | 11.78 | 0.52 |
| 10| 1948 | 38.22 | 17.68 | 0.67 |
| 40| 6617 | 98.92 | 54.55 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.54 | 8.47 | 0.46 |
| 2| 811 | 30.98 | 10.08 | 0.51 |
| 3| 921 | 32.72 | 11.23 | 0.54 |
| 5| 1263 | 34.55 | 13.11 | 0.58 |
| 10| 2184 | 48.68 | 20.43 | 0.79 |
| 35| 5762 | 99.65 | 51.32 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.15 | 0.53 |
| 2| 836 | 35.85 | 11.38 | 0.56 |
| 3| 1050 | 39.18 | 13.01 | 0.61 |
| 5| 1274 | 42.64 | 15.28 | 0.66 |
| 10| 2077 | 54.58 | 21.97 | 0.84 |
| 28| 4997 | 98.55 | 46.24 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 26.97 | 9.06 | 0.69 |
| 2| 6008 | 37.04 | 12.48 | 0.80 |
| 3| 5954 | 40.40 | 13.45 | 0.84 |
| 4| 6310 | 55.81 | 18.86 | 1.01 |
| 5| 6463 | 64.78 | 21.89 | 1.12 |
| 6| 6713 | 77.08 | 26.08 | 1.26 |
| 7| 6705 | 79.86 | 26.84 | 1.28 |
| 8| 7110 | 95.08 | 32.08 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2222 | 7162 | 98.68 | 37.80 | 1.54 |

