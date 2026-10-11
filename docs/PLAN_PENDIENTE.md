# Plan pendiente (lo que se quiere hacer después de separar los repos)

Estado: por ahora el foco es dividir el proyecto (tienda / admin / API). Lo de abajo queda anotado para revisarlo y hacerlo a futuro.

## Arquitectura
- [ ] Dos sitios separados que se comunican entre sí a través de esta API: **tienda** (clientes) y **admin** (panel).
- [ ] Mover el dominio a Cloudflare.

## Versión simplificada del ecommerce
- [ ] Quitar la pasarela de pago (Culqi) y la validación de DNI/RUC (API Perú), por costo.
- [ ] En su lugar: contacto directo con el dueño para negociar precios y acordar el pago.
- [ ] Quitar varias funcionalidades del admin y de la tienda (por definir cuáles).

## Mejoras técnicas
- [ ] Imágenes en WebP o AVIF (ya hay WebP con miniaturas; evaluar AVIF).
- [ ] Cachear páginas y productos para no consultar la base de datos en cada visita.
- [ ] Skeleton loaders en lugar del texto "Cargando".

## Errores conocidos
- [ ] Alineación visual del dashboard del admin (menor).
