<p align="center">
  <img width="100" src="./tx.svg" />
  <a href="https://lencx.github.io/nx">
  </a>
</p>

```bash
# create package
yarn nx <package_name>

# nx command
yarn nx [-bdirwhV] <package_name>
# -b   build
# -d   delete
# -i   install
# -r   remove build directory
# -w   watch current package
# -h   help
# -V   version

# ---------------------------

# lerna publish
yarn release

# clear build
yarn clean # package/{lib,esm} & storybook-static

# install package dependencies
yarn bootstrap
```

## Packages

* @l8n/fs - file handling
