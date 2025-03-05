# mkl

mkl-for-nelson
Intel oneAPI v2022 compatibility (x64 only since 2025)

# blas lapack wrapper

```
nmake libintel64 export=nelson_blas_lapack name=libnlsblaslapack install_dir=d:/x64 
```

# FFTW wrapper

Windows 64 bits

```
nmake libintel64 compiler=msvs INSTALL_LIBNAME=fftw3-static-x64.lib install_dir=d:/x64
```

# VML wrapper

Windows 64 bits

```
nmake libintel64 export=nlsvml_mkl_list name=libnlsvml_mkl
```
