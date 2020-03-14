# jpgshrink

Losslessly optimize JPEG files and report stats, while preserving the embedded color profile.

## Dependencies

- `jpegtran` for losslessly optimizing JPEG files (mozjpeg version is better)
- `exiftool` for copying ICC color profile
- GNU `parallel` for parallel processing

## Usage

```
Usage:
    jpgshrink [options] -- files ...

Options:
    -h, --help:
        display this help

    -s, --silent:
        don't print progress to stderr

    -r, --raw-output:
        produce a single output line with the number of bytes saved

    -p, --parallel:
        run parallelized via GNU parallel
```
