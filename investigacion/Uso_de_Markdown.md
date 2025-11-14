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

- [Documentación oficial](https://docs.ejemplo.com)
- [Repositorio en GitHub](https://github.com/usuario/proyecto)
- [Issue #42: Error en login](https://github.com/usuario/proyecto/issues/42)

## Imagen de arquitectura

![Diagrama de arquitectura del sistema](./assets/arquitectura.png)

> **Nota**: Asegúrate de tener Docker instalado antes de ejecutar `docker-compose up`.
