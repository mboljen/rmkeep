# rmkeep

Keep a number files matching a certain pattern and remove the rest

## Synopsis

```console
$ rmkeep [OPTION]... [REGEX]
```

## Description

This script keeps a certain number of files matching the regular expression _REGEX_ and removes the rest.  If no specific _path_ is defined, the current working directory will be searched.  If no regular expression _REGEX_ is submitted, all files will be matched.

## Options

+ `-p` _path_

  Changes working directory

+ `-k` _num_

  Changes number of files to keep (default: 0, i.e. all files will be kept)

+ `-r`

  Reverses sort order

+ `-n`

  Performs dry run only

+ `-h`

  Shows this help message

## Installation

Clone the remote repository and change into the local repository:

```console
$ git clone https://github.com/mboljen/rmkeep
$ cd rmkeep
```

Use the following command to install this software:

```console
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to successfully complete the installation, you need to have write permissions for the installation location.

## Contribution

Pull requests are welcome.  For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
