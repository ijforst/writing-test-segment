# Using QR Codes

QR codes are a type of barcode that involves a machine-readable series of black squares on a white background. QR codes work by communicating **data modules**, or patterns of squares, to the scanner or camera you used to scan the QR code. These data modules can communicate four types of data: numeric, alphanumeric, binary, and Kanji. For more information about what different data types contain, see the **Glossary** section.

## Scanning QR Codes
When you scan a QR code, your smartphone or QR code scanner takes the following steps to return the stored information: 

1. The camera identifies the three large, distinct squares, called the **position identifiers**, located in the corner of the QR code. These position identifiers help your camera identify the bounds of the QR code.
2.  Once the camera identifies the location of the QR code, it scans the QR code in two column intervals, starting with the first four data modules located in the bottom right corner. These data modules, known as the **mode indicator**, indicate what type of data the QR code contains. <br/>
**NOTE:** For more information about what different data types contain, see the **Glossary** section.
3. After the camera scans the first four data modules and determines what type of data is communicated by the QR Code, it scans the next eight data modules directly above the mode indicator. These eight data modules are called the **character count indicator**, and communicate the number of characters the message in the QR code contains. 
4. Once a camera knows the type of data and how many characters are in the message, it continues to scan the QR code in two column intervals until it reaches the **end indicator**, located on the left side of the QR code.
5. After the end indicator, the QR code continues to an **error correction data module**. In this module, up to 30% of the QR code’s message is stored and compared to the message relayed to the camera. If the message scanned by the camera doesn’t match the stored message, the stored message is used in place of the portion scanned by the camera.
6. The message in the QR code is displayed on your screen.

**Result:** You've scanned a QR code.

<!-- the image in this directory would be here on the page, and would include more information (arrows, maybe?) indicating the direction a QR code travels. -->

## Glossary

**Alphanumeric**
: A data type containing numbers, uppercase letters, spaces, and special characters. 

**Binary**
: A data type that includes only the characters outlined in [ISO 8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1).

**Character count indicator**
: The module responsible for communicating the number of characters in a QR Code

**Data modules**
: The pattern of squares that communicate the information contained in a QR Code

**End module**
: An indicator that the message communicated in the QR code is complete

**Error correction data module**
: The module that holds a backup of up to 30% of the message in a QR Code

**Kanji**
: A data type comprised of Japanese characters outlined in the [Shift JIS](https://en.wikipedia.org/wiki/Shift_JIS) character set.  

**Numeric**
: One of four data types a QR code can read. Numeric data contains a unique sequence of the numbers 0-9. 
