--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-15 05:28:04.877408556 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6240 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14286 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 227 | 858 | 52.42 | 14.97 | 0.72 |
| 5 | 284 | 969 | 61.33 | 17.62 | 0.82 |
| 6 | 336 | 1081 | 74.96 | 21.14 | 0.96 |
| 7 | 395 | 1192 | 85.97 | 24.21 | 1.07 |
| 8 | 449 | 1307 | 80.61 | 23.42 | 1.03 |
| 9 | 506 | 1414 | 96.10 | 27.53 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1966 | 26.62 | 9.02 | 0.52 |
| 3| 2129 | 28.06 | 10.08 | 0.54 |
| 5| 2429 | 32.41 | 12.62 | 0.61 |
| 10| 3239 | 42.36 | 18.74 | 0.77 |
| 38| 7158 | 92.36 | 51.27 | 1.58 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.80 | 7.36 | 0.41 |
| 2| 765 | 23.51 | 8.21 | 0.43 |
| 3| 866 | 24.11 | 9.04 | 0.45 |
| 5| 1170 | 28.16 | 11.51 | 0.51 |
| 10| 2019 | 39.99 | 18.19 | 0.69 |
| 42| 6692 | 98.52 | 55.78 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 794 | 30.91 | 10.06 | 0.51 |
| 3| 1114 | 32.29 | 11.17 | 0.54 |
| 5| 1241 | 37.13 | 13.80 | 0.60 |
| 10| 1940 | 46.80 | 19.85 | 0.76 |
| 36| 5899 | 96.55 | 51.17 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.16 | 0.53 |
| 2| 856 | 36.56 | 11.60 | 0.57 |
| 3| 946 | 37.87 | 12.61 | 0.59 |
| 5| 1345 | 43.25 | 15.47 | 0.67 |
| 10| 2105 | 55.00 | 22.08 | 0.85 |
| 29| 4840 | 96.51 | 46.26 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.13 | 9.10 | 0.69 |
| 2| 5865 | 32.65 | 10.90 | 0.75 |
| 3| 5974 | 40.32 | 13.45 | 0.84 |
| 4| 6284 | 55.06 | 18.50 | 1.01 |
| 5| 6425 | 62.24 | 20.97 | 1.09 |
| 6| 6426 | 65.61 | 21.99 | 1.12 |
| 7| 6888 | 84.92 | 28.74 | 1.35 |
| 8| 6991 | 95.22 | 32.16 | 1.46 |
| 9| 7029 | 99.29 | 33.45 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 283 | 6003 | 29.09 | 10.34 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2161 | 7123 | 97.07 | 37.14 | 1.52 |

