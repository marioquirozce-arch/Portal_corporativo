# Portal Corporativo TKINOV

Portal web corporativo de TKINOV, listo para publicarse en Azure como sitio estatico.

## Estructura

- `index.html`: entrada principal del sitio.
- `portaltkinov.html`: pagina principal del portal.
- `assets/`: imagenes y recursos estaticos.

## Publicacion recomendada

La opcion recomendada para este proyecto es `Azure Static Web Apps`.

## Flujo sugerido

1. Subir estos archivos al repositorio.
2. Crear una `Static Web App` en Azure.
3. Conectar Azure con el repositorio y la rama principal.
4. Configurar:
   - App location: `/`
   - Api location: vacio
   - Output location: `/`
5. Publicar y validar la URL generada por Azure.
6. Agregar dominio personalizado cuando el sitio ya este revisado.

## Archivos principales

- `index.html`
- `portaltkinov.html`
- `assets/Logo_tkinov.png`
- `.gitignore`
- `README.md`

## Notas

Los archivos `.docx` y `.pdf` de trabajo no forman parte del portal y estan ignorados en `.gitignore`.

## Siguientes mejoras sugeridas

- Cambiar el formulario para que envie correos reales.
- Agregar dominio personalizado y SSL en Azure.
- Consolidar `portaltkinov.html` dentro de una sola `index.html` final cuando el diseno quede estable.
