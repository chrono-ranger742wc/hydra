--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-16 09:39:48.618401972 UTC |
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
| 1| 5834 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 224 | 862 | 53.93 | 15.36 | 0.73 |
| 5 | 284 | 974 | 60.92 | 17.43 | 0.81 |
| 6 | 338 | 1081 | 70.35 | 20.12 | 0.91 |
| 7 | 394 | 1192 | 71.78 | 20.77 | 0.93 |
| 8 | 449 | 1303 | 90.22 | 25.77 | 1.12 |
| 9 | 504 | 1414 | 93.73 | 26.91 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.29 | 7.69 | 0.48 |
| 2| 1887 | 24.85 | 8.50 | 0.50 |
| 3| 2102 | 28.39 | 10.16 | 0.55 |
| 5| 2445 | 32.29 | 12.59 | 0.61 |
| 10| 3131 | 41.04 | 18.36 | 0.75 |
| 38| 7484 | 98.46 | 53.02 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 771 | 24.35 | 8.46 | 0.44 |
| 3| 897 | 25.52 | 9.47 | 0.46 |
| 5| 1171 | 28.77 | 11.70 | 0.52 |
| 10| 1915 | 38.85 | 17.83 | 0.68 |
| 40| 6641 | 99.40 | 54.69 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 817 | 29.26 | 9.62 | 0.49 |
| 3| 906 | 30.15 | 10.52 | 0.51 |
| 5| 1253 | 35.04 | 13.25 | 0.58 |
| 10| 2033 | 44.94 | 19.38 | 0.74 |
| 34| 5653 | 93.01 | 48.89 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 1038 | 39.30 | 13.04 | 0.61 |
| 5| 1162 | 41.29 | 14.86 | 0.64 |
| 10| 1943 | 53.50 | 21.63 | 0.82 |
| 29| 5015 | 98.55 | 46.88 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 6013 | 36.76 | 12.41 | 0.80 |
| 3| 6119 | 45.80 | 15.47 | 0.90 |
| 4| 6378 | 55.75 | 18.87 | 1.02 |
| 5| 6318 | 60.39 | 20.30 | 1.06 |
| 6| 6660 | 74.32 | 25.07 | 1.22 |
| 7| 6686 | 77.20 | 25.91 | 1.25 |
| 8| 6871 | 92.02 | 31.00 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1705 | 6852 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

