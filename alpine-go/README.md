Various container experiments containing shell scripts and compiled Go binaries.

Build and run Alpine x86-64 container with Go binary:
```
bazel run //sunflower:alpine_go

docker run -it bazel/sunflower:alpine_go

# Expected output: Hello Go 🌻🌻🌻
```
