--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-24 05:34:07.931576167 UTC |
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
| 1| 5836 | 10.74 | 3.42 | 0.52 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.72 | 4.66 | 0.58 |
| 5| 6643 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 42.68 | 12.30 | 0.62 |
| 4 | 227 | 858 | 53.77 | 15.30 | 0.73 |
| 5 | 282 | 969 | 61.11 | 17.50 | 0.81 |
| 6 | 337 | 1081 | 73.40 | 20.77 | 0.94 |
| 7 | 393 | 1192 | 80.83 | 23.07 | 1.02 |
| 8 | 448 | 1303 | 85.12 | 24.50 | 1.07 |
| 9 | 505 | 1414 | 94.95 | 27.33 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.37 | 7.71 | 0.48 |
| 2| 1957 | 25.84 | 8.78 | 0.51 |
| 3| 2099 | 28.43 | 10.17 | 0.55 |
| 5| 2432 | 32.60 | 12.67 | 0.61 |
| 10| 3172 | 41.08 | 18.41 | 0.75 |
| 39| 7535 | 98.24 | 53.60 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.81 | 7.38 | 0.42 |
| 2| 710 | 22.58 | 7.94 | 0.42 |
| 3| 978 | 26.16 | 9.61 | 0.47 |
| 5| 1186 | 29.22 | 11.82 | 0.52 |
| 10| 1944 | 39.95 | 18.15 | 0.69 |
| 41| 6566 | 99.00 | 55.19 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 850 | 29.18 | 9.60 | 0.49 |
| 3| 948 | 32.69 | 11.22 | 0.54 |
| 5| 1222 | 37.14 | 13.81 | 0.60 |
| 10| 2147 | 48.82 | 20.46 | 0.79 |
| 34| 5884 | 96.40 | 49.91 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 773 | 35.21 | 11.18 | 0.55 |
| 3| 960 | 37.91 | 12.62 | 0.59 |
| 5| 1394 | 44.17 | 15.75 | 0.68 |
| 10| 1956 | 53.45 | 21.62 | 0.82 |
| 29| 4821 | 97.75 | 46.61 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 26.97 | 9.07 | 0.69 |
| 2| 5826 | 31.52 | 10.49 | 0.74 |
| 3| 6156 | 45.88 | 15.48 | 0.90 |
| 4| 6169 | 51.27 | 17.24 | 0.96 |
| 5| 6279 | 61.84 | 20.77 | 1.08 |
| 6| 6447 | 72.05 | 24.19 | 1.19 |
| 7| 6790 | 83.81 | 28.29 | 1.33 |
| 8| 6896 | 91.96 | 30.95 | 1.42 |
| 9| 6966 | 97.73 | 32.94 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1704 | 6851 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

