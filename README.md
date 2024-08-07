# Clips-Production-System
CLIPS Production System (expert system shell) repository

This repository holds code I have written as well as common CLIPS code that I have modified.  Usually the common CLIPS code had to be modified to made it compatible with the current CLIPS interpreter.

Modified wine.clp on 2024-08-07 because it fails to load under the CLIPS 6.4.1 interpreter because the code uses the deprecated nth function.  nth was transitioned to nth$ at some point in the last few years (the code will almost certainly fail with CLIPS 6.4 as well).
