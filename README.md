# Perfumes L&R — Catálogo Réplicas 1.1

## Qué incluye esta versión

### Inicio
- **Banner 1**: foto de los fundadores (Reaul Torres y Luis Bonilla)
- **Banner 2**: presentaciones de envases ordinarios (30 / 60 / 120 ml)
- **Lo más pedido**: carrusel horizontal con **fotos** de los productos en promo (se puede tocar para agregar)

### Catálogo y carrito
- Réplicas 1.1 idénticas al original
- Envases tipo ordinario: **30 ml · 60 ml · 120 ml**
- Al agregar se elige tamaño + calidad (Normal / Premium)
- **WhatsApp corregido**: el mensaje incluye la lista completa del carrito con cantidades, tamaños y total (usa `encodeURIComponent`)

### Admin (contraseña: `lr2026`)
- Editar número de WhatsApp
- **Editar precios** de 30 / 60 / 120 ml (Normal y Premium) — se guardan en Firebase
- Agregar / editar / borrar perfumes y marcar promos

## Precios por defecto
| Tamaño | Normal | Premium |
|--------|--------|---------|
| 30 ml  | $5     | $5.5    |
| 60 ml  | $9     | $10     |
| 120 ml | $16    | $18     |

Se pueden cambiar desde el panel Admin.

## Estructura de archivos
```
index.html
README.md
images/
  banner_1.jpg
  banner_2.jpg
  1_FICHA_TECNICA_PERFUMES/   ← las 75 fichas técnicas
```

## Cómo probar WhatsApp
1. Agrega 2–3 productos al carrito (elige tamaños distintos).
2. Ve a Carrito → “Enviar pedido por WhatsApp”.
3. Debe abrirse WhatsApp con un mensaje tipo:

```
¡Hola! Quiero hacer este pedido de *Perfumes L&R* (Réplicas 1.1):

• DIOR SAUVAGE (30 ml Normal) x2 = $10.0
• LATTAFA YARA (60 ml Premium) x1 = $10.0

*Total: $20.0*

Gracias.
```

Si no abre, revisa en Admin que el número de WhatsApp esté bien (solo dígitos, con código de país, sin +).
