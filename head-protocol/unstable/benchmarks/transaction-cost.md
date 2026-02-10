--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-10 06:02:56.523129165 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.88 | 5.97 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 226 | 862 | 50.79 | 14.63 | 0.70 |
| 5 | 283 | 969 | 64.45 | 18.33 | 0.85 |
| 6 | 339 | 1081 | 63.84 | 18.52 | 0.85 |
| 7 | 396 | 1192 | 74.96 | 21.67 | 0.96 |
| 8 | 449 | 1303 | 98.69 | 27.75 | 1.20 |
| 10 | 560 | 1525 | 99.31 | 28.53 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.29 | 7.69 | 0.48 |
| 2| 1946 | 25.55 | 8.71 | 0.51 |
| 3| 2120 | 28.38 | 10.16 | 0.55 |
| 5| 2348 | 30.38 | 12.05 | 0.59 |
| 10| 3228 | 43.30 | 18.99 | 0.78 |
| 41| 7454 | 95.37 | 54.10 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.84 | 7.39 | 0.42 |
| 2| 811 | 25.13 | 8.71 | 0.45 |
| 3| 958 | 26.06 | 9.59 | 0.47 |
| 5| 1314 | 32.42 | 12.72 | 0.56 |
| 10| 2053 | 41.16 | 18.47 | 0.71 |
| 41| 6611 | 97.39 | 54.75 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 972 | 33.36 | 11.43 | 0.54 |
| 5| 1285 | 37.58 | 13.95 | 0.61 |
| 10| 1985 | 47.48 | 20.05 | 0.77 |
| 34| 5614 | 92.65 | 48.75 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 945 | 37.91 | 12.62 | 0.59 |
| 5| 1367 | 44.07 | 15.71 | 0.68 |
| 10| 2053 | 54.10 | 21.82 | 0.83 |
| 29| 4990 | 98.42 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.00 | 9.08 | 0.69 |
| 2| 5845 | 31.48 | 10.47 | 0.74 |
| 3| 6016 | 41.36 | 13.84 | 0.85 |
| 4| 6282 | 55.20 | 18.60 | 1.01 |
| 5| 6360 | 60.91 | 20.50 | 1.07 |
| 6| 6605 | 74.18 | 25.01 | 1.22 |
| 7| 6725 | 83.81 | 28.28 | 1.33 |
| 8| 6783 | 91.54 | 30.89 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1135 | 6509 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7159 | 97.16 | 37.28 | 1.52 |

