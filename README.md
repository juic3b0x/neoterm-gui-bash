# NeoTerm:GUI Bash
Bash library for NeoTerm:GUI.

[Documentation](Manual.md)

[Tutorial](TUTORIAL.md)

### Installing

#### With `pkg`

Use `pkg install neoterm-gui-bash` to install.

#### From Source

Additional dependency: CMake

````bash
git clone https://github.com/tareksander/neoterm-gui-bash.git
cd neoterm-gui-bash
cmake . -DCMAKE_INSTALL_PREFIX=$PREFIX
make install
````

### Dependencies

Only need to be installed manually when building from source.

- [jq](https://github.com/stedolan/jq)
- Bash (should be installed by default in NeoTerm)

### License

The license is the [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/).  
TL;DR: You can use this library in your own projects, regardless of the license you choose for it. Modifications to this
library have to be published under the MPL 2.0 (or a GNU license in some cases) though.

