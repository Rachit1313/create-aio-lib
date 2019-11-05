<!--
Copyright 2019 Adobe. All rights reserved.
This file is licensed to you under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License. You may obtain a copy
of the License at http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under
the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR REPRESENTATIONS
OF ANY KIND, either express or implied. See the License for the specific language
governing permissions and limitations under the License.
-->

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@adobe/create-aio-lib.svg)](https://npmjs.org/package/@adobe/create-aio-lib)
[![Downloads/week](https://img.shields.io/npm/dw/@adobe/create-aio-lib.svg)](https://npmjs.org/package/@adobe/create-aio-lib)
[![License](https://img.shields.io/npm/l/@adobe/create-aio-lib.svg)](https://github.com/adobe/create-aio-lib/blob/master/package.json)

@adobe/create-aio-lib
=====================

CLI tool to create AIO Libs

This uses [this template.](https://github.com/adobe/aio-lib-template)

# Usage (npm)

Make sure you have `npm` version `6.1.0` or greater:

`npm --version`

Then run:
```bash
mkdir <library_name>
cd <library_name>
npm init @adobe/aio-lib <library_name> <repo_name> [options]
```
where `<library_name>` is the name of your library

# Usage (cli)

```bash
npm install -g @adobe/create-aio-lib
create-aio-lib <library_name> <repo_name> [options]
```
where `<library_name>` is the name of your library
where `<repo_name>` is the scoped name of your repo

# Commands and flags
<pre>
Creates an AIO Lib

USAGE
  $ create-aio-lib LIBNAME REPONAME

ARGUMENTS
  LIBNAME   the name of the library
  REPONAME  the repo of the library

OPTIONS
  -h, --help                     show CLI help
  -o, --outputDir=outputDir      folder to output the library in (defaults to the current working folder)
  -t, --templateUrl=templateUrl  the template to use
  -v, --version                  show CLI version
  -w, --overwrite                overwrite any existing output folder
  </pre>