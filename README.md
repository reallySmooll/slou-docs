# slou-docs
Documentation for slou.

`slou-docs` gets its documentation from [Doxygen](https://www.doxygen.nl).

## Documentation types
`slou` currently has 2 types of documentation:

- HTML
- man

## Generating documentation
```bash
$ git clone --recursive https://github.com/reallySmooll/slou.git
$ git clone https://github.com/reallySmooll/slou-docs.git
$ cd slou/
$ doxygen
$ cp -r docs/ ../slou-docs/
```

After that you can commit changes and make a pull request.
