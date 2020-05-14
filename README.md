About enblend
=============

Home: http://enblend.sourceforge.net/

Package license: GPL-2.0-only

Feedstock license: BSD 3-Clause

Summary: Enblend combines images that overlap like this into a single large image with no seams.

Enblend blends away the seams in a panoramic image mosaic using a
multi-resolution spline. Enfuse merges different exposures of the same
scene to produce an image that looks much like a tone-mapped image.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=19&branchName=master">
            <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/enblend-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=19&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/enblend-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=19&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/enblend-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/ramonaoptics/feedstock-builds/_build/latest?definitionId=19&branchName=master">
                  <img src="https://dev.azure.com/ramonaoptics/feedstock-builds/_apis/build/status/enblend-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-enblend-green.svg)](https://anaconda.org/ramonaoptics/enblend) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/enblend.svg)](https://anaconda.org/ramonaoptics/enblend) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/enblend.svg)](https://anaconda.org/ramonaoptics/enblend) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/enblend.svg)](https://anaconda.org/ramonaoptics/enblend) |

Installing enblend
==================

Installing `enblend` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
```

Once the `ramonaoptics` channel has been enabled, `enblend` can be installed with:

```
conda install enblend
```

It is possible to list all of the versions of `enblend` available on your platform with:

```
conda search enblend --channel ramonaoptics
```




Updating enblend-feedstock
==========================

If you would like to improve the enblend recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/enblend-feedstock are
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

* [@hmaarrfk](https://github.com/hmaarrfk/)

