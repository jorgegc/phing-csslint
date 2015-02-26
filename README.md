Phing CSS Lint
==============

## Overview

A collection of CSS Lint targets for Phing.

## Installation

This project can be checked out with Composer.

Please note that this project assumes that CSS Lint is installed and configured
and ${csslint.bin} points to its binaries location.

```
"require": {
    "jorgegc/phing-csslint": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/jorgegc/phing-csslint/build.xml" optional="true" />
```

## Usage

To get a list of tasks.

```
phing -l
```
