--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-21 05:10:57.569574392 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 227 | 858 | 48.31 | 14.01 | 0.68 |
| 5 | 282 | 969 | 62.93 | 17.97 | 0.83 |
| 6 | 337 | 1081 | 71.68 | 20.43 | 0.92 |
| 7 | 397 | 1192 | 78.64 | 22.59 | 1.00 |
| 8 | 451 | 1303 | 91.92 | 26.08 | 1.14 |
| 9 | 505 | 1414 | 90.99 | 26.20 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.43 | 8.68 | 0.50 |
| 3| 2149 | 27.97 | 10.06 | 0.54 |
| 5| 2382 | 30.93 | 12.22 | 0.59 |
| 10| 3091 | 39.39 | 17.92 | 0.73 |
| 42| 7852 | 99.19 | 55.88 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.81 | 7.37 | 0.42 |
| 2| 814 | 25.39 | 8.76 | 0.45 |
| 3| 992 | 28.27 | 10.21 | 0.50 |
| 5| 1168 | 28.81 | 11.71 | 0.52 |
| 10| 1994 | 40.71 | 18.37 | 0.70 |
| 39| 6312 | 94.20 | 52.57 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 771 | 28.47 | 9.38 | 0.48 |
| 3| 1069 | 32.29 | 11.17 | 0.54 |
| 5| 1273 | 37.85 | 14.02 | 0.61 |
| 10| 2018 | 44.93 | 19.37 | 0.74 |
| 32| 5235 | 93.69 | 47.64 | 1.48 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 838 | 35.88 | 11.39 | 0.56 |
| 3| 976 | 38.66 | 12.84 | 0.60 |
| 5| 1257 | 42.49 | 15.24 | 0.66 |
| 10| 1999 | 53.91 | 21.77 | 0.83 |
| 29| 4889 | 98.12 | 46.75 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5907 | 32.64 | 10.90 | 0.75 |
| 3| 6078 | 44.93 | 15.08 | 0.89 |
| 4| 6392 | 55.78 | 18.86 | 1.02 |
| 5| 6423 | 61.71 | 20.80 | 1.08 |
| 6| 6565 | 71.62 | 24.18 | 1.19 |
| 7| 6825 | 84.79 | 28.67 | 1.34 |
| 8| 6949 | 91.01 | 30.71 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

