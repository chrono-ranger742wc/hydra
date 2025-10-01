--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-01 04:38:28.506446724 UTC |
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
| 1| 5837 | 10.64 | 3.38 | 0.52 |
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 43.56 | 12.48 | 0.63 |
| 4 | 225 | 858 | 53.88 | 15.35 | 0.73 |
| 5 | 282 | 974 | 60.86 | 17.41 | 0.81 |
| 6 | 340 | 1081 | 73.86 | 20.99 | 0.95 |
| 7 | 396 | 1192 | 71.77 | 20.85 | 0.93 |
| 8 | 450 | 1303 | 82.80 | 23.85 | 1.05 |
| 10 | 560 | 1525 | 97.09 | 28.06 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.29 | 7.69 | 0.48 |
| 2| 1890 | 24.40 | 8.39 | 0.49 |
| 3| 2163 | 29.02 | 10.36 | 0.55 |
| 5| 2418 | 31.41 | 12.34 | 0.60 |
| 10| 3096 | 39.48 | 17.94 | 0.73 |
| 38| 7603 | 99.69 | 53.38 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.57 | 7.32 | 0.41 |
| 2| 768 | 24.28 | 8.45 | 0.44 |
| 3| 881 | 25.12 | 9.33 | 0.46 |
| 5| 1251 | 31.10 | 12.35 | 0.55 |
| 10| 1971 | 38.38 | 17.71 | 0.67 |
| 41| 6531 | 97.11 | 54.71 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 868 | 32.05 | 11.02 | 0.53 |
| 5| 1299 | 37.62 | 13.97 | 0.61 |
| 10| 2182 | 46.72 | 19.94 | 0.77 |
| 39| 5982 | 97.71 | 53.37 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 817 | 35.85 | 11.38 | 0.56 |
| 3| 966 | 37.84 | 12.60 | 0.59 |
| 5| 1246 | 42.64 | 15.28 | 0.66 |
| 10| 1930 | 52.79 | 21.41 | 0.82 |
| 29| 4879 | 98.60 | 46.88 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 27.08 | 9.09 | 0.69 |
| 2| 5897 | 34.80 | 11.66 | 0.77 |
| 3| 6042 | 44.83 | 15.09 | 0.89 |
| 4| 6285 | 55.17 | 18.56 | 1.01 |
| 5| 6345 | 61.69 | 20.70 | 1.08 |
| 6| 6688 | 75.28 | 25.46 | 1.24 |
| 7| 6702 | 80.81 | 27.24 | 1.29 |
| 8| 6911 | 88.41 | 29.74 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2221 | 7161 | 99.12 | 37.95 | 1.54 |

