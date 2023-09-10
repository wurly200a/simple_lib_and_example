# simple_lib_and_example
Project that creates a simple library and example program

## Clone

```
git clone https://github.com/wurly200a/simple_lib_and_example.git
```

## Enter the build environment with Docker

```
cd simple_lib_and_example
docker run --rm -it -v ${PWD}:/home/builder/test_proj -w /home/builder/test_proj wurly/builder_linux
```

## cmake

```
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
```

## make

```
(cd build)
make math_functions
make example_main
```

## Execute

```
(cd build)
./example/example_main
```
