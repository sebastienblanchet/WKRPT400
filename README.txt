Sebastien Blanchet
April 26th 2017

MUST RUN ALL INSTALLER FILES AS ADMINSTRATOR 

First download MiKTeX (implementation of LaTeX) (install at http://www.pirbot.com/mirrors/ctan/systems/win32/miktex/setup/basic-miktex-2.9.6236-x64.exe)

Suggested LaTeX editor: Texmaker (install at http://www.xm1math.net/texmaker/texmakerwin32_install.exe)

To compile this document assure:
Options>Configure Texmaker>Quick Build>Quick Build Command: PdfLaTeX + Bib(la)tex +  PdfLaTeX(x2) + View PdF

Main File is Report.tex

Press "F1" key to peform quick build, accept all prompts to install packages

A Report.pdf file will appear in $, this is report PDF

Structure is:
	Report.tex:
		Tex/Frontpages.tex
			*contains: Title page fields + Letter of submittal
		Tex/Prematter.tex
			*contains Glossary + Summary
		Tex/Chap_guide.tex
			*Contains sections 1-7
			Section/1_Intro.tex
			Section/2_Stdrs.tex
			Section/3_Prelim.tex
			Section/4_FEA.tex
			Section/5_Disc.tex
			Section/6_Conc.tex
			Section/7_Recoms.tex
		Tex/Appendix.tex
			*contains python scripts and excel pdf
			Capstan.py
			DivVIII1.py
			DivVIII2.py
			EN134453.py
			Buckling.py
			Calcs/Uniform_p.pdf
		Biblio/Refs.bib
			*all fiels for creatin of Reference section

Note: python files to match those found in previous fodler