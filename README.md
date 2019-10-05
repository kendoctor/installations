# Tips and memo of installations for developing

## Git installation

```shell script
sudo apt install git
```

## NodeJs installation

```shell script
sudo apt install nodejs
sudo apt install npm
```
> Missing write access to /usr/lib/node_modules

```shell script
sudo chown -R $USER /usr/lib/node_modules 
```
### How to upgrade nodejs

```shell script
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
```
## Yarn installation
```shell script
sudo apt-get update && sudo apt-get install yarn
```

## Phpstorm installation
```shell script
sudo apt install phpstorm --classic
```

## Vue cli installation

```shell script
sudo npm install -g @vue/cli #vue cli
```

## Chrome installation 

> Add key
```shell script
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
```
>   Set repository:
```shell script
echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' | sudo tee /etc/apt/sources.list.d/google-chrome.list
```
>Install package:
```shell script
sudo apt-get update 
sudo apt-get install google-chrome-stable
```

### Useful Chrome web developer extensions

- [Responsive Design: Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en)
- [Full Page Screen Capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
- [ColorZilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp)
- [CSS Peeper](https://chrome.google.com/webstore/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk?hl=en)
- [CSSViewer](https://chrome.google.com/webstore/detail/cssviewer/ggfgijbpiheegefliciemofobhmofgce?hl=en)
- [ColorPick Eyedropper](https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg?hl=en%20)





