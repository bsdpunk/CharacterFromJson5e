# Generate LaTeX PDF of character based on JSON DnD 

I stole this latex template from https://www.overleaf.com/project/5f95d40d700e190001785077

# Use

```
node gen.js character.json > character.tex
pdflatex character.tex
```

Don't have json? You can use my CreateCharacter or CreateNPC funcion in dndshell. http://github.com/bsdpunk/dndshell

Generates character.pdf

# Generate Sample

``` js
 node gen.js examples/json/cljson.json > examples.tex
 pdflatex examples.tex 
```
