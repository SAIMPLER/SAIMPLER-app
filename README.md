# SAIMPLER — public files

SAIMPLER is a sample browser and editor for macOS. The application is
proprietary (© 2026 SAIMPLER, all rights reserved) and its source code is not
published here. This repository holds what SAIMPLER makes public:

## Models

The [`models-v1`](https://github.com/SAIMPLER/SAIMPLER-app/releases/tag/models-v1)
release hosts the model files the application downloads on first use. Their
licences are listed in the application, under SAIMPLER › About SAIMPLER.

## Third-party source code

`third-party/` holds the source code of the open-source components SAIMPLER
ships in executable form, at the exact versions it compiles, **unmodified**:

| Folder | Component | Licence | Upstream |
|---|---|---|---|
| `bungee-2.4.30-8cb6977` | Bungee 2.4.30, © Parabola Research Limited | MPL-2.0 | https://github.com/bungee-audio-stretch/bungee/tree/8cb6977d0c1a1b411ac320493b3c7f5182ed2d22 |
| `eigen-c29c800` | Eigen, © Benoit Jacob, Gaël Guennebaud and the Eigen contributors | MPL-2.0 (a few files Apache-2.0 or BSD-3-Clause, see its COPYING files) | https://gitlab.com/libeigen/eigen/-/tree/c29c800126982c561e8d0b9255dc65474cd98de3 |
| `pffft-02fe771` | PFFFT, © Julien Pommier, after FFTPACK © University Corporation for Atmospheric Research | FFTPACK licence (BSD-style), see `pffft.c` | https://bitbucket.org/jpommier/pffft/src/02fe7715a5bf8bfd914681c53429600f94e0f536 |

Each folder keeps its original licence files and headers. These copies are
provided so the source of the MPL-2.0 components stays available alongside the
application, as the Mozilla Public License 2.0 asks; nothing in SAIMPLER's own
terms limits your rights in them.
