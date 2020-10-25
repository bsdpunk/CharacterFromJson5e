# Generate LaTeX PDF of character based on JSON DnD 

I stole this latex template from https://www.overleaf.com/project/5f95d40d700e190001785077

# Use

```
node gen.js character.json > character.tex
pdflatex character.tex
```

Generates character.pdf

# Generate Sample

``` js
 node gen.js examples/json/cljson.json > examples.tex
 pdflatex examples.tex 
```
