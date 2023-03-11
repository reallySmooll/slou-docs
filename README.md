# slou-docs
Documentation for slou.

`slou-docs` gets its documentation from [Doxygen](https://www.doxygen.nl).

## Documentation types
`slou` currently has 2 types of documentation:

- HTML
- man

## Generating documentation
To generate the documentation you need to first clone the `slou` project repository and the `slou-docs` repository. After you've cloned it, you need to:

```bash
$ cd slou/
$ doxygen
$ cp -r docs/ ../slou-docs/
```

After that you can commit changes and make a pull request.
