# BarcodeGen
Creating a Barcode image file with Python

Insert an EAN code in the ean variable at the top.

It must be 8 or 13 figures long.

Note: the generator will create a barcode from any 8 or 13 figures long number. However barcodes are designed in a way that the last digit is a check digit.
It is derived from the other digits. The Programm will not validate if this digit is the correct check digit.

So a random ean might be converted to a barcode but will not be read correctly by a scanner.
