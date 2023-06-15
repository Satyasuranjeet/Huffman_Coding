# Huffman_Coding
# Text Compression using Huffman Coding

This project implements a text compression algorithm using Huffman coding. Huffman coding is a lossless data compression technique that assigns variable-length codes to characters based on their frequencies. This algorithm effectively reduces the size of text data by representing frequently occurring characters with shorter codes.

## Features

- Compresses text data using Huffman coding
- Supports compression of individual files
- Decompresses the compressed data back to its original form
- Provides efficient storage and retrieval of compressed files

## Usage

To compress a file:

```python
huffman = HuffmanCoding()
huffman.compress_file('input.txt', 'compressed.bin')
