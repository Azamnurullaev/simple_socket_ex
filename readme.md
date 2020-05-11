# SIMPLE C SOCKET CLIENT SERVER
# BUILT ON TOP OF C LANGUAGE
## How To Use

This simple program is using 16bit-length data transaction. You can edit the default length in `data_structure.h`

This program by default is using Clang, but able to check gcc if available and use when clang is missing.
```bash
git clone https://github.com/aviezab/simple_socket_ex
make
./server.elf 0.0.0.0 8080
./client.elf 127.0.0.1 8080
```

Tested on Arch Linux 64bit x86_64 using Clang 9.

### MIT LICENSE
### (C) 2020 Aviezab, Ammar Faizi