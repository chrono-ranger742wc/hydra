--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-29 09:29:12.097636196 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6039 | 12.53 | 3.97 | 0.55 |
| 3| 6243 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7648 | 29.57 | 9.34 | 0.79 |
| 43| 14285 | 99.08 | 30.97 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.11 | 11.88 | 0.60 |
| 4 | 226 | 858 | 49.88 | 14.44 | 0.70 |
| 5 | 283 | 969 | 56.54 | 16.38 | 0.77 |
| 6 | 338 | 1081 | 64.44 | 18.74 | 0.85 |
| 7 | 392 | 1192 | 76.63 | 22.06 | 0.98 |
| 8 | 449 | 1303 | 95.02 | 26.92 | 1.17 |
| 9 | 504 | 1414 | 88.78 | 25.84 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.29 | 7.69 | 0.48 |
| 2| 1925 | 25.80 | 8.77 | 0.51 |
| 3| 2111 | 28.26 | 10.13 | 0.54 |
| 5| 2396 | 30.96 | 12.23 | 0.59 |
| 10| 3200 | 42.01 | 18.64 | 0.76 |
| 40| 7410 | 94.80 | 53.31 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 840 | 24.13 | 9.04 | 0.45 |
| 5| 1230 | 30.73 | 12.26 | 0.54 |
| 10| 1944 | 38.56 | 17.77 | 0.68 |
| 41| 6557 | 99.16 | 55.24 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 29.17 | 8.91 | 0.48 |
| 2| 820 | 29.22 | 9.61 | 0.49 |
| 3| 973 | 30.94 | 10.75 | 0.52 |
| 5| 1287 | 34.90 | 13.21 | 0.58 |
| 10| 2137 | 45.39 | 19.53 | 0.75 |
| 35| 5783 | 99.67 | 51.32 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 886 | 36.60 | 11.61 | 0.57 |
| 3| 962 | 37.88 | 12.61 | 0.59 |
| 5| 1250 | 42.68 | 15.29 | 0.66 |
| 10| 2075 | 54.05 | 21.81 | 0.84 |
| 28| 4765 | 97.12 | 45.83 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.92 | 9.04 | 0.69 |
| 2| 6063 | 36.97 | 12.46 | 0.81 |
| 3| 6077 | 44.57 | 14.98 | 0.89 |
| 4| 6399 | 57.65 | 19.51 | 1.04 |
| 5| 6423 | 63.24 | 21.23 | 1.10 |
| 6| 6548 | 71.08 | 23.96 | 1.19 |
| 7| 6788 | 83.95 | 28.29 | 1.33 |
| 8| 6921 | 91.47 | 30.91 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

