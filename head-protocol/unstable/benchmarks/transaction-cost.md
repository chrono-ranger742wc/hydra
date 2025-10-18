--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-18 04:37:41.688187293 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6041 | 12.25 | 3.87 | 0.54 |
| 3| 6243 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 43.74 | 12.55 | 0.63 |
| 4 | 226 | 858 | 49.84 | 14.41 | 0.69 |
| 5 | 282 | 969 | 56.33 | 16.36 | 0.77 |
| 6 | 338 | 1081 | 75.77 | 21.45 | 0.96 |
| 7 | 395 | 1192 | 81.22 | 23.21 | 1.03 |
| 8 | 450 | 1303 | 86.06 | 24.83 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1976 | 26.58 | 9.01 | 0.52 |
| 3| 2059 | 26.94 | 9.77 | 0.53 |
| 5| 2444 | 32.19 | 12.57 | 0.61 |
| 10| 3177 | 40.87 | 18.32 | 0.75 |
| 38| 7226 | 93.33 | 51.54 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.38 | 0.41 |
| 2| 748 | 23.66 | 8.26 | 0.43 |
| 3| 886 | 25.09 | 9.32 | 0.46 |
| 5| 1272 | 31.15 | 12.36 | 0.55 |
| 10| 2051 | 40.36 | 18.28 | 0.70 |
| 41| 6516 | 96.27 | 54.47 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.54 | 8.47 | 0.46 |
| 2| 898 | 29.90 | 9.82 | 0.50 |
| 3| 877 | 32.09 | 11.03 | 0.53 |
| 5| 1381 | 39.15 | 14.42 | 0.63 |
| 10| 2025 | 47.63 | 20.09 | 0.77 |
| 38| 6175 | 99.62 | 53.40 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.64 | 11.62 | 0.57 |
| 3| 945 | 37.91 | 12.62 | 0.59 |
| 5| 1268 | 42.64 | 15.28 | 0.66 |
| 10| 2047 | 54.25 | 21.85 | 0.84 |
| 30| 4768 | 97.20 | 47.07 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.05 | 9.07 | 0.69 |
| 2| 6033 | 36.97 | 12.47 | 0.80 |
| 3| 5974 | 40.47 | 13.51 | 0.84 |
| 4| 6240 | 53.51 | 18.03 | 0.99 |
| 5| 6245 | 56.18 | 18.77 | 1.01 |
| 6| 6560 | 73.44 | 24.76 | 1.21 |
| 7| 6585 | 82.20 | 27.63 | 1.30 |
| 8| 7052 | 98.46 | 33.35 | 1.50 |
| 9| 6941 | 96.69 | 32.53 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

