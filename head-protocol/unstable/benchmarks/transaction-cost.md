--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-21 06:27:13.616372285 UTC |
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
| 1| 5837 | 10.86 | 3.46 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 42.50 | 12.23 | 0.61 |
| 4 | 227 | 858 | 50.87 | 14.63 | 0.70 |
| 5 | 282 | 969 | 64.25 | 18.22 | 0.84 |
| 6 | 338 | 1081 | 68.09 | 19.61 | 0.89 |
| 7 | 396 | 1192 | 80.18 | 22.82 | 1.02 |
| 8 | 449 | 1303 | 93.89 | 26.50 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1890 | 24.40 | 8.39 | 0.49 |
| 3| 2018 | 25.87 | 9.47 | 0.52 |
| 5| 2410 | 31.20 | 12.29 | 0.60 |
| 10| 3228 | 42.00 | 18.63 | 0.77 |
| 38| 7543 | 97.22 | 52.69 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.57 | 7.30 | 0.41 |
| 2| 818 | 25.35 | 8.77 | 0.45 |
| 3| 951 | 26.63 | 9.79 | 0.48 |
| 5| 1304 | 31.57 | 12.51 | 0.55 |
| 10| 2000 | 39.86 | 18.12 | 0.69 |
| 41| 6442 | 97.22 | 54.70 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 996 | 31.53 | 10.94 | 0.53 |
| 5| 1214 | 34.37 | 13.04 | 0.58 |
| 10| 2048 | 48.00 | 20.22 | 0.77 |
| 37| 6106 | 99.24 | 52.63 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 818 | 35.88 | 11.39 | 0.56 |
| 3| 899 | 37.16 | 12.39 | 0.58 |
| 5| 1317 | 43.43 | 15.51 | 0.67 |
| 10| 1929 | 52.89 | 21.46 | 0.82 |
| 28| 4737 | 95.53 | 45.35 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.00 | 9.07 | 0.69 |
| 2| 5956 | 36.77 | 12.41 | 0.80 |
| 3| 6165 | 45.88 | 15.46 | 0.90 |
| 4| 6295 | 54.88 | 18.52 | 1.00 |
| 5| 6359 | 62.81 | 21.11 | 1.09 |
| 6| 6472 | 68.85 | 23.10 | 1.16 |
| 7| 7004 | 86.88 | 29.50 | 1.37 |
| 8| 6785 | 88.06 | 29.69 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6510 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

