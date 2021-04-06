WAZNRig
======================

[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](https://opensource.org/licenses/GPL-3.0)

WAZNRig is a 0% high performance Wazn (RandomX) CPU/GPU miner supporting RandomX, KawPow, CryptoNight, AstroBWT and many more algorithms. Binaries are available for Windows and Linux.

#### Table of contents
* [Mining backends](#mining-backends)
* [Download](#download)
* [Usage](#usage)
* [License](#license)

## Mining backends
- **CPU** (x64/ARMv8)
- **OpenCL** for AMD GPUs.

## Download
* Binary releases: https://github.com/project-wazn/wazn-rig/releases
* Git tree: https://github.com/project-wazn/wazn-rig.git

## Usage
The preferred way to configure the miner is the [JSON config file](https://xmrig.com/docs/miner/config) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing [API](https://xmrig.com/docs/miner/api) calls.

## License
```
Licensed under the GPL-3.0
Copyright (c) 2019-2021 Wazn Project
Copyright (c) 2017-2021 xmrig
```
