--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-22 05:06:18.653547728 UTC |
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
| 1| 5834 | 10.78 | 3.43 | 0.52 |
| 2| 6038 | 13.01 | 4.14 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 42.62 | 12.25 | 0.62 |
| 4 | 227 | 858 | 53.77 | 15.32 | 0.73 |
| 5 | 281 | 974 | 59.85 | 17.23 | 0.80 |
| 6 | 340 | 1085 | 66.15 | 19.15 | 0.87 |
| 7 | 395 | 1192 | 72.32 | 20.94 | 0.94 |
| 8 | 451 | 1303 | 94.16 | 26.67 | 1.16 |
| 10 | 560 | 1525 | 96.77 | 28.04 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.44 | 8.41 | 0.49 |
| 3| 2091 | 26.94 | 9.77 | 0.53 |
| 5| 2348 | 30.30 | 12.03 | 0.59 |
| 10| 3023 | 38.78 | 17.74 | 0.72 |
| 39| 7537 | 98.03 | 53.53 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.50 | 7.30 | 0.41 |
| 2| 762 | 24.31 | 8.46 | 0.44 |
| 3| 974 | 26.06 | 9.59 | 0.47 |
| 5| 1315 | 30.87 | 12.29 | 0.55 |
| 10| 2101 | 42.22 | 18.79 | 0.72 |
| 42| 6584 | 98.46 | 55.69 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.51 | 8.47 | 0.46 |
| 2| 843 | 29.22 | 9.61 | 0.49 |
| 3| 988 | 33.47 | 11.45 | 0.55 |
| 5| 1228 | 34.41 | 13.05 | 0.58 |
| 10| 2205 | 46.73 | 19.92 | 0.77 |
| 38| 6192 | 99.99 | 53.48 | 1.62 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.16 | 0.53 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 988 | 38.55 | 12.81 | 0.60 |
| 5| 1334 | 44.15 | 15.73 | 0.68 |
| 10| 2063 | 54.54 | 21.95 | 0.84 |
| 29| 4902 | 97.85 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5874 | 32.61 | 10.87 | 0.75 |
| 3| 6183 | 45.91 | 15.46 | 0.90 |
| 4| 6315 | 54.91 | 18.49 | 1.01 |
| 5| 6471 | 65.38 | 22.07 | 1.12 |
| 6| 6655 | 73.96 | 25.02 | 1.22 |
| 7| 6785 | 83.18 | 28.04 | 1.32 |
| 8| 6987 | 94.38 | 31.82 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 570 | 6175 | 40.58 | 14.82 | 0.86 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

