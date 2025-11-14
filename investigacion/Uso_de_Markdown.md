# Documentación sobre Markdown

Este documento forma parte del repositorio de investigación sobre herramientas de documentación en proyectos de software. Aquí se detalla **qué es Markdown**, **su uso práctico** y **las ventajas de integrarlo con GitHub**.

---

## 1. ¿Qué es Markdown y por qué se utiliza en proyectos de software?

### Definición
**Markdown** es un lenguaje de marcado ligero creado por John Gruber en 2004, diseñado para escribir texto formateado de manera sencilla y legible tanto en su forma cruda como renderizada. Utiliza una sintaxis simple basada en caracteres como `#`, `*`, `-`, `>`, etc., que se convivierte automáticamente en HTML.

### ¿Por qué se utiliza en proyectos de software?
- **Legibilidad en texto plano**: Los archivos `.md` son fáciles de leer sin necesidad de renderizado.
- **Facilidad de escritura**: No requiere editores complejos; se puede escribir en cualquier editor de texto.
- **Integración con control de versiones**: Funciona perfectamente con Git y GitHub.
- **Documentación técnica**: Ideal para `README.md`, wikis, issues, pull requests y documentación de APIs.
- **Conversión multiplataforma**: Se puede exportar a HTML, PDF, etc., usando herramientas como Pandoc.
- **Estándar de facto en open source**: Usado en GitHub, GitLab, Bitbucket, npm, PyPI, etc.

---

## 2. Ejemplo práctico de uso de Markdown

Ejemplo:

markdown
# Título del Proyecto

## Características principales

- Soporte multi-plataforma
- Interfaz intuitiva
- Documentación completa
- Integración con API REST

### Tecnologías utilizadas

| Tecnología | Versión | Uso |
|------------|---------|-----|
| Node.js    | 18.x    | Backend |
| React      | 18.2    | Frontend |
| PostgreSQL | 15      | Base de datos |
| Docker     | 24.0    | Contenedores |

## Enlaces útiles

- [Documentación oficial](https://github.com)
- [Repositorio en GitHub](https://github.com/topics/repositorios)
- [Issue #42: Error en login](https://github.com/usuario/proyecto/issues/42)

## Imagen de arquitectura

![Diagrama de arquitectura del sistema](https://optim.tildacdn.net/tild3234-3066-4234-b638-306537326132/-/resize/760x/-/format/webp/markdown.png.webp)

> **Nota**: Asegúrate de tener Docker instalado antes de ejecutar `docker-compose up`.
>
> # Ventajas de Utilizar Markdown 

| # | **Ventaja** | **Descripción** |
|---|-------------|-----------------|
| 1 | **Legibilidad en texto plano** | Se lee fácilmente sin renderizar. Ideal para `README.md`, issues y wikis. |
| 2 | **Sintaxis simple y rápida** | Usa `#`, `*`, `-`, `>`, etc. No requiere HTML ni editores complejos. |
| 3 | **Portabilidad** | Archivos `.md` funcionan en cualquier editor, sistema operativo o plataforma. |
| 4 | **Control de versiones con Git** | Los cambios en documentación se versionan junto al código. |
| 5 | **Renderizado nativo en GitHub** | GitHub muestra `.md` con formato profesional automáticamente. |
| 6 | **GitHub Flavored Markdown (GFM)** | Soporta tablas, checklists, emojis, tachado y menciones. |
| 7 | **Colaboración en tiempo real** | Vista previa en pull requests y comentarios. |
| 8 | **Integración con herramientas** | Funciona con GitHub Pages, Jekyll, MkDocs, Docusaurus, Pandoc, etc. |
| 9 | **Exportable a múltiples formatos** | HTML, PDF, Word, ePub con herramientas como Pandoc. |
|10| **Estándar en open source** | Usado en npm, PyPI, GitLab, Bitbucket, Stack Overflow, etc. |
|11| **Accesible y ligero** | No depende de JavaScript. Ideal para documentación técnica. |
|12| **Mejora la mantenibilidad** | Fácil de actualizar, revisar y contribuir por cualquier desarrollador. |

---

> **Ejemplo de GFM en acción**:

- [x] Tarea completada
- [ ] Tarea pendiente

