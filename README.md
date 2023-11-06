# LinuxOperatingSystem

Note: Repos within this project/list contain code that cannot be made public. If you would like to see this code please contact me.

Kernel Programming for various OS components in C++
- Wrote Linux Round-robin CPU scheduler and compared performance to CFS as well as MuQSS (BFS) scheduler
- Wrote Multi-threaded, multi-process web server with interprocess communication that listens through multiple sockets
- Added syscalls to Linux kernel, Eg. 1) Print metadata of the file descriptor table of a specified process that works in x86 and arm64 architectures 2) Manually performs a 5-level page walk to read/write memory of a specified process
- Created an in-kernel key-value store with SLAB allocator with read-write spinlocks embedded in each bucket of the KKV array
- Implemented a filesystem driver that mounts disks, and reads/writes files and directories
