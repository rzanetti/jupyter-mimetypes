# Jupyter MIME Types PKGBUILD

A [Python](https://www.python.org) package that provides enhanced [Jupyter](https://jupyter.org) representation capabilities through proxy objects, enabling efficient [Apache Arrow-based](https://arrow.apache.org) serialization for [pandas](https://pandas.pydata.org) `DataFrames`/`Series` and [pickle-based serialization](https://docs.python.org/3/library/pickle.html) for generic Python objects in Jupyter environments.

## Why this package exists?

This repository provides an [Arch Linux](https://archlinux.org) `PKGBUILD` for software that is not currently available in the [official repositories](https://wiki.archlinux.org/title/Official_repositories).

The goal is to make installation reproducible, auditable, and compatible with standard Arch Linux packaging practices.

## Upstream project

This repository **does not** contain the original software! It contains only the Arch Linux packaging files.

The software itself is maintained by the upstream project.

Upstream source code:

- [datalayer/jupyter-mimetypes: 🪐 Jupyter Mimetypes - Enhanced Jupyter representation capabilities through proxy objects](https://github.com/datalayer/jupyter-mimetypes)

[PyPI](https://pypi.org) package:

- [jupyter-mimetypes · PyPI](https://pypi.org/project/jupyter-mimetypes)

## Installation

```bash
git clone https://aur.archlinux.org/python-jupyter-mimetypes.git
cd python-jupyter-mimetypes
makepkg -si
```

## Maintenance

The `PKGBUILD` tracks upstream releases published on [PyPI](https://pypi.org/project/jupyter-mimetypes).

Issues related to the packaged software itself should be reported [upstream](https://github.com/datalayer/jupyter-mimetypes).

Issues related to Arch Linux packaging can be reported in this repository.
