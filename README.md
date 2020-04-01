# Office management.

of_manager is shell tool for control/operating Open Office.

Developed in bash code: 100%.

The README is used to introduce the tool and provide instructions on
how to install the tool, any machine dependencies it may have and any
other information that should be provided before the tool is installed.

[![GitHub issues open](https://img.shields.io/github/issues/vroncevic/of_manager.svg)](https://github.com/vroncevic/of_manager/issues)
 [![GitHub contributors](https://img.shields.io/github/contributors/vroncevic/of_manager.svg)](https://github.com/vroncevic/of_manager/graphs/contributors)

### INSTALLATION

Navigate to release [page](https://github.com/vroncevic/of_manager/releases) download and extract release archive.

To install modules type the following:

```
tar xvzf of_manager-x.y.z.tar.gz
cd of_manager-x.y.z
cp -R ~/sh_tool/bin/   /root/scripts/of_manager/ver.1.0/
cp -R ~/sh_tool/conf/  /root/scripts/of_manager/ver.1.0/
cp -R ~/sh_tool/log/   /root/scripts/of_manager/ver.1.0/
```

Or You can use docker to create image/container.

:sparkles:

### USAGE

```
# Create symlink for shell tool
ln -s /root/scripts/of_manager/ver.1.0/bin/of_manager.sh /root/bin/of_manager

# Setting PATH
export PATH=${PATH}:/root/bin/

# Control/operating Open Office
of_manager version
```

### DEPENDENCIES

This tool requires these other modules and libraries:

* sh_util https://github.com/vroncevic/sh_util

### SHELL TOOL STRUCTURE

of_manager is based on MOP.

Shell tool structure:
```
.
├── bin/
│   ├── of_manager.sh
│   └── of_operation.sh
├── conf/
│   ├── of_manager.cfg
│   └── of_manager_util.cfg
└── log/
    └── of_manager.log
```

### DOCS

[![Documentation Status](https://readthedocs.org/projects/of_manager/badge/?version=latest)](https://of_manager.readthedocs.io/projects/of_manager/en/latest/?badge=latest)

More documentation and info at:

* https://of_manager.readthedocs.io/en/latest/

:sparkles:

### COPYRIGHT AND LICENCE

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Copyright (C) 2018 by https://vroncevic.github.io/of_manager

This tool is free software; you can redistribute it and/or modify
it under the same terms as Bash itself, either Bash version 4.2.47 or,
at your option, any later version of Bash 4 you may have available.

:sparkles:

