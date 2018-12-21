# txt2tags for NVDA

## What is this?

NVDA (NonVisual Desktop Access) is a free, open source screen reader for Microsoft Windows.

The documentation of NVDA is made using txt2tags.

This repository is the proof of concept of Python3 migration regarding NVDA documentations.

## Key Project Links

* [NVDA on GitHub](https://github.com/nvaccess/nvda)
* [txt2tags](https://txt2tags.org/)

## How to Use

```
pip install -r requirements.txt
scons -c
scons
```

## Environments

* Python 3.7.1 (Win32)
* Python 2.7.15 (Win32)
* Python 3.5.2 (Ubuntu 16.04.3 LTS on WSL)
* Python 2.7.12 (Ubuntu 16.04.3 LTS on WSL)

## Remarks

* The original source of txt2tags is version 2.5, which is used by NVDA.
* It only covers what is necessary for NVDA version 2018.4.
* It contains additional scripts, config files, and NVDA document sources in English and Japanese.
* So far, the generated HTML files are exactly same, regarding Python versions.
* On Linux and Windows, it generates different HTML files regarding line endings and the comment at the end of the files.
