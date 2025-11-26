--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-26 05:38:31.27212326 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.97 | 12.61 | 0.63 |
| 4 | 227 | 858 | 50.70 | 14.56 | 0.70 |
| 5 | 283 | 974 | 56.75 | 16.49 | 0.77 |
| 6 | 337 | 1081 | 64.97 | 18.87 | 0.86 |
| 7 | 394 | 1192 | 74.98 | 21.67 | 0.96 |
| 8 | 450 | 1303 | 89.79 | 25.57 | 1.12 |
| 9 | 505 | 1414 | 95.08 | 27.12 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1984 | 27.00 | 9.10 | 0.52 |
| 3| 2057 | 27.40 | 9.88 | 0.53 |
| 5| 2321 | 29.97 | 11.95 | 0.58 |
| 10| 3131 | 41.04 | 18.36 | 0.75 |
| 41| 7730 | 98.12 | 54.89 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.54 | 7.31 | 0.41 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 918 | 25.56 | 9.48 | 0.47 |
| 5| 1250 | 29.89 | 12.02 | 0.53 |
| 10| 1874 | 36.44 | 17.16 | 0.65 |
| 42| 6758 | 98.39 | 55.73 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 915 | 32.72 | 11.23 | 0.54 |
| 5| 1394 | 36.43 | 13.67 | 0.60 |
| 10| 2102 | 45.58 | 19.57 | 0.75 |
| 37| 6121 | 99.22 | 52.59 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.87 | 10.16 | 0.53 |
| 2| 856 | 36.64 | 11.62 | 0.57 |
| 3| 900 | 37.16 | 12.39 | 0.58 |
| 5| 1277 | 42.72 | 15.30 | 0.66 |
| 10| 2117 | 55.44 | 22.23 | 0.85 |
| 29| 5024 | 99.80 | 47.25 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 26.92 | 9.04 | 0.69 |
| 2| 5946 | 35.89 | 12.04 | 0.79 |
| 3| 6046 | 41.63 | 13.93 | 0.85 |
| 4| 6198 | 52.80 | 17.69 | 0.98 |
| 5| 6315 | 59.65 | 20.04 | 1.05 |
| 6| 6722 | 71.88 | 24.28 | 1.20 |
| 7| 6906 | 85.89 | 29.05 | 1.36 |
| 8| 6654 | 82.99 | 27.82 | 1.31 |
| 10| 6829 | 92.15 | 30.82 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.42 | 10.80 | 0.74 |
| 10 | 10 | 566 | 6170 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1141 | 6515 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2165 | 7127 | 96.88 | 37.08 | 1.51 |

