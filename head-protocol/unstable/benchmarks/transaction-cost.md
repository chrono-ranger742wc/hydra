--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-28 06:53:04.013415236 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 13.10 | 4.17 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 735 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 751 | 42.45 | 12.22 | 0.61 |
| 4 | 228 | 858 | 48.32 | 14.02 | 0.68 |
| 5 | 280 | 969 | 58.38 | 16.85 | 0.79 |
| 6 | 338 | 1085 | 75.08 | 21.28 | 0.96 |
| 7 | 394 | 1192 | 78.26 | 22.32 | 1.00 |
| 8 | 451 | 1303 | 93.93 | 26.56 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.40 | 8.40 | 0.49 |
| 3| 2080 | 27.06 | 9.80 | 0.53 |
| 5| 2354 | 30.26 | 12.02 | 0.58 |
| 10| 3166 | 41.43 | 18.46 | 0.76 |
| 41| 7696 | 97.98 | 54.86 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.84 | 7.38 | 0.42 |
| 2| 770 | 24.05 | 8.39 | 0.44 |
| 3| 854 | 24.07 | 9.03 | 0.45 |
| 5| 1273 | 30.91 | 12.30 | 0.54 |
| 10| 1995 | 39.42 | 17.99 | 0.69 |
| 42| 6712 | 98.75 | 55.84 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 844 | 31.62 | 10.27 | 0.52 |
| 3| 967 | 33.39 | 11.44 | 0.55 |
| 5| 1292 | 37.62 | 13.96 | 0.61 |
| 10| 2032 | 48.30 | 20.29 | 0.78 |
| 35| 6029 | 97.71 | 50.92 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.87 | 10.16 | 0.53 |
| 2| 835 | 35.85 | 11.38 | 0.56 |
| 3| 942 | 37.95 | 12.63 | 0.59 |
| 5| 1206 | 41.82 | 15.03 | 0.65 |
| 10| 2079 | 54.42 | 21.94 | 0.84 |
| 30| 4891 | 98.78 | 47.56 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.05 | 9.07 | 0.69 |
| 2| 6005 | 37.08 | 12.51 | 0.80 |
| 3| 6143 | 45.93 | 15.47 | 0.90 |
| 4| 6281 | 54.21 | 18.33 | 1.00 |
| 5| 6521 | 65.08 | 22.00 | 1.12 |
| 6| 6505 | 72.60 | 24.42 | 1.20 |
| 7| 6866 | 85.05 | 28.74 | 1.35 |
| 8| 6882 | 93.75 | 31.61 | 1.44 |
| 9| 6988 | 96.34 | 32.44 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2163 | 7125 | 97.33 | 37.23 | 1.52 |

