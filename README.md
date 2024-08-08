# AES Algorithm Implementation for 8086 Emulator

## Description
This project implements a single cycle of the AES (Advanced Encryption Standard) algorithm in assembly language for the 8086 emulator. It demonstrates how to encrypt data using AES to ensure secure message transmission.

## Implementation Overview
Encrypt a 128 bits block using assembly language of Intel 8086, use 4 Macros in each round and repeat it 10 times to make it more secured.
Subroutines implemented:
1) Procedure reads the input stream from the user and another 
procedure prints the result on the screen.
2) Macros for encryption process Sub Bytes, Shift Rows, Mix Columns  (http://www.angelfire.com/biz7/atleast/mix_columns.pdf) and Add Round Key (cipher block).

## Note
The code is proprietary and not intended for copying or redistribution.
