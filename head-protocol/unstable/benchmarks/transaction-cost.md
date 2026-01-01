--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-01 05:59:21.947610945 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.31 | 9.25 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 751 | 41.33 | 11.97 | 0.60 |
| 4 | 228 | 858 | 53.93 | 15.39 | 0.73 |
| 5 | 283 | 969 | 56.25 | 16.34 | 0.77 |
| 6 | 338 | 1081 | 65.62 | 18.98 | 0.86 |
| 7 | 394 | 1192 | 73.76 | 21.32 | 0.95 |
| 8 | 448 | 1303 | 98.53 | 27.61 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1832 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2120 | 28.02 | 10.07 | 0.54 |
| 5| 2280 | 29.04 | 11.69 | 0.57 |
| 10| 3258 | 43.35 | 19.00 | 0.78 |
| 40| 7637 | 97.74 | 54.13 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.37 | 0.42 |
| 2| 748 | 24.04 | 8.39 | 0.44 |
| 3| 964 | 26.02 | 9.58 | 0.47 |
| 5| 1269 | 31.09 | 12.36 | 0.55 |
| 10| 1959 | 37.59 | 17.48 | 0.67 |
| 41| 6558 | 97.12 | 54.70 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 775 | 28.47 | 9.38 | 0.48 |
| 3| 968 | 30.82 | 10.73 | 0.52 |
| 5| 1171 | 36.24 | 13.54 | 0.59 |
| 10| 2059 | 44.63 | 19.30 | 0.74 |
| 36| 6085 | 99.44 | 52.02 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.87 | 10.16 | 0.53 |
| 2| 852 | 36.56 | 11.60 | 0.57 |
| 3| 1016 | 38.66 | 12.84 | 0.60 |
| 5| 1246 | 42.53 | 15.25 | 0.66 |
| 10| 2186 | 55.40 | 22.22 | 0.85 |
| 29| 4685 | 95.47 | 45.94 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 26.97 | 9.06 | 0.69 |
| 2| 6013 | 36.85 | 12.42 | 0.80 |
| 3| 6072 | 44.84 | 15.09 | 0.89 |
| 4| 6320 | 56.00 | 18.94 | 1.02 |
| 5| 6406 | 64.14 | 21.61 | 1.11 |
| 6| 6444 | 70.06 | 23.52 | 1.17 |
| 7| 6611 | 79.16 | 26.56 | 1.27 |
| 8| 6859 | 85.65 | 28.85 | 1.35 |
| 9| 6935 | 97.25 | 32.70 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2222 | 7161 | 98.05 | 37.58 | 1.53 |

