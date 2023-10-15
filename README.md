pw# first_golang
Learning go long by making projects
## About Go
Go is a strong and statically typed language  <br />
Strong: all the variables cannot change types <br />
Statically typed: all the variables are decalred before complile time
### Go Features
* Simple
* Fast Compile Times
* Garbage Collected
* Built in Concurrency
* Compiled to standalone libraries: if we deploy the application, all the dependencies will be present

# PKG's
Package Main -- every package in go has to specify which package it is part of. Main is the entry point <br />
import "fmt" allow us to format strings<br />
main function is going to be the entry point of the application. 

## Go Root
Go Root is the location where you go SDK is located. The version of the Go you're using will be present here
## Go Path
GOPATH is a variable that defines the root of your workspace. Without this, we won't be able to execute the go program. <br />
The first go path is the location where the third party libraries are going to be stored but when you want to find your source code all the go paths will be searched for. <br />
Set Multiple go paths when you have multiple work spaces. 
### GOPATH is the root of your workspace and contains the following folders: <br />

* src/: location of Go source code (for example, .go, .c, .g, .s).

* pkg/: location of compiled package code (for example, .a).

* bin/: location of compiled executable programs built by Go

### Configuring GOPATH for different scopes﻿
You can configure GOPATH for the following scopes:

* Global GOPATH: settings apply to all projects of a specific installation of GoLand.

* Project GOPATH: settings apply only to the current project.

* Module GOPATH: settings apply only to one module. A module can have an SDK that is different from those configured for a project. They can also carry a specific technology or a framework.






