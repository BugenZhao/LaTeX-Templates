Put the template into ~/.local/share/pandoc/template or ~/.pandoc/template.
Then run

pandoc --pdf-engine=xelatex --template=bugen.latex --listings input.md  -o output.pdf
