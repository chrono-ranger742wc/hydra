--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-28 05:55:50.095212774 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.53 | 3.97 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 171 | 747 | 41.24 | 11.91 | 0.60 |
| 4 | 225 | 862 | 53.76 | 15.32 | 0.73 |
| 5 | 285 | 969 | 64.30 | 18.27 | 0.84 |
| 6 | 340 | 1085 | 72.30 | 20.62 | 0.93 |
| 7 | 395 | 1192 | 84.16 | 23.73 | 1.05 |
| 8 | 449 | 1303 | 94.84 | 26.88 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.47 | 8.41 | 0.49 |
| 3| 2060 | 26.90 | 9.76 | 0.53 |
| 5| 2352 | 29.84 | 11.92 | 0.58 |
| 10| 3121 | 39.84 | 18.03 | 0.74 |
| 41| 7557 | 96.11 | 54.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.50 | 7.29 | 0.41 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 857 | 24.07 | 9.03 | 0.45 |
| 5| 1090 | 27.15 | 11.22 | 0.50 |
| 10| 1994 | 39.61 | 18.06 | 0.69 |
| 41| 6607 | 96.97 | 54.68 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 817 | 29.22 | 9.61 | 0.49 |
| 3| 906 | 30.26 | 10.55 | 0.51 |
| 5| 1260 | 37.58 | 13.95 | 0.61 |
| 10| 1957 | 44.14 | 19.14 | 0.73 |
| 37| 5972 | 97.82 | 52.18 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 1016 | 38.59 | 12.82 | 0.60 |
| 5| 1257 | 42.61 | 15.27 | 0.66 |
| 10| 2031 | 54.09 | 21.82 | 0.83 |
| 28| 4474 | 92.66 | 44.46 | 1.42 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 27.08 | 9.08 | 0.69 |
| 2| 6013 | 37.16 | 12.54 | 0.81 |
| 3| 6125 | 44.88 | 15.06 | 0.89 |
| 4| 6027 | 45.88 | 15.27 | 0.90 |
| 5| 6392 | 63.53 | 21.31 | 1.10 |
| 6| 6417 | 68.78 | 23.12 | 1.15 |
| 7| 6772 | 82.64 | 27.84 | 1.32 |
| 8| 6815 | 85.35 | 28.77 | 1.35 |
| 9| 6830 | 92.68 | 31.18 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 20 | 1135 | 6509 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1705 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.05 | 37.58 | 1.53 |

