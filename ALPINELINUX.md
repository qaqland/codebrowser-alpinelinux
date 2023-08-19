Search "CMake build" needs in <https://pkgs.alpinelinux.org/contents>.

```
~ $ ldd codebrowser_generator
        /lib/ld-musl-x86_64.so.1 (0x7f70d80ef000)
        libclang-cpp.so.15 => /usr/lib/llvm15/lib/libclang-cpp.so.15 (0x7f70d4200000)
        libLLVM-15.so => /usr/lib/llvm15/lib/libLLVM-15.so (0x7f70cc400000)
        libstdc++.so.6 => /usr/lib/libstdc++.so.6 (0x7f70cc000000)
        libc.musl-x86_64.so.1 => /lib/ld-musl-x86_64.so.1 (0x7f70d80ef000)
        libgcc_s.so.1 => /usr/lib/libgcc_s.so.1 (0x7f70d80d1000)
        libffi.so.8 => /usr/lib/libffi.so.8 (0x7f70d80c7000)
        libz.so.1 => /lib/libz.so.1 (0x7f70d79e6000)
        libzstd.so.1 => /usr/lib/libzstd.so.1 (0x7f70cc34b000)
        libxml2.so.2 => /usr/lib/libxml2.so.2 (0x7f70cbeed000)
        liblzma.so.5 => /usr/lib/liblzma.so.5 (0x7f70d79af000)
~ $ ldd codebrowser_indexgenerator
        /lib/ld-musl-x86_64.so.1 (0x7f5042c1d000)
        libstdc++.so.6 => /usr/lib/libstdc++.so.6 (0x7f5042800000)
        libgcc_s.so.1 => /usr/lib/libgcc_s.so.1 (0x7f5042bef000)
        libc.musl-x86_64.so.1 => /lib/ld-musl-x86_64.so.1 (0x7f5042c1d000)
```
