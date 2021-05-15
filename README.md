#Image Repository
This repository contains a collection of images. The aim of this repository might be a bit silly. 
I however would like to think that is important as important as to choose 
a nice image that lives in the wallpaper of your machine.
Similarly, this repo is helpful to keep some nice images when I migrate to other machines.

## Clone repository
After generating your SSH keys as suggested [here](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), you can then clone the repository by typing (or copying) the following line in a terminal at your selected path in your machine:
```
git clone git@github.com:mxochicale/images.git
```

## Tools for image creation

### inkscape in Ubuntu 16.04 x64
* Installation
```
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt update
sudo apt install inkscape
```
Alternative, you can also check https://github.com/mxochicale/tools/tree/main/inkscape for installation in other versiosn of Ubuntu!

* Usage
Once you create a drawing, you can convert it easily in the terminal 
using the following commands!
```
inkscape --export-png drawing_v##.png drawing.svg
inkscape --export-pdf $(@) $(<)
inkscape -z -e drawing.png -w 1024 -h 1024 drawing.svg
``` 
Alternatively, you can use the template [00_template-vector-images](00_template-vector-images/) to automatically convert svg files to png or pdf.


## Contact 
If you have specific questions about the content of this repository, you can contact 
[Miguel Xochicale](mailto:perez.xochicale@gmail.com?subject="[images]"). 
If your question might be relevant to other people, please instead 
[open an issue](https://github.com/mxochicale/images/issues).
