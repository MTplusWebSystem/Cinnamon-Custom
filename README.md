# Cinnamon-Custom

### prerequisite

```shell script
sudo apt update -y
```
```shell script
sudo apt unzip
```
```shell script
sudo apt upgrade -y
```
```shell script
sudo apt install git
```
```shell script
sudo apt install wget
```

## repository installation required

https://github.com/vinceliuice/WhiteSur-gtk-theme
use --nord in ./install.sh

example: ./install.sh --nord

https://github.com/alvatip/Nordzy-icon
use --total in ./install.sh

example: ./install.sh --total

# installation 

```shell script
sudo apt install plank
```
```shell script
git clone https://github.com/MTplusWebSystem/Cinnamon-Custom
```
```shell script
cd Cinnamon-Custom 
```
```shell script
unzip wallpapers.zip
```
```shell script
mv wallpapers ~/Imagens 
```
```shell script
unzip cinnamon-config.zip
```
```shell script
cd cinnamon-config
```
```shell script
dconf load /org/cinnamon/ < cinnamon-nord.conf
```


