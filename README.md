# Unofficial Poster Template for Texas A&M University. 

## Poster dimensions: 48x36 inches. 
Preview PDF [here](https://github.com/ram-bhaskara/TAMU-Poster-Template/blob/main/TAMU_Poster_Template.pdf).
<!-- [![Overleaf Template](https://img.shields.io/badge/Overleaf-Template-success?logo=overleaf)](https://www.overleaf.com/latex/templates/unofficial-poster-template-for-uchicago-computer-science/kbbmbdxwbypb) -->

A fork of Gemini. Also available on Overleaf.

![gemini_tamu](https://github.com/ram-bhaskara/TAMU-Poster-Template/blob/main/TAMU_Poster_Template.png)

## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.

