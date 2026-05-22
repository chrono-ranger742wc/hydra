--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-22 08:09:01.006838594 UTC |
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
| 2| 6041 | 13.01 | 4.14 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 42.50 | 12.23 | 0.61 |
| 4 | 227 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 282 | 969 | 56.37 | 16.34 | 0.77 |
| 6 | 340 | 1081 | 69.46 | 19.82 | 0.90 |
| 7 | 395 | 1196 | 86.94 | 24.49 | 1.08 |
| 8 | 452 | 1303 | 81.15 | 23.56 | 1.03 |
| 9 | 507 | 1414 | 94.32 | 27.11 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1928 | 25.47 | 8.70 | 0.50 |
| 3| 2118 | 28.31 | 10.14 | 0.55 |
| 5| 2427 | 32.33 | 12.60 | 0.61 |
| 10| 3026 | 38.90 | 17.76 | 0.73 |
| 39| 7647 | 99.63 | 54.00 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.38 | 0.42 |
| 2| 788 | 25.59 | 8.80 | 0.46 |
| 3| 899 | 25.74 | 9.52 | 0.47 |
| 5| 1258 | 30.21 | 12.09 | 0.54 |
| 10| 2091 | 41.80 | 18.69 | 0.71 |
| 39| 6421 | 94.90 | 52.76 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 828 | 29.18 | 9.60 | 0.49 |
| 3| 1018 | 31.69 | 10.98 | 0.53 |
| 5| 1334 | 38.48 | 14.22 | 0.62 |
| 10| 2060 | 48.41 | 20.34 | 0.78 |
| 36| 6131 | 98.77 | 51.89 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 954 | 37.91 | 12.62 | 0.59 |
| 5| 1283 | 42.49 | 15.24 | 0.66 |
| 10| 1901 | 52.49 | 21.34 | 0.81 |
| 29| 4920 | 99.20 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 6019 | 37.09 | 12.49 | 0.80 |
| 3| 6019 | 43.88 | 14.72 | 0.88 |
| 4| 6280 | 55.72 | 18.85 | 1.01 |
| 5| 6513 | 64.89 | 21.91 | 1.12 |
| 6| 6442 | 68.47 | 22.90 | 1.15 |
| 7| 6733 | 81.10 | 27.37 | 1.30 |
| 8| 6872 | 89.92 | 30.38 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 567 | 6171 | 40.39 | 14.75 | 0.85 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

