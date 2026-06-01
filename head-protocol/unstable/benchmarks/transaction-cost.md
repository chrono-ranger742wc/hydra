--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-01 09:58:23.178094552 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.18 | 9.20 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 44.09 | 12.65 | 0.63 |
| 4 | 226 | 862 | 47.78 | 13.91 | 0.67 |
| 5 | 281 | 969 | 55.94 | 16.20 | 0.76 |
| 6 | 337 | 1081 | 69.97 | 20.02 | 0.91 |
| 7 | 395 | 1192 | 84.15 | 23.82 | 1.05 |
| 8 | 450 | 1303 | 99.09 | 27.85 | 1.21 |
| 9 | 506 | 1414 | 98.67 | 28.10 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2125 | 28.23 | 10.12 | 0.54 |
| 5| 2368 | 31.12 | 12.27 | 0.59 |
| 10| 3136 | 40.94 | 18.34 | 0.75 |
| 38| 7297 | 92.89 | 51.47 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 780 | 24.35 | 8.48 | 0.44 |
| 3| 889 | 25.05 | 9.31 | 0.46 |
| 5| 1221 | 29.62 | 11.94 | 0.53 |
| 10| 1976 | 39.87 | 18.13 | 0.69 |
| 40| 6454 | 99.80 | 54.71 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 825 | 29.19 | 9.60 | 0.49 |
| 3| 974 | 30.98 | 10.76 | 0.52 |
| 5| 1248 | 35.08 | 13.26 | 0.58 |
| 10| 1959 | 44.23 | 19.16 | 0.73 |
| 36| 5821 | 95.59 | 50.91 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.87 | 10.16 | 0.53 |
| 2| 838 | 35.92 | 11.40 | 0.56 |
| 3| 953 | 37.84 | 12.60 | 0.59 |
| 5| 1310 | 43.32 | 15.49 | 0.67 |
| 10| 2014 | 54.06 | 21.81 | 0.83 |
| 29| 4729 | 96.13 | 46.13 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 6046 | 36.84 | 12.42 | 0.80 |
| 3| 6180 | 47.45 | 16.05 | 0.92 |
| 4| 6229 | 51.49 | 17.31 | 0.97 |
| 5| 6485 | 64.65 | 21.81 | 1.12 |
| 6| 6559 | 74.58 | 25.12 | 1.22 |
| 7| 6822 | 83.72 | 28.34 | 1.33 |
| 8| 7037 | 95.14 | 32.17 | 1.46 |
| 9| 6944 | 98.43 | 33.08 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 283 | 6002 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2160 | 7123 | 96.88 | 37.08 | 1.51 |

