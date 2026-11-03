# Rafael Tomás Caldera

Sitio de [rafaeltomascaldera.com](https://rafaeltomascaldera.com): vida y obra del filósofo y profesor Rafael Tomás Caldera.

Está hecho con Jekyll y se publica gratis con GitHub Pages, igual que venezuelaentrelineas.com. Cada cambio en la rama `main` queda publicado en uno o dos minutos.

## Agregar un libro

Crea un archivo en `_libros/` (por ejemplo `titulo-del-libro.md`):

```markdown
---
title: "Título del libro"
anio: 2024
ediciones: "Caracas, Editorial, 2024"
tema: "Amor y persona"        # o: Metafísica y conocimiento, Educación y universidad, Cultura venezolana, Lectura y escritura, Biblioteca Caldera
resumen: "Una frase sobre el libro."
portada: /assets/img/portadas/titulo-del-libro.jpg   # opcional
---

Reseña o sinopsis del libro.
```

## Agregar un artículo, discurso o entrevista

Crea un archivo en `_textos/` con el nombre `AAAA-MM-DD-titulo.md`:

```markdown
---
title: "Título"
tipo: articulo        # articulo, academico, discurso o entrevista
date: 2026-05-22
fuente: "Revista SIC"
enlace: https://...
---
```

## Páginas

- `index.html`: portada. `biografia.md`, `libros.html`, `ensayos.html`, `discursos.html`, `prensa.html`, `contacto.md`.
- `assets/css/style.css`: estilos. Imágenes en `assets/img/`.
