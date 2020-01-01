# crowja.github.io

## Ongoing projects

### C scraps

Sometimes it's overkill to require an external library when all you really want
is a tiny fraction of it. **C scraps** reflects a [minimalist C library
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

See [the C scraps page](C-scraps.md) for more info.

### Acca

**Acca** is an experimental tool for creating hypotheses about causal relationships
between two categorical variables. Given a dataset (x0, y0), (x1, y1), ...,
where the x and y values are categorical, Acca will report candidate causal
relationships. See [the Acca page](https://github.com/crowja/acca) for more info
and a simple example.

### Fqutils

