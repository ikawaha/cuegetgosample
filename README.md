```
$ go version
go version go1.22.0 darwin/arm64
```
```
$ cue version
cue version v0.7.0

go version go1.21.5
      -buildmode exe
       -compiler gc
       -trimpath true
  DefaultGODEBUG panicnil=1
     CGO_ENABLED 1
          GOARCH arm64
            GOOS darwin
```

```
$ go get github.com/ikawaha/cuegetgosample && cue get go github.com/ikawaha/cuegetgosample
go: downloading github.com/ikawaha/cuegetgosample v0.0.0-20240209122316-7722e486d3de
go: added github.com/ikawaha/cuegetgosample v0.0.0-20240209122316-7722e486d3de
```
```
$ tree cue.mod/
cue.mod/
└── gen
    └── github.com
        └── ikawaha
            └── cuegetgosample
                └── sample_go_gen.cue
```
