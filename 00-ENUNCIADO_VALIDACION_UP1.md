# Prueba de validación UP1 — Biblioteca API

**Duración máxima:** 90 minutos. **Puntuación:** 10 puntos. **Modalidad:** individual.


> Se permite consultar las prácticas realizadas 

## Material

Se facilita:

- Repositorio de trabajo: https://github.com/espemm/validacion-up01.git
- Este enunciado
- Ayuda de comandos Git.
- Referencia visual para diseñar en Markdown

## Ejercicio 1. Git y GitHub (2 puntos)

1. Clona el repositorio y comprueba que mantiene todas las ramas incluidas en el origen.
2. Crea `VALIDACION.md` en la raíz, con tu identificador de alumno y una breve descripción del proyecto.
3. Registra los cambios con un commit descriptivo.
4. Publica el repositorio en tu GitHub.
5. Responde en `VALIDACION.md`: ¿qué diferencia hay entre `commit` y `push`?

> **Puntuación:** clonar 0,2; VALIDACION.md 0,3; commit 0,2; publicación en Github 1 y explicación 0,3.

> **Evidencias:** repositorio propio, commit e historial, respuesta.

## Ejercicio 2. Ramas e integración (2 puntos)

1. Identifica las ramas remotas `feature/docs` y `feature/openapi`.
2. Examina qué archivo aporta cada rama.
3. Integra ambas ramas en `main`.
4. Comprueba que ahora existen `docs/uso.md` y `openapi.yaml`.
5. Añade a `VALIDACION.md` qué ramas integraste y para qué sirve `git merge`.

> **Puntuación:** ramas 0,3; archivos 0,3; integrar 0,8; comprobar 0,3 y explicación 0,3.

> **Evidencias:** historial Git y archivos integrados.

## Ejercicio 3. MkDocs y Markdown (2,5 puntos)

1. Crea desde cero `mkdocs.yml` con el título **Biblioteca API** y una navegación con Inicio, Instalación y Uso.
2. Completa la maquetación de `docs/index.md` según el PDF de referencia.
3. Maqueta `docs/instalacion.md` con títulos, lista de requisitos, pasos numerados, bloque de comandos y aviso destacado.
4. Completa `docs/uso.md` con tabla de endpoints y ejemplos de peticiones.
5. Ejecuta `mkdocs serve` y `mkdocs build`. Añade `site/` a `.gitignore`.

> **Puntuación:** `mkdocs.yml` y navegación 0,6; `index.md` 0,4; `instalacion.md` 0,6; `uso.md` 0,4; comprobación y generación 0,5.

> **Evidencias:** archivos Markdown, configuración y sitio generado correctamente. Se valorará la estructura y el formato, no la coincidencia exacta de colores o tipografía.

## Ejercicio 4. Publicación en GitHub Pages (2 puntos)

1. Publica la documentación en Pages desde tu repositorio.
2. Comprueba la rama generada en GitHub y la URL pública del sitio.
3. Incluye en `VALIDACION.md` el enlace a la página y explica brevemente qué contiene la rama generada.

> **Puntuación:** publicacion y procedimiento de despliegue 1; URL accesible 0,6; rama generada y explicación 0,4.

> **Evidencias:** enlace público y rama creada.

## Ejercicio 5. API y OpenAPI (1,5 puntos)

1. Ejecuta la API Express desde `api/`.
2. Prueba `GET /api/libros`, `GET /api/libros/1` y `GET /api/libros/999` (404).
3. Corrige la indentación de `openapi.yaml` para que el endpoint ya escrito sea válido.
4. Documenta el endpoint pendiente `GET /api/libros/{id}`, incluyendo el parámetro entero `id` y las respuestas 200 y 404.
5. Explica en `VALIDACION.md` qué significa la respuesta HTTP 200.

> **Puntuación:** arranque 0,1; pruebas 0,2; indentación 0,5; nuevo endpoint 0,6; explicación 0,1.

> **Evidencias:** `openapi.yaml` corregido, pruebas realizadas y explicación.

## Entrega

Antes de finalizar, realiza los commits necesarios y publica los cambios en tu repositorio propio.

Entrega **dos enlaces**:

1. repositorio GitHub
2. sitio GitHub Pages. 

El archivo `VALIDACION.md` debe contener las respuestas solicitadas y ambos enlaces.
