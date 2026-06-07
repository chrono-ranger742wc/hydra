--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-07 08:29:59.048904501 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10036 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 228 | 862 | 50.84 | 14.62 | 0.70 |
| 5 | 283 | 969 | 59.20 | 17.01 | 0.79 |
| 6 | 339 | 1081 | 70.02 | 20.08 | 0.91 |
| 7 | 394 | 1192 | 74.35 | 21.39 | 0.96 |
| 8 | 450 | 1307 | 98.65 | 27.74 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.29 | 7.69 | 0.48 |
| 2| 1883 | 24.44 | 8.41 | 0.49 |
| 3| 2064 | 27.39 | 9.88 | 0.53 |
| 5| 2319 | 29.96 | 11.95 | 0.58 |
| 10| 3294 | 44.27 | 19.28 | 0.79 |
| 43| 7925 | 99.10 | 56.49 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.80 | 7.37 | 0.41 |
| 2| 787 | 24.25 | 8.44 | 0.44 |
| 3| 888 | 25.74 | 9.53 | 0.47 |
| 5| 1312 | 32.18 | 12.65 | 0.56 |
| 10| 1945 | 37.69 | 17.51 | 0.67 |
| 42| 6614 | 97.36 | 55.46 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.09 | 8.89 | 0.48 |
| 2| 876 | 29.86 | 9.81 | 0.50 |
| 3| 914 | 32.76 | 11.24 | 0.54 |
| 5| 1310 | 37.77 | 14.00 | 0.61 |
| 10| 2018 | 48.04 | 20.23 | 0.77 |
| 35| 5864 | 95.95 | 50.38 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.79 | 10.15 | 0.53 |
| 2| 837 | 35.81 | 11.37 | 0.56 |
| 3| 952 | 37.95 | 12.63 | 0.59 |
| 5| 1220 | 41.97 | 15.07 | 0.65 |
| 10| 2027 | 53.90 | 21.77 | 0.83 |
| 29| 4942 | 98.72 | 46.92 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 26.92 | 9.04 | 0.69 |
| 2| 5826 | 31.48 | 10.48 | 0.74 |
| 3| 6006 | 41.53 | 13.91 | 0.85 |
| 4| 6200 | 50.16 | 16.82 | 0.95 |
| 5| 6291 | 60.74 | 20.37 | 1.06 |
| 6| 6564 | 72.49 | 24.52 | 1.20 |
| 7| 6574 | 75.82 | 25.40 | 1.24 |
| 8| 6896 | 93.79 | 31.70 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 20 | 1139 | 6514 | 61.31 | 22.98 | 1.10 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2164 | 7126 | 96.19 | 36.84 | 1.51 |

