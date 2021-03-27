# mkl

mkl-for-nelson
Intel oneAPI v2021 compatibility

# blas lapack wrapper

Windows 64 bits

```
nmake libintel64 export=nelson_blas_lapack name=libnlsblaslapack
```

Windows 32 bits

```
nmake libia32 export=nelson_blas_lapack name=libnlsblaslapack
```

# FFTW wrapper

Windows 64 bits

```
nmake libintel64 compiler=msvs INSTALL_LIBNAME=fftw3-static-x64.lib
```

Windows 32 bits

```
nmake libia32 compiler=msvs INSTALL_LIBNAME=fftw3-static-x86.lib
```

# VML wrapper

Windows 64 bits

```
nmake libintel64 export=nlsvml_mkl_list name=libnlsvml_mkl
```

Windows 32 bits

```
nmake libia32 export=nlsvml_mkl_list name=libnlsvml_mkl
```
