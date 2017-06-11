[![Build Status](https://travis-ci.org/bartw/dotnetcore_node_travis.svg?branch=master)](https://travis-ci.org/bartw/dotnetcore_node_travis)

# dotnetcore_node_travis

## Description

Running tests for dotnet and a specific version of node together in one Travis build

## Run tests local

```shell
dotnet restore
npm install
dotnet test
npm test
```