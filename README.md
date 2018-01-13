# PDF Solution Pack [![Build Status](https://travis-ci.org/Islandora/islandora_solution_pack_pdf.png?branch=7.x)](https://travis-ci.org/Islandora/islandora_solution_pack_pdf)

## Introduction

Loads all required Fedora Objects, and creates an empty collection object to accept PDFs.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [ImageMagick](http://www.imagemagick.org/script/index.php) - Debian/Ubuntu `sudo apt-get install imagemagick`
* [ImageMagick module](https://www.drupal.org/project/imagemagick)
    * ensure that the **full path** to Imagemagick's convert is specified in the Image Toolkit (admin/config/media/image-toolkit)
* [pdftotext](http://poppler.freedesktop.org) -  Debian/Ubuntu `sudo apt-get install poppler-utils`
* [ghostscript](http://www.ghostscript.com) - Debian/Ubuntu `sudo apt-get install ghostscript`

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Configure thumbnail and preview image sizes, and set the path for `pdftotext` and `gs` if extract text stream and create PDFA derivative are selected, respectively, in Administration » Islandora »  Solution pack configuration »  PDF Solution Pack (admin/islandora/solution_pack_config/pdf).

![Configuration](https://raw.githubusercontent.com/dmoses/islandora_screenshots/master/pdf_sp_config.jpg)

## Documentation

Further documentation for this module is available at [our wiki](https://wiki.duraspace.org/display/ISLANDORA/PDF+Solution+Pack).

## Troubleshooting/Issues

Having problems or solved one? Create an issue, check out the Islandora Google
groups.

* [Users](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Devs](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

or contact [discoverygarden](http://support.discoverygarden.ca).

## Maintainers/Sponsors

Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module, please check out the helpful
[Documentation](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers),
[Developers](http://islandora.ca/developers) section on Islandora.ca and create
an issue, pull request and or contact
[discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
