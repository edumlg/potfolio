# Portfolio Profesional — Eduardo Morillas Rodríguez

Este repositorio contiene el código fuente completo del sitio web de portfolio profesional desarrollado para la asignatura de **Desarrollo de Web y de Apps** en el **Doble Grado en Ingeniería Matemática e Informática** de la **Universidad Europea**.

- **Autor:** Eduardo Morillas Rodríguez
- **Especialización:** Machine Learning Systems, Large Language Models (LLMs) & Big Data
- **URL Pública (GitHub Pages):** [https://edumlg.github.io/potfolio/](https://edumlg.github.io/potfolio/)

---

## 📂 Contenido del Sitio Web

El sitio web está compuesto por cuatro páginas HTML5 semánticas, accesibles e independientes de hojas de estilo externas propietarias:

1. **`index.html` (Inicio):**
   - Presentación personal y perfil profesional enfocado a ML Systems Engineer.
   - Fotografía / avatar optimizada mediante elemento `<picture>` con formato moderno WebP y respaldo JPEG.
   - Lista de definición técnica (`<dl>`) con siete áreas de especialización y competencias aplicadas.
   - Tabla semántica con historial de formación universitaria oficial.
   - Selección de tres proyectos destacados con enlaces directos a sus fichas técnicas.
   - Barra lateral (`<aside>`) con estado de disponibilidad profesional y fechas estandarizadas en `<time>`.

2. **`proyectos.html` (Proyectos):**
   - Navegación interna por tres categorías especializadas: *Desarrollo Web*, *Programación y Análisis de Datos*, e *Inteligencia Artificial y Big Data*.
   - Seis fichas completas de proyectos reales y universitarios (EcoMap, AeroMap, Open Data Accidentalidad, Depreciación Tesla Model Y, TFG Detección de Intrusiones con Spark y Recomendador de Coches con Deep Learning).
   - Imágenes optimizadas en dimensiones reales (1200×669 px) con carga diferida (`loading="lazy"`).
   - Metodología de trabajo en lista ordenada anidada y tabla resumen general de proyectos con cómputo en pie de tabla.

3. **`contacto.html` (Contacto):**
   - Formulario de contacto completamente accesible estructurado mediante tres `<fieldset>` temáticos (*Tus datos*, *Tu proyecto*, *Cómo te respondo*).
   - Campos tipificados con validación nativa (`required`, `minlength`, `maxlength`, `pattern`, `autocomplete`, `aria-describedby`).
   - Selección de modalidades, servicios y canales de contacto preferentes.

4. **`sobre-mi.html` (Sobre mí):**
   - Sección *«Mi trayectoria»*: relato narrativo en dos párrafos sobre la vocación matemática e informática y cita inspiradora en `<blockquote cite="...">` con atribución.
   - Sección *«Línea de tiempo»*: lista cronológica ordenada (`<ol>`) con cinco hitos fundamentales fechados con `<time datetime="...">`.
   - Sección *«Multimedia»*: vídeo representativo incrustado de YouTube con atributo `title` descriptivo (tráiler oficial de la serie *Mr. Robot*, referente en ciberseguridad e ingeniería) y reproductor musical `<audio controls>` con título y autor.
   - Sección *«Preguntas frecuentes»*: acordeón interactivo sin JavaScript mediante cinco elementos `<details>` con `<summary>`, el primero configurado con apertura por defecto (`open`).
   - Sección *«Nivel»*: indicadores de competencia cuantitativa mediante tres elementos `<meter>` con etiquetas accesibles asociadas.

---

## 🎨 Imágenes, Iconos y Rendimiento

- **Optimización de imágenes:** Ningún archivo de la carpeta `img/` supera los 170 KB (cumpliendo holgadamente el límite de 300 KB). Todas las imágenes disponen de versión WebP de alto rendimiento y JPEG de respaldo.
- **Logotipo vectorial:** Monograma personal `img/logo.svg` incrustado mediante etiqueta `<img>` en la cabecera compartida.
- **Iconografía accesible:** Enlaces sociales y de contacto en el pie de página con iconos SVG vectoriales en línea provistos de `aria-hidden="true"` y estilo `fill="currentColor"`.
- **Open Graph y Favicon:** Metadatos completos de previsualización social (`og:title`, `og:description`, `og:image`, `og:url`) con tarjetas gráficas dedicadas de 1200×630 px y favicon de 32×32 px.

---

## 🎵 Fuentes Multimedia y Licencias

- **Vídeo incrustado (YouTube):** Tráiler oficial de la primera temporada de *Mr. Robot* (USA Network / Universal Cable Productions), recurso audiovisual sobre ciberseguridad, arquitectura de sistemas y tecnología, incrustado mediante `<iframe>` con atributo `title` accesible.
- **Audio local (`media/audio.mp3`):** *«Down Under»* por Men at Work (álbum *Business as Usual*, 1981, CBS / Columbia Records), tema musical representativo en reproductor `<audio controls>` con indicación de título y artista.
