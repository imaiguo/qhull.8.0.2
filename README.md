

# QHULL


## Build with MSVC

### Release build
```bash
> cmd
> "C:\Program Files\Microsoft Visual Studio\2022\Community\VC\Auxiliary\Build\vcvars64.bat"
> cmake -B build -G Ninja  -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\QHULL.8.0.2
> ninja -C build & ninja -C build install
```

### Debug build
```bash
> cmake -B build -G Ninja  -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=D:\devtools\QHULL.8.0.2
```

## Build with Mingw6

```bash
> mingw64qt
> cmake .. -G Ninja  -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\QHULL.8.0.2
> ninja & ninja install
```
