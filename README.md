# rgevolve.wet_3.flavio

Package providing Renormalization Group Evolution matrices for the
**WET-3** in the **flavio** basis, following the
[wcxf](https://wcxf.github.io/) conventions for Wilson coefficient
bases.

It is a sub-package of the **rgevolve** ecosystem — a set of Python
namespace packages for fast renormalization group evolution of Wilson
coefficients in the SMEFT and the WET using the evolution matrix
formalism. See the [rgevolve organization](https://github.com/rgevolve)
for the full ecosystem and the
[`rgevolve` meta-package](https://github.com/rgevolve/rgevolve) for
installation in lockstep with the core and all companions.

<!-- BEGIN: auto-generated from data.h5 by .github/scripts/generate-readme.py — do not edit by hand -->

## Contents

This distribution bundles RG evolution matrices precomputed at
**5 scales** between **0.77526** and
**2** GeV:

| scale (GeV) |
| ----------- |
| 0.77526 |
| 1 |
| 1.15 |
| 1.3 |
| 2 |

Matrices are organised into **33 sectors** covering a total
of **720 Wilson coefficients** (counting the real and imaginary
parts of complex coefficients separately):

| sector | # Wilson coefficients |
| ------ | --------------------- |
| `dF=0` | 182 |
| `ffnuinui` | 30 |
| `ffnumunue` | 20 |
| `ffnumunutau` | 20 |
| `ffnutaunue` | 20 |
| `mue` | 88 |
| `muenuenumu` | 4 |
| `muenuenutau` | 4 |
| `muenuinui` | 12 |
| `muenumunue` | 4 |
| `muenumunutau` | 4 |
| `muenutaunue` | 4 |
| `muenutaunumu` | 4 |
| `sd` | 120 |
| `sdemu` | 16 |
| `sdmue` | 16 |
| `sdnuinui` | 12 |
| `sdnumunue` | 8 |
| `sdnumunutau` | 8 |
| `sdnutaunue` | 8 |
| `sdsd` | 16 |
| `udenue` | 10 |
| `udenumu` | 10 |
| `udenutau` | 10 |
| `udmunue` | 10 |
| `udmunumu` | 10 |
| `udmunutau` | 10 |
| `usenue` | 10 |
| `usenumu` | 10 |
| `usenutau` | 10 |
| `usmunue` | 10 |
| `usmunumu` | 10 |
| `usmunutau` | 10 |

<!-- END: auto-generated -->

## Installation

```bash
pip install rgevolve.wet_3.flavio
```

To install the core package together with all available EFT/basis
companion packages at once, use the meta-package:

```bash
pip install rgevolve
```

## License

`rgevolve.wet_3.flavio` is licensed under the MIT License — see [`LICENSE`](LICENSE).
