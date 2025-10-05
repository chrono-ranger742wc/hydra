--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-05 04:37:19.604909062 UTC |
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
| 1| 5840 | 10.40 | 3.30 | 0.52 |
| 2| 6037 | 12.75 | 4.04 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14285 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 40.25 | 11.70 | 0.59 |
| 4 | 227 | 858 | 53.96 | 15.37 | 0.73 |
| 5 | 283 | 969 | 61.04 | 17.43 | 0.81 |
| 6 | 340 | 1081 | 73.12 | 20.74 | 0.94 |
| 7 | 396 | 1192 | 78.54 | 22.48 | 1.00 |
| 8 | 449 | 1303 | 98.82 | 27.74 | 1.21 |
| 9 | 505 | 1414 | 94.63 | 27.25 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.37 | 7.71 | 0.48 |
| 2| 1940 | 25.43 | 8.68 | 0.50 |
| 3| 2018 | 25.94 | 9.49 | 0.52 |
| 5| 2495 | 32.87 | 12.77 | 0.62 |
| 10| 2998 | 38.06 | 17.54 | 0.72 |
| 40| 7635 | 99.30 | 54.58 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.80 | 7.39 | 0.42 |
| 2| 762 | 24.01 | 8.38 | 0.44 |
| 3| 965 | 26.12 | 9.60 | 0.47 |
| 5| 1215 | 29.04 | 11.76 | 0.52 |
| 10| 2143 | 40.49 | 18.30 | 0.70 |
| 41| 6567 | 95.21 | 54.21 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 29.13 | 8.90 | 0.48 |
| 2| 890 | 29.94 | 9.83 | 0.50 |
| 3| 1025 | 31.69 | 10.98 | 0.53 |
| 5| 1195 | 36.31 | 13.56 | 0.59 |
| 10| 2036 | 47.55 | 20.07 | 0.77 |
| 37| 6064 | 98.55 | 52.40 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.16 | 0.53 |
| 2| 836 | 35.89 | 11.39 | 0.56 |
| 3| 980 | 38.55 | 12.81 | 0.60 |
| 5| 1157 | 41.22 | 14.85 | 0.64 |
| 10| 2013 | 53.91 | 21.77 | 0.83 |
| 29| 4903 | 99.19 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.08 | 9.08 | 0.69 |
| 2| 5992 | 35.79 | 12.04 | 0.79 |
| 3| 6115 | 44.76 | 15.06 | 0.89 |
| 4| 6149 | 49.19 | 16.45 | 0.94 |
| 5| 6511 | 64.76 | 21.83 | 1.12 |
| 6| 6616 | 73.36 | 24.64 | 1.21 |
| 7| 6575 | 77.95 | 26.14 | 1.26 |
| 8| 6944 | 93.70 | 31.59 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.68 | 6.24 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.38 | 38.04 | 1.54 |

