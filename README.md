# Resume generator

These are all the files which are needed to create my own resume using LaTeX. Of course, the files can be adapted to create a resume for anybody else by editing the personal details.

I decided to share my LaTeX code with the world because many people have requested me to do it and also because I based my work in code by other people (refer to the Acknowledgments section).

In addition, by using Git, I can keep track of my changes and create different versions of my resume. LaTeX allows me to compare, add and modify every single aspect of the document, ultimatelly allowing me to do a sorts of "Resume-as-code" initiative.

You can read more about this small project in my blog: http://www.kippel.net/blog/?p=2204

### Prerequisites

Building resumes require LaTeX to be installed in your system. LaTeX is a document preparation system used for the communication and publication of scientific documents. LaTeX is free software and is distributed under the LaTeX Project Public License. For installation, please refer to: https://www.latex-project.org/get/

Install requirements:
```
sudo apt-get -qq update && sudo apt-get install -y --no-install-recommends latexmk texlive-fonts-extra texlive-fonts-recommended texlive-latex-base texlive-latex-extra texlive-latex-recommended texlive-luatex texlive-xetex texlive-pictures texlive-lang-french lmodern fonts-font-awesome
```

### Installation and deployment

Simply clone this repository to your sistem and compile using any LaTeX editor. For example:
```
latexmk -cd -f -lualatex -interaction=nonstopmode -synctex=1 cv.tex
```

This will create a file named cv.pdf, located in the same directory.

## Contributing

Feel free to edit the code and send pull requests. I can also be reached by GitHub itself or in my personal email (located in my personal details section).

## Authors

* **Alan Verdugo** - *Initial work* - [GitHub](https://github.com/alanverdugo)

## License

This project is licensed under the MIT License - [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Acknowledgements

* This project was based in Christophe Roger's template (https://github.com/darwiin/yaac-another-awesome-cv), which in turn is based in a template created by Alessandro Plasmati.
