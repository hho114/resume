# resume

A single-page, one-column resume for software developers. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.

### Motivation and Inspiration

Inspiration from [Sourabh Bajaj](https://github.com/sb2nov/resume)

Managing a resume on Google Docs was hard and changing any formatting was too difficult since it had to be applied in multiple places.

## Getting Started

- Rename huy_ho_resume.tex to yourname_resume.tex
- Edit yourname_resume.tex base on your resume
- Convert tex to pdf

## Prerequisites

- TexLive:

For Linux:
```
sudo apt-get install texlive
```

Texlive-latex-extra packages:

```
sudo apt-get install texlive-latex-extra
```

For [Mac](https://tug.org/mactex/mactex-download.html)

For [Window](http://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe)


## Convert tex to pdf on Linux Terminal

```
pdflatex yourname_resume.tex
```
