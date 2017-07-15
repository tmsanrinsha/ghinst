最新の実行ファイルをGitHubのreleaseページから取得するシェルスクリプト。

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
  ghinst [(-h|--help)] [(-d|--install-dir) dir] repository
Options:
  -h, --help        Displays this information
  -d, --install-dir Install directory (abusolute or relative path) (Default: $HOME/bin)
  -v, --verbose     Verbose
```

Example
-------

```bash
$ ghinst peco/peco
$ ghinst mattn/jvgrep -d ~/local/bin
$ ghinst https://<GHE_HOSTNAME>/foo/bar
```
