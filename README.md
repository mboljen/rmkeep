# rmkeep

This bash script keeps a number files matching a certain pattern and removes the rest.

## Installation

Use the following command to install this software:

```bash
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to succesfully complete the installation, you need to have write permissions for the installation location.

## Usage

The following command will keep `number` files matching the pattern `REGEX` and remove the rest.

```bash
$ rmkeep [-p path] [-k number] [-r] [-n] [-v] [-h] REGEX
```

### Options

+ `-p` Change working directory
+ `-k` Files to keep (default: `0` = all)
+ `-r` Reverse sort
+ `-n` Dry run
+ `-v` Verbose output
+ `-h` Show this help message

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
