## librtlsdr VS2019

Visual Studio 2019 solution to build ExtIO_RTL, librtlsdr, libusb and pthreads4w.

### Obtaining the sources

* [**ExtIO_RTL**](https://github.com/jorgem-seq/ExtIO_RTL/archive/master.zip)
* [**librtlsdr**](https://github.com/jorgem-seq/librtlsdr/archive/local.zip)
* [**libusb v1.0.23**](https://github.com/libusb/libusb/archive/v1.0.23.zip)
* [**pthreads4w v2.11.0**](https://sourceforge.net/projects/pthreads4w/files/pthreads4w-code-v2.11.0.zip/download)

### Preparing the directory structure

Extract files and organize directories according to this:

```
.
├── ExtIO_RTL
├── librtlsdr_vs2019
│   └── README.md (This file)
├── librtlsdr
├── libusb
└── pthreads4w
```

### Solution Files

* build.sln
* build_avx2.sln (AVX2 binaries, Visual Studio 2019 16.4.4+ needed)
