# go-containerregistry

[![Build Status](https://travis-ci.org/google/go-containerregistry.svg?branch=master)](https://travis-ci.org/google/go-containerregistry)
[![GoDoc](https://godoc.org/github.com/google/go-containerregistry?status.svg)](https://godoc.org/github.com/google/go-containerregistry)
[![Go Report Card](https://goreportcard.com/badge/google/go-containerregistry)](https://goreportcard.com/report/google/go-containerregistry)

## Introduction

This is a golang library for working with container registries. It's largely based on the [Python library of the same name](https://github.com/google/containerregistry), but more hip and uses GitHub as the source of truth.

## Tools

This repo hosts two tools built on top of the library.

### crane

[`crane`](cmd/crane/doc/crane.md) is a tool for interacting with remote images and registries.

### ko

[`ko`](cmd/ko/README.md) is a tool for building and deploying golang applications to kubernetes.
