deepCopy
========
[![GoDoc](https://godoc.org/github.com/mohae/deepcopy?status.svg)](https://godoc.org/github.com/mohae/deepcopy)[![Build Status](https://travis-ci.org/mohae/deepcopy.png)](https://travis-ci.org/mohae/deepcopy)

DeepCopy makes deep copies of things: unexported field values are not copied.

## Import

```shell
go get -u github.com/black-06/deepcopy-v2
```

## Usage

```go
cpy := deepcopy.Copy(orig)
```

## Features

* *NEW* [Generics](https://go.dev/doc/tutorial/generics) based implementation (
  requires [Go 1.18](https://go.dev/blog/go1.18beta1) or higher)