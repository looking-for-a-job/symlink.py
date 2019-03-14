<!--
https://pypi.org/project/readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/symlink.svg?longCache=True)](https://pypi.org/project/symlink/)
[![](https://img.shields.io/pypi/v/symlink.svg?maxAge=3600)](https://pypi.org/project/symlink/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/symlink.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/symlink.py/)

#### Installation
```bash
$ [sudo] pip install symlink
```

#### Functions
function|`__doc__`
-|-
`symlink.isbroken(path)` |return True if symbolic is broken
`symlink.lexists(path)` |return True if path exists and is a symbolic link
`symlink.read(path)` |return a string representing the path to which the symbolic link points. The result may be either an absolute or relative pathname
`symlink.update(source, link_name)` |create or update a symbolic link pointing to source named link_name

<p align="center">
    <a href="https://pypi.org/project/readme-generator/">readme-generator</a>
</p>