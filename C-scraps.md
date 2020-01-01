# C scraps

Code that reflects a [minimalist C library
philosophy](https://nullprogram.com/blog/2018/06/10/), particularly the ideas of
providing functionality with a minimum of overhead and API complexity. Basic
ideas:

*   Each scrap provides clear, limited functionality.
*   As a result a scrap's codebase potentially stabilizes very quickly.
*   Each is plain old standard C.
*   Drop its .c and .h files into your project and that's it. No formal
    libraries are built. The Github repos for each contain makefiles, build and
    test rigs, examples, etc., but you don't need any of it to use a scrap.
*   When it makes sense, the scrap is object-oriented and thread-safe. Objects
    are represented by opaque structs.

## General purpose

*   [cbuf](https://github.com/crowja/cbuf). Provides getc and ungetc on a
    character string. Nothing auspicious, simply handy.
*   [cstrm](https://github.com/crowja/cstrm). Provide something like a character
    stream based on a string.
*   [hashtab](https://github.com/crowja/hashtab). Provides a hash table.
*   [linereader](https://github.com/crowja/linereader). Read a file or stream
    line by line.
*   [linewrapper](https://github.com/crowja/linewrapper). Very simple text
    wrapping.
*   [pqueue](https://github.com/crowja/pqueue). A priority queue ADT.
*   [sbuf](https://github.com/crowja/sbuf). A simple string buffer.
*   [shuffle](https://github.com/crowja/shuffle). Shuffle a general array.
*   [stringer](https://github.com/crowja/stringer). Build a list of strings with
    attention to minimizing allocation of new memory.
*   [tokenset](https://github.com/crowja/tokenset). Map tokens/strings to
    integer ids and back again.
*   [varstr](https://github.com/crowja/varstr). A variable length string.

## Computational biology, bioinformatics

*   [fareader](https://github.com/crowja/fareader). Read a file or stream of
    sequences in FASTA format.
*   [fqreader](https://github.com/crowja/fqreader). Read a file or stream of
    sequences in FASTQ format.
*   [nsequtils](https://github.com/crowja/nsequtils). Utilities for working with
    nucleotide sequence data.
