--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-22 05:33:13.481693893 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 171 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 225 | 858 | 51.05 | 14.67 | 0.71 |
| 5 | 283 | 969 | 56.48 | 16.40 | 0.77 |
| 6 | 338 | 1081 | 67.97 | 19.47 | 0.89 |
| 7 | 397 | 1192 | 82.85 | 23.51 | 1.04 |
| 8 | 449 | 1303 | 87.61 | 25.10 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 1929 | 25.51 | 8.70 | 0.50 |
| 3| 2102 | 28.43 | 10.17 | 0.55 |
| 5| 2325 | 30.12 | 11.99 | 0.58 |
| 10| 3128 | 39.69 | 17.99 | 0.74 |
| 39| 7355 | 93.10 | 52.17 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.53 | 7.30 | 0.41 |
| 2| 695 | 22.58 | 7.96 | 0.42 |
| 3| 832 | 24.13 | 9.04 | 0.45 |
| 5| 1188 | 30.08 | 12.06 | 0.53 |
| 10| 2068 | 40.82 | 18.39 | 0.70 |
| 40| 6339 | 93.06 | 52.92 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.51 | 8.47 | 0.46 |
| 2| 791 | 30.95 | 10.07 | 0.51 |
| 3| 1006 | 31.65 | 10.97 | 0.53 |
| 5| 1297 | 35.69 | 13.45 | 0.59 |
| 10| 2022 | 44.59 | 19.29 | 0.74 |
| 36| 6178 | 99.79 | 52.19 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.16 | 0.53 |
| 2| 849 | 36.60 | 11.61 | 0.57 |
| 3| 961 | 37.84 | 12.60 | 0.59 |
| 5| 1334 | 43.17 | 15.45 | 0.67 |
| 10| 1963 | 53.50 | 21.63 | 0.82 |
| 29| 5038 | 99.89 | 47.31 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.13 | 9.11 | 0.69 |
| 2| 5866 | 32.69 | 10.93 | 0.75 |
| 3| 5999 | 43.96 | 14.71 | 0.88 |
| 4| 6276 | 51.19 | 17.22 | 0.96 |
| 5| 6475 | 64.68 | 21.76 | 1.11 |
| 6| 6659 | 75.32 | 25.39 | 1.23 |
| 7| 6756 | 80.96 | 27.29 | 1.30 |
| 8| 7041 | 95.44 | 32.21 | 1.46 |
| 9| 7031 | 99.80 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1136 | 6511 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

