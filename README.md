# Huffman-File-Compressor

- C++ programs which can compress and extract the file using Huffman Coding - A lossless data compression using variable length codes. It is the most efficient algorithm for data compression.
- The program encode.cpp needs the name of file as an argument. It will the compress the file using Huffman encoding algorithm and generate a new compressed file with .huf extension.
- The program decode.cpp needs the name of compressed file with extension .huf. Optionally you can also give a second argument specifying the name of the decoded output file.
- The compression ratios depend on the type of the input file.
- For small files(order of bytes) it is not recommended to compress, because of fractional compression ratio. The compressed file occupies more space than input file.
- In general, larger the input file sizes, better is the compression ratios. The compression ratios depend on the probabilities of source's data.

## Executing the program on a sample text file
![filecomp](https://user-images.githubusercontent.com/108319876/176507206-f0e7dd14-b6c4-46cf-9a76-c271d3977d56.png)
We can see that original file and file generated after decoding are same.
### Here are the file sizes of all the three files(input file, compressed file, output file).
<p float="left">
<img src=https://user-images.githubusercontent.com/108319876/176507233-fd9d84dd-ec06-47ba-a737-00f63cb14f22.png alt="imput file properties" width="300">
<img src=https://user-images.githubusercontent.com/108319876/176507253-6bb67732-3aeb-4236-b93c-fcaa9dc3d412.png alt="compressed file properties" width="300">
<img src=https://user-images.githubusercontent.com/108319876/176507273-df84e4a7-23d2-45f0-b433-cd6daf38998d.png alt="output file properties" width="300">
</p>
