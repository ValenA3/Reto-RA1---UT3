# Reto 03 — Elementos internos de un sistema informático (UT2 · RA1)
**Alumno/a:** Apellido1 Apellido2, Nombre  <br>
**Grupo:** 1ºASIR  <br>
**Fecha:**  06/12/2025 <br>
**Repositorio:** https://github.com/ValenA3/Reto-RA1---UT3.git 

1. [Portada](00-portada.md)
2. [Introducción](02-introduccion.md)
3. [Parte 1 — Fuentes y Refrigeración (A+B)](10-parte1_fuentes_y_refrigeracion/tu_parte1.md)
4. [Parte 2 — Componentes](retos/Reto_03_Elementos_Internos_SI/docs/20-parte2_TBD/parte2_componentes.md)
5. [Parte 3 — GPUs BlackFriday](retos/Reto_03_Elementos_Internos_SI/docs/30-parte3_TBD/parte3_gpus_blackfriday.md)
6. [Entrega y checklist](99-entrega_y_checklist.md)

En este reto nos centramos en **elementos internos** clave: alimentación y refrigeración.
- **Fuentes de alimentación:** formatos (ATX, SFX, TFX), eficiencia 80 PLUS, modularidad, PFC y dimensiones.
- **Refrigeración de CPU:** contraste entre soluciones **líquidas AIO** y **pasivas** para una **misma CPU**, evaluando eficiencia, ruido y coste.

## Parte 1 — Actividades A y B

## Actividad A — Investigación de **Fuentes de Alimentación** (9 modelos)

**Instrucciones:**
1. Elige **3 tiendas online españolas/especializadas** (p. ej., PcComponentes, Amazon ES, LDLC ES).
2. En **cada tienda**, selecciona **un modelo ATX**, **uno SFX** y **uno TFX** (total 9).
3. Para cada modelo, recoge: **Marca/Modelo**, **Potencia (W)**, **Certificación 80 PLUS**, **Precio (€)**, **Modularidad**, **PFC (activo/pasivo)**, **Dimensiones (mm)**, **Enlace**.
4. Al final, incluye una **tabla resumen comparativa global**.

### Tienda 1: PcComponentes
| Tipo | Marca/Modelo | Potencia (W) | 80 PLUS | Precio (€) | Modularidad | PFC | Dimensiones (L×W×H mm) | Enlace |
|------|---------------|--------------|---------|-----------:|------------|-----|------------------------|--------|
| ATX  | Mars Gaming MPB550SI| 550W | 80 Plus Bronze | 31,94€ | No modular | Activo | 150x145x85mm | https://www.pccomponentes.com/fuente-alimentacion-mars-gaming-mpb550si-fuente-alimentacion-atx-550w-7-anos-garantia-80-plus-bronze-90-blanca |
| SFX  | UNYKAch | 300W | 80 Plus Bronze | 35,95€ | No modular | Activo | 125x100x65mm | https://www.pccomponentes.com/unykach-fuente-de-alimentacion-sfx-300w-80-plus-bronze |
| TFX  | Tacens Anima Aptii500p | 500W | NO | 22,64€ | No mdoular | NO | 150x85x65mm | https://www.pccomponentes.com/tacens-anima-aptii500p-fuente-alimentacion-tfx-500w-ultracompacta-85-smd-ventilador-80mm-negro |

**Notas/criterios de la tienda 1:** El precio es bueno en los tres casos, pero varían bastante en potencia, eficiencia y formato, la elección dependerá de cuánto consuma tu sistema y del tamaño del gabinete

### Tienda 2: Amazon ES
| Tipo | Marca/Modelo | Potencia (W) | 80 PLUS | Precio (€) | Modularidad | PFC | Dimensiones (L×W×H mm) | Enlace |
|------|---------------|--------------|---------|-----------:|------------|-----|------------------------|--------|
| ATX  | CORSAIR CX650 | 650W | SI | 59,95€ | No modular | Activo | ‎12,5 x 15 x 8,6 cm | https://www.amazon.es/CORSAIR-CX650-650W-Fuente-Alimentaci%C3%B3n/dp/B0CK8NDN1Q/ref=sr_1_12?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=80DE4ROXV8QA&dib=eyJ2IjoiMSJ9.d15aCl0_L7KnChZ1kMHz3kNUXnG59f5k7Fq0sP3HBhSQp66c5MSxSMiOAq0Ubu58jNVDJVVs4qp4FD6ePq1FlNRCAlcefxK_JYr0oWogudQ5VR8s38pA16DkA3AguzUEG0jqbx9wLVORf6qNEi7ngnFRJeCZa8r2nVxNkvamzA84TR25UxHykTJpxH3KVQXGvSlGgJGWPTrN5Gwh_DFd0eanYTTHCs_hbYg41NFYy9CvXgMWyUrQjwfHINJcwq9AnslTfvJ4acpL0bpuBjkWvscm8LlJG6STuEnnYXfskZA.mevN9kgrqeXTUz3wI30aLWYZqjaDxfwqzKzt839dX60&dib_tag=se&keywords=fuente%2Bde%2Balimentacion%2BATX&qid=1762872611&sprefix=fuente%2Bde%2Balimentacion%2Batx%2Caps%2C100&sr=8-12&th=1 |
| SFX  | SHARKOON SilentStorm | 450W | SI | 66,66€ | No modular | Semipasivo | 125 x 100 x 63 mm | https://www.amazon.es/Sharkoon-SilentStorm-SFX-Bronze-alimentaci%C3%B3n/dp/B00W4IVZQY/ref=sr_1_6?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=3V3Y6JAIZQIUK&dib=eyJ2IjoiMSJ9.ZNp5AwXUBLjOo-NfP-6i2Hy6q4jSLW5_SAG1001_hdGhSNCIBEW9uY2S4bykvCOZ7tMW4aJ6Es5MjNp3RQ-ebcxiZ3-iTA5u4FUe5di7gqlKeFuFEQHWXjFaqEByrNMaLM1GTMFb8bdyS7B3D159hEt1ol7EsRugBL5gIMj2jXLvYR3Alts3B_3txe6oLp1bRCO1x4c7rhz0w_fKsibQGbXicuJwCM2cCatSW-viV5vCJEw8mmHqbrRFXIh-d3ib1O7-2JOcCoktmDJZajgISH6YXvWhXMfCuntNsvEVX0Y.Dq9eu1ODD7sqdtd35B3sh7mJIKZWWgprnmi19zzZ8Y0&dib_tag=se&keywords=fuente+de+alimentaci%C3%B3n+sfx&qid=1762872888&sprefix=fuente+de+alimentacion+sfx%2Caps%2C101&sr=8-6 |
| TFX  | be quiet! TFX Power 3 | 300W | 80 Plus Gold | 69,99€ | No modular | Semipasivo | ‎17,5 x 8,5 x 6,5 cm | https://www.amazon.es/quiet-Power-300W-PC-Fuente-alimentaci%C3%B3n/dp/B0937HPKFT/ref=sr_1_11?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=38DTE0ESE1FLF&dib=eyJ2IjoiMSJ9.zanI491Y8s0ehvBIA-ngBSvYMwcXG-n3kaj0NyIof8Kai66COLp-kwqcLdS_AAoUxKuJLWpu-OqliLUMfetrVHJKaV1_u8fen5jAUUwLv-SkkRz8jTnQTpYnxIS4gwmaEeRz_cDt-WyiSFxlBC6kOboEJSZRvs_KMM8CKZhnUGOfHOBdK8PBbCffUi_PSXfoVVODVL3eU2QLmFDicfyRcx1YiGV29hI7h-RJxrFpHjsdgD93YtSOzdwhIqJqa5IYXHpM8lo6Yhg-iluVrId9MKNnRAuc1wkxQeOHUaa8Uh4.aW_xdFjog11DDT2lVepc93oyBruGr1YmuV932Z20AIg&dib_tag=se&keywords=fuente%2Bde%2Balimentaci%C3%B3n%2BTFX&qid=1762873280&sprefix=fuente%2Bde%2Balimentaci%C3%B3n%2Btfx%2Caps%2C94&sr=8-11&th=1 |

**Notas/criterios de la tienda 2:**
La Corsair CX650 es potente y eficiente para PCs estándar.
La Sharkoon SilentStorm SFX 450W es compacta y adecuada para equipos pequeños.
La be quiet! TFX Power 3 300W es muy eficiente para PCs ultracompactos.

### Tienda 3: Alternate ES
| Tipo | Marca/Modelo | Potencia (W) | 80 PLUS | Precio (€) | Modularidad | PFC | Dimensiones (L×W×H mm) | Enlace |
|------|---------------|--------------|---------|-----------:|------------|-----|------------------------|--------|
| ATX  | Inter-Tech Argus APS-720 | 720W | NO | 40,79€ | NO | SI | Ancho: 150 mm x Altura: 86 mm x Profundidad/longitud: 140 mm | https://www.alternate.es/Inter-Tech/Argus-APS-720-720W-Fuente-de-alimentaci%C3%B3n-dePC/html/product/1857471|
| SFX  | Chieftec SFX-250VS | 250W | NO | 44,79€ | NO | SI | Ancho: 125 mm x Altura: 64 mm x Profundidad/longitud: 100 mm | https://www.alternate.es/Chieftec/SFX-250VS-unidad-de-fuente-de-alimentaci%C3%B3n-250-W-20plus4-pin-ATX-Plata-Fuente-de-alimentaci%C3%B3n-de-PC/html/product/1270519 |
| TFX  | Chieftec Smart | 300W | SI | 44,79€ | NO | SI | Ancho: 85 mm x Altura: 65 mm x Profundidad/longitud: 175 mm | https://www.alternate.es/Chieftec/Smart-300W-unidad-de-fuente-de-alimentaci%C3%B3n-20plus4-pin-ATX-TFX-Gris-Fuente-de-alimentaci%C3%B3n-de-PC/html/product/1641622 |

**Notas/criterios de la tienda 3:**Inter‑Tech Argus APS-720W: Buena para PC de sobremesa con bastante potencia para gaming moderado o multitarea.

Chieftec SFX-250VS: Ideal para sistemas muy compactos o de bajo consumo, en cajas pequeñas.

Chieftec Smart 300W (TFX): Pensada para equipos ultracompactos donde la eficiencia y el tamaño reducido importan.

#### Tabla **resumen comparativa** (global, 9 modelos)
| Tienda | Tipo | Marca/Modelo | Potencia (W) | 80 PLUS | Precio (€) | Modularidad | PFC | Dimensiones (mm) | Observaciones |
|--------|------|---------------|--------------|---------|-----------:|------------|-----|------------------|---------------|
|PcComponentes| ATX |Mars Gaming MPB550SI|550|Bronze|31,94|No modular| Activo |150 × 145 × 85 |Muy barata, eficiencia básica |
| PcComponentes | SFX  | UNYKAch 300W | 300 | Bronze  | 35,95 | No modular| Activo | 125 × 100 × 65| Compacta, para PCs pequeños |
| PcComponentes | TFX  | Tacens Anima APII500| 500| No | 22,64 | No modular | No | 150 × 85 × 65 | Muy económica, menor calidad |
| Amazon ES     | ATX  | Corsair CX650| 650| Sí| 59,95| No modular  | Activo | 125 × 150 × 86   | Fiable y potente, buena marca  |
| Amazon ES     | SFX  | Sharkoon SilentStorm SFX 450W| 450 | Sí| 66,66| No modular | Semi-pasivo| 125 × 100 × 63 | Silenciosa y compacta |
| Amazon ES     | TFX  | be quiet! TFX Power 3 300W| 300 | Gold| 69,99| No modular | Semi-pasivo| 175 × 85 × 65 | Muy eficiente, ideal SFF|
| Alternate ES  | ATX  | Inter-Tech Argus APS-720| 720  | No  | 40,79 | No | Sí | 150 × 86 × 140   | Mucha potencia, baja eficiencia |
| Alternate ES  | SFX  | Chieftec SFX-250VS| 250 | No | 44,79  | No  | Sí | 125 × 64 × 100 | Muy compacta, potencia limitada |
| Alternate ES  | TFX  | Chieftec Smart 300W | 300 | Sí  | 44,79  | No | Sí| 85 × 65 × 175| Equilibrada para TFX   |
---
## Actividad B — **Refrigeración para la MISMA CPU** (Líquida vs Pasiva)

**Instrucciones:**
1. Elige una **CPU concreta** (ej.: Intel Core i9-13900, AMD Ryzen 9 7950X…). Indícala abajo.
2. Selecciona **una refrigeración líquida AIO** y **una refrigeración pasiva** **compatibles** con esa CPU. Incluye **URLs** oficiales o de tienda.
3. Compara **precio, eficiencia térmica (TDP soportado/temperaturas), ruido, dimensiones, compatibilidad de socket, mantenimiento, garantía**…
4. **Concluye** con recomendaciones por perfil (**gamer**, **diseño/pro**, **usuario estándar**) y **calidad-precio**.

**CPU elegida:** Procesador AMD Ryzen 7 5700G 4.6GHz

### Modelos evaluados
| Tipo | Marca/Modelo | Precio (€) | TDP soportado / Rendimiento térmico | Ruido (dBA) | Dimensiones (mm) | Sockets | Mantenimiento | Garantía | Enlace |
|------|---------------|-----------:|-------------------------------------|-------------|------------------|---------|---------------|----------|--------|
| Líquida (AIO) | Arctic Liquid Freezer III Pro 360 | 86,99 | Alto, apto para CPU potentes / CPU de alto rendimiento | 40 dBA a velocidad normal  | Radiador: 398 × 120 × 38 mm; tubo 450 mm; bloque CPU 105,5 × 68,5 × 91 mm | Intel: LGA1700 / LGA1851; AMD: AM5, AM4 | Requiere mantenimiento ocasional para el radiador y polvo de ventiladores | 6 años | https://www.idealo.es/precios/206182027/arctic-liquid-freezer-iii-pro-360.html?gclid=EAIaIQobChMIh4vMoLjqkAMVAH9BAh1Xdx-tEAQYASABEgIO__D_BwE&utm_campaign=SEM-ES-WEB-CVR-SHOPPING-22719101037&utm_medium=cpc&utm_source=google#test |
| Pasiva | Noctua NH-P1 | 119,90 | TDP moderado: hasta 95 W usando convección natural | 0 dBA (sin ventilador) | 154 × 152 × 158 mm | Intel: LGA1700, LGA1200, LGA115x, LGA2066, LGA2011-0/3; AMD: AM5, AM4, AM2/AM3 | Casi cero mantenimiento sin ventiladores, sólo limpieza de polvo | 6 años | https://www.idealo.es/precios/206182027/arctic-liquid-freezer-iii-pro-360.html?gclid=EAIaIQobChMIh4vMoLjqkAMVAH9BAh1Xdx-tEAQYASABEgIO__D_BwE&utm_campaign=SEM-ES-WEB-CVR-SHOPPING-22719101037&utm_medium=cpc&utm_source=google#test |
### Análisis y elección por perfil
- **Gamer:** recomendable ARCTIC Liquid Freezer III Pro 360 porque ofrece la mejor refrigeración bajo carga intensa, ideal para sesiones largas de juego o uso de GPU potente.
- **Profesional de diseño/simulación:**  ARCTIC Liquid Freezer III Pro 360 porque mantiene el CPU fresco y estable durante tareas largas y exigentes.
- **Usuario estándar/ofimática:** recomendable Noctua NH-P1 porque es suficiente para tareas básicas, sin ruido, sin mantenimiento, ideal para uso tranquilo y diario.

### Conclusión general
Para el AMD Ryzen 7 5700G, ambas soluciones de refrigeración son compatibles y válidas, pero están pensadas para perfiles distintos. La refrigeración líquida AIO ofrece el mejor control térmico y mayor margen de rendimiento para gaming y uso profesional intensivo, a costa de más ruido y algo de mantenimiento. En cambio, la refrigeración pasiva destaca por su silencio absoluto, simplicidad y bajo mantenimiento, siendo suficiente para un usuario estándar con cargas moderadas. En resumen, la elección depende de si se prioriza rendimiento y versatilidad o silencio y comodidad.

---
## Parte 2 — Componentes
# Parte 2 — Componentes y DDR5
## Búsqueda de componentes
### RAM para oficina
Marca / Modelo: Kingston ValueRAM 8GB DDR4 2666MHz <br>
Características: 2666MHz, CL19, 1.2V, módulo único <br>
Precio: 65,49€ <br>
URL: https://www.pccomponentes.com/kingston-valueram-ddr4-2666mhz-8gb-cl19?s_kwcid=AL!14405!3!!!!x!!&gad_source=1&gad_campaignid=21435331652&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XPMPyUT95zyLh-Z0GXmWElDY6QEyP6GQ9z1ulfJ8wSGglxCTd5NhpBoCzeIQAvD_BwE
Captura: ![Kingston ValueRAM 8GB DDR4 2666MHz](retos/Reto_03_Elementos_Internos_SI/docs/20-parte2_TBD/ram.PNG) <br>
Justificación: Es una memoria económica, suficiente para tareas de ofimática y bajo consumo energético. <br>

### RAM para gaming
Marca / Modelo: Corsair Vengeance DDR5 32GB 6000MHz <br>
Características: 6000MHz, CL36, 1.25V, óptimo para placas DDR5 <br>
Precio: 429,95€ <br>
URL: https://www.pccomponentes.com/corsair-vengeance-ddr5-6000mhz-32-gb-2x16gb-cl36-memoria-dual-amd-expo-e-intel-xmp?campaigntype=eshopping&campaignchannel=shopping&gad_source=1&gad_campaignid=315043357&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XMUVGCCM4Ae8cbxbug03FxgXHrlteSsL5LHOrOmj9wzkqF8A394SkBoCE0cQAvD_BwE <br>
Justificación: Alta velocidad y baja latencia, ideal para juegos exigentes y multitarea. <br>

### CPU para oficina
Marca / Modelo: Intel Core i3-12100 <br>
Características: 4 núcleos / 8 hilos, 4.3GHz turbo, 60W <br>
Precio: 154,90€ <br>
URL: https://www.pccomponentes.com/intel-core-i3-12100-33-ghz?campaigntype=eshopping&campaignchannel=shopping&gad_source=1&gad_campaignid=17149275343&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XGMuLpCROALZkYOljbZ4pI2NPXNFjtRNN3_0P-Kjo5V_Q4rI7qAvFxoCuisQAvD_BwE <br>
Justificación: Excelente rendimiento en tareas de oficina con bajo consumo. <br>

### CPU para gaming
Marca / Modelo: AMD Ryzen 5 7600X <br>
Características: 6 núcleos / 12 hilos, 5.3GHz turbo, DDR5, PCIe 5.0 <br>
Precio: 189,90€ <br>
URL: https://www.pccomponentes.com/amd-ryzen-5-7600x-47-ghz-box-sin-ventilador?srsltid=AfmBOopnCA_dP5LEsUhmhavctyxrahxh7IJOF8gCrcgSB1enUUOvOG4R <br>
Justificación: Gran rendimiento en juegos, buena relación calidad/precio. <br>

## Tabla RAM: DDR4 vs DDR5
| Caracteristicas | DDR4 | DDR5 |
|-----------------|------|------|
| Velocidad | 2133–3600 MHz | 4800–8000+ MHz |
| Consumo | ~1.2V | ~1.1V | 
| Precio | Más barata | Más cara |
| Compatibilidad | Placas DDR4 | Placas DDR5 |

## Investigación DDR5
### Ventajas de DDR5 frente a DDR4
Mayor velocidad: DDR5 parte desde 4800 MHz y supera con facilidad los 6000–8000 MHz, frente a los 2133–3600 MHz habituales de DDR4. <br>
Mayor ancho de banda: Permite transferir más datos por segundo, mejorando tareas intensivas. <br> 
Menor consumo: DDR5 funciona a ~1.1V, reduciendo el uso energético. <br>
Mayor capacidad por módulo: DDR5 permite módulos de 32–128 GB con mayor facilidad. <br>
Mejor eficiencia interna: Incluye PMIC integrado y subcanales independientes que optimizan el rendimiento. <br>

### En qué usos se nota más DDR5
Gaming de alta gama, especialmente con GPUs modernas (RTX 4000/5000, Radeon 7000) que aprovechan mejor el ancho de banda. <br>
Edición de vídeo 4K/8K, renderizado y creación de contenido. <br> 
Trabajo con máquinas virtuales, ingeniería, simulación y compilación de proyectos grandes. <br>
Aplicaciones de IA, modelos locales y cargas paralelas. <br>

### Ejemplo concreto
Edición de vídeo: Un PC con un Ryzen 5 7600X y RAM DDR4 renderizaría proyectos 4K más lento debido al menor ancho de banda. Con DDR5 6000MHz, se obtienen mejoras en tiempos de exportación y una línea de tiempo más fluida cuando se utilizan múltiples efectos y capas.



---
## Parte 3 — GPUs BlackFriday
# Parte 3 — GPUs y precios reales
## 3.1 Visualización y notas
### ~200€: <br>
Intel B570 (10 GB) - 01:07 <br>
RX 7600 XTD (16 GB) - 01:34 <br>
RX 7600 (8 GB) - 1:37 <br>
### ~250€: <br>
B580 (12 GB) - 01:58 <br>
RTX 5050 (8 GB) - 01:58 <br> 
### ~300€: <br>
9060 XT (8 GB) - 04:46 <br>
5060 (8 GB, GDDR7) - 04:46 <br>
### ~350€: <br>
9060 XT (16 GB) - 07:57 <br>
5060 Ti (8 GB) - 08:46 <br>
5060 Ti (16 GB) - 09:01 <br>
### ~500€: <br>
9070 (16 GB) - 09:42 <br> 
5070 (12 GB, GDDR7) - 09:42 <br>
### ~ €600-€800: <br>
9070 XT (16 GB) - 11:43 <br> 
5070 Ti (12 GB, GDDR7) - 11:43 <br>
### +€1000: <br>
5090 (32 GB, GDDR7) - 14:18 <br>
5080 (16 GB) - 14:46 <br>

## 3.2 Dos tramos obligatorios:<br>
### ~350 €: minuto de inicio/fin + 2 GPUs principales.<br>
Min inicio: 7:41<br>
Min fin: 8:55<br>
2 GPUs principales: <br>
9060 XT (16 GB): Precio aproximado: 350 €, recomendada para juegos a 1440p gracias a su gran memoria y buen rendimiento.<br>
5060 Ti (8 GB): Precio entre 360 ​​€ y 370 €, aunque es menos atractiva; no se recomienda por su menor potencia, especialmente para un presupuesto de unos 300 €.<br>
### 600–800 €: minuto de inicio/fin + 2 GPUs principales.<br>
Min inicio: 11:43<br>
Min fin: 13:38<br>
2 GPUs principales: <br>
9070 XT (16 GB): Una excelente opción para juegos, con un precio inferior a 600 €, que ofrece un buen rendimiento a largo plazo.<br>
5070 Ti (12 GB): Con un precio de alrededor de 780 €, es mejor para el trazado de rayos e incluye tecnologías asociadas con Nvidia, pero a un coste mayor.<br>
### Modelos repetidos<br>
La 9060 XT aparece en las dos tramas, enfatizando su valor en el segmento de gama media baja.<br>
## 3.3 Búsqueda en tiendas
| GPU | Tienda | Precio actual |
|-----|--------|---------------|
| 9060 XT (16GB) | https://www.pccomponentes.com/tarjeta-grafica-gigabyte-amd-radeon-rx-9060-xt-gaming-oc-16gb-gddr6-fsr-4 | 409,90€ |
| 5060 Ti (8 GB) | https://www.pccomponentes.com/tarjeta-grafica-gigabyte-geforce-rtx-5060-ti-windforce-max-oc-8gb-gddr7-reflex-2-rtx-ai-dlss4?utm_source=624709&utm_medium=afi&utm_campaign=www.google.com&sv1=affiliate&sv_campaign_id=624709&awc=20981_1765019101_a2daade6c6d71d5481cc0d7f876e1a4b&utm_term=deeplink&utm_content=f0ecc762f30275698b45acf9867fcd94 | 361,80€ |
| 9070 XT (16 GB) | https://www.pccomponentes.com/tarjeta-grafica-sapphire-pulse-amd-radeon-rx-9070-xt-16gb-gddr6-fsr-4?s_kwcid=AL!14405!3!!!!x!!&gad_source=1&gad_campaignid=17335768752&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XNPemZF3Q9702y_8kmqVLImKzANGm8GLaeaapJHGP2qTl5AUsPkwuBoCxU4QAvD_BwE | 629,90€ |
| 5070 Ti (12 GB) | https://www.pccomponentes.com/tarjeta-grafica-asus-prime-geforce-rtx-5070-ti-oc-16gb-gddr7-reflex-2-rtx-ai-dlss4?s_kwcid=AL!14405!3!!!!x!!&gad_source=1&gad_campaignid=17335768752&gclid=CjwKCAiAxc_JBhA2EiwAFVs7XN5MfvltXBQF506oJe9kZN6EE7y80kMPk6ZNbayLDEC-i1dYkEGF_hoClkQQAvD_BwE | 819,90€ |
