--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-28 08:23:23.490779515 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.54 | 3.97 | 0.55 |
| 3| 6236 | 14.86 | 4.71 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 99.08 | 30.97 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 41.51 | 12.00 | 0.60 |
| 4 | 225 | 858 | 51.16 | 14.72 | 0.71 |
| 5 | 283 | 969 | 64.48 | 18.28 | 0.85 |
| 6 | 337 | 1081 | 64.32 | 18.63 | 0.85 |
| 7 | 392 | 1192 | 86.99 | 24.50 | 1.08 |
| 8 | 451 | 1303 | 91.75 | 25.99 | 1.14 |
| 9 | 505 | 1414 | 91.53 | 26.39 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1997 | 26.83 | 9.06 | 0.52 |
| 3| 2146 | 28.09 | 10.09 | 0.54 |
| 5| 2409 | 31.04 | 12.25 | 0.60 |
| 10| 3135 | 40.82 | 18.31 | 0.75 |
| 40| 7626 | 98.84 | 54.45 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.84 | 7.38 | 0.42 |
| 2| 781 | 24.25 | 8.44 | 0.44 |
| 3| 878 | 25.74 | 9.54 | 0.47 |
| 5| 1101 | 27.00 | 11.19 | 0.50 |
| 10| 1998 | 40.01 | 18.17 | 0.69 |
| 42| 6681 | 97.25 | 55.43 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.17 | 8.91 | 0.48 |
| 2| 832 | 29.26 | 9.62 | 0.49 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1266 | 35.01 | 13.24 | 0.58 |
| 10| 2082 | 48.64 | 20.40 | 0.78 |
| 36| 6048 | 98.84 | 51.87 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 853 | 36.64 | 11.62 | 0.57 |
| 3| 957 | 37.91 | 12.62 | 0.59 |
| 5| 1216 | 41.93 | 15.06 | 0.65 |
| 10| 2113 | 55.53 | 22.25 | 0.85 |
| 29| 5020 | 99.80 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5949 | 35.93 | 12.06 | 0.79 |
| 3| 5973 | 40.36 | 13.46 | 0.84 |
| 4| 6175 | 53.14 | 17.82 | 0.98 |
| 5| 6468 | 65.39 | 22.02 | 1.12 |
| 6| 6528 | 72.27 | 24.25 | 1.20 |
| 7| 6743 | 81.04 | 27.32 | 1.30 |
| 8| 6798 | 90.02 | 30.25 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2221 | 7161 | 97.61 | 37.43 | 1.52 |

