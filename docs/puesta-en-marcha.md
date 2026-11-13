# Puesta en marcha: lo que no se hace desde el código

Revisión del 13/11/2026. Lo que está aquí no se arregla con un commit: si no se
marca la casilla, no está hecho.

## Al publicar este cambio

- [ ] Comprobar en producción que `/assets/static/images/hero-poster-tododiscapacidad.webp`
      y `/assets/static/images/og-tododiscapacidad.jpg` devuelven 200.
- [ ] Comprobar con `curl -I` que `/assets/fonts/...` sale con `max-age=31536000`
      e imágenes con `max-age=2592000` (si no, `_headers` no se ha copiado).
- [ ] Netlify > Forms: confirmar que aparece el formulario **newsletter** y hacer
      una suscripción de prueba. Activar el aviso por correo de envíos nuevos.
- [ ] Netlify > Forms: si ya hay un proveedor de newsletter (Mailchimp, Brevo,
      Substack...), conectar o exportar desde ahí. Hasta ahora los envíos se perdían.

## Search Console

- [ ] Enviar `https://tododiscapacidad.com/sitemap.xml` (si no está ya).
- [ ] Pedir reindexación de las páginas cuya meta descripción o título ha cambiado:
      portada, ayudas-prestaciones, incapacidad-permanente, patrimonio-protegido,
      sentencias, sobre-pedro-lopez-cerro, blog y los cuatro artículos.
- [ ] Pasar la portada y un artículo por la prueba de resultados enriquecidos.

## Analítica y cookies (pendiente de decidir)

- [ ] Hoy **no hay ninguna medición** instalada (`tag_manager` vacío en
      `src/_data/global_index.json`), pero `/legal/cookies/` dice que se usa
      Google Analytics y que navegar equivale a consentir. Las dos cosas a la vez
      están mal: o se quita GA de la política, o se instala GA4 con banner de
      consentimiento previo (rechazar tan fácil como aceptar).
- [ ] Si se instala: GA4 recibe datos de **una sola fuente** (código o Tag Manager,
      no los dos) y la suscripción a la newsletter se marca como conversión.

## Restos de otro proyecto (Magna Urbis)

- [ ] `src/admin/index.html`, `src/admin/config.yml` y `src/pages/password-recovery.md`
      siguen con textos y estilos de magnaurbis.com.
- [ ] `global_index.json` tiene `legal_nif_titular` y `legal_direccion_titular` con
      texto de relleno: el aviso legal está obligado a mostrarlos (LSSI art. 10).
