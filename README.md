# Evaluacion Parcial N1 - Pipeline DevOps

## 1. Modelo de Ramificacion
Seleccionamos **GitFlow** porque permite un aislamiento claro entre el codigo listo para produccion (`main`), la rama de integracion continua (`develop`), y el desarrollo de nuevas funciones (`feature/`) o arreglos urgentes (`hotfix/`).

## 2. Convenciones del Proyecto
* **Naming de Ramas:** `feature/nombre-funcionalidad`, `hotfix/nombre-bug`.
* **Commits (Conventional Commits):** `feat:` para funcionalidades, `fix:` para arreglos, `docs:` para documentacion.
* **Merge:** Todos los cambios pasan por Pull Request obligatorio con revision.

## 3. Declaracion de Uso de IA
* **Herramienta:** ChatGPT / Gemini para estructuracion de sintaxis YAML y apoyo en la guia de comandos.

## 4. Reflexiones Individuales (Obligatorio)
* **Estudiante 1 (Marcos Necul):** En este trabajo aprendí lo importante que es seguir un flujo de trabajo ordenado como GitFlow. Al principio no tenía experiencia usando tantas ramas. Pero al simular las features y el hotfix, entendí cómo se trabaja en un ambiente profesional para no afectar el código principal de producción. También, al configurar GitHub Actions, vi lo útil que es la integración continua para revisar los cambios de forma automática.
* **Estudiante 2 (Ignacio Pilar):** Lo más importante que aprendí en esta actividad fue entender cómo funcionan los Pull Requests y las reglas para trabajar en equipo. Probar la automatización con GitHub Actions me ayudó a ver para qué sirve DevOps en proyectos reales. Así se asegura que el código que se sube a develop o main siempre esté revisado.
