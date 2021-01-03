# WAX-CDT (Contract Development Toolkit)
## Update Docker image to: CDT v1.7
WAX-CDT is a toolchain for WebAssembly (WASM) and set of tools to facilitate contract writing for the WAX platform. The Docker version is outdated. If you need to compile smart contracts with version 1.7 you can easily upgrade your version 1.6 to 1.7.

### Uninstall WAX-CDT 1.6
There is no pre-compiled version of the package so manual uninstallation is required. Download uninstaller and run it with sudo.

```sh
$ wget https://github.com/worldwide-asset-exchange/wax-cdt/blob/master/uninstall.sh
$ sudo ./uninstall.sh
```

### Install EOSIO-CDT 1.7
Download packages from EOSIO github and install them.

```sh
$ wget https://github.com/eosio/eosio.cdt/releases/download/v1.7.0/eosio.cdt_1.7.0-1-ubuntu-18.04_amd64.deb
$ sudo apt install ./eosio.cdt_1.7.0-1-ubuntu-18.04_amd64.deb
```

### Resources
- [EOSIO-CDT Github](https://github.com/EOSIO/eosio.cdt)
- [WAX-CDT Docker](https://hub.docker.com/r/waxteam/cdt/tags?page=1&ordering=last_updated)
- [WAX-CDT](https://github.com/worldwide-asset-exchange/wax-cdt)

### License
[MIT](https://github.com/worldwide-asset-exchange/wax-blockchain/blob/master/LICENSE)

