ccminer (will be ccminer-dll and ccminer-service)
=======

Based on [tpruvot](https://github.com/tpruvot)'s CUDA project.

Check the [README.txt](README.txt) for the additions

BTC donation address: 1HWvaezh5AynL4AgkEscAfmgUoPL8Hsf8k (VassilSanych)

A part of the recent algos were originally written by [djm34](https://github.com/djm34) and [alexis78](https://github.com/alexis78)

This variant was tested and built on Windows 10 and CUDA Toolkit 9.0 RC.

About source code dependencies
------------------------------

This project requires some libraries to be built :

- pthreads (prebuilt for win)

and loads others from Nuget:

- OpenSSL (1.0.2)
- Curl (winssl version)
