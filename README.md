# Migmaq Lessons
Repository for website hosting Mi'gmaq language lessons.

# How tos
* Site Plan [(pdf)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/siteplan.pdf?raw=true)
* How to Add a Webpage [(pdf)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Add a Webpage.pdf?raw=true) [(edit)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Add a Webpage.docx?raw=true)
* How to Use Jekyll [(pdf)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Use Jekyll.pdf?raw=true) [(edit)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Use Jekyll.docx?raw=true)
* How to Use Version Control [(pdf)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Use Version Control.pdf?raw=true) [(edit)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to Use Version Control.docx?raw=true)
* How to write a lesson [(pdf)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to write a lesson.pdf?raw=true) [(edit)](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/How to write a lesson.docx?raw=true)
* [UsefulCodeSnippets.txt](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/UsefulCodeSnippets.txt?raw=true)
* [XMLconventions.txt](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/XMLconventions.txt?raw=true)
* [audio_list.html](https://github.com/OpenSourceFieldlinguistics/MigmaqLessons/blob/gh-pages/documentation/audio_list.html?raw=true)




Directory structure:

Source code:
 *	data: contains the xml, xslt, and python files used to generate the webcode.

Media:
 *	audio: audio recordings by Mi'gmaq speakers
 *	emoji: small imgs that accompany a line in lessons
 *	img: images used on site

Styles:
 *	css: CSS code. All changes should be made to custom.css, not the Bootstrap files.
 *	fonts: fonts for the site
 *	js: Javascript code

Documentation:
 *	documentation: website plans and documentation. These files do not appear on the website

Generated webfiles:
 *	sections: webpages for each section of the curriculum; generated by big.py
 *	units: webpages for each unit of the curriculum; generated by big.py
 *	lessons: webpages for each language lesson; generated by big.py
 *	dialogs: webpages for each dialog; generated by big.py
 *	vocabs: webpages for each vocab section; generated by big.py

Jekyll:
 *	_site: contains the actual website code; auto-generated by running jekyll build
 *	_layouts: contains Jekyll layouts to be applied to webfiles
 *	_includes: code snippets that Jekyll pastes into webfiles

To build the website, run `$ make`. The Makefile will run the python scripts if necessary and build Jekyll. 

Jekyll output should not be committed to this repository, only source code.

This repository is now public, since we have permission to use the audio files.

The website is found at http://learn.migmaq.org
