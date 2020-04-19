# Generate Protocol Buffer Code

## Java

```sh
// generate from 1 proto file
protoc -I=proto --java_out=java proto/simple.proto

// generate from all proto file
protoc -I=proto --java_out=java proto/*.proto
```

## Python

```sh
protoc -I=proto --python_out=python proto/simple.proto
```

## Go

```sh
protoc -I=proto --go_out=go proto/simple.proto
```
