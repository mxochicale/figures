# Figures 
This repository contains a collection of images and figures. 
Maybe the most relevant fetaure is the [makefile template](00_template-vector-images) to edit figures in inkspace.
I however would like to think that is important to choose a nice image that lives in the wallpaper of your machine.
The repo is helpful to keep some nice images when I migrate to other machines.

## Clone repository
After generating your SSH keys as suggested [here](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) or [here](https://github.com/mxochicale/tools/blob/main/github/SSH.md) with few personal notes.
You can then clone the repository by typing (or copying) the following line in a terminal at your selected path in your machine:
```
cd && mkdir -p repositories/mxochicale && cd repositories/mxochicale
git clone git@github.com:mxochicale/figures.git
```

## Tools for image creation

### inkscape in Ubunut*
* Installation
```
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt update
sudo apt install inkscape
```
Alternative, you can also check https://github.com/mxochicale/tools/tree/main/inkscape for installation in other versiosn of Ubuntu!

# Usage
Once installed, you create a drawing, you can convert it easily in the terminal using the following commands!
```
make png
make pdf
make view-png #eog *.png
make view-pdf #evince *.pdf
make reduce-pdf-size dPDFSETTING=book # screen, ebook, prepress, printer and default
make edit # inkscape vector/drawing-v$NN.svg
make clean
``` 
See and download template [00_template-vector-images](00_template-vector-images/) to automatically convert svg files to png or pdf.

## Issues 
Please [open an issue](https://github.com/mxochicale/figures/issues) if you have specific questions about the content of this repository.

