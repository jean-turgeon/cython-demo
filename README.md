# cython-demo

## Description

This is a small proof of concept on how to use cython within a python project.
The cython file (pyx) contain one function calculating the fibonacci sequence.
The main file import the compiled library and use the function.


## Repository content
```
.
├── LICENSE
├── main.py
├── README.md
├── setup.py
└── src
    └── fibonacci.pyx
```

## Compile and run
Dependencies needed are setuptools and cython

### Compile
```bash
python3 ./setup.py build_ext --inplace
```
### Run
```bash
python3 ./main.py
```

## Expected output
```bash
1 1 2 3 5 8 13 21 34 55 89 144 233 377 610 987 1597
```


