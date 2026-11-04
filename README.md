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
detalles: "ISBN … · páginas · medidas"                # opcional
amazon: https://www.amazon.com/dp/XXXXXXXXXX          # opcional: botón "Comprar en Amazon"
editor: true                                         # opcional: botón "Comprar en Venezuela" (Luis Felipe Capriles Editor)
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

El enlace de la tienda de Luis Felipe Capriles Editor está en `_config.yml` (`editorial.url`). Un libro puede llevar su propio enlace con `editor_url:`.

## Versión en inglés

Las páginas en inglés están en `en/` (portada, biografía, libros, escritos y contacto). El botón "English" / "Español" de la cabecera cambia de idioma; cada página indica su equivalente con `alt:`. Los libros llevan su título traducido en `titulo_en:` y enlazan a su ficha en español. Si cambias un texto en español de la portada o la biografía, actualiza también su versión en `en/`.
