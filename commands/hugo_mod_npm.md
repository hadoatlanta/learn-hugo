---
title: "hugo mod npm"
slug: hugo_mod_npm
url: /commands/hugo_mod_npm/
---
## hugo mod npm

Various npm helpers

### Synopsis

Various npm (Node package manager) helpers.

```
hugo mod npm [command] [flags]
```

### Options

```
  -h, --help   help for npm
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

* [hugo mod](/commands/hugo_mod.md)	 - Manage modules
* [hugo mod npm pack](/commands/hugo_mod_npm_pack.md)	 - Experimental: Prepares and writes a composite package.json file for your project

