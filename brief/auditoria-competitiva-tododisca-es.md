# Auditoría SEO Competitiva: tododisca.es vs. TodoDiscapacidad.com

> Análisis preparado el 23 de mayo de 2026 para guiar la estrategia SEO de TodoDiscapacidad.com.

## 1. Resumen ejecutivo

tododisca.es es un competidor formidable en superficie pero vulnerable en profundidad jurídica. Es la versión .es de Tododisca SL (matriz tododisca.com, ~3-4M visitas/mes según SimilarWeb, premio Autónomo del Año 2025), un medio digital generalista sobre discapacidad, prestaciones y sociedad con sede en Jerez de la Frontera, dirigido por Francisco Zuasti.

Publica entre 10 y 16 piezas al día (sitemap de noticias muestra 18 URLs en las últimas ~24h), usa WordPress + tema JNews + Rank Math, y monetiza con publicidad programática agresiva. Su contenido jurídico es derivado: noticias sobre sentencias y resúmenes de prestaciones escritos por periodistas (Álvaro Gutiérrez del Álamo, Alejandro Perdigones, "Fran", "Pepe"), sin firmas con credenciales legales.

**Ahí está la grieta.** TodoDiscapacidad.com, liderado por el abogado Pedro López Cerro, puede ganar terreno atacando:

- (a) Keywords jurídicas de cola larga donde la profundidad y E-E-A-T legal importan más que la frescura noticiosa.
- (b) Guías evergreen con autoridad de abogado en activo.
- (c) Territorios temáticos que tododisca.es trata superficialmente (capacidad jurídica Ley 8/2021, patrimonio protegido, fiscalidad, asistencia personal, reclamaciones INSS paso a paso).

La estrategia debe ser **nicho profundo y firmado, no volumen**.

## 2. Perfil del competidor

| Campo | Dato |
|---|---|
| Dominio | tododisca.es (réplica/satélite de tododisca.com) |
| Empresa | Tododisca SL, CIF B11968526, Jerez de la Frontera (Cádiz) |
| CEO | Francisco Zuasti (lesión medular cervical, 90% discapacidad, Premio Autónomo del Año 2025 ATA) |
| Equipo editorial | 4-5 autores visibles en `/author-sitemap.xml`: alvaro, fran, alejandroperdigones, admin, pepe. Sin credenciales jurídicas firmadas |
| Stack | WordPress + tema JNews + Rank Math SEO |
| Frecuencia | 10-16 posts/día, 7 días/semana (cadencia industrial) |
| Volumen | ~15 post-sitemaps con ~1.000 URLs cada uno = ~15.000+ URLs indexadas estimadas |
| Categorías principales | `/prestaciones/`, `/discapacidad/`, `/accesibilidad/`, `/deporte-adaptado/`, `/sociedad/`, `/entrevistas/`, `/buenas-practicas/` |
| Modelo de negocio | Publicidad display programática (alta densidad), tráfico SEO, Google News |
| Indexación Google News | Sí, tiene `news-sitemap.xml` activo |
| Schema implementado | Article, WebSite, WebPage, Person, Place, PostalAddress, SearchAction, ImageObject |
| Autoridad/menciones | Premio ATA 2025 entregado por Díaz Ayuso; entrevistas en El Mira, Andalucía Información; proyecto GoFrama |

### Fortalezas

- Marca consolidada (Tododisca) con tráfico cruzado desde tododisca.com.
- Frescura: publican varias noticias al día; ganan SERPs noticiosos.
- Indexación rápida vía Google News.
- Schema y SEO técnico bien resueltos (Rank Math).
- Cobertura amplia: prestaciones, sociedad, accesibilidad, deporte, entrevistas.
- CEO con historia personal poderosa (silla de ruedas, premio nacional) que aporta autoridad humana al medio.

### Debilidades

- Contenido jurídico escrito por periodistas, no abogados.
- Headlines clickbait ("Lo que dicen los expertos…", "Hacienda confirma…") en lugar de análisis legal.
- Baja profundidad: artículos centrados en una sentencia anecdótica sin guía de proceso/recurso.
- Densidad publicitaria muy alta (perjudica UX y Core Web Vitals).
- Sin actores autorizados (no `Lawyer`/`Attorney` schema, no autores con `jobTitle` jurídico).
- Solapamiento canibalizador con tododisca.com (riesgo de contenido duplicado).
- Cobertura del cupón de la ONCE y noticias de famosos diluye el foco temático.
- `<h1 style="display:none;">Tododisca</h1>` en home: oculta H1, mala práctica.

## 3. Análisis técnico SEO de tododisca.es

**Lo bueno**

- `robots.txt` correcto, sitemaps anidados (`sitemap_index.xml` + `news-sitemap.xml`).
- URLs limpias con categoría en el path.
- Schema Article completo con `author`, `publisher`, `datePublished`, `dateModified`.
- HTTPS, dominio consolidado, lastmod actualizados.
- Imágenes con `srcset` responsive.

**Lo malo**

- H1 oculto en home (mala señal SEO/accesibilidad).
- Meta description homepage genérica, sin keywords jurídicas.
- Densidad publicitaria daña LCP/CLS percibido.
- Autores sin schema `Person` con credenciales (`alumniOf`, `knowsAbout`, `jobTitle`).
- Ausencia de FAQ schema y HowTo schema en artículos de prestaciones.

**Oportunidades para TodoDiscapacidad**

- tododisca.es no marca contenido como `LegalService` ni firma con `Attorney`/`Lawyer` schema → TodoDiscapacidad puede dominar con schema E-E-A-T jurídico bien resuelto.
- Profundidad: artículos de 2.500-4.000 palabras con índice, FAQ y CTA "consulta al abogado" superarán los 800-1.500 palabras de tododisca.es.
- Velocidad: un sitio Eleventy estático bien optimizado es estructuralmente más rápido que WordPress + JNews + ads.

## 4. Análisis de contenido de tododisca.es

**Tipologías que publican**

1. Noticia de sentencia comentada ("El Supremo unifica doctrina…").
2. Pieza humana / historia personal.
3. Anuncios de prestaciones / cambios normativos.
4. Resultado del cupón de la ONCE (relleno SEO diario).
5. Buenas prácticas y entrevistas a deportistas/activistas.
6. Notas de prensa institucionales reescritas.

**Frecuencia editorial:** 10-16 piezas/día, 7/7. Industrial.

**Profundidad media:** 600-1.200 palabras, formato noticia con párrafos cortos, sin tablas comparativas ni esquemas de proceso paso a paso.

**Calidad jurídica:** Baja-media. Los textos describen sentencias pero no analizan el iter procesal (reclamación previa al INSS → demanda en lo Social → recurso de suplicación → casación), no explican plazos de prescripción, ni redactan modelos.

## 5. Análisis de palabras clave

**Keywords donde tododisca.es posiciona en página 1:**

- "incapacidad permanente absoluta 2026"
- "beneficios fiscales discapacidad 33%"
- "pensión viudedad 2026 cuantía máxima"
- Long-tail noticiosas: "supremo incapacidad permanente sentencia X"

**Keywords donde NO domina** (los SERPs los lideran despachos y aseguradoras):

- "incapacidad permanente absoluta requisitos" → dominan Campmany Abogados, Lexway, Conceptos Jurídicos.
- "patrimonio protegido discapacidad" → dominan Agencia Tributaria, CaixaBank, BBVA, asesorías.
- "ley 8/2021 capacidad jurídica" → dominan BOE, Iberley, Legaltoday, Noticias Jurídicas.
- "asistente personal ley dependencia" → dominan Junta de Andalucía, PREDIF, Plena Inclusión.

**Conclusión clave:** Las SERPs jurídicas españolas premian a despachos especializados y portales legales, no a medios generalistas. Esa es la puerta de entrada de TodoDiscapacidad.com.

## 6. Gaps de contenido detectados (priorizados)

1. **Ley 8/2021 sobre capacidad jurídica: guía operativa.**
2. **Patrimonio protegido: cómo constituirlo paso a paso (notaría, aportaciones, fiscalidad).**
3. **Reclamación previa al INSS modelo descargable.**
4. **Recursos contra denegación de grado de discapacidad.**
5. **CUME tras la flexibilización del Supremo 2026 (sin ingreso hospitalario).**
6. **Compatibilidades: IPA + trabajo, IPT + paro, PNC + herencia.**
7. **Fiscalidad IRPF de pensiones por incapacidad: cuáles tributan y cuáles no.**
8. **Hipoteca inversa para personas con discapacidad.**
9. **Herencias y legados a favor de hijos con discapacidad.**
10. **Despido durante incapacidad temporal: nulidad y procedimiento.**
11. **Adaptación de puesto de trabajo por discapacidad sobrevenida.**
12. **Asistencia personal: cómo solicitarla, cuantías por CCAA, modelos de contrato.**
13. **Tarjeta de estacionamiento para personas con movilidad reducida: requisitos por CCAA.**
14. **Pensión de orfandad por incapacidad permanente del huérfano mayor de 21.**
15. **Revisión del grado de discapacidad: cómo recurrir si te lo bajan.**
16. **Discapacidad sobrevenida y pensión de jubilación anticipada.**
17. **Discapacidad y separación/divorcio: pensión compensatoria, custodia.**
18. **Accesibilidad obligatoria en comunidades de propietarios: derechos y costes.**
19. **Bono Social Térmico y Bono Social Eléctrico con discapacidad: tramitación 2026.**
20. **Modelos de testamento con sustitución fideicomisaria especial para hijos con discapacidad.**

## 7. Comparativa TodoDiscapacidad vs. tododisca.es

| Dimensión | tododisca.es | TodoDiscapacidad.com |
|---|---|---|
| Autoría | Periodistas sin credencial jurídica | Abogado en activo (Pedro López Cerro), firma real |
| E-E-A-T legal | Bajo (no hay schema Attorney/LegalService) | Alto si se ejecuta bien |
| Frecuencia | 10-16 piezas/día | 2-3 piezas/semana (suficiente si son evergreen profundas) |
| Volumen URL | 15.000+ | Decenas (al inicio) |
| Velocidad | WP + tema pesado + ads | Eleventy estático, ventaja estructural |
| Profundidad | 600-1.200 palabras | 2.500-4.000 palabras objetivo |
| Tipo de contenido | Noticia + historia humana | Guía jurídica + análisis + plantilla |
| Monetización | Display ads | Captación de leads jurídicos |
| Intención de búsqueda objetivo | Informativa / noticiosa | Comercial / transaccional (alto valor) |

## 8. Plan de batalla 6 meses

### Quick wins (mes 1)

Keywords realistas para entrar rápido:

- "modelo reclamación previa INSS incapacidad permanente"
- "cómo recurrir denegación grado discapacidad"
- "CUME sin ingreso hospitalario 2026"
- "patrimonio protegido discapacidad cómo constituirlo"
- "incapacidad permanente absoluta y trabajar"
- "herencia hijo con discapacidad sustitución fideicomisaria"
- "despido durante baja por incapacidad temporal nulidad"

Formato: guía de 2.500-3.500 palabras, índice clicable, FAQ Schema, autoría firmada por Pedro López Cerro con schema `Person`/`Attorney`, CTA a consulta.

### Medium plays (meses 2-3)

- "revisión grado discapacidad cómo recurrir"
- "asistente personal solicitud Andalucía/Madrid/Cataluña" (replicar por CCAA)
- "fiscalidad pensión incapacidad permanente IRPF"
- "pensión orfandad incapacidad mayor 21 años"
- "tarjeta estacionamiento discapacidad requisitos [CCAA]"
- "adaptación puesto trabajo discapacidad sobrevenida"
- "ley 8/2021 medidas de apoyo cómo solicitar"

Formato: cluster temático interlinkado. Una pieza pilar + 4-6 satélites por tema.

### Long-term plays (meses 4-6+)

- "incapacidad permanente absoluta requisitos"
- "patrimonio protegido discapacidad"
- "ayudas discapacidad 2026"
- "grado discapacidad 33 beneficios"
- "pensión no contributiva invalidez"

Estrategia: contenido pilar de >4.000 palabras con esquema, tabla comparativa, vídeo del abogado, descargables PDF y backlinks de asociaciones.

### Keywords donde NO competir (por ahora)

- "discapacidad" (excesivamente genérica).
- "cupón ONCE" y derivados.
- Noticias de actualidad diarias.
- "ayudas dependencia" puras (territorio del IMSERSO).
- Famosos con discapacidad.

## 9. 20 keywords objetivo concretas

| # | Keyword | Intención | Volumen est. | Dificultad (1-10) | Tipo de contenido |
|---|---|---|---|---|---|
| 1 | modelo reclamación previa INSS incapacidad permanente | Transaccional | Medio | 4 | Guía + plantilla descargable PDF |
| 2 | cómo recurrir denegación grado de discapacidad | Transaccional | Medio | 4 | Guía paso a paso + FAQ |
| 3 | CUME sin ingreso hospitalario | Informativa-comercial | Bajo | 3 | Análisis de la sentencia TS + cómo solicitarla |
| 4 | patrimonio protegido discapacidad cómo constituir | Comercial | Medio | 6 | Guía notarial + ventajas fiscales |
| 5 | incapacidad permanente absoluta y trabajar | Informativa | Alto | 6 | Guía de compatibilidades + jurisprudencia |
| 6 | despido durante baja incapacidad temporal nulidad | Transaccional | Medio | 5 | Análisis jurídico + plantilla demanda |
| 7 | herencia hijo con discapacidad cómo planificar | Comercial | Bajo-medio | 4 | Guía sucesoria + sustitución fideicomisaria |
| 8 | revisión grado discapacidad bajada cómo recurrir | Transaccional | Medio | 4 | Guía + plazo + dictamen pericial |
| 9 | asistente personal ley dependencia cómo solicitar | Informativa | Medio | 5 | Guía nacional + cuantías por CCAA |
| 10 | fiscalidad pensión incapacidad absoluta IRPF | Informativa | Medio | 5 | Guía con casuística + ejemplos |
| 11 | adaptación puesto trabajo discapacidad sobrevenida | Informativa-comercial | Bajo-medio | 4 | Guía laboral + cita art. 25 LPRL |
| 12 | pensión orfandad incapacidad mayor 21 | Informativa | Bajo | 3 | Guía + jurisprudencia |
| 13 | ley 8/2021 medidas de apoyo cómo solicitar | Informativa | Bajo-medio | 4 | Guía civil + plazos + modelo |
| 14 | tarjeta estacionamiento discapacidad madrid (y por CCAA) | Transaccional | Alto agregado | 4 | Cluster regional |
| 15 | hipoteca inversa persona con discapacidad | Comercial | Bajo-medio | 5 | Guía financiera-jurídica |
| 16 | accesibilidad comunidad vecinos quién paga obras | Informativa-comercial | Medio | 4 | Análisis LPH + jurisprudencia |
| 17 | bono social térmico discapacidad 2026 | Transaccional | Medio | 4 | Guía con requisitos y plazos |
| 18 | grado discapacidad 65 ventajas y ayudas | Informativa | Alto | 6 | Guía exhaustiva + tabla |
| 19 | incapacidad permanente revisión por mejoría defensa | Transaccional | Bajo-medio | 4 | Guía + estrategia procesal |
| 20 | testamento hijo discapacidad sustitución fideicomisaria | Comercial | Bajo | 3 | Guía sucesoria especializada |

## 10. Recomendaciones tácticas

### Contenido y producto editorial

- Adopta el formato "guía firmada por abogado": índice, tiempo de lectura, fecha de última revisión, autoría con foto y credenciales, FAQ al final con FAQPage Schema.
- En cada artículo de keyword transaccional, ofrece un PDF descargable (modelo de reclamación previa, modelo de recurso, checklist documental). Captura emails y refuerza E-E-A-T.
- No compitas a volumen; compite a profundidad. 2-3 guías evergreen/semana de altísima calidad supera a 80 noticias/semana de tododisca.es en SERPs jurídicas.
- Crea clusters: un pilar (Incapacidad permanente) + 8-12 satélites con interlinking interno.
- Aprovecha sentencias recientes: cuando el Supremo dicte doctrina, publica una guía operativa "qué cambia y qué hacer ahora" en 24-48h.

### E-E-A-T y schema

- Schema `Attorney`/`LegalService` en home/about y schema `Person` con `jobTitle`, `worksFor`, `alumniOf`, `memberOf` en el perfil de Pedro.
- En artículos, schema `Article` con `author` apuntando al perfil del abogado.
- "About the author" al final de cada pieza con foto, bio, redes y colegio profesional.
- Página dedicada de "Política editorial" y "Política de correcciones".

### Velocidad y técnica

- Mantén el sitio estático (Eleventy). Ventaja competitiva directa.
- Imágenes WebP + `loading="lazy"` + dimensiones explícitas.
- Sitemap por tipo: posts, guías, autores.
- HSTS, security headers, hreflang `es-ES` declarado.

### Link building

- Pacta con asociaciones (COCEMFE, CERMI, Plena Inclusión, FAMMA) intercambio de enlaces vía colaboraciones.
- Contribuye a portales legales (Legaltoday, Noticias Jurídicas, Confilegal) con artículos firmados.
- Participa en foros profesionales y newsletters de derecho laboral/civil.
- HARO/Help a B2B Writer: responde como fuente experta a periodistas españoles.

### Redes sociales y multimedia

- LinkedIn personal del abogado como canal principal (audiencia jurídica y prescriptora).
- YouTube/Shorts con vídeos explicativos cortos (2-3 min) por keyword.
- Newsletter quincenal con análisis de la última sentencia relevante.

### Defensa frente a tododisca.es

- No intentes ganarles en noticia diaria. Pierdes.
- Cuando tododisca.es publique una noticia sobre sentencia, publica tú una **guía operativa** derivada con título tipo "Qué significa la sentencia X y cómo aplicarla si estás en la situación Y". Tu pieza durará años, la suya 72 horas.
- Monitoriza sus URLs con `site:tododisca.es [keyword]` mensualmente y detecta dónde rankean superficialmente: ahí ataca con profundidad.

### KPIs a 6 meses (objetivos realistas)

- 80-120 URLs indexadas de alta calidad.
- 30-50 keywords en Top 20.
- 8-15 keywords en Top 10 (especialmente las de dificultad 3-4).
- 5-10 backlinks dofollow desde sitios DA40+ del nicho jurídico/social.
- 2.000-5.000 visitas orgánicas mensuales al mes 6 (escalable a partir de ahí).
- 30-60 leads de consulta jurídica/mes desde formularios de descarga.

---

## Fuentes consultadas

- [tododisca.es Quiénes somos](https://tododisca.es/quienes-somos/)
- [tododisca.es robots.txt y sitemap_index.xml](https://tododisca.es/sitemap_index.xml)
- [Andalucía Información - Francisco Zuasti Autónomo del Año 2025](https://www.andaluciainformacion.es/articulo/jerez-empresas/el-jerezano-francisco-zuasti-director-de-tododisca-autonomo-del-ano-en-prensa-en-espana/202507281409533121453.html)
- [Semrush - tododisca.com overview](https://www.semrush.com/website/tododisca.com/overview/)
- [BOE - Ley 8/2021 capacidad jurídica](https://www.boe.es/buscar/act.php?id=BOE-A-2021-9233)
- [Agencia Tributaria - Patrimonios protegidos discapacidad](https://sede.agenciatributaria.gob.es/Sede/ciudadanos-familias-personas-discapacidad/patrimonios-protegidos-prevision-social-personas-discapacidad.html)
- [Iberley - Supremo flexibiliza CUME ingreso hospitalario](https://www.iberley.es/noticias/el-supremo-flexibiliza-requisito-ingreso-hospitalario-cume-36391)
- [Campmany Abogados - IPA 2026](https://www.campmanyabogados.com/incapacidad-permanente/absoluta)
- [Conceptos Jurídicos - IPA guía actualizada](https://www.conceptosjuridicos.com/incapacidad-permanente-absoluta/)
