# morning_checklist

El listado del checklist ahora vive en `checklist.yaml` para editarlo facilmente sin tocar JavaScript.

## Editar el checklist

1. Abre `checklist.yaml`.
2. Edita secciones dentro de `sections` (`key`, `title`, `icon`).
3. Dentro de `items`, puedes usar:
	- `checkbox` (por defecto): `id`, `text`
	- `meal-title`: `text`
	- `nutrient`: `id`, `label`, `placeholder`, `aria_label`

## Ejecutar

Para que el navegador pueda cargar el YAML con `fetch`, abre el proyecto con un servidor local (no directamente con `file://`).