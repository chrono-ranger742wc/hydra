--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-12 07:07:13.160165315 UTC |
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
| 1| 5838 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 227 | 858 | 47.56 | 13.81 | 0.67 |
| 5 | 283 | 969 | 62.43 | 17.75 | 0.83 |
| 6 | 339 | 1081 | 65.41 | 18.85 | 0.86 |
| 7 | 393 | 1196 | 78.28 | 22.37 | 1.00 |
| 8 | 451 | 1303 | 99.54 | 28.06 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1750 | 22.92 | 7.32 | 0.47 |
| 2| 1945 | 25.76 | 8.76 | 0.51 |
| 3| 2017 | 26.40 | 9.60 | 0.52 |
| 5| 2425 | 32.21 | 12.57 | 0.61 |
| 10| 3229 | 42.52 | 18.80 | 0.77 |
| 40| 7570 | 95.16 | 53.43 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.77 | 7.36 | 0.42 |
| 2| 775 | 24.32 | 8.46 | 0.44 |
| 3| 951 | 27.06 | 9.89 | 0.48 |
| 5| 1295 | 30.19 | 12.08 | 0.54 |
| 10| 1942 | 37.39 | 17.43 | 0.66 |
| 39| 6321 | 94.21 | 52.59 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 806 | 30.91 | 10.06 | 0.51 |
| 3| 919 | 32.79 | 11.25 | 0.54 |
| 5| 1206 | 36.42 | 13.59 | 0.60 |
| 10| 2023 | 48.14 | 20.27 | 0.77 |
| 36| 5779 | 93.86 | 50.38 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.16 | 0.53 |
| 2| 911 | 36.52 | 11.59 | 0.57 |
| 3| 993 | 38.59 | 12.82 | 0.60 |
| 5| 1307 | 43.28 | 15.47 | 0.67 |
| 10| 2371 | 58.39 | 23.12 | 0.89 |
| 29| 4818 | 97.29 | 46.47 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.05 | 9.07 | 0.69 |
| 2| 5998 | 36.73 | 12.40 | 0.80 |
| 3| 6018 | 41.33 | 13.83 | 0.85 |
| 4| 6248 | 53.95 | 18.13 | 0.99 |
| 5| 6511 | 64.60 | 21.79 | 1.12 |
| 6| 6652 | 71.13 | 23.99 | 1.19 |
| 7| 6814 | 83.49 | 28.08 | 1.33 |
| 8| 6898 | 92.07 | 31.18 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

