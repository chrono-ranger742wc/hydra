--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-02 07:06:16.671116328 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 228 | 862 | 48.25 | 14.03 | 0.68 |
| 5 | 282 | 969 | 59.69 | 17.14 | 0.80 |
| 6 | 340 | 1081 | 70.58 | 20.25 | 0.91 |
| 7 | 394 | 1192 | 74.64 | 21.54 | 0.96 |
| 8 | 449 | 1303 | 98.40 | 27.68 | 1.20 |
| 9 | 504 | 1418 | 92.76 | 26.57 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1930 | 25.47 | 8.70 | 0.50 |
| 3| 2064 | 26.91 | 9.76 | 0.53 |
| 5| 2366 | 31.38 | 12.33 | 0.60 |
| 10| 3254 | 42.57 | 18.81 | 0.77 |
| 38| 7616 | 99.93 | 53.46 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.57 | 7.31 | 0.41 |
| 2| 794 | 24.28 | 8.45 | 0.44 |
| 3| 948 | 26.63 | 9.79 | 0.48 |
| 5| 1211 | 29.40 | 11.88 | 0.53 |
| 10| 1908 | 37.57 | 17.48 | 0.66 |
| 43| 6773 | 98.56 | 56.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.50 | 8.46 | 0.46 |
| 2| 837 | 29.22 | 9.61 | 0.49 |
| 3| 1000 | 31.57 | 10.95 | 0.53 |
| 5| 1231 | 37.06 | 13.79 | 0.60 |
| 10| 2200 | 49.62 | 20.70 | 0.80 |
| 36| 5838 | 95.94 | 51.03 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 899 | 37.16 | 12.39 | 0.58 |
| 5| 1249 | 42.68 | 15.29 | 0.66 |
| 10| 1976 | 53.27 | 21.57 | 0.82 |
| 30| 4866 | 99.19 | 47.67 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5848 | 27.08 | 9.10 | 0.69 |
| 2| 5897 | 34.91 | 11.70 | 0.78 |
| 3| 6016 | 43.68 | 14.63 | 0.87 |
| 4| 6346 | 56.27 | 18.99 | 1.02 |
| 5| 6458 | 65.46 | 22.03 | 1.12 |
| 6| 6721 | 76.65 | 25.97 | 1.25 |
| 7| 6756 | 83.44 | 28.11 | 1.32 |
| 8| 6952 | 94.11 | 31.78 | 1.45 |
| 9| 6979 | 99.19 | 33.31 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 570 | 6175 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

