MDFILE=3-ponteiros.md
OUTHTML=index.html
OUTPDF=3-ponteiros.pdf

all: deps
    #    --filter pandoc-source-exec --filter pandoc-katex --css katex.min.css
	/usr/bin/pandoc --verbose -s --self-contained -V theme=beige -s -t revealjs \
	$(MDFILE) -o $(OUTHTML) --slide-level 2 # --toc
	#
	/usr/bin/pandoc --verbose -s --self-contained $(MDFILE) -o single_$(OUTHTML) --slide-level 2
	#
	echo "making pdf now"
	#
	#
	# -F pandoc-crossref
	# --filter pandoc-latex-color --filter pandoc-source-exec  -H header.tex \
	/usr/bin/pandoc --verbose --toc -s --self-contained -V theme:Warsaw -t beamer \
	      -H header.tex \
			$(MDFILE) -o $(OUTPDF) --slide-level 2

#--filter pandoc-source-exec

run:
	python3 -m http.server 8081
	#python2 -m SimpleHTTPServer 8081

env:
	source ~/.cargo/env
	conda activate

deps:
	wget -nc https://cdn.jsdelivr.net/npm/katex@0.11.1/dist/katex.min.css
	#wget -nc https://github.com/hakimel/reveal.js/archive/master.tar.gz
	#tar -xzvf master.tar.gz && mv reveal.js-master reveal.js
