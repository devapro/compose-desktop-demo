### Compose desktop demo

This is simple demo of how to build compose desktop app (and any other java app) for different OS by using docker

#### Structure
```
|- main project
  |- docker
    |- deb_amd - config for build deb package for x86
    |- deb_arm - config for build deb package for ARM
    |- rmp - config for build rpm package
```

### GitHub actions

./github/workflows/release.yml - an example of building deb package