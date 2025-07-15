# SocioMol
Sociomol is a lightweight, extensible toolkit for clustering and visualizing subtomogram particles based on geometric features such as orientation, distance, and curvature.
The name Sociomol combines "socio-" (structure, interaction, or network) and "mol" (molecule), reflecting the toolkit's purpose: understanding the spatial organization and interaction of molecular assemblies in tomographic data.

----
This project is a **clean and working fork** of [MagpiEM](https://github.com/fnight128/MagpiEM) version 0.2.20, originally developed by **Frank Nightingale**.

It has been restructured and renamed as **SocioMol** for further development, with bug fixes and environment compatibility improvements.

---

## Key changes from MagpiEM 0.2.20

- Changed package folder from `MagpiEM/` to lowercase `sociomol/` to comply with PEP8 and Python import conventions.
- Updated `pyproject.toml`:
  - Project name changed to `sociomol`
  - Version set to `0.0.0`
  - Maintainer set to `Long Chen <longleochen91@gmail.com>`
  - `dash` version updated from `2.9.3` to `2.15.0` to fix JS loading bugs.
- Confirmed editable install and GUI launch with:
  ```bash
  pip install -e .
  python -m sociomol.dash_ui


