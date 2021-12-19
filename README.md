# NAME

rmkeep - Keep a number files matching a certain pattern and remove the rest.


# SYNOPSIS

**rmkeep** [ **-p** _path_ ] [ **-k** _num_ ] [ **-r** ] [ **-n** ] [ **-q** ] [ _REGEX_ ]


# DESCRIPTION

This command will keep a certain number of files matching the regular expression _REGEX_ and remove the rest.  If no specific _path_ is defined, the current working directory will be searched.  If no regular expression _REGEX_ is submitted, all files will be matched.


# OPTIONS

**-p** _path_
: change working directory.

**-k** _num_
: change number of files to keep (default: 0, i.e. all files will be kept).

**-r**
: reverse sort order.

**-n**
: perform dry run only.

**-q**
: be quiet.

**-h**
: show this help message.


# INSTALLATION

Clone the remote repository and change into the local repository:

```bash
$ git clone https://github.com/mboljen/rmkeep
$ cd rmkeep
```

Use the following command to install this software:

```bash
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to successfully complete the installation, you need to have write permissions for the installation location.


# CONTRIBUTION

Pull requests are welcome.  For major changes, please open an issue first to discuss what you would like to change.

Submit bug reports online at: <https://github.com/mboljen/rmkeep/issues>

Please make sure to update tests as appropriate.


# SEE ALSO

Full documentation and sources at: <https://github.com/mboljen/rmkeep>


# LICENSE

[MIT](https://choosealicense.com/licenses/mit/)
