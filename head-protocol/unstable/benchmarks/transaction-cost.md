--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-08 05:58:30.792950012 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 112 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 751 | 41.40 | 11.97 | 0.60 |
| 4 | 226 | 858 | 52.73 | 15.10 | 0.72 |
| 5 | 282 | 974 | 62.76 | 17.90 | 0.83 |
| 6 | 337 | 1081 | 66.05 | 19.09 | 0.87 |
| 7 | 396 | 1192 | 80.64 | 22.94 | 1.02 |
| 8 | 451 | 1303 | 96.10 | 27.03 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.84 | 8.78 | 0.51 |
| 3| 2017 | 25.91 | 9.48 | 0.52 |
| 5| 2382 | 31.34 | 12.32 | 0.60 |
| 10| 3253 | 42.99 | 18.91 | 0.78 |
| 38| 7553 | 97.88 | 52.86 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.54 | 7.30 | 0.41 |
| 2| 785 | 24.32 | 8.46 | 0.44 |
| 3| 933 | 27.10 | 9.90 | 0.48 |
| 5| 1334 | 32.25 | 12.67 | 0.56 |
| 10| 2087 | 41.06 | 18.46 | 0.71 |
| 39| 6561 | 99.41 | 53.98 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 835 | 29.26 | 9.62 | 0.49 |
| 3| 898 | 30.19 | 10.53 | 0.51 |
| 5| 1253 | 36.95 | 13.76 | 0.60 |
| 10| 2150 | 46.66 | 19.90 | 0.77 |
| 35| 5984 | 96.41 | 50.57 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 904 | 36.56 | 11.60 | 0.57 |
| 3| 939 | 37.91 | 12.62 | 0.59 |
| 5| 1203 | 41.93 | 15.06 | 0.65 |
| 10| 2074 | 54.65 | 21.99 | 0.84 |
| 29| 4880 | 98.72 | 46.93 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.08 | 9.09 | 0.69 |
| 2| 5954 | 37.05 | 12.46 | 0.80 |
| 3| 6091 | 44.80 | 15.08 | 0.89 |
| 4| 6333 | 56.18 | 18.99 | 1.02 |
| 5| 6382 | 60.73 | 20.41 | 1.07 |
| 6| 6480 | 72.30 | 24.33 | 1.19 |
| 7| 6779 | 84.63 | 28.51 | 1.34 |
| 8| 6867 | 92.17 | 31.05 | 1.42 |
| 9| 6795 | 90.22 | 30.28 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 56 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1136 | 6510 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1706 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2220 | 7159 | 98.24 | 37.65 | 1.53 |

