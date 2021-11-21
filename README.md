# install_cocoapods

Handles cocoapods installation and caching.

Example:

```xml
jobs:

  build:
    runs-on: macos-latest

    steps:
      - uses: actions/checkout@v2

      - uses: NiftyStack/install_cocoapods@1.0.0

      - run: pod install
``` 
