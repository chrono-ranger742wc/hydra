--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-14 06:23:52.639056774 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6638 | 18.58 | 5.86 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 858 | 48.19 | 13.98 | 0.68 |
| 5 | 281 | 974 | 55.95 | 16.23 | 0.76 |
| 6 | 341 | 1081 | 66.10 | 19.06 | 0.87 |
| 7 | 394 | 1192 | 75.33 | 21.70 | 0.97 |
| 8 | 450 | 1303 | 82.75 | 23.88 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1941 | 25.92 | 8.80 | 0.51 |
| 3| 2151 | 28.39 | 10.16 | 0.55 |
| 5| 2391 | 31.16 | 12.28 | 0.60 |
| 10| 3326 | 43.54 | 19.09 | 0.79 |
| 41| 7724 | 99.24 | 55.19 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.84 | 7.37 | 0.42 |
| 2| 836 | 25.49 | 8.78 | 0.46 |
| 3| 905 | 25.56 | 9.48 | 0.46 |
| 5| 1163 | 28.39 | 11.61 | 0.51 |
| 10| 1985 | 38.66 | 17.78 | 0.68 |
| 41| 6637 | 97.33 | 54.80 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 813 | 29.18 | 9.60 | 0.49 |
| 3| 960 | 33.31 | 11.41 | 0.54 |
| 5| 1280 | 35.00 | 13.24 | 0.58 |
| 10| 2092 | 48.34 | 20.31 | 0.78 |
| 36| 5892 | 96.55 | 51.21 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.15 | 0.53 |
| 2| 841 | 35.85 | 11.38 | 0.56 |
| 3| 954 | 37.80 | 12.59 | 0.59 |
| 5| 1229 | 41.82 | 15.03 | 0.65 |
| 10| 2124 | 55.33 | 22.20 | 0.85 |
| 28| 4688 | 94.13 | 44.95 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.12 | 9.10 | 0.69 |
| 2| 5876 | 32.54 | 10.87 | 0.75 |
| 3| 6054 | 43.84 | 14.68 | 0.88 |
| 4| 6253 | 51.50 | 17.29 | 0.97 |
| 5| 6323 | 56.81 | 19.04 | 1.02 |
| 6| 6672 | 74.88 | 25.30 | 1.23 |
| 7| 6540 | 74.97 | 25.17 | 1.23 |
| 8| 6874 | 89.54 | 30.20 | 1.39 |
| 9| 6994 | 99.86 | 33.63 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 568 | 6172 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1137 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

