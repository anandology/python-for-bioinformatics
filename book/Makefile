
.PHONY: default
default: sync

build:
	quarto render

sync: build
	rsync -avz _book/* anandology.com:/var/www/anandology.com/python-for-bioinformatics/