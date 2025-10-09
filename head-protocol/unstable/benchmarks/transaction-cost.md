--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-09 04:40:02.486709395 UTC |
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
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2166 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 226 | 858 | 48.03 | 13.95 | 0.68 |
| 5 | 283 | 969 | 64.04 | 18.17 | 0.84 |
| 6 | 338 | 1081 | 73.80 | 20.94 | 0.95 |
| 7 | 394 | 1192 | 76.53 | 21.99 | 0.98 |
| 8 | 450 | 1303 | 84.46 | 24.24 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.00 | 7.62 | 0.48 |
| 2| 1972 | 26.87 | 9.07 | 0.52 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2449 | 33.03 | 12.81 | 0.62 |
| 10| 3043 | 37.79 | 17.47 | 0.72 |
| 40| 7742 | 99.75 | 54.69 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 743 | 24.00 | 8.38 | 0.44 |
| 3| 912 | 25.83 | 9.55 | 0.47 |
| 5| 1275 | 30.56 | 12.22 | 0.54 |
| 10| 2056 | 39.39 | 17.99 | 0.69 |
| 39| 6368 | 95.79 | 52.99 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.51 | 8.47 | 0.46 |
| 2| 783 | 30.98 | 10.08 | 0.51 |
| 3| 872 | 32.01 | 11.01 | 0.53 |
| 5| 1346 | 38.52 | 14.23 | 0.62 |
| 10| 2022 | 44.79 | 19.34 | 0.74 |
| 35| 5958 | 97.36 | 50.83 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.79 | 10.15 | 0.53 |
| 2| 855 | 36.60 | 11.61 | 0.57 |
| 3| 899 | 37.20 | 12.40 | 0.58 |
| 5| 1384 | 43.99 | 15.69 | 0.68 |
| 10| 2085 | 55.22 | 22.15 | 0.85 |
| 29| 5029 | 99.32 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.16 | 9.11 | 0.69 |
| 2| 5901 | 34.91 | 11.69 | 0.78 |
| 3| 6041 | 41.39 | 13.85 | 0.85 |
| 4| 6229 | 55.18 | 18.58 | 1.00 |
| 5| 6400 | 64.26 | 21.61 | 1.11 |
| 6| 6529 | 70.06 | 23.54 | 1.17 |
| 7| 6777 | 84.86 | 28.62 | 1.34 |
| 8| 6892 | 90.02 | 30.28 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.42 | 5.80 | 0.59 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6855 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2216 | 7155 | 98.24 | 37.65 | 1.53 |

