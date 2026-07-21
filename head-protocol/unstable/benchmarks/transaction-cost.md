--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-21 07:01:06.652652852 UTC |
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
| 1| 5834 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 15.24 | 4.85 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.76 | 12.53 | 0.63 |
| 4 | 228 | 858 | 52.58 | 15.06 | 0.72 |
| 5 | 281 | 969 | 57.57 | 16.62 | 0.78 |
| 6 | 338 | 1081 | 71.58 | 20.41 | 0.92 |
| 7 | 393 | 1192 | 74.99 | 21.63 | 0.96 |
| 8 | 451 | 1307 | 96.91 | 27.33 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.29 | 7.69 | 0.48 |
| 2| 1887 | 24.80 | 8.49 | 0.49 |
| 3| 2092 | 27.02 | 9.79 | 0.53 |
| 5| 2358 | 29.97 | 11.95 | 0.58 |
| 10| 3260 | 42.87 | 18.88 | 0.78 |
| 40| 7686 | 99.59 | 54.68 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.57 | 7.31 | 0.41 |
| 2| 788 | 24.32 | 8.46 | 0.44 |
| 3| 930 | 26.09 | 9.61 | 0.47 |
| 5| 1151 | 28.84 | 11.73 | 0.52 |
| 10| 2034 | 40.68 | 18.34 | 0.70 |
| 38| 6420 | 96.56 | 52.58 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 876 | 29.82 | 9.80 | 0.50 |
| 3| 1038 | 34.03 | 11.63 | 0.55 |
| 5| 1438 | 36.98 | 13.85 | 0.61 |
| 10| 2008 | 47.63 | 20.11 | 0.77 |
| 36| 5981 | 97.83 | 51.58 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 1019 | 38.55 | 12.81 | 0.60 |
| 5| 1281 | 42.57 | 15.26 | 0.66 |
| 10| 1950 | 53.31 | 21.58 | 0.82 |
| 30| 4827 | 98.28 | 47.36 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.13 | 9.10 | 0.69 |
| 2| 5910 | 35.80 | 12.03 | 0.79 |
| 3| 6183 | 46.98 | 15.90 | 0.92 |
| 4| 6172 | 50.71 | 16.98 | 0.95 |
| 5| 6435 | 65.03 | 21.92 | 1.12 |
| 6| 6785 | 75.98 | 25.74 | 1.25 |
| 7| 6597 | 78.93 | 26.54 | 1.27 |
| 8| 6753 | 89.24 | 30.05 | 1.38 |
| 9| 7036 | 99.58 | 33.50 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2217 | 7157 | 97.61 | 37.43 | 1.52 |

