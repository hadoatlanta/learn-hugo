---
title: "hugo mod"
slug: hugo_mod
url: /commands/hugo_mod/
---
## hugo mod

Manage modules

### Synopsis

Various helpers to help manage the modules in your project's dependency graph.
Most operations here requires a Go version installed on your system (>= Go 1.12) and the relevant VCS client (typically Git).
This is not needed if you only operate on modules inside /themes or if you have vendored them via "hugo mod vendor".


Note that Hugo will always start out by resolving the components defined in the site
configuration, provided by a _vendor directory (if no --ignoreVendorPaths flag provided),
Go Modules, or a folder inside the themes directory, in that order.

See https://gohugo.io/hugo-modules/ for more information.



### Options

```
  -h, --help   help for mod
```

### Options inherited from parent commands

```
      --clock string               set the clock used by Hugo, e.g. --clock 2021-11-06T22:30:00.00+09:00
      --config string              config file (default is hugo.yaml|json|toml)
      --configDir string           config dir (default "config")
  -d, --destination string         filesystem path to write files to
  -e, --environment string         build environment
      --ignoreVendorPaths string   ignores any _vendor for module paths matching the given Glob pattern
      --logLevel string            log level (debug|info|warn|error)
      --noBuildLock                don't create .hugo_build.lock file
      --quiet                      build in quiet mode
  -M, --renderToMemory             render to memory (mostly useful when running the server)
  -s, --source string              filesystem path to read files relative from
      --themesDir string           filesystem path to themes directory
```

### SEE ALSO

* [hugo](/commands/hugo.md)	 - Build your site
* [hugo mod clean](/commands/hugo_mod_clean.md)	 - Delete the Hugo Module cache for the current project
* [hugo mod get](/commands/hugo_mod_get.md)	 - Resolves dependencies in your current Hugo project
* [hugo mod graph](/commands/hugo_mod_graph.md)	 - Print a module dependency graph
* [hugo mod init](/commands/hugo_mod_init.md)	 - Initialize this project as a Hugo Module
* [hugo mod npm](/commands/hugo_mod_npm.md)	 - Various npm helpers
* [hugo mod tidy](/commands/hugo_mod_tidy.md)	 - Remove unused entries in go.mod and go.sum
* [hugo mod vendor](/commands/hugo_mod_vendor.md)	 - Vendor all module dependencies into the _vendor directory
* [hugo mod verify](/commands/hugo_mod_verify.md)	 - Verify dependencies

