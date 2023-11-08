# spanning
Utility to spread a large amount of data across many fixed-size data discs before burning

## Install
```sh
$ curl -O https://raw.githubusercontent.com/zlwu/spanning/main/spanning && chmod +x spanning
```

## Usage
```txt
Usage: ./spanning /path/to/source /path/to/target max_size_in_bytes
  An example for spanning BD-R 25GB disk: ./spanning ./source/dir ./target/dir 25000000000
```

## Reference
 - [Disc spanning](https://en.wikipedia.org/wiki/Disc_spanning)
