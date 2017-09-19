ccminer (will be ccminer-dll and ccminer-service)
=======

Based on [tpruvot](https://github.com/tpruvot)'s CUDA project.

Check the [README.txt](README.txt) for the additions

BTC donation address: 1HWvaezh5AynL4AgkEscAfmgUoPL8Hsf8k (VassilSanych)

A part of the recent algos were originally written by [djm34](https://github.com/djm34) and [alexis78](https://github.com/alexis78)

This variant was tested and built on Windows 10 x64 and CUDA SDK 9.0 RC.

About source code dependencies
------------------------------

This project requires some libraries to be built :

- pthreads (prebuilt for win)

and loads others from Nuget:

- OpenSSL 1.0.2 (don't update. OpenSSL 1.1 changed BIGNUM)
- Curl 7.51 (winssl version)

For the first build in VS 2017:
- don't update tools to 141
- switch Release/x64
- run 
	Update-Package –reinstall
	in the Nuget Package Manager Console