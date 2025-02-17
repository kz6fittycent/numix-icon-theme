[![numix-icon-theme](https://snapcraft.io/numix-icon-theme/badge.svg)](https://snapcraft.io/numix-icon-theme) [![🧪 Snap Builds](https://github.com/kz6fittycent/numix-icon-theme/actions/workflows/test-snap-can-build.yml/badge.svg)](https://github.com/kz6fittycent/numix-icon-theme/actions/workflows/test-snap-can-build.yml)

# numix-icon-theme

A snap for the [Numix icon theme](https://github.com/numixproject/numix-icon-theme/).

## Install the snap

`sudo snap install numix-icon-theme`

## Connect the icon theme 

```
for i in $(snap connections | grep gtk-common-themes:icon-themes | awk '{print $2}'); do sudo snap connect $i numix-icon-theme:icon-themes; done
```
