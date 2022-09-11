# c-intro-and-ref-mirror
Mirror of https://git.savannah.nongnu.org/cgit/c-intro-and-ref.git/

# Generate html and pdf files
```
sudo apt update
sudo apt install texlive-latex-extra
sudo apt install ghostscript
sudo apt install texinfo

makeinfo --html -v c.texi -o c.html --no-split

texi2pdf c.texi
```
