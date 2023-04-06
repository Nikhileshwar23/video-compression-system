# video-compression-system

# Data Compression using Python

This is a simple Python program for data compression.

## Introduction
The main algorithm used in the code is the video compression algorithm, which is achieved using the `compress_video()` and `compress_videos_from_dir()` methods of the `Video` class provided by the Katna package.

The video compression technique used in this code is not explicitly stated, but the Katna package documentation suggests that it uses a combination of different algorithms, including Huffman coding, Discrete Cosine Transform (DCT), and Motion Compensation. DCT is a popular algorithm used in video compression to transform image data from the spatial domain to the frequency domain, while Motion Compensation is used to reduce redundancy in consecutive frames by exploiting the similarity between them.

Note that the specific algorithms and techniques used by the Katna package are not explicitly stated in the code, and the package may use multiple algorithms in conjunction to achieve efficient video compression.

## Requirements

To run this program, you need the following:

- Python 3.11

## Instructions

1. Clone this repository using the following command:

    
    git clone https://github.com/Nikhileshwar23/video-compression-system
    

2. Go to the project directory:
   
    
    cd data-compression-python
    

3. Run the program:
    
    python example_video_compression.py
    

4. Follow the on-screen instructions to compress data.

## Usage

This program can be used to compress data such as videos(.mp4 files).

1. Compressing Data

To compress data, Run the python code. Enter the path of the file you want to compress in the example_video_compression.py code as an input, and the program will compress the data and save the file as pos_video.mp4 in the new folder as compressed_video.

## Contributing

If you find any bugs or have any suggestions for improving this program, feel free to open an issue or submit a pull request.
