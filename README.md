# clustering

Ejemplos workshop: Métodos Matemáticos para la Física de Partículas. 

Hay dos notebooks jupyter con ejemplos. El de procesos de Dirichlet está vacío por el momento. 


## Instalar el kernel de R en jupyer: (necesitan conexión a internet)

Antes de programar necesitan instalar un par de cosas en sus computadoras.

Primero la última versión de R estable:

https://www.r-project.org/

Luego Anaconda:

https://anaconda.org/

#### En R (V. 3.3)
[https://github.com/IRkernel/IRkernel]

Por último abran R y copien:

install.packages(c('repr', 'IRdisplay', 'crayon', 'pbdZMQ', 'devtools'))

devtools::install_github('IRkernel/IRkernel')

IRkernel::installspec()  

IRkernel::installspec(name = 'ir33', displayname = 'R 3.3')
Como correr un Jupyter NoteBook
Abran Anaconda;

### Click en Jupyter:

Nuevo -> R 3.3
