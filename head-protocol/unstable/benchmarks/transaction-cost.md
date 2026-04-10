--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-10 06:23:03.226380734 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6240 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 169 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 226 | 858 | 47.79 | 13.89 | 0.67 |
| 5 | 281 | 969 | 64.68 | 18.33 | 0.85 |
| 6 | 338 | 1081 | 71.59 | 20.37 | 0.92 |
| 7 | 394 | 1196 | 86.90 | 24.48 | 1.08 |
| 8 | 450 | 1303 | 84.74 | 24.40 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2017 | 25.91 | 9.48 | 0.52 |
| 5| 2368 | 31.33 | 12.32 | 0.60 |
| 10| 3323 | 43.28 | 19.02 | 0.78 |
| 40| 7745 | 99.83 | 54.71 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.84 | 7.37 | 0.42 |
| 2| 735 | 24.04 | 8.40 | 0.44 |
| 3| 979 | 27.00 | 9.88 | 0.48 |
| 5| 1143 | 28.07 | 11.50 | 0.51 |
| 10| 1888 | 36.40 | 17.15 | 0.65 |
| 39| 6328 | 95.28 | 52.85 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 29.17 | 8.91 | 0.48 |
| 2| 837 | 31.66 | 10.29 | 0.52 |
| 3| 961 | 33.40 | 11.43 | 0.54 |
| 5| 1232 | 37.03 | 13.78 | 0.60 |
| 10| 2114 | 45.35 | 19.52 | 0.75 |
| 35| 6054 | 98.95 | 51.32 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.87 | 10.16 | 0.53 |
| 2| 823 | 35.88 | 11.39 | 0.56 |
| 3| 946 | 37.88 | 12.61 | 0.59 |
| 5| 1352 | 43.69 | 15.59 | 0.68 |
| 10| 1987 | 53.46 | 21.62 | 0.83 |
| 29| 5002 | 98.41 | 46.86 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5921 | 34.86 | 11.67 | 0.78 |
| 3| 6019 | 41.43 | 13.88 | 0.85 |
| 4| 6169 | 50.20 | 16.84 | 0.95 |
| 5| 6319 | 63.38 | 21.25 | 1.09 |
| 6| 6563 | 73.18 | 24.64 | 1.21 |
| 7| 6673 | 81.72 | 27.47 | 1.30 |
| 8| 6952 | 90.59 | 30.52 | 1.41 |
| 9| 7062 | 99.62 | 33.58 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2164 | 7126 | 96.00 | 36.77 | 1.50 |

