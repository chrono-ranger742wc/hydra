--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-11 06:45:52.038524729 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 13.18 | 4.20 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.72 | 5.91 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 751 | 40.25 | 11.70 | 0.59 |
| 4 | 226 | 858 | 48.23 | 13.99 | 0.68 |
| 5 | 283 | 969 | 61.08 | 17.49 | 0.81 |
| 6 | 340 | 1081 | 71.23 | 20.28 | 0.92 |
| 7 | 392 | 1192 | 81.28 | 23.22 | 1.03 |
| 8 | 454 | 1303 | 87.50 | 24.97 | 1.09 |
| 9 | 506 | 1414 | 93.43 | 26.78 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 23.92 | 7.60 | 0.48 |
| 2| 1884 | 24.40 | 8.40 | 0.49 |
| 3| 2077 | 27.31 | 9.86 | 0.53 |
| 5| 2453 | 32.15 | 12.56 | 0.61 |
| 10| 3067 | 39.81 | 18.02 | 0.74 |
| 41| 7591 | 97.04 | 54.57 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.31 | 0.41 |
| 2| 812 | 25.47 | 8.78 | 0.46 |
| 3| 886 | 25.82 | 9.54 | 0.47 |
| 5| 1249 | 31.37 | 12.43 | 0.55 |
| 10| 1958 | 39.96 | 18.16 | 0.69 |
| 43| 6758 | 99.30 | 56.65 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 29.13 | 8.90 | 0.48 |
| 2| 847 | 31.62 | 10.28 | 0.52 |
| 3| 959 | 33.43 | 11.44 | 0.55 |
| 5| 1319 | 37.73 | 13.99 | 0.61 |
| 10| 1992 | 44.25 | 19.18 | 0.73 |
| 35| 5775 | 95.76 | 50.28 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 995 | 38.55 | 12.81 | 0.60 |
| 5| 1235 | 41.86 | 15.04 | 0.65 |
| 10| 2060 | 54.08 | 21.83 | 0.84 |
| 30| 4997 | 99.92 | 47.87 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 26.97 | 9.05 | 0.69 |
| 2| 5893 | 32.64 | 10.90 | 0.75 |
| 3| 6114 | 42.60 | 14.29 | 0.87 |
| 4| 6324 | 54.41 | 18.37 | 1.00 |
| 5| 6322 | 58.98 | 19.83 | 1.05 |
| 6| 6646 | 71.98 | 24.38 | 1.20 |
| 7| 6705 | 80.43 | 27.11 | 1.29 |
| 8| 6764 | 87.94 | 29.48 | 1.37 |
| 9| 6995 | 93.19 | 31.29 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

