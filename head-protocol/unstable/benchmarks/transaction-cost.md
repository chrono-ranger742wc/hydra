--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-04 06:57:59.004195864 UTC |
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
| 1| 5837 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14279 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 227 | 858 | 52.13 | 14.90 | 0.72 |
| 5 | 283 | 969 | 57.79 | 16.68 | 0.78 |
| 6 | 339 | 1081 | 74.02 | 21.03 | 0.95 |
| 7 | 393 | 1196 | 82.98 | 23.54 | 1.04 |
| 8 | 449 | 1303 | 84.26 | 24.24 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2084 | 27.39 | 9.88 | 0.53 |
| 5| 2431 | 32.33 | 12.60 | 0.61 |
| 10| 3139 | 41.35 | 18.44 | 0.76 |
| 41| 7604 | 97.63 | 54.74 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.37 | 0.42 |
| 2| 769 | 24.35 | 8.47 | 0.44 |
| 3| 1038 | 27.45 | 10.01 | 0.49 |
| 5| 1163 | 28.04 | 11.49 | 0.51 |
| 10| 2076 | 40.03 | 18.17 | 0.70 |
| 40| 6291 | 92.87 | 52.87 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.50 | 8.46 | 0.46 |
| 2| 775 | 30.94 | 10.07 | 0.51 |
| 3| 948 | 30.86 | 10.73 | 0.52 |
| 5| 1177 | 36.35 | 13.57 | 0.59 |
| 10| 2195 | 47.70 | 20.22 | 0.78 |
| 37| 6182 | 99.96 | 52.87 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 941 | 37.84 | 12.60 | 0.59 |
| 5| 1288 | 43.20 | 15.46 | 0.67 |
| 10| 2060 | 54.74 | 22.02 | 0.84 |
| 30| 4822 | 97.49 | 47.18 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5849 | 31.48 | 10.48 | 0.74 |
| 3| 6066 | 44.95 | 15.10 | 0.89 |
| 4| 6284 | 54.60 | 18.39 | 1.00 |
| 5| 6361 | 60.71 | 20.35 | 1.07 |
| 6| 6543 | 73.44 | 24.76 | 1.21 |
| 7| 6842 | 85.21 | 28.82 | 1.35 |
| 8| 6991 | 90.71 | 30.64 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1138 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2217 | 7157 | 98.49 | 37.73 | 1.53 |

