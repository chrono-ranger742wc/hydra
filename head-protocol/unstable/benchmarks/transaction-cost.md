--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-22 05:34:08.696737243 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 858 | 49.40 | 14.25 | 0.69 |
| 5 | 282 | 974 | 61.03 | 17.45 | 0.81 |
| 6 | 338 | 1081 | 69.35 | 19.83 | 0.90 |
| 7 | 392 | 1192 | 78.52 | 22.43 | 1.00 |
| 8 | 450 | 1303 | 91.61 | 25.96 | 1.13 |
| 9 | 504 | 1414 | 88.73 | 25.66 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2073 | 27.39 | 9.88 | 0.53 |
| 5| 2382 | 31.01 | 12.24 | 0.59 |
| 10| 3285 | 41.78 | 18.58 | 0.77 |
| 39| 7627 | 99.19 | 53.89 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.84 | 7.39 | 0.42 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 944 | 26.09 | 9.59 | 0.47 |
| 5| 1240 | 30.54 | 12.19 | 0.54 |
| 10| 1947 | 39.66 | 18.09 | 0.69 |
| 41| 6578 | 99.20 | 55.28 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 837 | 31.69 | 10.29 | 0.52 |
| 3| 913 | 32.76 | 11.24 | 0.54 |
| 5| 1326 | 35.64 | 13.44 | 0.59 |
| 10| 2085 | 46.14 | 19.73 | 0.76 |
| 37| 6051 | 98.49 | 52.42 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.15 | 0.53 |
| 2| 870 | 36.48 | 11.58 | 0.57 |
| 3| 1090 | 39.27 | 13.03 | 0.61 |
| 5| 1232 | 41.78 | 15.02 | 0.65 |
| 10| 2081 | 54.51 | 21.96 | 0.84 |
| 29| 4878 | 98.02 | 46.73 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 6008 | 37.05 | 12.49 | 0.80 |
| 3| 5974 | 40.47 | 13.51 | 0.84 |
| 4| 6183 | 50.17 | 16.80 | 0.95 |
| 5| 6318 | 56.65 | 18.99 | 1.02 |
| 6| 6630 | 73.90 | 24.91 | 1.22 |
| 7| 6792 | 81.74 | 27.55 | 1.31 |
| 8| 7018 | 94.51 | 31.92 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

