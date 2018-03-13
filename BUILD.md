Build
=====
How to build on Mac

### setup go

`brew install go`
then follow: http://www.golangbootcamp.com/book/get_setup
i.e., 
```bash
export GOPATH=$HOME/go
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOPATH/bin
```

### Build
```bash
make deps
make
make dist
make release
```

