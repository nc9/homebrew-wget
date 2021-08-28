# Homebrew Wget

Version of `wget` (`v1.22.1`) patched to include an option to limit file size downloads with the `--limit-size` option.

Skips any HTTP or FTP download that is larger than a size, specified as a number in `M` (megabyte) or `k` (kilobyte) format.

```sh
$ wget --help | grep limit-size
       --limit-size=SIZE           limit download file size to SIZE.
```

This has been adapted from an old patch [published here](https://yurichev.com/wget.html) that was never applied to the upstream wget project.

## Install

```sh
$ brew tap nc9/wget
$ brew install nc9/wget/wget
```
