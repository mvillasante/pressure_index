<a href="http://nies.soccer/"><img src="https://github.com/nepito/world_cup_semis/blob/develop/img/logo.jpeg" align="right" width="256" /></a>

# Pressure index
[![codecov](https://codecov.io/github/niesfutbol/pressure_index/graph/badge.svg?token=SPGA1DM17D)](https://codecov.io/github/niesfutbol/pressure_index)
![licencia](https://img.shields.io/github/license/niesfutbol/pressure_index)
![languages](https://img.shields.io/github/languages/top/niesfutbol/pressure_index)
![commits](https://img.shields.io/github/commit-activity/y/niesfutbol/pressure_index)

## Step to use
1. Transform the files `Team Stats {team}.xlsx` from xlsx to `{team}.csv`.
2. Calculate build-up and tilt
``` sh
Rscript src/build_up.R
Rscript src/tilt_match.R
```
3. Add column tilt to build-up.
``` sh
Rscript src/concatenate_build_and_tilt.R
```


Los mayores xG creados por un equipo en un juego en todo el año:
Tigres: 6.04 (vs Guadalajara)
Santos: 5.97 (vs Pumas)
Mazatlán: 5.76 (vs Toluca)
América: 3.87 (vs Puebla)
