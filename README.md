Install
=======

```bash
$ curl -L 'https://raw.githubusercontent.com/tmsanrinsha/ghinst/master/ghinst' > ~/bin/ghinst
$ chmod a+x ~/bin/ghinst
```

Usage
=====

```
Usage:
  ghinst [(-h|--help)] [(-d|--install-dir) dir] [--url url] repository
Options:
  -h, --help        Displays this information
  -d, --install-dir Install directory (abusolute or relative path) (Default: $HOME/bin)
      --url         GitHub URL (Default: https://github.com)
```

Example
-------

```bash
$ ghinst peco/peco
$ ghinst mattn/jvgrep -d ~/local/bin
$ ghinst --url https://<GHE_URL> foo/bar
```
