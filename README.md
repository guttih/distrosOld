# distros

Distros is a system to create a linux distribution.  The consists of collection
of console applications, QT application and bash & python3 scripts.

## Project directory structure overview


```
distros
├── code                            # Scrips and application
│   ├── config                      # System configuration files, system defaults and general user settings.
│   ├── documents                   # User data folder for distros he makes
│   ├── cpp                         # C++ console- and Qt applications and libraries
│   │   └── apps                    # Applications written in c++ including QT apps
│   │       └── configurer          # Console app used to configure the system
│   ├────── libs                    # C++ libraries written in c++
│   │       └── json                # Library to save and load data in a file on json format
│   ├────── tests                   # All tests for c++ applications and libraries
│   │       ├── apps                # Tests for applications written in c++
│   │       │   └── configurerTests # Tests for the configurer c++ console application
│   │       └───libs                # Test for C++ libraries
│   │           └── jsonTests       # Tests for the json library
│   └── scripts                     # Bash and python3 scripts
│       ├── bash                    # Bash scripts
│       ├── python                  # Python3 scripts
│       └── tests                   # All tests for bash and python3 scripts
│           ├── bash                # Tests for scripts written in bash
│           └── python              # Tests for scripts written in python3
├── docs                            # Documentation - User guide on how to use distros
│   └──development                  # Documentation - Development of the distros system
└── installation                    # System installers

```

## Directory links

### distros [README]

- [code] - Scrips and application
    - [config] System configuration files, system defaults and general user settings
    - [documents] - User data folder for distros he makes
    - [cpp] - C++ console- and Qt applications and libraries
       - [apps] - Applications written in c++ including QT apps
           - [configurer] - Console app used to configure the system
       - [libs] - C++ libraries written in c++
           - [json] -Library to save and load data in a file on json format
       - [tests] - All tests for c++ applications and libraries
           - [apps_] - Tests for applications written in c++
               - [configurerTests] Tests for the configurer c++ console application
           - [libs_] - Test for C++ libraries
               - [jsonTests] - Tests for the json library
    - [scripts] - Bash and python3 scripts
       - [bash] - Bash scripts
       - [python] - Python3 scripts
       - [tests_] - All tests for bash and python3 scripts
           - [bash_] - Tests for scripts written in bash
           - [python_] Tests for scripts written in python3
- [docs] - Documentation - User guide on how to use distros
    - [development] - Documentation - Development of the distros system
- [installation] - System installers

[README]: ./README.md
[code]: ./code/README.md
[config]: ./code/config/README.md
[documents]: ./code/documents/README.md
[cpp]: ./code/cpp/README.md
[apps]: ./code/cpp/apps/README.md
[configurer]: ./code/cpp/apps/configurer/README.md
[libs]: ./code/cpp/libs/README.md
[json]: ./code/cpp/libs/json/README.md
[tests]: ./code/cpp/tests/README.md
[apps_]: ./code/cpp/tests/apps/README.md
[configurerTests]: ./code/cpp/tests/apps/configurerTests/README.md
[libs_]: ./code/cpp/tests/libs/README.md
[jsonTests]: ./code/cpp/tests/libs/jsonTests/README.md
[scripts]: ./code/scripts/README.md
[bash]: ./code/scripts/bash/README.md
[python]: ./code/scripts/python/README.md
[tests_]: ./code/scripts/tests/README.md
[bash_]: ./code/scripts/tests/bash/README.md
[python_]: ./code/scripts/tests/python/README.md
[docs]: ./docs/README.md
[development]: ./docs/development/README.md
[installation]: ./installation/README.md
