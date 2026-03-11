--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-11 05:35:43.064306359 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 171 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 227 | 858 | 53.82 | 15.31 | 0.73 |
| 5 | 283 | 969 | 57.62 | 16.63 | 0.78 |
| 6 | 338 | 1081 | 64.43 | 18.66 | 0.85 |
| 7 | 393 | 1192 | 85.31 | 24.19 | 1.07 |
| 8 | 450 | 1307 | 93.79 | 26.48 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1881 | 24.43 | 8.40 | 0.49 |
| 3| 2131 | 28.02 | 10.07 | 0.54 |
| 5| 2455 | 32.41 | 12.62 | 0.61 |
| 10| 3215 | 42.22 | 18.70 | 0.77 |
| 38| 7319 | 94.87 | 51.99 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.77 | 7.36 | 0.42 |
| 2| 764 | 23.62 | 8.24 | 0.43 |
| 3| 949 | 26.84 | 9.83 | 0.48 |
| 5| 1409 | 33.54 | 13.04 | 0.58 |
| 10| 2038 | 39.41 | 17.99 | 0.69 |
| 41| 6678 | 99.41 | 55.33 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.51 | 8.47 | 0.46 |
| 2| 782 | 30.90 | 10.06 | 0.51 |
| 3| 907 | 30.15 | 10.52 | 0.51 |
| 5| 1248 | 37.13 | 13.80 | 0.60 |
| 10| 1986 | 44.41 | 19.22 | 0.74 |
| 36| 6136 | 98.26 | 51.71 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.79 | 10.15 | 0.53 |
| 2| 811 | 35.89 | 11.39 | 0.56 |
| 3| 968 | 37.91 | 12.62 | 0.59 |
| 5| 1223 | 41.90 | 15.05 | 0.65 |
| 10| 2073 | 54.76 | 22.02 | 0.84 |
| 30| 4949 | 99.28 | 47.71 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.05 | 9.07 | 0.69 |
| 2| 6006 | 37.00 | 12.50 | 0.80 |
| 3| 6071 | 44.85 | 15.09 | 0.89 |
| 4| 6149 | 50.26 | 16.83 | 0.95 |
| 5| 6328 | 60.82 | 20.41 | 1.07 |
| 6| 6646 | 74.13 | 24.98 | 1.22 |
| 7| 6773 | 84.84 | 28.67 | 1.34 |
| 8| 6796 | 92.37 | 31.07 | 1.42 |
| 9| 6839 | 94.54 | 31.81 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.73 | 7.73 | 0.65 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

