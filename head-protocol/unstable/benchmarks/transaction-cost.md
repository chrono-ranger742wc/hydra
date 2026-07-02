--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-02 08:18:06.373622105 UTC |
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
| 1| 5836 | 10.35 | 3.28 | 0.51 |
| 2| 6042 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 15.05 | 4.78 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 751 | 41.40 | 11.95 | 0.60 |
| 4 | 226 | 858 | 51.10 | 14.68 | 0.71 |
| 5 | 283 | 969 | 61.33 | 17.56 | 0.81 |
| 6 | 339 | 1085 | 71.98 | 20.58 | 0.93 |
| 7 | 393 | 1192 | 73.51 | 21.22 | 0.95 |
| 8 | 450 | 1303 | 81.01 | 23.51 | 1.03 |
| 9 | 505 | 1414 | 99.23 | 28.29 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.00 | 7.62 | 0.48 |
| 2| 1981 | 26.39 | 8.96 | 0.52 |
| 3| 2072 | 27.40 | 9.88 | 0.53 |
| 5| 2348 | 30.87 | 12.19 | 0.59 |
| 10| 3335 | 43.91 | 19.17 | 0.79 |
| 42| 7830 | 98.87 | 55.79 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.81 | 7.37 | 0.42 |
| 2| 754 | 24.35 | 8.46 | 0.44 |
| 3| 908 | 25.06 | 9.31 | 0.46 |
| 5| 1167 | 28.11 | 11.50 | 0.51 |
| 10| 1959 | 37.66 | 17.50 | 0.67 |
| 39| 6270 | 95.02 | 52.79 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 29.13 | 8.90 | 0.48 |
| 2| 826 | 29.22 | 9.61 | 0.49 |
| 3| 926 | 32.80 | 11.25 | 0.54 |
| 5| 1325 | 35.65 | 13.44 | 0.59 |
| 10| 1964 | 44.08 | 19.12 | 0.73 |
| 37| 6201 | 99.30 | 52.64 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 864 | 36.52 | 11.59 | 0.57 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1333 | 43.98 | 15.69 | 0.68 |
| 10| 2097 | 55.02 | 22.10 | 0.85 |
| 29| 5025 | 99.05 | 47.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 26.92 | 9.04 | 0.69 |
| 2| 6046 | 36.76 | 12.41 | 0.80 |
| 3| 6167 | 45.74 | 15.42 | 0.90 |
| 4| 6367 | 56.01 | 18.91 | 1.02 |
| 5| 6245 | 58.70 | 19.63 | 1.04 |
| 6| 6365 | 65.74 | 22.05 | 1.12 |
| 7| 6753 | 80.88 | 27.21 | 1.30 |
| 8| 6962 | 95.28 | 32.21 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

