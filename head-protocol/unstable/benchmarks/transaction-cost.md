--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-25 05:48:15.370560902 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.91 | 5.98 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 171 | 747 | 40.25 | 11.70 | 0.59 |
| 4 | 227 | 858 | 53.58 | 15.25 | 0.73 |
| 5 | 282 | 969 | 59.59 | 17.14 | 0.80 |
| 6 | 337 | 1081 | 72.08 | 20.45 | 0.93 |
| 7 | 394 | 1196 | 80.51 | 22.95 | 1.02 |
| 8 | 450 | 1303 | 91.38 | 25.90 | 1.13 |
| 9 | 504 | 1414 | 91.55 | 26.50 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.00 | 7.62 | 0.48 |
| 2| 1944 | 25.51 | 8.70 | 0.50 |
| 3| 2060 | 26.94 | 9.77 | 0.53 |
| 5| 2416 | 32.11 | 12.55 | 0.61 |
| 10| 3133 | 39.97 | 18.06 | 0.74 |
| 38| 7508 | 99.65 | 53.34 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.77 | 7.36 | 0.42 |
| 2| 765 | 23.66 | 8.26 | 0.43 |
| 3| 828 | 24.13 | 9.04 | 0.45 |
| 5| 1298 | 30.15 | 12.07 | 0.54 |
| 10| 1877 | 36.67 | 17.22 | 0.65 |
| 43| 6693 | 97.75 | 56.25 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.79 | 8.25 | 0.45 |
| 2| 797 | 30.94 | 10.07 | 0.51 |
| 3| 903 | 30.23 | 10.54 | 0.51 |
| 5| 1288 | 35.12 | 13.27 | 0.59 |
| 10| 2043 | 44.76 | 19.33 | 0.74 |
| 36| 5973 | 97.84 | 51.58 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 1020 | 38.59 | 12.82 | 0.60 |
| 5| 1248 | 42.57 | 15.26 | 0.66 |
| 10| 2064 | 55.00 | 22.08 | 0.84 |
| 28| 4557 | 94.00 | 44.84 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 27.08 | 9.09 | 0.69 |
| 2| 5889 | 32.72 | 10.93 | 0.75 |
| 3| 6183 | 46.07 | 15.51 | 0.91 |
| 4| 6225 | 54.83 | 18.46 | 1.00 |
| 5| 6442 | 61.57 | 20.75 | 1.08 |
| 6| 6435 | 68.05 | 22.79 | 1.15 |
| 7| 6765 | 84.45 | 28.52 | 1.34 |
| 8| 6850 | 90.89 | 30.59 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.99 | 7.82 | 0.65 |
| 10 | 5 | 283 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 38 | 2161 | 7124 | 96.63 | 36.99 | 1.51 |

