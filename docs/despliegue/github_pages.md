# Despliegue: GitHub Pages

Instrucciones paso a paso para la construcción y publicación de esta documentación de forma estática en la web.

## Configuración del Entorno
1.  Inicializar el framework generador de sitios estáticos (por ejemplo, MkDocs).
2.  Configurar el archivo principal (ej. `mkdocs.yml`) estableciendo el nombre del sitio y el tema.

## Proceso de Publicación
*   **Flujo manual:** Ejecutar el comando de construcción y despliegue hacia la rama `gh-pages`.
*   **Flujo automático (CI/CD):** Configurar un workflow en `.github/workflows` que compile y publique el contenido automáticamente tras cada *push* en la rama principal.