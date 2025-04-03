Overview
The File Zipper is a Python-based file compression tool that efficiently reduces file sizes using Huffman Encoding and LZ77 algorithms. It enhances storage efficiency and accelerates file transfers by eliminating redundant data, making it an ideal solution for file management and transmission.

Features
Compress and decompress files with high efficiency
Implements Huffman Encoding and LZ77 for lossless compression
Utilizes arrays, stacks, hash tables, and binary trees for optimized performance
Reduces storage requirements and speeds up file transfers

Installation
1. Clone the repository
git clone https://github.com/your-username/file-zipper.git
cd file-zipper

2. Install dependencies (if required)
pip install -r requirements.txt

3. Run the script
python file_zipper.py

Usage
To compress a file:
python file_zipper.py -c input.txt output.zip

To decompress a file:
python file_zipper.py -d output.zip decompressed.txt

How It Works

Huffman Encoding
Constructs a frequency table of characters.
Builds a Huffman Tree using a priority queue.
Assigns variable-length binary codes to characters based on frequency.
Encodes the input file using optimized binary codes.

LZ77 Compression
Uses a sliding window to find repeated sequences.
Replaces redundant data with (distance, length) references.
Effectively reduces file size while preserving original content.

Future Improvements
Integration of additional compression algorithms (e.g., LZW, Bzip2).
Development of a Graphical User Interface (GUI) for better usability.
Optimization for large-scale file compression.
