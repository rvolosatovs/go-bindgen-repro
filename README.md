```
$ go run go.bytecodealliance.org/cmd/wit-bindgen-go generate -vv -w imports -o bindings wit

Output dir: bindings
Package root: github.com/rvolosatovs/go-bindgen-repro/bindings
Generating Go for 10 world(s)
wasm-tools: error: failed to process feature gate for world [wasi-io-WORLD-imports-v021] in package [go:bindgen]

Caused by:
    0: package [go:bindgen] contains a feature gate with a version specifier, so it must have a version
wasm-tools: error: failed to process feature gate for world [wasi-io-WORLD-imports-INTERFACE-error-v021] in package [go:bindgen]

Caused by:
    0: package [go:bindgen] contains a feature gate with a version specifier, so it must have a version
Type:	wasi:io/error@0.2.1.error
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/error.Error
wasm-tools: error: failed to process feature gate for world [wasi-io-WORLD-imports-INTERFACE-poll-v021] in package [go:bindgen]

Caused by:
    0: package [go:bindgen] contains a feature gate with a version specifier, so it must have a version
Type:	wasi:io/poll@0.2.1.pollable
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/poll.Pollable
wasm-tools: error: failed to process feature gate for world [wasi-io-WORLD-imports-INTERFACE-streams-v021] in package [go:bindgen]

Caused by:
    0: package [go:bindgen] contains a feature gate with a version specifier, so it must have a version
Type:	wasi:io/streams@0.2.1.error
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams.Error
Type:	wasi:io/streams@0.2.1.pollable
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams.Pollable
Type:	wasi:io/streams@0.2.1.stream-error
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams.StreamError
Type:	wasi:io/streams@0.2.1.input-stream
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams.InputStream
Type:	wasi:io/streams@0.2.1.output-stream
	github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams.OutputStream
Generated 4 Go package(s)
Generated package: github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/error
	bindings/wasi/io/error/empty.s
	bindings/wasi/io/error/error.wit.go
	bindings/wasi/io/error/ioerror.wasm.go
Generated package: github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/imports
	bindings/wasi/io/imports/imports.wit.go
Generated package: github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/poll
	bindings/wasi/io/poll/empty.s
	bindings/wasi/io/poll/poll.wasm.go
	bindings/wasi/io/poll/poll.wit.go
Generated package: github.com/rvolosatovs/go-bindgen-repro/bindings/wasi/io/streams
	bindings/wasi/io/streams/empty.s
	bindings/wasi/io/streams/streams.wasm.go
	bindings/wasi/io/streams/streams.wit.go
```
