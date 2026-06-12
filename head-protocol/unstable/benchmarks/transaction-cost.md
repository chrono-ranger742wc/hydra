--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-12 08:56:24.162333674 UTC |
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
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6646 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.51 | 12.01 | 0.61 |
| 4 | 228 | 862 | 49.42 | 14.25 | 0.69 |
| 5 | 283 | 974 | 61.39 | 17.60 | 0.82 |
| 6 | 338 | 1081 | 73.39 | 20.88 | 0.94 |
| 7 | 393 | 1192 | 82.71 | 23.48 | 1.04 |
| 8 | 449 | 1303 | 83.10 | 24.02 | 1.05 |
| 9 | 504 | 1414 | 95.96 | 27.44 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 1985 | 26.84 | 9.06 | 0.52 |
| 3| 2140 | 27.94 | 10.05 | 0.54 |
| 5| 2395 | 31.21 | 12.29 | 0.60 |
| 10| 3402 | 45.95 | 19.75 | 0.81 |
| 38| 7250 | 92.25 | 51.29 | 1.58 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 753 | 23.58 | 8.24 | 0.43 |
| 3| 937 | 26.71 | 9.80 | 0.48 |
| 5| 1208 | 29.92 | 12.04 | 0.53 |
| 10| 2161 | 43.21 | 19.05 | 0.73 |
| 39| 6439 | 97.59 | 53.51 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.13 | 8.90 | 0.48 |
| 2| 784 | 30.94 | 10.07 | 0.51 |
| 3| 1007 | 31.50 | 10.93 | 0.53 |
| 5| 1256 | 35.01 | 13.24 | 0.58 |
| 10| 1945 | 43.96 | 19.09 | 0.73 |
| 36| 6015 | 98.14 | 51.68 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.79 | 10.15 | 0.53 |
| 2| 841 | 35.88 | 11.39 | 0.56 |
| 3| 980 | 38.66 | 12.84 | 0.60 |
| 5| 1350 | 43.28 | 15.47 | 0.67 |
| 10| 2226 | 56.14 | 22.46 | 0.86 |
| 29| 4745 | 95.80 | 46.04 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5841 | 26.92 | 9.05 | 0.69 |
| 2| 5958 | 35.96 | 12.07 | 0.79 |
| 3| 5970 | 40.54 | 13.54 | 0.84 |
| 4| 6358 | 55.78 | 18.82 | 1.02 |
| 5| 6308 | 61.07 | 20.53 | 1.07 |
| 6| 6503 | 69.88 | 23.49 | 1.17 |
| 7| 6809 | 84.23 | 28.48 | 1.34 |
| 8| 6940 | 92.82 | 31.44 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.72 | 10.56 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

