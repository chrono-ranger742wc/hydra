--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-16 05:33:00.589306204 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.81 | 4.69 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 227 | 858 | 50.85 | 14.60 | 0.70 |
| 5 | 284 | 969 | 62.80 | 17.88 | 0.83 |
| 6 | 337 | 1081 | 65.86 | 19.00 | 0.87 |
| 7 | 393 | 1192 | 79.43 | 22.59 | 1.01 |
| 8 | 449 | 1303 | 92.66 | 26.41 | 1.15 |
| 9 | 506 | 1414 | 92.46 | 26.67 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.37 | 7.71 | 0.48 |
| 2| 1995 | 26.55 | 9.00 | 0.52 |
| 3| 2163 | 28.48 | 10.21 | 0.55 |
| 5| 2330 | 29.92 | 11.94 | 0.58 |
| 10| 3303 | 43.34 | 19.03 | 0.78 |
| 39| 7600 | 96.99 | 53.26 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.81 | 7.37 | 0.42 |
| 2| 811 | 25.08 | 8.68 | 0.45 |
| 3| 878 | 25.55 | 9.49 | 0.46 |
| 5| 1348 | 31.69 | 12.53 | 0.56 |
| 10| 2140 | 43.06 | 19.03 | 0.73 |
| 41| 6395 | 93.77 | 53.80 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 834 | 29.15 | 9.59 | 0.49 |
| 3| 1056 | 32.28 | 11.17 | 0.54 |
| 5| 1272 | 37.02 | 13.77 | 0.60 |
| 10| 1935 | 43.73 | 19.02 | 0.73 |
| 37| 6136 | 98.90 | 52.56 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 998 | 38.66 | 12.84 | 0.60 |
| 5| 1280 | 42.61 | 15.27 | 0.66 |
| 10| 2005 | 53.95 | 21.78 | 0.83 |
| 29| 4909 | 99.01 | 47.00 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.13 | 9.11 | 0.69 |
| 2| 5941 | 35.96 | 12.07 | 0.79 |
| 3| 6138 | 45.62 | 15.38 | 0.90 |
| 4| 6175 | 50.28 | 16.84 | 0.95 |
| 5| 6418 | 64.37 | 21.65 | 1.11 |
| 6| 6420 | 68.36 | 22.95 | 1.15 |
| 7| 6825 | 84.18 | 28.35 | 1.34 |
| 8| 6801 | 87.07 | 29.38 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6856 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2163 | 7126 | 97.33 | 37.23 | 1.52 |

