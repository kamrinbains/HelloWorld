[![Build C++](https://github.com/kamrinbains/HelloWorld/actions/workflows/main.yml/badge.svg)](https://github.com/kamrinbains/HelloWorld/actions/workflows/main.yml)

# Hello World

This program demonstrates printing `Hello World` to the command line in C++.

The project includes `test_runner.sh` to be compatible with [cpp-container](https://github.com/ChicoState/cpp-container)

## Using cpp-container

If you have built cpp-container image, you can run it with a volume mounted to the current source code:

```
docker run -v "$(pwd)":/usr/src -it cpp-container
```

...or run it interactively in a shell:

```
docker run -v "$(pwd)":/usr/src -it cpp-container sh
```
