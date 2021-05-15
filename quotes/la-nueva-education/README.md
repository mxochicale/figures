# Manuel Bartolomé Cossío

## Notes
* https://laboratorios.fundacionginer.org/
* https://en.wikipedia.org/wiki/Manuel_Bartolom%C3%A9_Coss%C3%ADo
* https://es.wikipedia.org/wiki/Manuel_Bartolom%C3%A9_Coss%C3%ADo


## Usage
* save images, create svg files
```
make png #or make pdf
eog versions/drawing-v$NN.png
inkscape vector/drawing-v$NN.svg
```
where `$NN` is the version of the drawing.

## Download template
Open a terminal and type:
```
cd ~/Desktop && svn checkout https://github.com/mxochicale/images/trunk/00_template-vector-images
cd 00_template-vector-images && rm -rf .svn
```

Reference: [:link:](https://stackoverflow.com/questions/7106012/download-a-single-folder-or-directory-from-a-github-repo)
