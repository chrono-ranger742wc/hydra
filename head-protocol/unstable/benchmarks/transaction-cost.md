--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-02 06:31:51.929339234 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 99.33 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 228 | 858 | 51.20 | 14.73 | 0.71 |
| 5 | 281 | 969 | 64.09 | 18.18 | 0.84 |
| 6 | 337 | 1085 | 70.10 | 19.97 | 0.91 |
| 7 | 394 | 1192 | 80.66 | 22.98 | 1.02 |
| 8 | 449 | 1303 | 80.59 | 23.37 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.29 | 7.69 | 0.48 |
| 2| 1890 | 24.85 | 8.50 | 0.50 |
| 3| 2103 | 28.31 | 10.14 | 0.54 |
| 5| 2457 | 32.23 | 12.58 | 0.61 |
| 10| 3121 | 40.56 | 18.24 | 0.75 |
| 41| 7801 | 99.23 | 55.26 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.57 | 7.31 | 0.41 |
| 2| 853 | 25.06 | 8.68 | 0.45 |
| 3| 836 | 24.13 | 9.04 | 0.45 |
| 5| 1274 | 31.10 | 12.34 | 0.55 |
| 10| 2079 | 41.71 | 18.65 | 0.71 |
| 42| 6686 | 98.57 | 55.76 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.54 | 8.47 | 0.46 |
| 2| 860 | 31.54 | 10.25 | 0.52 |
| 3| 920 | 32.75 | 11.24 | 0.54 |
| 5| 1215 | 34.37 | 13.04 | 0.58 |
| 10| 1986 | 46.84 | 19.85 | 0.76 |
| 38| 5998 | 98.19 | 52.93 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.85 | 11.38 | 0.56 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1336 | 43.27 | 15.47 | 0.67 |
| 10| 2230 | 56.07 | 22.42 | 0.86 |
| 29| 4817 | 96.78 | 46.35 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.09 | 9.08 | 0.69 |
| 2| 6029 | 36.93 | 12.44 | 0.80 |
| 3| 6166 | 45.55 | 15.38 | 0.90 |
| 4| 6215 | 54.70 | 18.45 | 1.00 |
| 5| 6446 | 63.78 | 21.49 | 1.10 |
| 6| 6563 | 70.05 | 23.57 | 1.17 |
| 7| 6878 | 83.42 | 28.17 | 1.33 |
| 8| 6851 | 91.11 | 30.70 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1707 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

