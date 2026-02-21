--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-21 05:31:23.075751629 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 41.22 | 11.92 | 0.60 |
| 4 | 227 | 858 | 53.75 | 15.37 | 0.73 |
| 5 | 281 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 340 | 1081 | 66.12 | 19.06 | 0.87 |
| 7 | 395 | 1192 | 81.61 | 23.35 | 1.03 |
| 8 | 450 | 1303 | 85.59 | 24.66 | 1.08 |
| 10 | 560 | 1525 | 99.87 | 28.79 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1953 | 26.22 | 8.90 | 0.51 |
| 3| 2017 | 25.95 | 9.49 | 0.52 |
| 5| 2383 | 31.45 | 12.35 | 0.60 |
| 10| 3323 | 42.30 | 18.74 | 0.77 |
| 40| 7553 | 96.47 | 53.74 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.38 | 0.42 |
| 2| 776 | 24.25 | 8.44 | 0.44 |
| 3| 931 | 27.10 | 9.90 | 0.48 |
| 5| 1268 | 31.06 | 12.33 | 0.55 |
| 10| 2063 | 42.28 | 18.79 | 0.72 |
| 39| 6456 | 96.86 | 53.31 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 29.13 | 8.90 | 0.48 |
| 2| 820 | 31.54 | 10.26 | 0.52 |
| 3| 996 | 31.65 | 10.97 | 0.53 |
| 5| 1321 | 35.64 | 13.44 | 0.59 |
| 10| 2033 | 48.16 | 20.26 | 0.77 |
| 35| 5897 | 95.52 | 50.29 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 803 | 35.88 | 11.39 | 0.56 |
| 3| 899 | 37.13 | 12.38 | 0.58 |
| 5| 1290 | 43.24 | 15.46 | 0.67 |
| 10| 2091 | 55.00 | 22.10 | 0.85 |
| 29| 4831 | 97.92 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.97 | 9.07 | 0.69 |
| 2| 5894 | 34.91 | 11.68 | 0.78 |
| 3| 6092 | 44.84 | 15.09 | 0.89 |
| 4| 6223 | 54.18 | 18.25 | 0.99 |
| 5| 6360 | 60.18 | 20.23 | 1.06 |
| 6| 6614 | 73.62 | 24.85 | 1.22 |
| 7| 6618 | 79.87 | 26.87 | 1.28 |
| 8| 6991 | 94.32 | 31.85 | 1.45 |
| 9| 6792 | 83.02 | 27.77 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 283 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6173 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1137 | 6511 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1710 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 37 | 2102 | 7087 | 94.58 | 36.18 | 1.49 |

