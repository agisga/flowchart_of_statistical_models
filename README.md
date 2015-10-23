# A flowchart of statistical models

![This is a JPG image of the flowchart](flowchart.jpg)

The flowchart is done in LuaLaTeX with the *tikz* package. I want to extend it further. 
:point_right: Any contributions, suggestions and criticism are very welcome. :tada:

Compilation and generation of the JPG image:

```
lualatex flowchart.tex
pdftops -eps flowchart.pdf
convert -density 200 flowchart.eps flowchart.jpg
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/agisga/flowchart_of_statistical_models" property="cc:attributionName" rel="cc:attributionURL">Alexej Gossmann</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
