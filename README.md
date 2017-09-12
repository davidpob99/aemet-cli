# aemet-cli

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GRXHT9CGJ4L7G)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg?label=my-website)](https://davidpob99.github.io/aemet-cli/)


aemet-cli es una aplicación de terminal que permite obtener las previsiones del tiempo meteorológico en España. Usa datos abiertos de la Agencia Estatal de Meteorología (AEMET) del Gobierno de España.

# Instalación
## Ubuntu y derivados: 
En progreso..

## Arch Linux
[AUR](https://aur.archlinux.org/packages/aemet-cli/)

## Debian y derivados

En progreso..

# Ejemplos
Ver la previsión de los 7 días siguientes en Salamanca: `aemet-cli -m Salamanca`

Ver la previsión solo del día siguiente en Aranda de Duero: `aemet-cli -n 1 -m 'Aranda de Duero'`

Ver la previsión de los 7 días siguiente sabiendo el id del municipio de Valladolid: `aemet-cli -i 47186`

# Licencia

Código disponible bajo licencia Apache 2.0.
