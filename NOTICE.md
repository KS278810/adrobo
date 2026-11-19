# AdRobo, notices

Copyright 2026 Kohei Shintani. AdRobo is released under the Creative Commons Attribution-NonCommercial 4.0 International licence, the full text is in `LICENSE`. Free to use for education, research and teaching material. Please get in touch before any commercial use.

## Third-party material

| Part | Source | Licence |
|---|---|---|
| TeVAE code that `tevae_torch` ports | https://github.com/lcs-crr/TeVAE, kept in the notice of the sibling repository `tevae_torch` | MIT |
| scikit-learn, the covariance and neighbour estimators and the metrics | https://scikit-learn.org | BSD-3-Clause |
| uPlot 1.6.32, `adrobo/web/static/vendor/uplot` | https://github.com/leeoniya/uPlot | MIT |
| Chakra Petch and IBM Plex Mono, embedded in `adrobo/web/static/index.html`, licence texts in `adrobo/web/static/fonts` | the font projects | SIL Open Font License 1.1 |
| The layout, CSS and generic scripts of the screen | the SurRobo front end by the same author | CC BY-NC 4.0 |
| `adrobo/web/static/img/robot_*.gif`, the mascot robot06_navy: still image by Qwen-Image, motion by Wan 2.2 I2V-A14B, background removed by the author's own keyer, no MiniMax H3 file | https://huggingface.co/Qwen/Qwen-Image and https://huggingface.co/Wan-AI/Wan2.2-I2V-A14B, read on 2026-11-10 | Apache-2.0 for both models |
| `adrobo/web/static/img/favicon.svg` | made by the author | CC BY-NC 4.0 |
| `adrobo/web/static/sample.csv`, built by `scripts/make_web_sample_tire.py` | https://github.com/kerzeyc/tire-monitoring-dataset, commit b05ce1c8: in-cavity tyre pressure, temperature and speed of real vehicles, 120 everyday runs and 45 controlled-deflation runs | CC BY 4.0, attribution required |
| Pyodide 0.28.0, bundled in the browser build as `vendor/pyodide/` and served by the page itself, fetched by `_shared/publish/fetch_vendor.py` with sha256 checks and not changed | https://pyodide.org, source of the MPL files at https://github.com/pyodide/pyodide, tag 0.28.0 | MPL-2.0, text in `licenses/Pyodide-MPL-2.0.txt` |
| The Python standard library in `python_stdlib.zip` of that folder | https://www.python.org | PSF License, text in `licenses/CPython-PSF-3.13.txt` |
| numpy 2.2.5, scipy 1.14.1, pandas 2.3.0 and scikit-learn 1.7.0 as wasm wheels of that folder, with joblib 1.4.2, threadpoolctl 3.5.0, python-dateutil 2.9.0.post0, pytz 2025.2 and six 1.17.0 | the Pyodide 0.28.0 distribution | BSD-3-Clause, MIT and the dual licence of python-dateutil, each licence file stays inside its wheel |
| OpenBLAS 0.3.26, `openblas-0.3.26.zip` of that folder | https://github.com/OpenMathLib/OpenBLAS | BSD-3-Clause, text in `licenses/OpenBLAS-BSD-3-Clause.txt` |
| terser, javascript-obfuscator and python-minifier, used by `_shared/publish` to make the public copy and not part of it | npm and PyPI | BSD-2-Clause, BSD-2-Clause and MIT |

Japanese text uses the fonts of the viewer's system. No Japanese font is bundled.
