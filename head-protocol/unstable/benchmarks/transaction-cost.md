--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-26 05:22:00.860392324 UTC |
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
| 1| 5836 | 10.74 | 3.42 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.53 | 12.22 | 0.61 |
| 4 | 227 | 858 | 50.97 | 14.63 | 0.71 |
| 5 | 282 | 969 | 57.79 | 16.71 | 0.78 |
| 6 | 341 | 1085 | 71.90 | 20.45 | 0.93 |
| 7 | 395 | 1196 | 76.41 | 21.92 | 0.98 |
| 8 | 451 | 1303 | 87.77 | 25.14 | 1.10 |
| 9 | 506 | 1414 | 93.89 | 26.95 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.85 | 8.78 | 0.51 |
| 3| 2061 | 27.31 | 9.86 | 0.53 |
| 5| 2484 | 33.19 | 12.85 | 0.62 |
| 10| 3140 | 40.95 | 18.34 | 0.75 |
| 39| 7505 | 97.27 | 53.31 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.81 | 7.37 | 0.42 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 928 | 24.99 | 9.29 | 0.46 |
| 5| 1269 | 30.94 | 12.31 | 0.54 |
| 10| 1944 | 37.66 | 17.50 | 0.67 |
| 42| 6866 | 99.52 | 56.04 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.54 | 8.47 | 0.46 |
| 2| 740 | 30.19 | 9.84 | 0.50 |
| 3| 975 | 30.98 | 10.76 | 0.52 |
| 5| 1360 | 38.48 | 14.22 | 0.62 |
| 10| 2141 | 46.01 | 19.72 | 0.76 |
| 34| 5742 | 95.40 | 49.59 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.89 | 11.39 | 0.56 |
| 3| 1023 | 38.55 | 12.81 | 0.60 |
| 5| 1271 | 42.57 | 15.26 | 0.66 |
| 10| 1943 | 53.20 | 21.55 | 0.82 |
| 28| 4753 | 96.62 | 45.64 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 27.08 | 9.09 | 0.69 |
| 2| 5945 | 35.80 | 12.03 | 0.79 |
| 3| 5991 | 43.89 | 14.69 | 0.87 |
| 4| 6279 | 54.86 | 18.46 | 1.00 |
| 5| 6294 | 59.75 | 20.02 | 1.05 |
| 6| 6503 | 69.29 | 23.30 | 1.16 |
| 7| 6561 | 73.59 | 24.64 | 1.21 |
| 8| 6807 | 93.06 | 31.39 | 1.43 |
| 9| 6975 | 96.12 | 32.37 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2165 | 7128 | 97.07 | 37.14 | 1.52 |

