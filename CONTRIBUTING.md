# Guía de contribución

Resumen de cómo trabajamos en los repositorios de Q·REAS Lab.

## Flujo
1. Crea una rama desde `main`: `tipo/descripcion-corta`
   (tipos: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `exp`).
2. Haz commits pequeños con Conventional Commits y mensaje en español:
   `tipo(ámbito): descripción`.
3. Abre un pull request con la plantilla y pide revisión a otro socio.
4. Nadie fusiona su propio pull request.
5. La fusión es *squash merge*; la rama se elimina después de fusionar.

## Idioma
- Documentación y mensajes de commit: español de España.
- Variables, funciones, clases e identificadores técnicos: inglés.

## Qué nunca se sube
Credenciales, claves, `.env`, datos personales o de clientes, y documentación
comercial, económica o legal. Si algo se sube por error, avisa a los
propietarios de la organización antes de intentar borrarlo.
