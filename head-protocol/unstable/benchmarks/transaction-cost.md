--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-25 06:11:33.914050705 UTC |
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
| 2| 6035 | 12.73 | 4.04 | 0.55 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 170 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 227 | 862 | 52.32 | 14.95 | 0.72 |
| 5 | 282 | 969 | 57.41 | 16.58 | 0.78 |
| 6 | 337 | 1081 | 65.65 | 18.91 | 0.86 |
| 7 | 392 | 1196 | 76.03 | 21.91 | 0.98 |
| 8 | 450 | 1303 | 96.04 | 27.07 | 1.18 |
| 9 | 505 | 1418 | 99.12 | 28.32 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 2012 | 26.76 | 9.04 | 0.52 |
| 3| 2060 | 26.94 | 9.77 | 0.53 |
| 5| 2395 | 31.19 | 12.29 | 0.60 |
| 10| 3162 | 41.95 | 18.62 | 0.76 |
| 40| 7542 | 96.45 | 53.79 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.57 | 7.31 | 0.41 |
| 2| 718 | 22.52 | 7.93 | 0.42 |
| 3| 884 | 25.01 | 9.30 | 0.46 |
| 5| 1271 | 31.27 | 12.39 | 0.55 |
| 10| 2047 | 40.52 | 18.32 | 0.70 |
| 40| 6530 | 98.87 | 54.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 816 | 31.61 | 10.27 | 0.52 |
| 3| 961 | 33.51 | 11.47 | 0.55 |
| 5| 1299 | 35.00 | 13.24 | 0.59 |
| 10| 2058 | 48.34 | 20.30 | 0.78 |
| 34| 5775 | 94.63 | 49.35 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 895 | 36.60 | 11.61 | 0.57 |
| 3| 993 | 38.59 | 12.82 | 0.60 |
| 5| 1288 | 43.21 | 15.46 | 0.67 |
| 10| 2109 | 55.56 | 22.26 | 0.85 |
| 29| 4925 | 98.78 | 46.94 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.93 | 7.56 | 0.64 |
| 2| 5874 | 35.02 | 11.74 | 0.78 |
| 3| 6239 | 47.17 | 15.92 | 0.92 |
| 4| 6264 | 54.73 | 18.43 | 1.00 |
| 5| 6427 | 60.21 | 20.24 | 1.07 |
| 6| 6649 | 70.89 | 23.91 | 1.19 |
| 7| 6643 | 75.86 | 25.55 | 1.24 |
| 8| 6962 | 94.29 | 31.74 | 1.45 |
| 9| 6889 | 96.73 | 32.57 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.74 | 14.19 | 0.84 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2163 | 7126 | 97.33 | 37.23 | 1.52 |

