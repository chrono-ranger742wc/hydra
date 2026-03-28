--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-28 05:45:41.674203249 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.76 | 4.67 | 0.58 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 29.02 | 9.14 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 913 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10036 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 862 | 50.99 | 14.65 | 0.71 |
| 5 | 282 | 969 | 56.16 | 16.32 | 0.76 |
| 6 | 338 | 1081 | 64.24 | 18.61 | 0.85 |
| 7 | 395 | 1192 | 84.97 | 24.10 | 1.06 |
| 8 | 450 | 1303 | 87.21 | 24.90 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.92 | 8.80 | 0.51 |
| 3| 2133 | 28.31 | 10.14 | 0.55 |
| 5| 2429 | 32.23 | 12.58 | 0.61 |
| 10| 3252 | 42.86 | 18.88 | 0.78 |
| 40| 7712 | 99.90 | 54.74 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.54 | 7.31 | 0.41 |
| 2| 726 | 22.56 | 7.94 | 0.42 |
| 3| 901 | 25.76 | 9.53 | 0.47 |
| 5| 1245 | 30.13 | 12.07 | 0.54 |
| 10| 1961 | 37.86 | 17.56 | 0.67 |
| 41| 6607 | 98.55 | 55.09 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.50 | 8.46 | 0.46 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 914 | 32.72 | 11.23 | 0.54 |
| 5| 1206 | 34.41 | 13.05 | 0.58 |
| 10| 2105 | 46.22 | 19.77 | 0.76 |
| 35| 5656 | 99.97 | 51.36 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 1068 | 39.38 | 13.06 | 0.61 |
| 5| 1204 | 41.78 | 15.02 | 0.65 |
| 10| 2121 | 55.29 | 22.19 | 0.85 |
| 29| 4613 | 95.71 | 45.97 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.00 | 9.08 | 0.69 |
| 2| 5948 | 35.96 | 12.08 | 0.79 |
| 3| 6094 | 44.80 | 15.06 | 0.89 |
| 4| 6302 | 55.09 | 18.55 | 1.01 |
| 5| 6429 | 64.57 | 21.73 | 1.11 |
| 6| 6500 | 69.59 | 23.37 | 1.17 |
| 7| 6694 | 79.90 | 26.99 | 1.28 |
| 8| 6822 | 88.78 | 29.87 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 571 | 6175 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6515 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

