# Drawing figures

## Notes
> to add notes of the version of the drawings or some sort of message related to the vector files

## Usage 
```
make png
make pdf
make view-png #eog *.png
make view-pdf #evince *.pdf
make reduce-pdf-size dPDFSETTING=book # screen, ebook, prepress, printer and default
make edit # inkscape vector/drawing-v$NN.svg
make clean
```

## tree file and file size
```
tree -s
[       4096]  .
├── [       1771]  Makefile
├── [       4096]  outputs
│   ├── [       8378]  drawing-v00.pdf
│   ├── [      30203]  drawing-v00.png
│   ├── [       9015]  drawing-v00_reduced_size.pdf
│   └── [         70]  README.md
├── [        508]  README.md
├── [       4096]  references
│   └── [         15]  README.md
└── [       4096]  vectors
    └── [       6982]  drawing-v00.svg

3 directories, 8 files

```

## Download template
Open a terminal and type:
Download [https://ssgithub.com/mxochicale/figures/tree/main/00_template-vector-images](https://ssgithub.com/mxochicale/figures/tree/main/00_template-vector-images)
```
unzip 00_template-vector-images.zip
```

# References
https://stackoverflow.com/questions/7106012/download-a-single-folder-or-directory-from-a-github-repo
