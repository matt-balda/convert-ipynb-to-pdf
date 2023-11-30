# convert ipynb to PDF

1. Upload ipynb file
<br>

![Captura de tela 2023-11-30 154514](https://github.com/matt-balda/convert-ipynb-to-pdf/assets/94808306/21053fb3-5dd8-4c49-89c8-3e999f8eeacc)

2. Convert to HTML
```bash
jupyter nbconvert --to html regression22_11.ipynb
```
  Put exactly name of the upload file, **example:** regression22_11.ipynb

3. Adding fonts, styles on current machine
```
!sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
```

4. Convert to PDF
```
!jupyter nbconvert --to pdf /content/regression22_11.ipynb
```
