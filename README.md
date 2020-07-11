About pytest-qt
===============

Home: https://github.com/pytest-dev/pytest-qt

Package license: MIT

Feedstock license: BSD-3-Clause

Summary: pytest support for PyQt and PySide applications



Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=227&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/pytest-qt-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pytest--qt-green.svg)](https://anaconda.org/nsls2forge/pytest-qt) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/pytest-qt.svg)](https://anaconda.org/nsls2forge/pytest-qt) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/pytest-qt.svg)](https://anaconda.org/nsls2forge/pytest-qt) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/pytest-qt.svg)](https://anaconda.org/nsls2forge/pytest-qt) |

Installing pytest-qt
====================

Installing `pytest-qt` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `pytest-qt` can be installed with:

```
conda install pytest-qt
```

It is possible to list all of the versions of `pytest-qt` available on your platform with:

```
conda search pytest-qt --channel nsls2forge
```




Updating pytest-qt-feedstock
============================

If you would like to improve the pytest-qt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/pytest-qt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@nicoddemus](https://github.com/nicoddemus/)

