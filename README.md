BSD
===

This repository contains an attempt at translating the [BSD operating system][1] and related software to the [Go programming language][2].

Status
------

**Rough Translation Complete**

 - hammer/hammer.go
 - hammer/hammer_btree.go

**Translation Underway**

 - sys/vfs/hammer/hammer_vfsops.go
 - sys/vfs/hammer/hammer_vnops.go

Setup
-----

 1. [Install and configure Go][3]
 2. export GOPATH=$HOME/go
 3. go get -d github.com/varialus/bsd
 4. cd ~/go/src/github.com/varialus/bsd/
 5. go test ./...

[1]:http://en.wikipedia.org/wiki/Berkeley_Software_Distribution
[2]:http://en.wikipedia.org/wiki/Go_%28programming_language%29
[3]:http://golang.org/doc/install
