[![Build Status](https://travis-ci.org/opentraveldata/opentraveldata.svg?branch=master)](https://travis-ci.org/opentraveldata/opentraveldata)

# Overview
Open Travel Data (OPTD) provides a collection of transport, travel and leisure
related data. The project makes extensive use of already existing data sources
such as [Geonames](http://geonames.org) and [Wikipedia](http://wikipedia.org),
and adds some glue around those (e.g. links).

All data sets are as carefully maintained as possible,
and kept up-to-date by the OPTD team, which we would be glad
to welcome you on!

Flat/data files are used with hat (^) separated columns,
so that it should be easy to use with your own tools of choice.

# Directory structure
* All the data sets, which are directly curated and maintained by OPTD,
  are located in the
  [``opentraveldata`` directory](https://github.com/opentraveldata/opentraveldata/tree/master/opentraveldata).
* The [``data``](https://github.com/opentraveldata/opentraveldata/tree/master/data)
  directory contains a sub-directory per collected data source.
  For instance, the
  [``data/unlocode`` directory](https://github.com/opentraveldata/opentraveldata/tree/master/data/unlocode) contains data snapshots from UN/LOCODE.
  See the
  [``README`` file](https://github.com/opentraveldata/opentraveldata/tree/master/data/unlocode/README.md)
  in that directory for more details.
  In all the cases, those data are collected legally, either directly
  from a download service, when it exists, or through public web
  screen-scraping methods when required.
* Some usage examples can be found in the
  [``examples`` directory](https://github.com/opentraveldata/opentraveldata/tree/master/examples).
* The [``tools``](https://github.com/opentraveldata/opentraveldata/tree/master/tools)
  directory contains scripts, which are used to generate the data sets.
* [``.travis``](https://github.com/opentraveldata/opentraveldata/tree/master/.travis)
  contains continuous integration (CI) related code.

# GeoBases
[GeoBases](http://opentraveldata.github.io/geobases/) is a good addition to OPTD,
offering easy-to-use data manipulation and visualization Python-based tools
and API, on top of OPTD curated data files.

# OpenTREP
[OpenTREP](http://github.com/trep/opentrep) is a C++-based transport related
full-text search library, with Python bindings, powering the
[Travel Search Web application](http://search-travel.org).
That Web application also gets
[its own Wikipedia template](http://en.wikipedia.org/wiki/Template:STV),
so as to ease its use on that world wide encyclopedia.

The full stack of that Web application is open, from the data sources up to
the front-end source code, through the back-end Python and C++ libraries.
So, do not hesitate to contribute, for instance just for the fun of it.

# Data Quality
An independent
[Service Delivery Quality (SDQ) project](http://github.com/service-delivery-quality/quality-assurance/tree/master/samples/opentraveldata)
aims at monitoring the quality of data provide by OPTD. There is still some work
to be done in order to automate most of the steps, though.

# Legacy
This is the master repository of the Open Travel Data (OPTD) project.
For backwards compatibility reasons, all changes are synchronized back to the
[old repository](http://github.com/opentraveldata/optd).

# Licensing
The data curated and/or generated by the OPTD project are governed by the
[CC-BY license](http://creativecommons.org/licenses/by/4.0/).

## With OPTD own generated/curated data, you are free to
* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material for any purpose,
  even commercially.

This license is acceptable for Free Cultural Works.
The licensor cannot revoke these freedoms as long as
you follow the license terms.

## Under the following terms
* **Attribution** — You must give appropriate credit, provide a link to the
  license, and indicate if changes were made. You may do so in any reasonable
  manner, but not in any way that suggests the licensor endorses you
  or your use.
* **No additional restrictions** — You may not apply legal terms or
  technological measures that legally restrict others from doing anything
  the license permits.

## Non OPTD maintained data
For the data in the
[``data`` directory](https://github.com/opentraveldata/opentraveldata/tree/master/data),
you should check directly with the corresponding data producer. In no way
OPTD endorses you to use, remix, transform or build upon those data sources.

# Contributions
Any contribution or feedback is welcome!

Please do not hesitate
[to open an issue request](http://github.com/opentraveldata/opentraveldata/issues/new)
or
[to suggest enhancement through pull request (PR)](http://github.com/opentraveldata/opentraveldata/compare)!

If you notice something missing, like
[Laudamotion airline (OE)](http://github.com/opentraveldata/opentraveldata/issues/93)
at some point, you can just step up, and we will try to fix what is wrong.

You can also become a regular contributor: just create a GitHub account and
we will enlist you right away! That is the surest way for you to know that you
will always be best served (by yourself) and receive our eternal gratefulness :)

OpenTravelData aims at being useful to the human kind, no more, no less.
Anyone is welcome to contribute to make our world a better place.
Knowledge is key, essential to preserve our freedom. We are happy that you read
so far, thanks!

