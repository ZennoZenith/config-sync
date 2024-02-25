## Environment variables

```toml
['$HOME']
linux.default = '$HOME'
windows.default = '%USERPROFILE%'
```

Use case

```toml
copyTo = ['$AppData/helix']
```

By default `copyTo` value will be start with `$HOME` if '/' is not the starting character in file value. 

Any value starting from '$' inside `copyTo` will be considered as environment variable if not escaped with '\\'


## Symbolic

default = true
