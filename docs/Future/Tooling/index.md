### Code Overhaul

While all current CLI tools are written in C, I seek to re-implement them in Go.<br/>
For the time being, I'm using re-existing C code as a library to achieve this.<br/>
Eventually, I hope to remove these C FFI shims, completely re-implementing
SCUMM in Go.

I also plan to complement the CLI tool suite with a distinct set of GUI tools.<br/>
These will be implemented in modern HTML5, using [Astilectron](https://github.com/asticode/go-astilectron)
and WASM for lower level access.
