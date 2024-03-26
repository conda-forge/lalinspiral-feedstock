About lalinspiral-feedstock
===========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/lalinspiral-feedstock/blob/main/LICENSE.txt)


About lalinspiral
-----------------

Home: https://wiki.ligo.org/Computing/LALSuite

Package license: GPL-2.0-or-later

Summary: LSC Algorithm Inspiral Library

Development: https://git.ligo.org/lscsoft/lalsuite/

Documentation: https://docs.ligo.org/lscsoft/lalsuite/lalinspiral/

The LSC Algorithm Inspiral Library for gravitational wave data analysis.


About liblalinspiral
--------------------

Home: https://wiki.ligo.org/Computing/LALSuite

Package license: GPL-2.0-or-later

Summary: LSC Algorithm Inspiral Library shared object libraries

Development: https://git.ligo.org/lscsoft/lalsuite/

Documentation: https://docs.ligo.org/lscsoft/lalsuite/lalinspiral/

The LSC Algorithm Inspiral Library for gravitational wave data analysis.
This package contains the shared object libraries needed to run
applications that use the LAL Inspiral library.


About python-lalinspiral
------------------------

Home: https://wiki.ligo.org/Computing/LALSuite

Package license: GPL-2.0-or-later

Summary: LSC Algorithm Inspiral Library Python libraries

Development: https://git.ligo.org/lscsoft/lalsuite/

Documentation: https://docs.ligo.org/lscsoft/lalsuite/lalinspiral/

The LSC Algorithm Inspiral Library for gravitational wave data analysis.
This package contains the Python bindings of the LALInspiral C libraries
and additional Python modules.

Note: this package only provides the importable Python libraries.
All command-line interfaces, scripts, and executables are
part of the `lalinspiral` package.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=3991&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/lalinspiral-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lalinspiral-green.svg)](https://anaconda.org/conda-forge/lalinspiral) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/lalinspiral.svg)](https://anaconda.org/conda-forge/lalinspiral) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/lalinspiral.svg)](https://anaconda.org/conda-forge/lalinspiral) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/lalinspiral.svg)](https://anaconda.org/conda-forge/lalinspiral) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-liblalinspiral-green.svg)](https://anaconda.org/conda-forge/liblalinspiral) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/liblalinspiral.svg)](https://anaconda.org/conda-forge/liblalinspiral) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/liblalinspiral.svg)](https://anaconda.org/conda-forge/liblalinspiral) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/liblalinspiral.svg)](https://anaconda.org/conda-forge/liblalinspiral) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-python--lalinspiral-green.svg)](https://anaconda.org/conda-forge/python-lalinspiral) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/python-lalinspiral.svg)](https://anaconda.org/conda-forge/python-lalinspiral) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/python-lalinspiral.svg)](https://anaconda.org/conda-forge/python-lalinspiral) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/python-lalinspiral.svg)](https://anaconda.org/conda-forge/python-lalinspiral) |

Installing lalinspiral
======================

Installing `lalinspiral` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `lalinspiral, liblalinspiral, python-lalinspiral` can be installed with `conda`:

```
conda install lalinspiral liblalinspiral python-lalinspiral
```

or with `mamba`:

```
mamba install lalinspiral liblalinspiral python-lalinspiral
```

It is possible to list all of the versions of `lalinspiral` available on your platform with `conda`:

```
conda search lalinspiral --channel conda-forge
```

or with `mamba`:

```
mamba search lalinspiral --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search lalinspiral --channel conda-forge

# List packages depending on `lalinspiral`:
mamba repoquery whoneeds lalinspiral --channel conda-forge

# List dependencies of `lalinspiral`:
mamba repoquery depends lalinspiral --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating lalinspiral-feedstock
==============================

If you would like to improve the lalinspiral recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/lalinspiral-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@duncanmmacleod](https://github.com/duncanmmacleod/)
* [@skymoo](https://github.com/skymoo/)

