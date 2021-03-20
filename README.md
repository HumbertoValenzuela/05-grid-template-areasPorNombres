# 05-grid-template-areasPorNombres
* Uso de grid-template-areas usando los nombres y uso de gap

```javascript
/* index2 grid-template-areas sin usar los grid-templates-column*/
.contenedor-media {
    margin: 0 auto;
    max-width: 800px;
    display: grid;
    grid-template-areas: 
    "titulo titulo titulo titulo"
    "imagen desc desc desc"
    ;
    gap: 1rem;
}


.titulo {
   grid-area: titulo;
}

.imagen {
    grid-area: imagen;
}
.descripcion {
    grid-area: desc;
}
```
