# crowja.github.io

## Ongoing projects

### C scraps

Sometimes it feels like overkill to depend on an external library when all one
needs is a tiny fraction of what it provides. **C scraps** reflects the
[minimalist C library philosophy](https://nullprogram.com/blog/2018/06/10/),
particularly the ideas of providing functionality with a minimum of overhead and
API complexity. Basic ideas:

*   Each scrap provides clear, limited functionality. A benefit of this is that
    the scrap's codebase potentially stabilize very quickly.
*   Each is plain old standard C.
*   Drop its .c and .h files into your project and that's it. No formal
    libraries are built.
*   When it makes sense, the scrap is object-oriented and thread-safe. Objects
    are represented by opaque structs.

See [C scraps](C-scraps.md) for more info. The Github repos for each contain
makefiles, build and test rigs, examples, etc., but you don't need any of
it to use a scrap.

### Acca

### Fqutils

