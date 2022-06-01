# BarcodeGen
Creating a Barcode image file with Python

There are two ways to use this script:

1. From with the script open:
    Insert an EAN code in the ean variable at the top.
    change the width of the code via the size variable

2. From the console:
    start the script via $python3 save_barcode.py
    Optional arguments (order does not matter):
        4002846034504 ...enter the EAN
        --big / --small  ...sets the width of the code 

    EXAMPLE:
    $python3 save_barcode.py 4002846034504 --small

The EAN must be 8 or 13 figures long.

Note: the generator will create a barcode from any 8 or 13 figures long number.
However barcodes are designed in a way that the last digit is a check digit.
It is derived from the other digits. The Programm will not validate if this digit is the correct check digit.

So a random EAN might be converted to a barcode but will not be read correctly by a scanner.
