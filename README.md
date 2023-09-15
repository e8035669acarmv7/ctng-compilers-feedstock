About gcc_compilers-feedstock
=============================

Feedstock license: [BSD-3-Clause](https://github.com/e8035669acarmv7/ctng-compilers-feedstock/blob/main/LICENSE.txt)


About gcc_compilers
-------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: GNU Compiler Collection

About libgcc-devel_linux-armv7l
-------------------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GNU C development libraries and object files

About libstdcxx-devel_linux-armv7l
----------------------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GNU C++ headers and development libraries

About gcc_impl_linux-armv7l
---------------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: GNU C Compiler

About gxx_impl_linux-armv7l
---------------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: GNU C++ Compiler

About gfortran_impl_linux-armv7l
--------------------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: GNU Fortran Compiler

About libgfortran5
------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GNU Fortran Runtime Library

About libgomp
-------------

Home: https://gcc.gnu.org/onlinedocs/gccint/Libgcc.html

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GCC OpenMP implementation.

About _openmp_mutex
-------------------

Home: https://github.com/conda-forge/ctng-compilers-feedstock

Package license: BSD-3-Clause

Summary: OpenMP Implementation Mutex

About libgfortran-ng
--------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GNU Fortran Runtime Library

About libgcc-ng
---------------

Home: https://gcc.gnu.org/onlinedocs/gccint/Libgcc.html

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GCC low-level runtime library

About libsanitizer
------------------

Home: https://gcc.gnu.org/onlinedocs/gccint/Libgcc.html

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GCC runtime libraries for sanitizers

About libstdcxx-ng
------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: The GNU C++ Runtime Library

About conda-gcc-specs
---------------------

Home: https://gcc.gnu.org/

Package license: GPL-3.0-only WITH GCC-exception-3.1

Summary: conda-specific specfile for GNU C/C++ Compiler

Documentation: https://gcc.gnu.org/onlinedocs/gcc/Spec-Files.html

When installed, this optional package provides a specfile that
directs gcc (and g++ or gfortran) to automatically:
  * search for includes in $PREFIX/include
  * link libraries in $PREFIX/lib
  * set RPATH to $PREFIX/lib
  * use RPATH instead of the newer RUNPATH
This package is intended to aid usability of the compiler
toolchain as a replacement for system-installed compilers.
It should not be used in recipes.  Use the 'compiler(<lang>)'
jinja function as described on
https://conda-forge.org/docs/maintainer/knowledge_base.html#dep-compilers


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_build/latest?definitionId=&branchName=main">
            <img src="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_apis/build/status/ctng-compilers-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_gcc_maj_ver12gcc_version12.3.0</td>
              <td>
                <a href="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_apis/build/status/ctng-compilers-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_gcc_maj_ver12gcc_version12.3.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_gcc_maj_ver13gcc_version13.2.0</td>
              <td>
                <a href="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_apis/build/status/ctng-compilers-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_gcc_maj_ver13gcc_version13.2.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_armv7l_gcc_maj_ver12gcc_version12.3.0</td>
              <td>
                <a href="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_apis/build/status/ctng-compilers-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_armv7l_gcc_maj_ver12gcc_version12.3.0" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_armv7l_gcc_maj_ver13gcc_version13.2.0</td>
              <td>
                <a href="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_build/latest?definitionId=&branchName=main">
                  <img src="https://dev.azure.com/e8035669acarmv7/feedstock-builds/_apis/build/status/ctng-compilers-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_armv7l_gcc_maj_ver13gcc_version13.2.0" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-_openmp_mutex-green.svg)](https://anaconda.org/e8035669acarmv7/_openmp_mutex) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/_openmp_mutex.svg)](https://anaconda.org/e8035669acarmv7/_openmp_mutex) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/_openmp_mutex.svg)](https://anaconda.org/e8035669acarmv7/_openmp_mutex) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/_openmp_mutex.svg)](https://anaconda.org/e8035669acarmv7/_openmp_mutex) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-conda--gcc--specs-green.svg)](https://anaconda.org/e8035669acarmv7/conda-gcc-specs) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/conda-gcc-specs.svg)](https://anaconda.org/e8035669acarmv7/conda-gcc-specs) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/conda-gcc-specs.svg)](https://anaconda.org/e8035669acarmv7/conda-gcc-specs) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/conda-gcc-specs.svg)](https://anaconda.org/e8035669acarmv7/conda-gcc-specs) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gcc_impl_linux--armv7l-green.svg)](https://anaconda.org/e8035669acarmv7/gcc_impl_linux-armv7l) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/gcc_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gcc_impl_linux-armv7l) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/gcc_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gcc_impl_linux-armv7l) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/gcc_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gcc_impl_linux-armv7l) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gfortran_impl_linux--armv7l-green.svg)](https://anaconda.org/e8035669acarmv7/gfortran_impl_linux-armv7l) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/gfortran_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gfortran_impl_linux-armv7l) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/gfortran_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gfortran_impl_linux-armv7l) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/gfortran_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gfortran_impl_linux-armv7l) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gxx_impl_linux--armv7l-green.svg)](https://anaconda.org/e8035669acarmv7/gxx_impl_linux-armv7l) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/gxx_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gxx_impl_linux-armv7l) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/gxx_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gxx_impl_linux-armv7l) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/gxx_impl_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/gxx_impl_linux-armv7l) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libgcc--devel_linux--armv7l-green.svg)](https://anaconda.org/e8035669acarmv7/libgcc-devel_linux-armv7l) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libgcc-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libgcc-devel_linux-armv7l) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libgcc-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libgcc-devel_linux-armv7l) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libgcc-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libgcc-devel_linux-armv7l) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libgcc--ng-green.svg)](https://anaconda.org/e8035669acarmv7/libgcc-ng) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libgcc-ng.svg)](https://anaconda.org/e8035669acarmv7/libgcc-ng) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libgcc-ng.svg)](https://anaconda.org/e8035669acarmv7/libgcc-ng) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libgcc-ng.svg)](https://anaconda.org/e8035669acarmv7/libgcc-ng) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libgfortran--ng-green.svg)](https://anaconda.org/e8035669acarmv7/libgfortran-ng) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libgfortran-ng.svg)](https://anaconda.org/e8035669acarmv7/libgfortran-ng) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libgfortran-ng.svg)](https://anaconda.org/e8035669acarmv7/libgfortran-ng) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libgfortran-ng.svg)](https://anaconda.org/e8035669acarmv7/libgfortran-ng) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libgfortran5-green.svg)](https://anaconda.org/e8035669acarmv7/libgfortran5) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libgfortran5.svg)](https://anaconda.org/e8035669acarmv7/libgfortran5) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libgfortran5.svg)](https://anaconda.org/e8035669acarmv7/libgfortran5) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libgfortran5.svg)](https://anaconda.org/e8035669acarmv7/libgfortran5) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libgomp-green.svg)](https://anaconda.org/e8035669acarmv7/libgomp) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libgomp.svg)](https://anaconda.org/e8035669acarmv7/libgomp) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libgomp.svg)](https://anaconda.org/e8035669acarmv7/libgomp) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libgomp.svg)](https://anaconda.org/e8035669acarmv7/libgomp) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libsanitizer-green.svg)](https://anaconda.org/e8035669acarmv7/libsanitizer) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libsanitizer.svg)](https://anaconda.org/e8035669acarmv7/libsanitizer) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libsanitizer.svg)](https://anaconda.org/e8035669acarmv7/libsanitizer) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libsanitizer.svg)](https://anaconda.org/e8035669acarmv7/libsanitizer) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libstdcxx--devel_linux--armv7l-green.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-devel_linux-armv7l) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libstdcxx-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-devel_linux-armv7l) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libstdcxx-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-devel_linux-armv7l) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libstdcxx-devel_linux-armv7l.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-devel_linux-armv7l) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libstdcxx--ng-green.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-ng) | [![Conda Downloads](https://img.shields.io/conda/dn/e8035669acarmv7/libstdcxx-ng.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-ng) | [![Conda Version](https://img.shields.io/conda/vn/e8035669acarmv7/libstdcxx-ng.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-ng) | [![Conda Platforms](https://img.shields.io/conda/pn/e8035669acarmv7/libstdcxx-ng.svg)](https://anaconda.org/e8035669acarmv7/libstdcxx-ng) |

Installing gcc_compilers
========================

Installing `gcc_compilers` from the `e8035669acarmv7` channel can be achieved by adding `e8035669acarmv7` to your channels with:

```
conda config --add channels e8035669acarmv7
conda config --set channel_priority strict
```

Once the `e8035669acarmv7` channel has been enabled, `_openmp_mutex, conda-gcc-specs, gcc_impl_linux-armv7l, gfortran_impl_linux-armv7l, gxx_impl_linux-armv7l, libgcc-devel_linux-armv7l, libgcc-ng, libgfortran-ng, libgfortran5, libgomp, libsanitizer, libstdcxx-devel_linux-armv7l, libstdcxx-ng` can be installed with `conda`:

```
conda install _openmp_mutex conda-gcc-specs gcc_impl_linux-armv7l gfortran_impl_linux-armv7l gxx_impl_linux-armv7l libgcc-devel_linux-armv7l libgcc-ng libgfortran-ng libgfortran5 libgomp libsanitizer libstdcxx-devel_linux-armv7l libstdcxx-ng
```

or with `mamba`:

```
mamba install _openmp_mutex conda-gcc-specs gcc_impl_linux-armv7l gfortran_impl_linux-armv7l gxx_impl_linux-armv7l libgcc-devel_linux-armv7l libgcc-ng libgfortran-ng libgfortran5 libgomp libsanitizer libstdcxx-devel_linux-armv7l libstdcxx-ng
```

It is possible to list all of the versions of `_openmp_mutex` available on your platform with `conda`:

```
conda search _openmp_mutex --channel e8035669acarmv7
```

or with `mamba`:

```
mamba search _openmp_mutex --channel e8035669acarmv7
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search _openmp_mutex --channel e8035669acarmv7

# List packages depending on `_openmp_mutex`:
mamba repoquery whoneeds _openmp_mutex --channel e8035669acarmv7

# List dependencies of `_openmp_mutex`:
mamba repoquery depends _openmp_mutex --channel e8035669acarmv7
```




Updating gcc_compilers-feedstock
================================

If you would like to improve the gcc_compilers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`e8035669acarmv7` channel, whereupon the built conda packages will be available for
everybody to install and use from the `e8035669acarmv7` channel.
Note that all branches in the e8035669acarmv7/gcc_compilers-feedstock are
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

* [@beckermr](https://github.com/beckermr/)
* [@isuruf](https://github.com/isuruf/)
* [@timsnyder](https://github.com/timsnyder/)
* [@xhochy](https://github.com/xhochy/)

