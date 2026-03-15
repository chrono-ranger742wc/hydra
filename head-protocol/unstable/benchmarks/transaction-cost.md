--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-15 05:53:01.267965391 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 43.84 | 12.55 | 0.63 |
| 4 | 226 | 858 | 49.67 | 14.34 | 0.69 |
| 5 | 280 | 969 | 64.39 | 18.26 | 0.84 |
| 6 | 337 | 1081 | 71.96 | 20.50 | 0.93 |
| 7 | 393 | 1192 | 72.16 | 20.90 | 0.94 |
| 8 | 450 | 1303 | 98.57 | 27.62 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 1947 | 25.47 | 8.69 | 0.50 |
| 3| 2018 | 25.87 | 9.47 | 0.52 |
| 5| 2337 | 29.96 | 11.95 | 0.58 |
| 10| 3054 | 38.56 | 17.68 | 0.72 |
| 41| 7849 | 99.78 | 55.41 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 771 | 24.01 | 8.38 | 0.44 |
| 3| 918 | 25.56 | 9.48 | 0.47 |
| 5| 1204 | 29.11 | 11.78 | 0.52 |
| 10| 1897 | 38.76 | 17.82 | 0.68 |
| 43| 6638 | 99.47 | 56.64 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.50 | 8.46 | 0.46 |
| 2| 831 | 29.22 | 9.61 | 0.49 |
| 3| 1018 | 33.73 | 11.54 | 0.55 |
| 5| 1209 | 34.33 | 13.03 | 0.57 |
| 10| 2079 | 45.05 | 19.42 | 0.75 |
| 37| 6109 | 98.99 | 52.55 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 963 | 37.91 | 12.62 | 0.59 |
| 5| 1314 | 43.25 | 15.47 | 0.67 |
| 10| 2183 | 55.84 | 22.37 | 0.86 |
| 30| 4906 | 98.99 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 26.96 | 9.06 | 0.69 |
| 2| 5899 | 34.83 | 11.64 | 0.78 |
| 3| 6125 | 45.66 | 15.43 | 0.90 |
| 4| 6335 | 55.65 | 18.83 | 1.01 |
| 5| 6430 | 63.70 | 21.47 | 1.10 |
| 6| 6600 | 74.03 | 24.99 | 1.22 |
| 7| 6596 | 76.05 | 25.53 | 1.24 |
| 8| 6862 | 92.77 | 31.20 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1710 | 6856 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2218 | 7158 | 97.79 | 37.50 | 1.53 |

