# Redes de Colaboración entre Docentes en Ciencia Política de la PUCP 👨‍🏫

### Alumno: Nicolas Silva Andujar (20200832)
---------------------------------------------------------------------------

Esta repositorio consiste en el desarrollo de una red de colaboración académica entre docentes del Departamento Académico de Ciencias Sociales - Sección Ciencia Política de la Pontificia Universidad Católica del Perú. 

Con **"colaboración académica"** nos referimos al trabajo conjunto entre docentes para el desarrollo de artículos, libros, capítulos y publicaciones, en la forma de coautorías.  El trabajo parte de la hipótesis de que los docentes Principales, son quienes han desarrollado mayores redes de colaboración entre ellos. Cada categoría de docencia se obtiene progresivamente, de modo que se asume que los profesores Principales, y más antigüos, han desarrollado un sentido de comunidad así como una red de contactos académicos al interior de la especialidad. 

### **Insumos de la base de datos** 📚
___
La información de los docentes ha sido extraída del [Portal del Profesorado de la PUCP](https://www.pucp.edu.pe/profesor/), donde se ha seleccionado exclusivamente a los profesores que forman parte de la "Sección Ciencia Política". 

En lo que refiere a la producción académica, esta información ha sido extraída del mismo portal y de [Google Scholar](https://scholar.google.com/). Para ello, se ha utilizado el paquete [*scholarly*](https://pypi.org/project/scholarly/). La información obtenida ha sido organizada manualmente a través de *Google Sheets* en la forma de una **matriz de adyacencia**.

### **Leyenda** 🧭
___
|**Categoría**| **Elemento**                  | **Descripción**                                                                                                                         |
|-------|---------------------------|------------------------------------------------------------------------------------------
|**Principal**| **Nodos Azules 🔵**          | Docentes ordinarios principales, nombrados por un periodo de 7 años. Pueden integrar órganos de gobierno y comisiones universitarias. Suelen ser los de mayor antigüedad.  |
|**Asociado**| **Nodos verdes 🟢**          | Docentes asociados ordinarios, nombrados por un periodo de 5 años. Pueden integrar órganos de gobierno y comisiones universitarias. |
|**Auxiliar**| **Nodos Rojos 🔴**           |  Docentes auxiliares ordinarios, nombrados por un periodo de 3 años. Pueden integrar órganos de gobierno y comisiones universitarias.  |
|**Contratado**| **Nodos Amarillos 🟡** | Los profesores contratados mantienen un vínculo laboral con la PUCP, en las condiciones que fija el respectivo contrato. Durante el período de su contratación tienen derecho a participar en los concursos para plazas de profesor ordinario que la Universidad convoque periódicamente |


![Red de Docentes](network_teachers.png)

___

**Enlace**: https://nicosil02.github.io/Tarea_Networks/PoliticalScience_Teachers.html
