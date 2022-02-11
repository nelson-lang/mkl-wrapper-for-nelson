# mkl

mkl-for-nelson
Intel oneAPI v2022 compatibility

# blas lapack wrapper

Windows 64 bits

```
nmake libintel64 export=nelson_blas_lapack name=libnlsblaslapack install_dir=d:/x64 
```

Windows 32 bits

```
nmake libia32 export=nelson_blas_lapack name=libnlsblaslapack install_dir=d:/x86  
```

# FFTW wrapper

Windows 64 bits

```
nmake libintel64 compiler=msvs INSTALL_LIBNAME=fftw3-static-x64.lib install_dir=d:/x64
```

Windows 32 bits

```
nmake libia32 compiler=msvs INSTALL_LIBNAME=fftw3-static-x86.lib  install_dir=d:/x86 
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
