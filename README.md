About gnuradio-adsb
===================

Home: https://github.com/mhostetter/gr-adsb

Package license: GPL-3.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/ryanvolz/gnuradio-adsb-feedstock-local-feedstock/blob/master/LICENSE.txt)

Summary: GNU Radio module to demodulate and decode ADS-B messages

Development: https://github.com/mhostetter/gr-adsb

Documentation: https://github.com/mhostetter/gr-adsb

A GNU Radio out-of-tree (OOT) module to demodulate and decode Automatic Dependent Surveillance Broadcast (ADS-B) messages.
To use the built-in web app, run `python -m gr_adsb.webserver`.


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gnuradio--adsb-green.svg)](https://anaconda.org/ryanvolz/gnuradio-adsb) | [![Conda Downloads](https://img.shields.io/conda/dn/ryanvolz/gnuradio-adsb.svg)](https://anaconda.org/ryanvolz/gnuradio-adsb) | [![Conda Version](https://img.shields.io/conda/vn/ryanvolz/gnuradio-adsb.svg)](https://anaconda.org/ryanvolz/gnuradio-adsb) | [![Conda Platforms](https://img.shields.io/conda/pn/ryanvolz/gnuradio-adsb.svg)](https://anaconda.org/ryanvolz/gnuradio-adsb) |

Installing gnuradio-adsb
========================

Installing `gnuradio-adsb` from the `ryanvolz` channel can be achieved by adding `ryanvolz` to your channels with:

```
conda config --add channels ryanvolz
conda config --set channel_priority strict
```

Once the `ryanvolz` channel has been enabled, `gnuradio-adsb` can be installed with:

```
conda install gnuradio-adsb
```

It is possible to list all of the versions of `gnuradio-adsb` available on your platform with:

```
conda search gnuradio-adsb --channel ryanvolz
```




Updating gnuradio-adsb-feedstock
================================

If you would like to improve the gnuradio-adsb recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ryanvolz` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ryanvolz` channel.
Note that all branches in the ryanvolz/gnuradio-adsb-feedstock are
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

* [@ryanvolz](https://github.com/ryanvolz/)

