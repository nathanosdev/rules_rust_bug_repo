Fetch packages

```shell
bazel run //3rdparty:crates_vendor -- --repin
```

Build binary

```shell
CARGO_BAZEL_REPIN=true bazel build //demo:hello_world --verbose_failures --sandbox_debug
```
