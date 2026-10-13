# scQOI compressor
scQOI (Single-Channel Quite OK Image) the first compression algorithm from the KQI Hub. It is used by the MQIF format and has acceptable compression ratios for repetitive data such as uncompressed grayscale images. scQOI is based off of the Quite OK Image format.

```
SCQ_OP_RUN (Code 00) - Declares a run of repeated bytes
SCQ_OP_DIFF (Code 01) - Declares a difference between the last byte the byte succeeding it
SCQ_OP_INDEX (Code 10) - Declares a repeat of a previously cached byte
SCQ_OP_BYTE (Code 11) - Declares a byte literal
```
