# OSSP Practicals

Operating Systems and System Programming practical programs.

## Practical 1
Linux command execution using:
- fork()
- execvp()
- wait()

## Practical 2
File copying using:
- open()
- read()
- write()
- close()

## Practical 3
Process creation and process states using:
- fork()
- getpid()
- getppid()
- sleep()
- wait()

## Practical 4
Process synchronization using:
- wait()
- waitpid()

Also demonstrates:
- Zombie processes
- Process reaping

## Practical 5

### Producer-Consumer
Uses:
- pipe()
- fork()
- read()
- write()
- clock_gettime()

### Pipeline
Implements:

ls -l | grep ".c"

Using:
- fork()
- pipe()
- dup2()
- execlp()
- waitpid()

## Technologies

- C
- Linux
- GCC
- Git
- GitHub
- System Calls
- Processes
- Pipes
## Practical 6: Inter-Process Communication Using FIFO

- Demonstrate communication between processes using Named Pipes (FIFO).
- Implement a FIFO client and server.
- Source files:
  - `src/prog6_fifo_client.c`
  - `src/prog6_fifo_server.c`

## Practical 7: Linux Process Memory Layout

- Demonstrate the Linux process memory address space.
- Inspect process memory mappings using `/proc/<PID>/maps`.
- Source files:
  - `src/prog7_linuxaddr.c`
  - `src/memory_demo.c`

## Practical 8: Dynamic Memory Allocation and Memory Leak Detection

- Demonstrate dynamic memory allocation using:
  - `malloc()`
  - `calloc()`
  - `realloc()`
  - `free()`
- Source file:
  - `src/dynamic_memory.c`
- Valgrind/Memcheck can be used for memory leak detection when available.

## Practical 9: File Copy Using Linux I/O and Standard Library I/O

- Implement file copying using low-level Linux I/O functions:
  - `open()`
  - `read()`
  - `write()`
  - `lseek()`
  - `close()`
- Implement file copying using C standard library functions:
  - `fopen()`
  - `fread()`
  - `fwrite()`
  - `fclose()`
- Demonstrate I/O redirection using `dup2()`.
- Source files:
  - `src/copy_lowlevel.c`
  - `src/copy_stdio.c`
  - `src/redirect_output.c`
  - `src/redirect_input.c`
