--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-17 07:08:51.432699557 UTC |
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
| 1| 5840 | 10.38 | 3.29 | 0.51 |
| 2| 6039 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 41.18 | 11.91 | 0.60 |
| 4 | 227 | 862 | 52.29 | 14.97 | 0.72 |
| 5 | 282 | 969 | 62.49 | 17.80 | 0.83 |
| 6 | 339 | 1081 | 74.72 | 21.12 | 0.95 |
| 7 | 394 | 1192 | 74.45 | 21.58 | 0.96 |
| 8 | 448 | 1303 | 85.01 | 24.38 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.88 | 8.79 | 0.51 |
| 3| 2115 | 28.51 | 10.19 | 0.55 |
| 5| 2454 | 32.44 | 12.63 | 0.61 |
| 10| 3045 | 38.48 | 17.66 | 0.72 |
| 40| 7532 | 93.79 | 53.06 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.80 | 7.38 | 0.41 |
| 2| 824 | 25.47 | 8.80 | 0.46 |
| 3| 838 | 24.09 | 9.05 | 0.45 |
| 5| 1276 | 30.98 | 12.33 | 0.55 |
| 10| 2144 | 43.41 | 19.10 | 0.73 |
| 41| 6633 | 99.88 | 55.47 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 27.47 | 8.46 | 0.46 |
| 2| 792 | 30.91 | 10.06 | 0.51 |
| 3| 978 | 33.47 | 11.45 | 0.55 |
| 5| 1275 | 37.77 | 14.00 | 0.61 |
| 10| 2058 | 47.88 | 20.19 | 0.77 |
| 37| 5986 | 98.45 | 52.38 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.16 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 1058 | 39.23 | 13.02 | 0.61 |
| 5| 1294 | 43.25 | 15.47 | 0.67 |
| 10| 2080 | 54.84 | 22.04 | 0.84 |
| 29| 4905 | 98.91 | 46.97 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5843 | 27.08 | 9.09 | 0.69 |
| 2| 5908 | 32.57 | 10.87 | 0.75 |
| 3| 6045 | 45.08 | 15.13 | 0.89 |
| 4| 6244 | 52.62 | 17.72 | 0.98 |
| 5| 6244 | 58.44 | 19.52 | 1.04 |
| 6| 6654 | 74.85 | 25.31 | 1.23 |
| 7| 6663 | 80.31 | 27.09 | 1.29 |
| 8| 6931 | 93.40 | 31.50 | 1.44 |
| 9| 6870 | 94.36 | 31.75 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2164 | 7127 | 97.07 | 37.14 | 1.52 |

