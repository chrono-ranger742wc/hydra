--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-13 08:28:46.859988308 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.88 | 4.72 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 751 | 41.51 | 12.02 | 0.61 |
| 4 | 226 | 858 | 49.50 | 14.30 | 0.69 |
| 5 | 283 | 969 | 64.04 | 18.17 | 0.84 |
| 6 | 338 | 1081 | 68.28 | 19.62 | 0.89 |
| 7 | 393 | 1196 | 80.97 | 23.06 | 1.02 |
| 8 | 452 | 1303 | 89.58 | 25.57 | 1.12 |
| 9 | 506 | 1414 | 98.90 | 28.21 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2119 | 28.47 | 10.18 | 0.55 |
| 5| 2428 | 32.07 | 12.54 | 0.61 |
| 10| 3096 | 39.70 | 18.01 | 0.74 |
| 41| 7725 | 98.57 | 55.00 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.81 | 7.37 | 0.42 |
| 2| 832 | 25.53 | 8.79 | 0.46 |
| 3| 921 | 25.52 | 9.47 | 0.47 |
| 5| 1199 | 29.03 | 11.76 | 0.52 |
| 10| 2194 | 42.74 | 18.92 | 0.73 |
| 42| 6675 | 98.93 | 55.88 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 803 | 30.98 | 10.08 | 0.51 |
| 3| 1047 | 32.36 | 11.19 | 0.54 |
| 5| 1168 | 33.58 | 12.81 | 0.57 |
| 10| 2080 | 48.64 | 20.40 | 0.78 |
| 36| 5802 | 99.81 | 52.00 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.83 | 10.15 | 0.53 |
| 2| 885 | 36.60 | 11.61 | 0.57 |
| 3| 1101 | 39.22 | 13.02 | 0.61 |
| 5| 1253 | 42.72 | 15.30 | 0.66 |
| 10| 2072 | 54.85 | 22.04 | 0.84 |
| 30| 4942 | 98.89 | 47.57 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 26.92 | 9.04 | 0.69 |
| 2| 5997 | 37.09 | 12.49 | 0.80 |
| 3| 6094 | 44.96 | 15.13 | 0.89 |
| 4| 6265 | 52.38 | 17.63 | 0.98 |
| 5| 6519 | 62.59 | 21.12 | 1.10 |
| 6| 6670 | 74.92 | 25.35 | 1.23 |
| 7| 6650 | 81.88 | 27.58 | 1.30 |
| 8| 6941 | 95.26 | 32.18 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6005 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.37 | 14.06 | 0.83 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

