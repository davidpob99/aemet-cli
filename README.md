# aemet-cli

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=GRXHT9CGJ4L7G)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg?label=my-website)](https://davidpob99.github.io/aemet-cli/)


aemet-cli es una aplicación de terminal que permite obtener las previsiones del tiempo meteorológico en España. Usa datos abiertos de la Agencia Estatal de Meteorología (AEMET) del Gobierno de España.

![iss040e008244](https://images-assets.nasa.gov/image/iss040e008244/iss040e008244~small.jpg)

# Instalación
## Ubuntu y derivados: 


## Arch Linux
[AUR](https://aur.archlinux.org/packages/aemet-cli/)

## Debian y derivados

[AUR](https://aur.archlinux.org/packages/nasa-wallpaper/)

## With the code
`git clone https://github.com/davidpob99/aemet-cli`

`cd aemet-cli`

`chmod -x ./aemet-cli`

`./aemet-cli`

# Ejemplos
Set the APOD image as wallpaper (GNOME): `nasa-wallpaper -T gnome -a`

Set the APOD image of the 27th March 1999 (MATE): `nasa-wallpaper -d 1999-03-27 -T mate -a`

Set a random image from the NASA Image Library (LXDE): `nasa-wallpaper -T lxde -n`

Set a random image with the `earth` keyword (GNOME): `nasa-wallpaper -w earth -T gnome -n`

Read the manual: `man aemet-cli`

# Licencia

Código disponible bajo licencia Apache 2.0.
