--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-17 06:48:33.757779668 UTC |
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
| 1| 5841 | 10.85 | 3.45 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.38 | 4.54 | 0.57 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.48 | 12.44 | 0.62 |
| 4 | 225 | 858 | 49.80 | 14.42 | 0.69 |
| 5 | 281 | 969 | 56.77 | 16.47 | 0.77 |
| 6 | 338 | 1081 | 64.98 | 18.87 | 0.86 |
| 7 | 396 | 1192 | 74.49 | 21.51 | 0.96 |
| 8 | 448 | 1307 | 90.59 | 25.91 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.85 | 8.50 | 0.50 |
| 3| 2071 | 27.39 | 9.88 | 0.53 |
| 5| 2435 | 32.19 | 12.57 | 0.61 |
| 10| 3224 | 42.46 | 18.78 | 0.77 |
| 40| 7522 | 96.41 | 53.78 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 701 | 22.55 | 7.94 | 0.42 |
| 3| 948 | 26.12 | 9.60 | 0.47 |
| 5| 1196 | 28.01 | 11.47 | 0.51 |
| 10| 1873 | 37.46 | 17.45 | 0.66 |
| 42| 6620 | 96.36 | 55.20 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.50 | 8.46 | 0.46 |
| 2| 831 | 29.26 | 9.62 | 0.49 |
| 3| 1043 | 34.19 | 11.67 | 0.56 |
| 5| 1292 | 37.77 | 14.00 | 0.61 |
| 10| 1881 | 42.91 | 18.76 | 0.71 |
| 34| 5821 | 95.70 | 49.68 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 833 | 35.92 | 11.40 | 0.56 |
| 3| 983 | 38.17 | 12.70 | 0.59 |
| 5| 1385 | 44.07 | 15.71 | 0.68 |
| 10| 2072 | 54.65 | 21.99 | 0.84 |
| 28| 4702 | 95.69 | 45.37 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5919 | 35.97 | 12.06 | 0.79 |
| 3| 6201 | 47.02 | 15.89 | 0.92 |
| 4| 6337 | 55.87 | 18.94 | 1.02 |
| 5| 6404 | 64.12 | 21.62 | 1.11 |
| 6| 6604 | 74.35 | 25.10 | 1.22 |
| 7| 6808 | 84.59 | 28.54 | 1.34 |
| 8| 6933 | 93.70 | 31.62 | 1.44 |
| 9| 7017 | 93.66 | 31.49 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 30.42 | 10.80 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1141 | 6516 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2219 | 7158 | 98.68 | 37.80 | 1.53 |

