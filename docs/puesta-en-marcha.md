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

Instalado: GTM-MVGKRKHM con banner y bloqueo previo (solo carga tras aceptar).
Comprobado en producción el 13/11/2026: sin aceptar no se descarga nada de
Google; al aceptar carga el contenedor y GA4 (`_ga_2HPLPTDR3N`); al retirar el
consentimiento se borran las `_ga`.

- [ ] En GTM: que GA4 viva **solo** en el contenedor (la web entrega por
      `delivery: 'gtm'`, nunca también por gtag en el código).
- [ ] En GTM: etiqueta de evento GA4 para `generate_lead` (con `form_id`:
      `newsletter` o `contacto`) y marcarlo como evento clave en GA4.
- [ ] En GA4: registrar como dimensiones `form_id`, `page_type` y `traffic_type`
      y activar el filtro de tráfico interno.
- [ ] Quien trabaje en la web: abrirla una vez con `?equipo=1` en cada
      navegador para que sus visitas no cuenten.

## Netlify

- [ ] El CMS de `/admin` y la recuperación de contraseña se han quitado (eran de
      otro proyecto y no funcionaban). Si Netlify Identity sigue activado en el
      panel del sitio, desactivarlo.

## Datos legales

- [ ] `global_index.json` tiene `legal_nif_titular` y `legal_direccion_titular` con
      texto de relleno: el aviso legal está obligado a mostrarlos (LSSI art. 10).
