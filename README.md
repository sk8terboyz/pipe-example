## Pipe Example

This is code from a class I took a couple years ago where all code was developed on Linux servers.

This program was created to fulfill homework/classroom requirements, not professional development.

Old README/Explanation:

Shane Kennedy

The pipe() system call is used to allocate part of the main memory to be treated
as a virtual file. With this file, such as a pipe, there are two ends. One end
of the pipe is used for writing, while the other end is used for reading. Without
writing to the pipe, a read call will be suspended until something is written.
The write() system call is used to write to a file using a buffer. The parameters
for write() are the file descriptor, the buffer, the size of the characters that
you are trying to write, and an optional offset to tell the function where to
start writing from.
