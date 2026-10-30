# Sinaloa: law history in git

The law of the State of Sinaloa (Estado Libre y Soberano de Sinaloa, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-sin/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

153 ordenamientos with 1222 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE SINALOA | 199 | as first published, then each reform: 23 June 1922 to 10 October 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE SINALOA | 61 | as first published, then each reform: 26 July 1940 to 12 March 2022 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE SINALOA | 42 | as first published, then each reform: 25 October 1940 to 29 December 2016 |
| `codigo-de-procedimientos-familiares/` | CODIGO DE PROCEDIMIENTOS FAMILIARES DEL ESTADO DE SINALOA | 10 | as first published, then each reform: 27 December 2013 to 23 July 2019 |
| `codigo-familiar/` | CODIGO FAMILIAR DEL ESTADO DE SINALOA | 24 | as first published, then each reform: 8 March 2013 to 5 September 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE SINALOA | 9 | as first published, then each reform: 12 January 1995 to 28 December 2019 |
| `codigo-fiscal-municipal/` | CODIGO FISCAL MUNICIPAL DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 17 December 2016 to 1 April 2018 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE SINALOA | 95 | as first published, then each reform: 27 November 1992 to 8 October 2026 |
| `ley-ambiental-para-el-desarrollo-sustentable/` | LEY AMBIENTAL PARA EL DESARROLLO SUSTENTABLE DEL ESTADO DE SINALOA | 12 | as first published, then each reform: 8 May 2013 to 27 August 2026 |
| `ley-austeridad/` | LEY AUSTERIDAD PARA EL ESTADO DE SINALOA | 1 | as first published: 7 February 2019 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE SINALOA | 21 | as first published, then each reform: 31 July 2007 to 7 June 2025 |
| `ley-de-adquisiciones-arrendamientos-servicios-y-administraci/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS, SERVICIOS Y ADMINISTRACION DE BIENES MUEBLES PARA EL ESTADO DE SINALOA | 3 | as first published, then each reform: 18 March 2010 to 29 December 2016 |
| `ley-de-agua-potable-y-alcantarillado/` | LEY DE AGUA POTABLE Y ALCANTARILLADO DEL ESTADO DE SINALOA | 12 | as first published, then each reform: 20 February 1984 to 10 February 2022 |
| `ley-de-amnistia/` | LEY DE AMNISTIA DEL ESTADO DE SINALOA | 1 | as first published: 1 April 2021 |
| `ley-de-aranceles/` | LEY DE ARANCELES DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 21 March 1943 to 1 November 1977 |
| `ley-de-aranceles-para-los-abogados/` | LEY DE ARANCELES PARA LOS ABOGADOS DEL ESTADO DE SINALOA | 1 | as first published: 7 October 2021 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE SINALOA | 1 | as first published: 5 February 2022 |
| `ley-de-atencion-y-proteccion-a-victimas/` | LEY DE ATENCION Y PROTECCION A VICTIMAS DEL ESTADO DE SINALOA | 7 | as first published, then each reform: 2 August 2014 to 18 July 2026 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 17 June 2001 to 23 September 2021 |
| `ley-de-camaras-de-la-propiedad-urbana/` | LEY DE CAMARAS DE LA PROPIEDAD URBANA PARA EL ESTADO DE SINALOA | 1 | as first published: 17 November 1970 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE SINALOA | 8 | as first published, then each reform: 11 January 1994 to 29 December 2016 |
| `ley-de-ciencia-tecnologia-e-innovacion/` | LEY DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE SINALOA | 5 | as first published, then each reform: 18 October 2012 to 24 September 2022 |
| `ley-de-contratos-de-colaboracion-publico-privada/` | LEY DE CONTRATOS DE COLABORACION PUBLICO PRIVADA PARA EL ESTADO DE SINALOA | 3 | as first published, then each reform: 15 May 2013 to 28 December 2017 |
| `ley-de-coordinacion-de-sanidad-e-inocuidad-agricola/` | LEY DE COORDINACION DE SANIDAD E INOCUIDAD AGRICOLA DEL ESTADO DE SINALOA | 1 | as first published: 25 January 2018 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE SINALOA | 13 | as first published, then each reform: 16 January 1990 to 7 June 2025 |
| `ley-de-cultura/` | LEY DE CULTURA DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 14 August 2008 to 4 September 2021 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE PARA EL ESTADO DE SINALOA | 4 | as first published, then each reform: 19 May 2016 to 25 December 2025 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE SINALOA | 1 | as first published: 20 August 2016 |
| `ley-de-desarrollo-ganadero/` | LEY DE DESARROLLO GANADERO DEL ESTADO DE SINALOA | 1 | as first published: 19 February 2022 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 25 February 2014 to 18 July 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE SINALOA | 1 | as first published: 1 January 2018 |
| `ley-de-educacion/` | LEY DE EDUCACION PARA EL ESTADO DE SINALOA | 10 | as first published, then each reform: 5 December 2020 to 12 September 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE SINALOA | 1 | as first published: 1 March 2023 |
| `ley-de-ejecucion-de-las-consecuencias-juridicas-del-delito/` | LEY DE EJECUCION DE LAS CONSECUENCIAS JURIDICAS DEL DELITO DEL ESTADO DE SINALOA | 9 | as first published, then each reform: 17 September 2001 to 31 May 2014 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 23 December 2017 to 24 September 2022 |
| `ley-de-entrega-y-recepcion-de-los-asuntos-y-recursos-publico/` | LEY DE ENTREGA Y RECEPCION DE LOS ASUNTOS Y RECURSOS PUBLICOS DEL ESTADO DE SINALOA | 1 | as first published: 6 June 2010 |
| `ley-de-fomento-a-la-inversion-para-el-desarrollo-economico/` | LEY DE FOMENTO A LA INVERSION PARA EL DESARROLLO ECONOMICO DEL ESTADO DE SINALOA | 9 | as first published, then each reform: 28 November 1996 to 25 August 2018 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE SINALOA | 1 | as first published: 5 May 2016 |
| `ley-de-fomento-apicola-y-proteccion-de-agentes-polinizadores/` | LEY DE FOMENTO APICOLA Y PROTECCION DE AGENTES POLINIZADORES DEL ESTADO DE SINALOA | 1 | as first published: 8 May 2021 |
| `ley-de-fomento-de-valores-formacion-civica-y-cultura-de-la-l/` | LEY DE FOMENTO DE VALORES, FORMACION CIVICA Y CULTURA DE LA LEGALIDAD DEL ESTADO DE SINALOA | 1 | as first published: 5 May 2016 |
| `ley-de-fomento-minero/` | LEY DE FOMENTO MINERO DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 9 August 2014 to 28 December 2019 |
| `ley-de-fomento-para-el-desarrollo-economico-de-madres-jefas/` | LEY DE FOMENTO PARA EL DESARROLLO ECONOMICO DE MADRES JEFAS DE FAMILIA DEL ESTADO DE SINALOA | 1 | as first published: 9 September 2017 |
| `ley-de-fomento-y-proteccion-del-maiz-nativo/` | LEY DE FOMENTO Y PROTECCION DEL MAIZ NATIVO DEL ESTADO DE SINALOA | 1 | as first published: 8 May 2021 |
| `ley-de-gobierno-electronico/` | LEY DE GOBIERNO ELECTRONICO DEL ESTADO DE SINALOA | 1 | as first published: 2 August 2016 |
| `ley-de-gobierno-municipal/` | LEY DE GOBIERNO MUNICIPAL DEL ESTADO DE SINALOA | 31 | as first published, then each reform: 1 January 2002 to 5 September 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE SINALOA | 43 | as first published, then each reform: 27 March 1990 to 18 June 2024 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO DE SINALOA | 79 | as first published, then each reform: 30 November 1978 to 18 July 2026 |
| `ley-de-ingresos-y-presupuesto-de-egresos/` | LEY DE INGRESOS Y PRESUPUESTO DE EGRESOS DEL ESTADO DE SINALOA PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-de-asistencia-privada/` | LEY DE INSTITUCIONES DE ASISTENCIA PRIVADA PARA EL ESTADO DE SINALOA | 2 | as first published, then each reform: 29 November 2001 to 29 December 2016 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES DEL ESTADO DE SINALOA | 19 | as first published, then each reform: 16 July 2015 to 5 September 2026 |
| `ley-de-integracion-social-de-personas-con-discapacidad/` | LEY DE INTEGRACION SOCIAL DE PERSONAS CON DISCAPACIDAD DEL ESTADO DE SINALOA | 5 | as first published, then each reform: 9 September 2000 to 6 October 2018 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA PARA EL ESTADO DE SINALOA | 12 | as first published, then each reform: 27 March 1993 to 28 September 2021 |
| `ley-de-justicia-alternativa-en-materia-penal/` | LEY DE JUSTICIA ALTERNATIVA EN MATERIA PENAL PARA EL ESTADO SINALOA | 3 | as first published, then each reform: 18 May 2013 to 31 May 2014 |
| `ley-de-la-auditoria-superior/` | LEY DE LA AUDITORIA SUPERIOR DEL ESTADO DE SINALOA | 11 | as first published, then each reform: 24 April 2008 to 16 July 2026 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA DEL ESTADO DE SINALOA | 6 | as first published, then each reform: 26 September 2013 to 29 September 2022 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD DEL ESTADO DE SINALOA | 1 | as first published: 19 April 2016 |
| `ley-de-los-comites-locales-de-caminos-vecinales-en-el-estado/` | LEY DE LOS COMITES LOCALES DE CAMINOS VECINALES EN EL ESTADO DE SINALOA | 2 | as first published, then each reform: 2 January 1975 to 27 June 1983 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 11 November 2017 to 1 November 2021 |
| `ley-de-los-derechos-de-los-pueblos-y-comunidades-indigenas/` | LEY DE LOS DERECHOS DE LOS PUEBLOS Y COMUNIDADES INDIGENAS PARA EL ESTADO DE SINALOA | 1 | as first published: 10 February 2018 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE SINALOA | 14 | as first published, then each reform: 15 October 2015 to 8 October 2026 |
| `ley-de-los-trabajadores-al-servicio-de-los-municipios/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LOS MUNICIPIOS DEL ESTADO DE SINALOA | 9 | as first published, then each reform: 21 March 1984 to 5 September 2026 |
| `ley-de-los-trabajadores-al-servicio/` | LEY DE LOS TRABAJADORES AL SERVICIO DEL ESTADO DE SINALOA | 12 | as first published, then each reform: 5 April 1986 to 5 September 2026 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS DEL ESTADO DE SINALOA | 1 | as first published: 7 November 2024 |
| `ley-de-mejora-regulatoria-y-gestion-empresarial/` | LEY DE MEJORA REGULATORIA Y GESTION EMPRESARIAL DEL ESTADO DE SINALOA | 1 | as first published: 8 November 2018 |
| `ley-de-movilidad-y-seguridad-vial-antes-ley-de-movilidad-sus/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL --ANTES LEY DE MOVILIDAD SUSTENTABLE-- DEL ESTADO DE SINALOA | 8 | as first published, then each reform: 11 October 2018 to 23 July 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO DE SINALOA | 7 | as first published, then each reform: 19 August 2016 to 24 October 2020 |
| `ley-de-ordenamiento-territorial-y-desarrollo-urbano/` | LEY DE ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 1 March 2018 to 7 November 2024 |
| `ley-de-organizaciones-agricolas/` | LEY DE ORGANIZACIONES AGRICOLAS DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 1 April 1997 to 21 December 2017 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 11 August 2012 to 28 August 2023 |
| `ley-de-pensiones/` | LEY DE PENSIONES PARA EL ESTADO DE SINALOA | 3 | as first published, then each reform: 31 March 2009 to 1 January 2021 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES DEL ESTADO DE SINALOA | 6 | as first published, then each reform: 11 October 2012 to 17 July 2025 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE SINALOA | 4 | as first published, then each reform: 3 November 1987 to 1 April 2018 |
| `ley-de-prestacion-de-servicios-inmobiliarios/` | LEY DE PRESTACION DE SERVICIOS INMOBILIARIOS DEL ESTADO DE SINALOA | 1 | as first published: 11 November 2022 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 28 November 2013 to 12 August 2023 |
| `ley-de-presupuesto-y-responsabilidad-hacendaria/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE SINALOA | 3 | oldest version available, then each reform: 1 January 2018 to 22 August 2020 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE SINALOA | 1 | as first published: 26 November 2019 |
| `ley-de-proteccion-a-los-animales/` | LEY DE PROTECCION A LOS ANIMALES PARA EL ESTADO DE SINALOA | 6 | as first published, then each reform: 5 November 2013 to 19 August 2025 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE SINALOA | 5 | as first published, then each reform: 26 January 2013 to 1 December 2017 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE SINALOA | 1 | as first published: 27 July 2017 |
| `ley-de-regularizacion-de-predios-rurales/` | LEY DE REGULARIZACION DE PREDIOS RURALES DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 17 April 2000 to 29 December 2016 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE SINALOA | 1 | as first published: 2 February 2019 |
| `ley-de-residuos/` | LEY DE RESIDUOS DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 27 September 2018 to 27 August 2026 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL PARA EL ESTADO DE SINALOA Y SUS MUNICIPIOS | 1 | as first published: 4 January 2024 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE SINALOA | 7 | as first published, then each reform: 19 June 2017 to 14 February 2026 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE SINALOA | 6 | as first published, then each reform: 9 November 1985 to 1 April 2018 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO DEL ESTADO DE SINALOA | 1 | as first published: 3 February 2024 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE SINALOA | 33 | as first published, then each reform: 4 September 2004 to 20 June 2026 |
| `ley-de-salud-mental/` | LEY DE SALUD MENTAL DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 28 December 2017 to 18 July 2026 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA DEL ESTADO DE SINALOA | 21 | as first published, then each reform: 15 October 2009 to 23 July 2026 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE SINALOA | 1 | as first published: 6 March 1982 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE SINALOA | 6 | as first published, then each reform: 5 May 2016 to 24 September 2022 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE SINALOA | 2 | as first published, then each reform: 16 August 2018 to 12 September 2026 |
| `ley-del-instituto-de-evaluacion-educativa/` | LEY DEL INSTITUTO DE EVALUACION EDUCATIVA DEL ESTADO DE SINALOA | 1 | as first published: 6 October 2007 |
| `ley-del-merito-social/` | LEY DEL MERITO SOCIAL DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 29 April 1961 to 5 February 1980 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE SINALOA | 6 | as first published, then each reform: 14 October 1998 to 5 September 2026 |
| `ley-del-servicio-de-administracion-tributaria/` | LEY DEL SERVICIO DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE SINALOA | 1 | as first published: 1 April 2018 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 17 June 2017 to 24 September 2022 |
| `ley-del-sistema-de-medios-de-impugnacion-en-materia-electora/` | LEY DEL SISTEMA DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL Y DE PARTICIPACION CIUDADANA PARA EL ESTADO DE SINALOA | 7 | as first published, then each reform: 18 July 2015 to 21 January 2023 |
| `ley-en-materia-de-desaparicion-forzada-de-personas-desaparic/` | LEY EN MATERIA DE DESAPARICION FORZADA DE PERSONAS, DESAPARICION COMETIDA POR PARTICULARES Y DEL SISTEMA ESTATAL DE BUSQUEDA DE PERSONAS DE SINALOA | 2 | as first published, then each reform: 23 July 2019 to 25 December 2025 |
| `ley-estatal-de-cambio-climatico-sinaloa/` | LEY ESTATAL DE CAMBIO CLIMATICO, SINALOA | 1 | as first published: 5 December 2020 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE SINALOA | 11 | as first published, then each reform: 5 January 1981 to 24 September 2022 |
| `ley-organica-de-la-comision-estatal-de-los-derechos-humanos/` | LEY ORGANICA DE LA COMISION ESTATAL DE LOS DERECHOS HUMANOS DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 2 November 2017 to 24 September 2022 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE SINALOA | 12 | as first published, then each reform: 9 September 2017 to 1 January 2026 |
| `ley-organica-de-la-procuraduria-fiscal/` | LEY ORGANICA DE LA PROCURADURIA FISCAL DEL ESTADO DE SINALOA | 1 | as first published: 1 April 2018 |
| `ley-organica-de-la-universidad-autonoma-de-occidente-sinaloa/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE OCCIDENTE, SINALOA | 2 | as first published, then each reform: 22 February 2018 to 6 April 2024 |
| `ley-organica-de-la-universidad-autonoma-de-sinaloa/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA DE SINALOA | 4 | as first published, then each reform: 8 August 2006 to 3 October 2024 |
| `ley-organica-de-la-universidad-autonoma-indigena-de-mexico/` | LEY ORGANICA DE LA UNIVERSIDAD AUTONOMA INDIGENA DE MEXICO | 1 | as first published: 28 November 2019 |
| `ley-organica-de-la-universidad-de-la-policia/` | LEY ORGANICA DE LA UNIVERSIDAD DE LA POLICIA DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 9 December 2021 to 24 September 2022 |
| `ley-organica-de-la-universidad-pedagogica/` | LEY ORGANICA DE LA UNIVERSIDAD PEDAGOGICA DEL ESTADO SINALOA | 1 | as first published: 9 April 2013 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 14 December 2021 to 29 September 2022 |
| `ley-organica-del-congreso/` | LEY ORGANICA DEL CONGRESO DEL ESTADO DE SINALOA | 40 | as first published, then each reform: 23 November 1995 to 15 February 2025 |
| `ley-organica-del-fondo-auxiliar-para-la-administracion-de-ju/` | LEY ORGANICA DEL FONDO AUXILIAR PARA LA ADMINISTRACION DE JUSTICIA DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 29 March 1983 to 19 January 1991 |
| `ley-organica-del-ministerio-publico/` | LEY ORGANICA DEL MINISTERIO PUBLICO DEL ESTADO DE SINALOA | 12 | as first published, then each reform: 17 November 1998 to 31 May 2014 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE SINALOA | 20 | as first published, then each reform: 25 April 1995 to 5 September 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 2 October 2018 to 24 September 2022 |
| `ley-para-el-aprovechamiento-integral-de-alimentos-y-su-donac/` | LEY PARA EL APROVECHAMIENTO INTEGRAL DE ALIMENTOS Y SU DONACION ALTRUISTA DEL ESTADO DE SINALOA | 1 | as first published: 2 October 2018 |
| `ley-para-el-desarrollo-de-la-competitividad-de-las-micro-peq/` | LEY PARA EL DESARROLLO DE LA COMPETITIVIDAD DE LAS MICRO, PEQUEÑAS Y MEDIANAS EMPRESAS DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 9 August 2014 to 15 November 2025 |
| `ley-para-el-fomento-de-la-actividad-artesanal/` | LEY PARA EL FOMENTO DE LA ACTIVIDAD ARTESANAL DEL ESTADO DE SINALOA | 1 | as first published: 7 June 2018 |
| `ley-para-el-fomento-del-turismo-en-el-estado-de-sinaloa/` | LEY PARA EL FOMENTO DEL TURISMO EN EL ESTADO DE SINALOA | 2 | as first published, then each reform: 8 July 1988 to 12 August 2023 |
| `ley-para-impulsar-la-productividad-y-competitividad-de-la-ec/` | LEY PARA IMPULSAR LA PRODUCTIVIDAD Y COMPETITIVIDAD DE LA ECONOMIA DEL ESTADO DE SINALOA | 1 | as first published: 28 April 2018 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS PARA EL ESTADO DE SINALOA | 1 | as first published: 8 January 2016 |
| `ley-para-la-atencion-y-proteccion-a-personas-con-la-condicio/` | LEY PARA LA ATENCION Y PROTECCION A PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 20 July 2017 to 18 July 2026 |
| `ley-para-la-deteccion-oportuna-del-cancer-en-la-infancia-y-l/` | LEY PARA LA DETECCION OPORTUNA DEL CANCER EN LA INFANCIA Y LA ADOLESCENCIA DEL ESTADO DE SINALOA | 1 | as first published: 12 July 2022 |
| `ley-para-la-dotacion-gratuita-de-uniformes-calzado-deportivo/` | LEY PARA LA DOTACION GRATUITA DE UNIFORMES, CALZADO DEPORTIVO Y UTILES ESCOLARES DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 28 September 2019 to 15 August 2020 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE SINALOA | 7 | as first published, then each reform: 12 March 2009 to 19 August 2025 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA, CON PARTICIPACION CIUDADANA DEL ESTADO DE SINALOA | 1 | as first published: 17 January 2015 |
| `ley-para-la-prevencion-y-atencion-de-la-violencia-familiar/` | LEY PARA LA PREVENCION Y ATENCION DE LA VIOLENCIA FAMILIAR DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 17 April 2018 to 1 November 2021 |
| `ley-para-la-promocion-y-desarrollo-de-los-jovenes-emprendedo/` | LEY PARA LA PROMOCION Y DESARROLLO DE LOS JOVENES EMPRENDEDORES DEL ESTADO DE SINALOA | 1 | as first published: 28 November 2013 |
| `ley-para-la-proteccion-de-personas-defensoras-de-derechos-hu/` | LEY PARA LA PROTECCION DE PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y PERIODISTAS DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 28 May 2022 to 17 June 2025 |
| `ley-para-la-proteccion-de-personas-que-intervienen-en-el-pro/` | LEY PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL PARA EL ESTADO DE SINALOA | 1 | as first published: 31 December 2016 |
| `ley-para-la-proteccion-apoyo-y-promocion-a-la-lactancia-mate/` | LEY PARA LA PROTECCION, APOYO Y PROMOCION A LA LACTANCIA MATERNA DEL ESTADO DE SINALOA | 1 | as first published: 12 August 2017 |
| `ley-para-la-proteccion-atencion-y-asistencia-a-las-victimas/` | LEY PARA LA PROTECCION, ATENCION Y ASISTENCIA A LAS VICTIMAS DE LOS DELITOS EN MATERIA DE TRATA DE PERSONAS DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 9 September 2017 to 21 January 2023 |
| `ley-para-prevenir-y-eliminar-la-discriminacion/` | LEY PARA PREVENIR Y ELIMINAR LA DISCRIMINACION DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 4 July 2013 to 20 August 2024 |
| `ley-para-prevenir-atender-y-erradicar-la-violencia-escolar/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR LA VIOLENCIA ESCOLAR DEL ESTADO DE SINALOA | 1 | as first published: 2 October 2016 |
| `ley-para-prevenir-atender-y-reparar-integralmente-el-desplaz/` | LEY PARA PREVENIR, ATENDER Y REPARAR INTEGRALMENTE EL DESPLAZAMIENTO FORZADO INTERNO EN EL ESTADO DE SINALOA | 2 | as first published, then each reform: 22 August 2020 to 1 November 2021 |
| `ley-para-prevenir-investigar-y-sancionar-el-delito-de-extors/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR EL DELITO DE EXTORSION DEL ESTADO DE SINALOA | 1 | as first published: 21 March 2026 |
| `ley-para-prevenir-investigar-y-sancionar-la-tortura-y-otros/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR LA TORTURA Y OTROS TRATOS O PENAS CRUELES, INHUMANOS O DEGRADANTES EN EL ESTADO DE SINALOA | 1 | as first published: 8 June 2023 |
| `ley-por-la-que-se-establece-el-fondo-para-la-dotacion-y-mant/` | LEY POR LA QUE SE ESTABLECE EL FONDO PARA LA DOTACION Y MANTENIMIENTO DE EQUIPO Y PROGRAMAS DE COMPUTO A LOS PLANTELES DE EDUCACION PUBLICA BASICA DEL ESTADO DE SINALOA | 1 | as first published: 19 February 2000 |
| `ley-que-crea-el-instituto-de-seguridad-y-servicios-sociales/` | LEY QUE CREA EL INSTITUTO DE SEGURIDAD Y SERVICIOS SOCIALES DE LOS TRABAJADORES DE LA EDUCACION DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 14 March 1974 to 30 January 1978 |
| `ley-que-crea-la-institucion-publica-descentralizada-viveros/` | LEY QUE CREA LA INSTITUCION PUBLICA DESCENTRALIZADA VIVEROS DE SINALOA | 2 | as first published, then each reform: 25 November 1970 to 9 August 1994 |
| `ley-que-establece-el-catalago-de-pueblos-y-comunidades-indig/` | LEY QUE ESTABLECE EL CATALAGO DE PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE SINALOA | 2 | as first published, then each reform: 10 March 2018 to 26 May 2018 |
| `ley-que-establece-el-derecho-de-vias-de-las-carreteras-y-cam/` | LEY QUE ESTABLECE EL DERECHO DE VIAS DE LAS CARRETERAS Y CAMINOS LOCALES DEL ESTADO DE SINALOA | 1 | as first published: 17 February 2018 |
| `ley-que-establece-las-bases-normativas-para-la-expedicion-de/` | LEY QUE ESTABLECE LAS BASES NORMATIVAS PARA LA EXPEDICION DE LOS BANDOS DE POLICIA Y BUEN GOBIERNO DEL ESTADO DE SINALOA | 3 | as first published, then each reform: 2 May 1988 to 1 August 2017 |
| `ley-que-protege-la-salud-y-los-derechos-de-los-no-fumadores/` | LEY QUE PROTEGE LA SALUD Y LOS DERECHOS DE LOS NO FUMADORES PARA EL ESTADO DE SINALOA | 4 | as first published, then each reform: 11 May 2008 to 8 September 2022 |
| `ley-que-regula-el-aseguramiento-administracion-enajenacion-y/` | LEY QUE REGULA EL ASEGURAMIENTO, ADMINISTRACION, ENAJENACION Y DISPOSICION FINAL DE VEHICULOS AUTOMOTORES, ACCESORIOS O COMPONENTES ABANDONADOS DEL ESTADO DE SINALOA | 1 | as first published: 7 June 2018 |
| `ley-que-regula-la-prevencion-y-el-control-de-las-adicciones/` | LEY QUE REGULA LA PREVENCION Y EL CONTROL DE LAS ADICCIONES EN EL ESTADO DE SINALOA | 3 | as first published, then each reform: 27 March 2010 to 29 December 2016 |
| `ley-que-regula-las-casas-de-empeno-en-el-estado-de-sinaloa/` | LEY QUE REGULA LAS CASAS DE EMPEÑO EN EL ESTADO DE SINALOA | 2 | as first published, then each reform: 14 December 2016 to 28 December 2019 |
| `ley-reglamentaria-de-la-fraccion-iii-del-articulo-104-de-la/` | LEY REGLAMENTARIA DE LA FRACCION III, DEL ARTICULO 104 DE LA CONSTITUCION POLITICA DEL ESTADO DE SINALOA | 1 | as first published: 15 December 1998 |
| `ley-reglamentaria-del-articulo-154-reformado-de-la-constituc/` | LEY REGLAMENTARIA DEL ARTICULO 154, REFORMADO, DE LA CONSTITUCION POLITICA DEL ESTADO | 3 | as first published, then each reform: 13 February 1937 to 14 February 1954 |
| `ley-sobre-el-regimen-de-propiedad-en-condominio-de-inmuebles/` | LEY SOBRE EL REGIMEN DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE SINALOA | 2 | as first published, then each reform: 25 September 1973 to 18 January 1992 |
| `ley-sobre-el-sistema-estatal-de-asistencia-social/` | LEY SOBRE EL SISTEMA ESTATAL DE ASISTENCIA SOCIAL | 6 | as first published, then each reform: 27 June 1987 to 28 April 2018 |
| `ley-sobre-inmuebles/` | LEY SOBRE INMUEBLES DEL ESTADO Y MUNICIPIOS | 4 | as first published, then each reform: 21 January 1932 to 29 December 2007 |
| `ley-sobre-operacion-y-funcionamiento-de-establecimientos-des/` | LEY SOBRE OPERACION Y FUNCIONAMIENTO DE ESTABLECIMIENTOS DESTINADOS A LA PRODUCCION, DISTRIBUCION, VENTA Y CONSUMO DE BEBIDAS ALCOHOLICAS DEL ESTADO DE SINALOA | 4 | as first published, then each reform: 4 August 1998 to 1 January 2024 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mazatlan, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
