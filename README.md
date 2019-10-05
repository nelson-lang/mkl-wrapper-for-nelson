# mkl
mkl-for-nelson


# blas lapack wrapper

Windows 64 bits
```
nmake libintel64 export=user_example_list name=libnlsblaslapack
```

Windows 32 bits
```
nmake libia32 export=user_example_list name=libnlsblaslapack
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