--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-13 04:40:03.956515838 UTC |
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
| 1| 5838 | 10.64 | 3.38 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.83 | 12.33 | 0.62 |
| 4 | 228 | 858 | 52.57 | 15.04 | 0.72 |
| 5 | 282 | 969 | 55.80 | 16.20 | 0.76 |
| 6 | 339 | 1081 | 73.13 | 20.70 | 0.94 |
| 7 | 394 | 1192 | 78.59 | 22.49 | 1.00 |
| 8 | 450 | 1303 | 96.87 | 27.32 | 1.19 |
| 9 | 507 | 1414 | 96.16 | 27.60 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1827 | 23.92 | 7.60 | 0.48 |
| 2| 2010 | 26.50 | 8.99 | 0.52 |
| 3| 2120 | 28.06 | 10.09 | 0.54 |
| 5| 2424 | 32.56 | 12.66 | 0.61 |
| 10| 3132 | 40.90 | 18.33 | 0.75 |
| 38| 7581 | 98.28 | 52.99 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.37 | 0.41 |
| 2| 799 | 24.05 | 8.40 | 0.44 |
| 3| 930 | 25.07 | 9.31 | 0.46 |
| 5| 1176 | 28.66 | 11.68 | 0.52 |
| 10| 2013 | 39.16 | 17.95 | 0.68 |
| 38| 6318 | 93.75 | 51.78 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.17 | 8.91 | 0.48 |
| 2| 797 | 30.87 | 10.05 | 0.51 |
| 3| 940 | 32.72 | 11.23 | 0.54 |
| 5| 1245 | 34.70 | 13.14 | 0.58 |
| 10| 1973 | 44.08 | 19.12 | 0.73 |
| 34| 5402 | 95.78 | 49.54 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 811 | 35.92 | 11.40 | 0.56 |
| 3| 955 | 37.91 | 12.62 | 0.59 |
| 5| 1228 | 42.01 | 15.08 | 0.65 |
| 10| 2031 | 54.01 | 21.80 | 0.83 |
| 29| 4943 | 99.68 | 47.20 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.13 | 9.09 | 0.69 |
| 2| 5952 | 35.92 | 12.06 | 0.79 |
| 3| 6067 | 45.12 | 15.18 | 0.89 |
| 4| 6172 | 50.41 | 16.88 | 0.95 |
| 5| 6353 | 62.76 | 21.12 | 1.09 |
| 6| 6677 | 74.95 | 25.29 | 1.23 |
| 7| 6524 | 73.98 | 24.81 | 1.21 |
| 8| 7076 | 95.77 | 32.52 | 1.47 |
| 10| 6981 | 99.53 | 33.40 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2221 | 7160 | 99.38 | 38.04 | 1.54 |

