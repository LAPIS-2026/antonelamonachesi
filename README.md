# Códigos para Práctico — Prof. Antonela Monachesi (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Antonela Monachesi (*Resolving the Stellar Halos of Galaxies to Decipher their Accretion History*) en la escuela de astrofísica **XII LAPIS 2026**.

## Proyecto y Datos

- **Proyecto**: *Characterization of Stellar Halos in Nearby Galaxies* — caracterización de halos estelares de galaxias cercanas mediante poblaciones estelares resueltas (perfiles de color, metalicidad, densidad y masa estelar) a partir de imágenes del HST y catálogos del relevamiento GHOSTS.
- **Datos y catálogos**: Imágenes de HST y catálogos de fuentes estelares resueltas.

## Software y Estructura

- **Herramientas**: Python, SAOImage DS9.
- `pyds9plugin/` — Submódulo con el fork de [vpicouet/pyds9plugin](https://github.com/vpicouet/pyds9plugin) en [`LAPIS-2026/pyds9plugin`](https://github.com/LAPIS-2026/pyds9plugin).

## Lecturas Previas Sugeridas

- [Monachesi et al. (2016a)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.457.1419M/abstract)
- [Harmsen, Monachesi et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017MNRAS.466.1491H/abstract)
- [Monachesi et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019MNRAS.485.2589M/abstract)
- [Smercina et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...949L..37S/abstract)
- [Gozman et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023ApJ...947...21G/abstract)

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/antonelamonachesi.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
