--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-22 05:44:24.685073679 UTC |
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
| 2| 6037 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.44 | 12.22 | 0.61 |
| 4 | 227 | 858 | 52.37 | 14.96 | 0.72 |
| 5 | 281 | 969 | 62.77 | 17.93 | 0.83 |
| 6 | 338 | 1081 | 70.80 | 20.18 | 0.92 |
| 7 | 394 | 1192 | 72.59 | 21.01 | 0.94 |
| 8 | 450 | 1303 | 83.72 | 24.22 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 23.92 | 7.60 | 0.48 |
| 2| 1945 | 25.84 | 8.78 | 0.51 |
| 3| 2063 | 27.35 | 9.87 | 0.53 |
| 5| 2280 | 29.26 | 11.74 | 0.57 |
| 10| 3155 | 40.51 | 18.23 | 0.75 |
| 41| 7759 | 99.21 | 55.21 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.77 | 7.36 | 0.42 |
| 2| 849 | 25.06 | 8.68 | 0.45 |
| 3| 994 | 27.34 | 9.97 | 0.49 |
| 5| 1244 | 29.08 | 11.77 | 0.52 |
| 10| 2057 | 40.95 | 18.42 | 0.70 |
| 38| 6145 | 93.16 | 51.62 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.79 | 8.25 | 0.45 |
| 2| 834 | 31.62 | 10.27 | 0.52 |
| 3| 969 | 33.51 | 11.46 | 0.55 |
| 5| 1224 | 36.98 | 13.77 | 0.60 |
| 10| 1974 | 44.08 | 19.12 | 0.73 |
| 37| 6148 | 99.23 | 52.61 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.16 | 0.53 |
| 2| 761 | 35.14 | 11.16 | 0.55 |
| 3| 1036 | 38.66 | 12.84 | 0.60 |
| 5| 1278 | 42.61 | 15.27 | 0.66 |
| 10| 2078 | 54.58 | 21.96 | 0.84 |
| 30| 5071 | 99.85 | 47.89 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.09 | 9.08 | 0.69 |
| 2| 5952 | 35.96 | 12.08 | 0.79 |
| 3| 6157 | 47.25 | 15.92 | 0.92 |
| 4| 6405 | 56.67 | 19.17 | 1.03 |
| 5| 6606 | 67.09 | 22.77 | 1.15 |
| 6| 6477 | 68.52 | 22.96 | 1.15 |
| 7| 6655 | 78.82 | 26.47 | 1.27 |
| 8| 6793 | 88.68 | 29.84 | 1.38 |
| 9| 6971 | 99.24 | 33.46 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 571 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

