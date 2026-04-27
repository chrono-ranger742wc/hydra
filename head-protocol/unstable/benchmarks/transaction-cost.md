--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-27 06:52:06.043672783 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.81 | 4.69 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.23 | 9.22 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.46 | 11.98 | 0.60 |
| 4 | 227 | 858 | 48.20 | 13.99 | 0.68 |
| 5 | 281 | 969 | 64.58 | 18.36 | 0.85 |
| 6 | 337 | 1081 | 75.00 | 21.15 | 0.96 |
| 7 | 395 | 1192 | 72.91 | 21.17 | 0.94 |
| 8 | 449 | 1307 | 80.38 | 23.21 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.29 | 7.69 | 0.48 |
| 2| 1979 | 26.59 | 9.01 | 0.52 |
| 3| 2126 | 27.86 | 10.03 | 0.54 |
| 5| 2379 | 31.22 | 12.29 | 0.60 |
| 10| 3139 | 40.52 | 18.23 | 0.75 |
| 39| 7250 | 90.42 | 51.43 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.57 | 7.31 | 0.41 |
| 2| 735 | 22.56 | 7.94 | 0.42 |
| 3| 960 | 28.15 | 10.18 | 0.49 |
| 5| 1172 | 28.16 | 11.51 | 0.51 |
| 10| 2086 | 41.86 | 18.70 | 0.72 |
| 42| 6758 | 99.06 | 55.93 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.50 | 8.46 | 0.46 |
| 2| 842 | 29.18 | 9.60 | 0.49 |
| 3| 970 | 33.47 | 11.46 | 0.55 |
| 5| 1301 | 35.68 | 13.45 | 0.59 |
| 10| 2209 | 47.33 | 20.11 | 0.77 |
| 37| 6075 | 99.16 | 52.63 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 815 | 35.89 | 11.39 | 0.56 |
| 3| 899 | 37.20 | 12.40 | 0.58 |
| 5| 1154 | 41.26 | 14.85 | 0.64 |
| 10| 2064 | 54.78 | 22.02 | 0.84 |
| 27| 4943 | 97.42 | 45.35 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 6002 | 36.84 | 12.43 | 0.80 |
| 3| 6265 | 46.73 | 15.82 | 0.92 |
| 4| 6232 | 53.45 | 18.01 | 0.99 |
| 5| 6469 | 65.19 | 22.04 | 1.12 |
| 6| 6538 | 71.83 | 24.09 | 1.19 |
| 7| 6584 | 79.02 | 26.56 | 1.27 |
| 8| 6840 | 87.33 | 29.44 | 1.37 |
| 9| 6930 | 96.81 | 32.54 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7159 | 99.31 | 38.01 | 1.54 |

