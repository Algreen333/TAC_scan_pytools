# Visualització en 3D
L'objectiu és convertir les màscares de l'output de la IA de detecció de tumors a models 3d.

**To-do list:**
- [x] Passar de màscares (o les imatges dels labels) a coordenades
- [x] Utilitzar les màscares directament de la IA. *Encara pendent de certs ajustos*
- [ ] Generar les cares del polígon en 3d a partir dels vèrtex
- [ ] Generar models 

<br />

***Fites opcionals:***
- [ ] Visualitzar els TAC sencers amb transparència (destacant el tumor)
- [ ] Afegir eines per visualitzar capa per capa el tumor

--- 

### 1. Mascares a coordenades
S'ha pogut realitzar directament amb python. He implementat un algoritme que troba els vèrtex del polígon que forma el tumor.

He comprovat també que hi ha eines i llibreries per python que facilment permeten generar models 3d '.stl', amb els quals es pot imprimir una maqueta amb la impresora 3d.

| Escala Real | Ampliat |
| :----: | :----: |
| ![alt text](https://github.com/Algreen333/TAC_scan_pytools/blob/main/scatter_tumor_1.gif) | ![alt text](https://github.com/Algreen333/TAC_scan_pytools/blob/main/scatter_tumor_3.png) |

| Animació |
| :---: |
| ![alt text](https://github.com/Algreen333/TAC_scan_pytools/blob/main/scatter_tumor_1.gif) |


*Les visualizacions s'han generat a partir dels labels del pancreas '0004'*
