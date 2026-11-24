# Instrucciones permanentes del proyecto

## Generación de imágenes
- Cuando el usuario pida crear, generar o hacer una imagen, usa SIEMPRE la skill `generate-image` (Pollinations.ai, gratuita, sin API key), ubicada en `.claude/skills/generate-image`.
- Guarda las imágenes en `imagenes/` y haz commit y push a la rama de desarrollo de la sesión.
- Condiciones: sin claves de API, sin cuentas, sin servicios de pago ni créditos. Si el servicio exige clave, créditos o pago, detente y avisa. No uses servicios alternativos (Canva, Mage, ComfyUI, etc.) sin consultar.
- Un 503 de capacidad ("at its limit, retry after 10s") no es una exigencia de pago: reintenta una vez tras 10 s.
- Informa siempre las limitaciones reales del resultado: tamaño real, marca de agua "pollinations.ai", modelo usado si difiere del pedido y fidelidad parcial al prompt. El prompt sale a un tercero: no uses fotos ni datos privados.
- El dominio `image.pollinations.ai` debe estar en Allowed domains del entorno en la nube; si el proxy responde 403, avisa al usuario en lugar de rodear el bloqueo.

## Edición de fotografías
- Aún no hay skill de edición instalada. Busca una gratuita, sin API y sin GPU local, y revisa su contenido antes de instalarla.
