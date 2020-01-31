# LeaderF-filer

This Plugin use [LeaderF](https://github.com/Yggdroot/LeaderF) to navigate the files in directory.
Inspired by [vim-clap's filer provider](https://github.com/liuchengxu/vim-clap/pull/272), [helm's find-files](https://github.com/emacs-helm/helm).

## Usage

```
:LeaderfFiler
```
or
```
:Leaderf filer
```

## Mappings

INSERT MODE:

| Key     | Action                                                  |
|---------|---------------------------------------------------------|
| `<C-h>` | Show files in parent directory                          |
| `<C-l>` | Show files in directory under cursor                    |
| `<C-f>` | Toggle show hidden files                                |
| `<C-g>` | Show files of directory where `g:Lf_RootMarkers` exists |
| `~/`    | Show files in home directory                            |

NORMAL MODE:

| Key           | Action                                           |
|---------------|--------------------------------------------------|
| `<C-h>` / `h` | Show files in parent directory                   |
| `<C-l>` / `l` | Show files in directory under cursor             |
| `I`           | Toggle show hidden files                         |
| `<C-g>`       | Show files of directory where root marker exists |
| `I`           | Toggle show hidden files                         |
