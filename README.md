```
$ go run go.bytecodealliance.org/cmd/wit-bindgen-go generate -vv -w importsx -o bindings wit
...

error: wasm-tools: error: interface not found in package
     --> component.wit:35:21
      |
   35 | 	import wasi:clocks/timezone@0.2.1;
      |                     ^-------

exit status 1
