# Tips_Tricks

# Depending on Installation
export GOROOT=/usr/local/opt/go/libexec
export GOPATH=$HOME/go
export GOBIN=$GOPATH/bin
export PATH=$PATH:$GOPATH
export PATH=$PATH:$GOROOT/bin

# Connect postgres to database
psql -h localhost -p 5432 -U postgres
