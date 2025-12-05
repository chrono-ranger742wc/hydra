--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-05 05:40:03.101322057 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 912 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.40 | 11.97 | 0.60 |
| 4 | 226 | 858 | 48.08 | 13.96 | 0.68 |
| 5 | 283 | 969 | 58.89 | 16.97 | 0.79 |
| 6 | 340 | 1081 | 75.64 | 21.39 | 0.96 |
| 7 | 394 | 1192 | 82.41 | 23.40 | 1.04 |
| 8 | 449 | 1303 | 89.80 | 25.57 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1947 | 25.51 | 8.70 | 0.50 |
| 3| 2150 | 28.32 | 10.17 | 0.55 |
| 5| 2386 | 31.25 | 12.30 | 0.60 |
| 10| 3000 | 37.48 | 17.38 | 0.71 |
| 40| 7439 | 94.68 | 53.28 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.54 | 7.31 | 0.41 |
| 2| 764 | 24.04 | 8.41 | 0.44 |
| 3| 853 | 23.99 | 9.01 | 0.45 |
| 5| 1181 | 29.03 | 11.75 | 0.52 |
| 10| 2158 | 41.60 | 18.63 | 0.72 |
| 44| 6913 | 99.30 | 57.34 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 931 | 32.72 | 11.23 | 0.54 |
| 5| 1307 | 37.65 | 13.97 | 0.61 |
| 10| 2138 | 48.75 | 20.44 | 0.79 |
| 33| 5631 | 98.22 | 49.63 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 956 | 37.91 | 12.62 | 0.59 |
| 5| 1268 | 42.49 | 15.24 | 0.66 |
| 10| 2020 | 54.09 | 21.81 | 0.83 |
| 29| 4848 | 98.15 | 46.75 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.08 | 9.09 | 0.69 |
| 2| 5970 | 37.06 | 12.49 | 0.80 |
| 3| 6019 | 41.32 | 13.83 | 0.85 |
| 4| 6212 | 53.48 | 18.02 | 0.99 |
| 5| 6370 | 59.19 | 19.89 | 1.05 |
| 6| 6688 | 75.15 | 25.42 | 1.23 |
| 7| 6602 | 76.09 | 25.63 | 1.24 |
| 8| 7145 | 97.18 | 32.88 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6002 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 40 | 2283 | 7199 | 99.84 | 38.30 | 1.55 |

