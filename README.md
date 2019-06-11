# Hasher
Hasher is a program that returns one or more message digests for your files and strings!

## Getting Started
### Prerequisites
You will need Python3 and the pyfiglet library:
```
pip install pyfiglet
```
### Usage
```
usage: hasher [-h] [-a ALGORITHM] [-i INPUT] [-f FILE]

Returns the hash output(s) for a given input string.

optional arguments:
  -h, --help            show this help message and exit
  -a ALGORITHM, --algorithm ALGORITHM
                        Returns the hash output of the input string for the
                        specified hashing algorithm. Available options: md5,
                        sha1, sha256, sha512
  -i INPUT, --input INPUT
                        Specifies the string to be hashed.
  -f FILE, --file FILE  Specifies the file to be hashed.
  ```
  ### Examples
  ```
  ./hasher
  ```
  ```
  ./hasher -f hasher
  ```
  ```
  ./hasher -i "Test" -a md5
  ```
