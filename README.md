# AES_OpenCL
Simple AES implementation in OpenCL

This is a simple OpenCL 1.2 and 2.0 (SVM) implementations of the AES-256 algorithm.  The main_ocl12.c and kernel_ocl12.cl are for OpenCL 1.2 and use buffers to transfer the input data to the GPU.  The main_ocl20.c and kernel_ocl20.cl are for OpenCL 2.0 and use SVM to transfer the input data to the GPU.

When running the tool, the first argument must be either ‘a’ or ‘h’ which indicates whether the input file should be read as ASCII values or as hex data.  The second parameter is the input file, the third parameter is the keyfile, and finally the last parameter is the output file.

This code is licensed under the MIT license and may be used under the terms of the license.  Attribution is required.