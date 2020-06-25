# TextCompressor-DeCompressor

This project is mainly divided into 2 modules, i.e., first, creation of compressed file and the file that contain character and codes; Second, decompression of compressed file 
for getting actual content in human readable language. We’ll identify the distinct character present in the input file, make a tree based on the frequency of the characters.
Substitute the actual characters with their codes for the contents of the input file. Write the final code for the content in a binary file.

Each character takes 1 byte to store in memory, but if we use the code generated with the help of tree, instead of the actual character, it’s size will based on its frequency 
in the input file so number of bits will differ for each character, which will definitely result in a file, whose size will be lesser than the original file.

We will also maintain a file which will store the code and actual character, for each code used in the compressed file, with which we can decompress the compressed file 
whenever we want.
