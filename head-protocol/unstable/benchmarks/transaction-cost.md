--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-09 08:10:18.281108469 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 227 | 858 | 52.65 | 15.08 | 0.72 |
| 5 | 283 | 974 | 56.14 | 16.28 | 0.76 |
| 6 | 340 | 1081 | 68.37 | 19.65 | 0.89 |
| 7 | 392 | 1192 | 78.50 | 22.51 | 1.00 |
| 8 | 451 | 1303 | 85.22 | 24.48 | 1.07 |
| 10 | 560 | 1525 | 96.66 | 27.96 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2015 | 26.36 | 9.59 | 0.52 |
| 5| 2520 | 33.29 | 12.87 | 0.62 |
| 10| 3151 | 40.73 | 18.29 | 0.75 |
| 40| 7657 | 96.83 | 53.89 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.84 | 7.38 | 0.42 |
| 2| 848 | 25.40 | 8.77 | 0.46 |
| 3| 878 | 25.09 | 9.31 | 0.46 |
| 5| 1250 | 30.10 | 12.07 | 0.54 |
| 10| 1920 | 37.31 | 17.40 | 0.66 |
| 39| 6308 | 93.10 | 52.26 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 857 | 31.70 | 10.30 | 0.52 |
| 3| 942 | 32.79 | 11.25 | 0.54 |
| 5| 1399 | 36.51 | 13.69 | 0.61 |
| 10| 2057 | 44.75 | 19.33 | 0.74 |
| 38| 6109 | 99.51 | 53.35 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.83 | 10.15 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 1042 | 39.26 | 13.03 | 0.61 |
| 5| 1158 | 41.22 | 14.85 | 0.64 |
| 10| 2004 | 53.31 | 21.58 | 0.82 |
| 29| 4902 | 98.61 | 46.90 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 27.08 | 9.09 | 0.69 |
| 2| 6000 | 37.05 | 12.48 | 0.80 |
| 3| 6102 | 44.58 | 15.00 | 0.89 |
| 4| 6194 | 51.76 | 17.39 | 0.97 |
| 5| 6325 | 59.28 | 19.88 | 1.05 |
| 6| 6521 | 69.90 | 23.48 | 1.17 |
| 7| 6890 | 85.30 | 28.90 | 1.35 |
| 8| 6876 | 86.32 | 29.06 | 1.36 |
| 9| 6915 | 97.56 | 32.77 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1710 | 6856 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2164 | 7126 | 96.44 | 36.92 | 1.51 |

