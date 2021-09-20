Test with

```
mkdir -p build && cd build
cmake -G Ninja ..
cd ..
ln -s build/compile_commands.json compile_commands.json
```

then use editor to test "go to definition" from `yoyo.h` to `yoyo.cpp`.
