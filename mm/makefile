all:
	latexmk -C
	rm -f cv_mm_quant.{aux,log,out,fdb_latexmk,fls} cv_mm.pdf
	latexmk -pdf -f -interaction=nonstopmode -file-line-error cv_mm.tex

setup:
	sudo apt-get install -y texlive-latex-extra texlive-fonts-extra latexmk
