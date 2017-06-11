[![Build Status](https://travis-ci.org/bartw/dotnetcore_node_travis.svg?branch=master)](https://travis-ci.org/bartw/dotnetcore_node_travis)

# dotnetcore_node_travis

## Description

Running tests for dotnet and a specific version of node together in one Travis build

## Blog post

https://medium.com/@bartwijnants/running-tests-for-net-and-node-js-on-travis-ci-8704ea3a5512

## Run tests local

```shell
dotnet restore
npm install
dotnet test
npm test
```

## Tests

You can play with the tests in DotNetTest.cs and node.test.js to see the build failing and succeeding on Travis.

## Creating this project

```shell
dotnet new xunit
dotnet restore
npm init
npm install --save-dev jest
```