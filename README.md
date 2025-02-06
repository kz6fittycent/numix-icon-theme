# numix-icon-theme

A snap for the [Numix icon theme](https://github.com/numixproject/numix-icon-theme/).

## Install the snap

`sudo snap install numix-icon-theme`

## Connect the icon theme 

```
for i in $(snap connections | grep gtk-common-themes:icon-themes | awk '{print $2}'); do sudo snap connect $i numix-icon-theme:icon-themes; done
```
