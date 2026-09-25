--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-25 09:57:08.678209187 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6039 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 42.57 | 12.28 | 0.62 |
| 4 | 225 | 862 | 48.04 | 13.95 | 0.68 |
| 5 | 282 | 969 | 57.55 | 16.59 | 0.78 |
| 6 | 337 | 1081 | 66.43 | 19.18 | 0.87 |
| 7 | 395 | 1196 | 84.18 | 23.78 | 1.05 |
| 8 | 451 | 1307 | 98.46 | 27.60 | 1.20 |
| 10 | 560 | 1525 | 97.37 | 28.24 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.47 | 8.70 | 0.50 |
| 3| 2212 | 29.21 | 10.40 | 0.56 |
| 5| 2549 | 34.34 | 13.17 | 0.63 |
| 10| 3125 | 41.22 | 18.41 | 0.75 |
| 39| 7629 | 99.13 | 53.85 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.84 | 7.38 | 0.42 |
| 2| 788 | 24.05 | 8.39 | 0.44 |
| 3| 901 | 25.83 | 9.54 | 0.47 |
| 5| 1285 | 30.56 | 12.18 | 0.54 |
| 10| 2063 | 40.88 | 18.40 | 0.70 |
| 44| 6849 | 99.26 | 57.29 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 823 | 29.26 | 9.62 | 0.49 |
| 3| 1003 | 31.65 | 10.97 | 0.53 |
| 5| 1358 | 36.47 | 13.68 | 0.60 |
| 10| 1865 | 42.87 | 18.75 | 0.71 |
| 37| 6186 | 99.44 | 52.70 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 841 | 35.88 | 11.39 | 0.56 |
| 3| 957 | 37.91 | 12.62 | 0.59 |
| 5| 1273 | 42.45 | 15.23 | 0.66 |
| 10| 1959 | 53.27 | 21.57 | 0.82 |
| 28| 4740 | 96.91 | 45.76 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.13 | 9.11 | 0.69 |
| 2| 5971 | 35.92 | 12.05 | 0.79 |
| 3| 6175 | 46.22 | 15.61 | 0.91 |
| 4| 6349 | 55.82 | 18.86 | 1.02 |
| 5| 6488 | 63.93 | 21.63 | 1.11 |
| 6| 6497 | 69.95 | 23.49 | 1.17 |
| 7| 6685 | 80.82 | 27.17 | 1.29 |
| 8| 6913 | 93.44 | 31.48 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

