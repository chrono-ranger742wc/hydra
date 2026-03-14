--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-14 05:35:32.630553148 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.41 | 5.80 | 0.63 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 43.70 | 12.54 | 0.63 |
| 4 | 227 | 858 | 48.20 | 13.99 | 0.68 |
| 5 | 282 | 969 | 58.05 | 16.74 | 0.78 |
| 6 | 337 | 1081 | 74.10 | 21.05 | 0.95 |
| 7 | 394 | 1196 | 78.89 | 22.65 | 1.00 |
| 8 | 450 | 1307 | 96.45 | 27.17 | 1.18 |
| 9 | 505 | 1418 | 88.62 | 25.69 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.00 | 7.62 | 0.48 |
| 2| 1994 | 26.76 | 9.04 | 0.52 |
| 3| 2104 | 28.10 | 10.09 | 0.54 |
| 5| 2391 | 31.11 | 12.27 | 0.60 |
| 10| 3144 | 40.52 | 18.23 | 0.75 |
| 39| 7508 | 95.72 | 52.93 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.84 | 7.38 | 0.41 |
| 2| 789 | 24.28 | 8.45 | 0.44 |
| 3| 882 | 25.82 | 9.55 | 0.47 |
| 5| 1148 | 28.60 | 11.65 | 0.52 |
| 10| 2005 | 39.60 | 18.05 | 0.69 |
| 39| 6318 | 93.89 | 52.50 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 709 | 27.54 | 8.47 | 0.47 |
| 2| 775 | 28.51 | 9.39 | 0.48 |
| 3| 925 | 32.69 | 11.22 | 0.54 |
| 5| 1257 | 35.05 | 13.25 | 0.58 |
| 10| 2093 | 45.61 | 19.58 | 0.75 |
| 34| 5757 | 94.16 | 49.24 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 893 | 36.56 | 11.60 | 0.57 |
| 3| 985 | 38.63 | 12.83 | 0.60 |
| 5| 1328 | 43.24 | 15.46 | 0.67 |
| 10| 2035 | 53.75 | 21.73 | 0.83 |
| 29| 5009 | 99.12 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.09 | 9.09 | 0.69 |
| 2| 5976 | 35.87 | 12.06 | 0.79 |
| 3| 6078 | 42.75 | 14.34 | 0.87 |
| 4| 6249 | 53.64 | 18.04 | 0.99 |
| 5| 6489 | 64.89 | 21.89 | 1.12 |
| 6| 6475 | 70.67 | 23.84 | 1.18 |
| 7| 6620 | 79.67 | 26.75 | 1.28 |
| 8| 6872 | 91.98 | 30.90 | 1.42 |
| 9| 6928 | 98.25 | 33.01 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 30.42 | 10.80 | 0.74 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6511 | 59.91 | 22.51 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.68 | 37.80 | 1.53 |

