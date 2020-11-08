**Última actualización**: 2020-11-08 19:37:55 UTC

[![DOI](https://zenodo.org/badge/247552256.svg)](https://zenodo.org/badge/latestdoi/247552256)

[<img src="COVID-19 Data Hub - CONTRIBUTOR COVID-19 Data Hub - 2020-07-21.svg" width="100" align="right"/>](https://eu.badgr.com/public/assertions/nmrQrfZnQPmsV-ZcG8nrLA)

Motivación
----------

MINSA está publicando en su cuenta de Twitter y en la sección de
“Noticias” del portal del gobierno peruano, comunicados con información
sobre COVID-19, pero no hay un repositorio de datos abiertos que pueda
ser usado por todos.

Seguiré actualizando diariamente mientras esta información se encuentre
disponible.

Espero que pronto MINSA ponga un repositorio de datos abiertos con la
información nececasaria, y cuando eso ocurra, este repositorio ya no se
actualzará.

Importante
----------

**2020-03-03**: A partir de hoy, MINSA ha puesto una “Sala situacional”
oficial en
<a href="https://covid19.minsa.gob.pe/sala_situacional.asp" class="uri">https://covid19.minsa.gob.pe/sala_situacional.asp</a>.
Los datos de este día fueron tomados de las “Sala Situacional” del
MINSA, el cual no tiene información (al día de hoy) acerca del número de
recuperados

**2020-04-08**: A partir de hoy, en la “Sala situacional” se comenzaron
a publicar el número de casos confirmados por pruebas moleculares (PCR),
y por “pruebas rápidas” (serológicas) por cada región. Esto se ha
agregado a los datos.

**2020-04-12**: A partir de este día, la “Sala Situacional” ha dejado de
publicar el número de fallecimientos por región, y ha agregado el número
de casos positivos confirmados por ambos tipos de pruebas: moleculares
(PCR) y serológica (“rapida”).

**2020-04-13**: La “Sala Situacional” no fue actualizada en este día
(revisado a las 21:53h), por lo que no hay datos disponibles de pruebas
por región.

**2020-04-14**: La “Sala Situacional” está mostrando nuevamente los
fallecimientos y los resultados de pruebas positivas por región.

**2020-04-15**: La “Sala Situacional” ya no publica los casos en que se
confirmaron por ambos tipos de pruebas, para las regiones.

**2020-04-23**: Se ha ampliado la cuarentena hasta el 2020-05-10.
Cálculo del tiempo de duplicación cambiado a cada 5 días.

**2020-04-27**: En la “Sala Situacional” se ha comenzado a publicar el
número de camas UCI disponibles y en uso.

**2020-05-03**: MINSA no publicó hoy información acerca de las camas
UCI.

**2020-05-04**: MINSA no actualizó su “Sala Situacional” hoy [Captura de
pantalla del
2020-05-04](minsa-reportes/screenshot-covid19.minsa.gob.pe-2020.05.05-00_15_53.png),
de manera que no se ha actualizado ni el número de fallecimientos por
región, ni el número de positivos por tipo de prueba.

**2020-05-05**: MINSA nuevamente publicó su “Sala Situacional”
actualizada, incluyendo información de camas UCI.

**2020-05-06**: Desde hoy se pueden descargar los datos (parciales) de
la “Sala Situacional” del MINSA en formato XLSX

**2020-05-16**: He añadido los datos en formato JSON comprimido
(.json.gz) convertidos a partir de los CSV (Issue \#2)

**2020-05-18**: Desde hoy hay un API que han construído tomando este
repositorio como una fuente:
<a href="https://github.com/DataScienceResearchPeru/covid-19_latinoamerica" class="uri">https://github.com/DataScienceResearchPeru/covid-19_latinoamerica</a>

**2020-05-22**: El presidente anunció que el estado de emergencia se
extenderá hasta el 2020-06-30

**2020-05-28**: Usando los datos de positivad por departamento
publicados en la “Sala Situacional…” del MINSA, he podido recuperar el
número de negativos por departamento, desde el 2020-05-06 hasta hoy.

**2020-05-29**: Hasta las 22:40h (PET), no se han publicado nuevos datos
en la “Sala Situacional…”. Datos con menos detalle para el día de hoy.

**2020-05-30**: Los datos de ayer y hoy están disponibles en la “Sala
Situacional …”, la visualización es la correspondiente al día de hoy.

**2020-06-10**: Desde hoy ya no aparece en la “Sala Situacional …” el
archivo en formato XLSX con los datos de casos, se está reconstruyendo
de la visualización en el dashboard, en formato ISO OpenDocument (.ods)

**2020-06-11**: El archivo de casos aún no está disponible, el intentar
descargarlo produce un error **HTTP 404**

**2020-06-12**: Hasta las 18:30h (PET) no se ha actualizado la “Sala
Situacional …” del MINSA. La “Sala Situacional …” aparace actualizada
aparentemente a ~21:38h (según el timestamp de los archivos XLSX).

**2020-06-16**: La “Sala Situacional …” no incluye hoy información sobre
las camas UCI en uso o disponibles.

**2020-06-17**: Retornó la información sobre camas UCI en la “Sala
Situacional …”

**2020-07-05**: Hoy los datos del Departamento de Lima están separados
en Lima Metropolitana y Lima Región, en la “Sala Situacional …”

**2020-07-07**: A partir de hoy, en la información de la Sala
Situacional, la positividad de los resultados sólo está considerando los
que provienen de PCR, y ya no la suma de PCR + Pruebas serológicas. He
agregado una columna con el total de pruebas reportadas por cada
departamento.

**2020-07-18**: Hoy no han publicado archivos con datos en la Sala
Situacional (hasta las 18:30h), por lo que los datos han sido extraídos
de la visualización publicada.

**2020-07-20**: Hoy tampoco han publicado archivos con datos en la Sala
Situacional (hasta las 20:00h), por lo que los datos han sido extraídos
de la visualización publicada.

**2020-07-22**: En el comunicado 180 del MINSA se indica que se ha
revisado el número de fallecimientos para incluir a 3,688 casos
comprobados de COVID-19, pero esto no se refleja aún en los datos
publicados.

**2020-07-25**: Hoy, hasta las 20:35h, no se han publicado datos ni
actualizado la Sala Situacional, y el comunicado 183 no contiene
información por departamento. MINSA indica que han tenido problemas
técnicos (ref:
<a href="https://twitter.com/Minsa_Peru/status/1287111345024925697" class="uri">https://twitter.com/Minsa_Peru/status/1287111345024925697</a>)

**2020-07-26**: Hoy, hasta las 22:50h, no se han publicado datos ni
actualizado las Sala Situacional, y el comunicado 186 no contiene
información por departamento, ni los detalles de las pruebas que
usualmente se publican. (ref:
<a href="https://twitter.com/Minsa_Peru/status/1287587172892246016" class="uri">https://twitter.com/Minsa_Peru/status/1287587172892246016</a>)

**2020-07-27**: Tampoco hoy se ha actualizado (hasta las 20:00h) la
“Sala Situacional…”, y el comunicado 187 ya no contiene la información
por departamente, pero volvieron los detalle generales por tipo de
prueba. (ref:
<a href="https://www.gob.pe/institucion/minsa/noticias/216606-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-389-717-en-el-peru-comunicado-n-187" class="uri">https://www.gob.pe/institucion/minsa/noticias/216606-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-389-717-en-el-peru-comunicado-n-187</a>
y
<a href="https://twitter.com/Minsa_Peru/status/1287917699474042887" class="uri">https://twitter.com/Minsa_Peru/status/1287917699474042887</a>)

**2020-07-28**: Sala Situacional ha sido actualizada con datos al
2020-07-27, nuevamente los datos están disponibles en
<a href="https://covid19.minsa.gob.pe/sala_situacional.asp" class="uri">https://covid19.minsa.gob.pe/sala_situacional.asp</a>

**2020-07-30**: La “Sala Situacional…” no ha sido actualizada hasta las
23:30h de hoy. (Nota del 2020-07-31, 19:00h: aún se observan los datos
del 2020-07-29)

**2020-08-01**: Hoy se observan publicados los datos del 2020-07-30 en
la “Sala Situacional …”. El comunicado con información del 2020-07-31
fue publicado sin información por departamento. No hay datos en la “Sala
Situacional…” del 2020-07-31.

**2020-08-02**: Los datos del 2020-08-01 fueron publicados hoy en la
“Sala Situacional…”. Hoy salió el comunicado 194, con información
general, sin detalles por tipo de prueba ni por departamento.

**2020-08-03**: Hoy en la mañana salieron publicados en la “Sala
Situacional…” los datos del 2020-08-02, y por la noche los datos de hoy
(2020-08-03). Por tercer día consecutivo la información de camas UCI no
ha variado (los datos son los mismos para el 2020-08-01, el 2020-08-02 y
el 2020-08-03)

**2020-08-04**: Los datos de la “Sala Situacional …” fueron publicados,
pero el comunicado 196 tiene menos detalles que antes.

**2020-08-05**: Por quinto dia, ya no hay detalles sobre el número de
pruebas por tipo (moleculares o serológica), dejaré de actualizar esa
parte de la información por ahora.

**2020-08-06**: Los datos de UCI y de altas médicas se están repitiendo
con frecuencia de un día al siguiente.

**2020-08-11**: Desde el 2020-08-01, los datos de UCI y de altas médicas
no han cambiado, son exactamente los mismos.

**2020-08-17**: Los datos de UCI se están actualizando nuevamente, pero
la cifre de altas médicas en la Sala Situacional permanece inalterada
desde el 2020-08-02

**2020-09-03**: No se publicaron datos del 2020-09-02 en la Sala
Situacional, que permanece hasta hoy (22:45PET) con datos del 2020-09-01

**2020-09-22**: No se publicaron datos del 2020-09-21 en la Sala
Situacional. Hasta hoy (2020-09-22, 21:45PET) aparecen los datos del 20
de setiembre del 2020.

**2020-10-04**: Hasta las 23:50h de hoy no se han publicado los datoe
del 2020-10-03 en la Sala Situacional, pero si los del 2020-10-04

**2020-11-02**: Hasta las 20:00h de hoy, no han publicado en la Sala
Situacional, los datos del 2020-11-01

**2020-11-03**: Hasta las 23:10h de hoy, no han publicado en la Sala
Situacional, los datos del 2020-11-02

**2020-11-04**: Datos de casos, fallecimientos confirmados y pruebas por
departamento para 2020-11-01,02,03 han sido obtenidos de otra fuente,
pues la Sala Situacional del MINSA no ha sido actualizada en varios
dias. Debido a esto, los datos de “Lima Región” contienen el total del
departamento de Lima, y no se han desdoblado los valores para Lima
Metropolitana. - Datos del 2020-11-01: del documento
<a href="https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus311020.pdf" class="uri">https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus311020.pdf</a>
- Datos del 2020-11-02: del documento
<a href="https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus0111120.pdf" class="uri">https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus0111120.pdf</a>
- Datos del 2020-11-03: del documento
<a href="https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus0211120.pdf" class="uri">https://www.dge.gob.pe/portal/docs/tools/coronavirus/coronavirus0211120.pdf</a>

**2020-11-04**: A aproximadamente 18:50h, se actualizó la Sala
Situacional con datos de hoy

Fuentes
-------

-   [Cuenta de twitter del MINSA](https://twitter.com/Minsa_Peru)
-   [Noticias del
    MINSA](https://www.gob.pe/busquedas?contenido%5B%5D=noticias&institucion%5B%5D=minsa&reason=sheet&sheet=1)
    -   [RSS de Noticias del
        MINSA](https://www.gob.pe/busquedas.rss?contenido%5B%5D=noticias&institucion%5B%5D=minsa)
-   [Reportes del Centro Nacional de Epidemiología, Prevención y control
    de
    enfermedades](https://www.dge.gob.pe/portal/index.php?option=com_content&view=article&id=678)

Notas
-----

-   Códigos de UBIGEO de
    <a href="https://github.com/CONCYTEC/ubigeo-peru" class="uri">https://github.com/CONCYTEC/ubigeo-peru</a>
-   Códigos ISO-3166-2, usando el paquete en R `ISOcodes`:
    <a href="https://cran.r-project.org/package=ISOcodes" class="uri">https://cran.r-project.org/package=ISOcodes</a>
-   A partir del 2020-07-21, estoy usando los datos de población al
    2019, así como latitud y longitud de las capitales de departamento
    reportados por CEPLAN en:
    <a href="https://www.ceplan.gob.pe/informacion-sobre-zonas-y-departamentos-del-peru/" class="uri">https://www.ceplan.gob.pe/informacion-sobre-zonas-y-departamentos-del-peru/</a>
    -   Anteriormente se emplearon los datos de población por
        departamento (al 2017):
        <a href="https://www.inei.gob.pe/estadisticas/indice-tematico/poblacion-y-vivienda/" class="uri">https://www.inei.gob.pe/estadisticas/indice-tematico/poblacion-y-vivienda/</a>
-   El [reporte N°29 del
    MINSA](https://www.gob.pe/institucion/minsa/noticias/109838-minsa-casos-confirmados-por-coronavirus-covid-19-son-395-en-peru-comunicado-n-29)
    corrige el número de casos confirmados en Huánuco del [reporte N°
    28](https://www.gob.pe/institucion/minsa/noticias/109810-minsa-casos-confirmados-por-coronavirus-covid-19-son-363-en-peru-comunicado-n-28)
-   El dataset de JHU
    (<a href="https://github.com/CSSEGISandData/COVID-19" class="uri">https://github.com/CSSEGISandData/COVID-19</a>),
    indica que Perú tiene 14 recuperados el día 2020-03-26
-   En el dashboard se han agregado gráficos de la trayectoria total de
    casos, gráficos del número de recuperados y fallecidos, y un mapa
    con la densidad (casos por millón de personas) por región.

Visualizaciones
---------------

-   [Dashboard interactivo sobre COVID-19 en el
    Perú](https://castagnetto.site/peru/dashboard-peru-covid-19.html)

Formato de datos
----------------

-   Los datos se están guardando en formatos abiertos exclusivamente,
    para asegurar la mayor compatibilidad posible: CSV y OpenDocument
    (ISO/IEC 26300-1:2015, ISO/IEC 26300-2:2015, ISO/IEC 26300-3:2015)

Estructura de los archivos CSV
------------------------------

**`covid-19-peru-data.csv`**

-   country: Peru (país)
-   iso3c: PER (código ISO de 3 letras para Perú)
-   region: Departamento del Perú (sólo a partir del 2020-03-13)
-   date: Fecha en formato ISO (YYYY-MM-DD)
-   confirmed: Casos confirmados
-   deaths: Decesos
-   recovered: Recuperados
-   total\_tests: Número total de pruebas
-   negative\_tests Casos descartados/negativos
-   pcr\_test\_positive: Casos detectados con pruebas moleculares
-   serological\_test\_positive: Casos detectados con pruebas
    serológicas (“pruebas rápidas”)
-   pcr\_serological\_test\_positive: Casos detectados con pruebas
    moleculares y serológicas (“pruebas rápidas”)

**`covid-19-peru-data-augmented.csv`**

-   country: Peru (país)
-   iso3c: PER (código ISO de 3 letras para Perú)
-   region: Departamento del Perú (sólo a partir del 2020-03-13)
-   region\_orig: Denominación original de la región (a partir del
    2020-07-05)
-   ubigeo: UBIGEO del departamenteo (INEI)
-   iso\_3166\_2\_code: Códigos ISO-3166-2 para el Departamento.
-   date: Fecha en formato ISO (YYYY-MM-DD)
-   confirmed: Casos confirmados
-   deaths: Decesos
-   recovered: Recuperados
-   total\_tests: Número total de pruebas
-   negative\_tests Casos descartados/negativos
-   pcr\_test\_positive: Casos detectados con pruebas moleculares
-   serological\_test\_positive: Casos detectados con pruebas
    serológicas (“pruebas rápidas”)
-   pcr\_serological\_test\_positive: Casos detectados con pruebas
    moleculares y serológicas (“pruebas rápidas”)
-   zone: Zona geográfica: Centro, Norte ó Sur (CEPLAN)
-   pop2019: Población por departamento al 2019 (CEPLAN)
-   surface: Superficie en Km² (CEPLAN)
-   capital: Capital de Departamento (CEPLAN)
-   altitude: Altitude de la capital de departamento (CEPLAN)
-   lat: Latitud de la capital de departamento (CEPLAN)
-   lon: Longitud de la capital de departamento (CEPLAN)

**`covid-19-peru-fallecimientos.csv`**

-   fecha\_anuncio: Fecha en formato ISO (YYYY-MM-DD)
-   fecha\_fallecimiento: Fecha en formato ISO (YYYY-MM-DD)
-   fecha\_ingreso: Fecha en formato ISO (YYYY-MM-DD)
-   edad: en años
-   sexo: hombre/mujer
-   región: Departamento del Perú donde ocurrió el fallecimiento
-   viaje: País o región geográfica donde viajó la persona
-   contacto: Si la enfermadad se aquirió por contacto, la relación:
    amigo, familiar, etc.
-   contacto\_origen: Origne de la(s) persona(s) que contactaron y
    trajeron la enfermedad
-   lugar\_fallecimiento: hospital/casa/etc.
-   insuf\_resp: Si ingresó por insuficiencia respiratoria (1)
-   neumonia: Si ingresó por neumonía
-   otros\_síntomas: lista delimitada por “;” de otros síntomas
-   factores: si se conocen, otros factores (obesidad, asma, etc.)
-   misc: otra información
-   comunicado\_minsa: número del comunicado del MINSA

Información empleada para recolectar los datos
----------------------------------------------

Generales
---------

-   [Ministra de Salud exhortó a directores regionales implementar Plan
    Nacional por alerta mundial ante el
    COVID-19](https://www.gob.pe/institucion/minsa/noticias/84982-ministra-de-salud-exhorto-a-directores-regionales-implementar-plan-nacional-por-alerta-mundial-ante-el-covid-19)
    2020-02-25
-   [Ninguno de los 54 casos investigados ha resultado positivo por
    coronavirus](https://www.gob.pe/institucion/minsa/noticias/85190-ninguno-de-los-54-casos-investigados-ha-resultado-positivo-por-coronavirus)
    2020-02-28
-   [Ministerio de Salud aclara algunos mitos respecto al nuevo
    coronavirus
    Covid-19](https://www.gob.pe/institucion/minsa/noticias/85213-ministerio-de-salud-aclara-algunos-mitos-respecto-al-nuevo-coronavirus-covid-19)
    2020-02-29
-   [Minsa procesó 107 muestras por coronavirus COVID-19 y todas tienen
    resultado
    negativo](https://www.gob.pe/institucion/minsa/noticias/85332-minsa-proceso-107-muestras-por-coronavirus-covid-19-y-todas-tienen-resultado-negativo)
    2020-03-04
-   [Ministerio de Salud informa sobre resultado del procesamiento de
    muestras por coronavirus
    COVID-19](https://www.gob.pe/institucion/minsa/noticias/94105-ministerio-de-salud-informa-sobre-resultado-del-procesamiento-de-muestras-por-coronavirus-covid-19)
    2020-03-07
-   [Minsa brinda recomendaciones para la atención de una persona con
    coronavirus en
    casa](https://www.gob.pe/institucion/minsa/noticias/94095-minsa-brinda-recomendaciones-para-la-atencion-de-una-persona-con-coronavirus-en-casa)
    2020-03-07
-   [Número de nuevos casos de COVID – 19 está dentro de la curva
    esperada por
    autoridades](https://www.gob.pe/institucion/minsa/noticias/109581-numero-de-nuevos-casos-de-covid-19-esta-dentro-de-la-curva-esperada-por-autoridades)
    2020-03-19
-   [Minsa pone al alcance de la ciudadanía datos abiertos relacionados
    a la pandemia por
    Covid-19](https://www.gob.pe/institucion/minsa/noticias/163853-minsa-pone-al-alcance-de-la-ciudadania-datos-abiertos-relacionados-a-la-pandemia-por-covid-19)
    2020-05-22

Casos confirmados
-----------------

-   [Minsa procesó 155 muestras por coronavirus COVID-19 y una resultó
    positivo](https://www.gob.pe/institucion/minsa/noticias/108937-minsa-proceso-155-muestras-por-coronavirus-covid-19-y-una-resulto-positivo)
    2020-03-06
-   [Minsa procesó 219 muestras por coronavirus COVID-19 y 6 resultaron
    positivas](https://www.gob.pe/institucion/minsa/noticias/108938-minsa-proceso-219-muestras-por-coronavirus-covid-19-y-6-resultaron-positivas)
    2020-03-07
-   [Casos confirmados de coronavirus son importados y no existe
    transmisión
    comunitaria](https://www.gob.pe/institucion/minsa/noticias/94121-casos-confirmados-de-coronavirus-son-importados-y-no-existe-transmision-comunitaria)
    2020-03-08
-   [Minsa: Se elevaron a nueve los casos positivos por coronavirus
    COVID-19 tras analizarse 318
    muestras](https://www.gob.pe/institucion/minsa/noticias/108939-minsa-se-elevaron-a-nueve-los-casos-positivos-por-coronavirus-covid-19-tras-analizarse-318-muestras)
    2020-03-09
-   [Minsa: Se elevaron a once los casos positivos por coronavirus
    COVID-19 tras analizarse 346
    muestras](https://www.gob.pe/institucion/minsa/noticias/108940-minsa-se-elevaron-a-once-los-casos-positivos-por-coronavirus-covid-19-tras-analizarse-346-muestras)
    2020-03-10
-   [Minsa: Se elevaron a quince los casos positivos por coronavirus
    COVID-19 tras analizarse 656
    muestras](https://www.gob.pe/institucion/minsa/noticias/108943-minsa-se-elevaron-a-quince-los-casos-positivos-por-coronavirus-covid-19-tras-analizarse-656-muestras)
    2020-03-11
-   [Comunicado Oficial de Prensa - Coronavirus
    N°12](https://www.gob.pe/institucion/minsa/noticias/108935-comunicado-oficial-de-prensa-coronavirus-n-12)
    2020-03-15
-   [Comunicado Oficial de Prensa - Coronavirus
    N°13](https://www.gob.pe/institucion/minsa/noticias/108958-comunicado-oficial-de-prensa-coronavirus-n-13)
    2020-03-16
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 117
    (Comunicado
    N° 15)](https://www.gob.pe/institucion/minsa/noticias/109438-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-117-comunicado-n-15)
    2020-03-17
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 145
    (Comunicado
    N°17)](https://www.gob.pe/institucion/minsa/noticias/109467-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-145-comunicado-n-17)
    2020-03-18
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 263 y se han
    producido 4 fallecidos (Comunicado
    N° 23)](https://www.gob.pe/institucion/minsa/noticias/109657-minsa-casos-confirmados-por-coronavirus-covid-19-son-263-y-se-han-producido-4-fallecidos-comunicado-n-23)
    2020-03-20
-   [Minsa: El Perú presenta 318 personas diagnosticadas y 5 fallecidas
    por COVID-19 (Comunicado
    N°27)](https://www.gob.pe/institucion/minsa/noticias/109792-minsa-el-peru-presenta-318-personas-diagnosticadas-y-5-fallecidas-por-covid-19-comunicado-n-27)
    2020-03-21
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 395 en Perú
    (Comunicado
    N°29)](https://www.gob.pe/institucion/minsa/noticias/109838-minsa-casos-confirmados-por-coronavirus-covid-19-son-395-en-peru-comunicado-n-29)
    2020-03-23
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 363 en Perú
    (Comunicado
    N° 28)](https://www.gob.pe/institucion/minsa/noticias/109810-minsa-casos-confirmados-por-coronavirus-covid-19-son-363-en-peru-comunicado-n-28)
    2020-03-22
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 416 en Perú
    (Comunicado
    N°31)](https://www.gob.pe/institucion/minsa/noticias/109942-minsa-casos-confirmados-por-coronavirus-covid-19-son-416-en-peru-comunicado-n-31)
    2020-03-24
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 480 en Perú
    (Comunicado
    N°33)](https://www.gob.pe/institucion/minsa/noticias/110065-minsa-casos-confirmados-por-coronavirus-covid-19-son-480-en-peru-comunicado-n-33)
    2020-03-25
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 580 en Perú
    (Comunicado
    N°34)](https://www.gob.pe/institucion/minsa/noticias/111476-minsa-casos-confirmados-por-coronavirus-covid-19-son-580-en-peru-comunicado-n-34)
    2020-03-26
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 635 en Perú
    (Comunicado
    N°36)](https://www.gob.pe/institucion/minsa/noticias/111543-minsa-casos-confirmados-por-coronavirus-covid-19-son-635-en-peru-comunicado-n-36)
    2020-03-27
-   [Minsa: Casos confirmados por coronavirus COVID-19 asciende a 671 en
    el Perú (Comunicado
    N°38)](https://www.gob.pe/institucion/minsa/noticias/111568-minsa-casos-confirmados-por-coronavirus-covid-19-asciende-a-671-en-el-peru-comunicado-n-38)
    2020-03-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 852
    en el Perú (Comunicado
    N° 40)](https://www.gob.pe/institucion/minsa/noticias/111590-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-852-en-el-peru-comunicado-n-40)
    2020-03-29
-   [Minsa: Casos confirmados por Coronavirus COVID-19 asciende a 950 en
    el Perú (Comunicado
    N°41)](https://www.gob.pe/institucion/minsa/noticias/111623-minsa-casos-confirmados-por-coronavirus-covid-19-asciende-a-950-en-el-peru-comunicado-n-41)
    2020-03-30
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 1065
    en el Perú (Comunicado
    N°44)](https://www.gob.pe/institucion/minsa/noticias/111653-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-1065-en-el-peru-comunicado-n-44)
    2020-03-31
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 1323
    en el Perú (Comunicado
    N°46)](https://www.gob.pe/institucion/minsa/noticias/111718-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-1323-en-el-peru-comunicado-n-46)
    2020-04-01
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 1414
    en el Perú (Comunicado
    N°49)](https://www.gob.pe/institucion/minsa/noticias/111774-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-1414-en-el-peru-comunicado-n-499)
    2020-04-02
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 2281
    en el Perú (Comunicado
    N°55)](https://www.gob.pe/institucion/minsa/noticias/111888-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-2281-en-el-peru-comunicado-n-55)
    2020-04-05
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 2561
    en el Perú (Comunicado
    N°56)](https://www.gob.pe/institucion/minsa/noticias/111994-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-2561-en-el-peru-comunicado-n-56)
    2020-04-06
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 2 954
    en el Perú (Comunicado
    N° 57)](https://www.gob.pe/institucion/minsa/noticias/112042-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-2-954-en-el-peru-comunicado-n-57)
    2020-04-07
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 4 342
    en el Perú (Comunicado
    N°58)](https://www.gob.pe/institucion/minsa/noticias/112079-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-4-342-en-el-peru-comunicado-n-58)
    2020-04-08
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 5 256
    en el Perú (Comunicado
    N°60)](https://www.gob.pe/institucion/minsa/noticias/112117-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-5-256-en-el-peru-comunicado-n-60)
    2020-04-09
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 5 897
    en el Perú (Comunicado
    N°61](https://www.gob.pe/institucion/minsa/noticias/112148-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-5-897-en-el-peru-comunicado-n-61)
    2020-04-10
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 6 848
    en el Perú (Comunicado
    N° 62)](https://www.gob.pe/institucion/minsa/noticias/112163-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-6-848-en-el-peru-comunicado-n-62)
    2020-04-11
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 7 519
    en el Perú (Comunicado
    N° 63)](https://www.gob.pe/institucion/minsa/noticias/112194-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-7-519-en-el-peru-comunicado-n-63)
    2020-04-12
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 9 784
    en el Perú (Comunicado
    N°64)](https://www.gob.pe/institucion/minsa/noticias/112315-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-9-784-en-el-peru-comunicado-n-64)
    2020-04-13
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 10
    303 en el Perú (Comunicado
    N° 65)](https://www.gob.pe/institucion/minsa/noticias/112670-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-10-303-en-el-peru-comunicado-n-65)
    2020-04-14
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 11
    475 en el Perú (Comunicado
    N° 66)](https://www.gob.pe/institucion/minsa/noticias/125568-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-11-475-en-el-peru-comunicado-n-66)
    2020-04-15
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 12
    491 en el Perú ( Comunicado
    N°67)](https://www.gob.pe/institucion/minsa/noticias/126023-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-12-491-en-el-peru-comunicado-n-67)
    2020-04-16
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 13
    489 en el Perú (Comunicado
    N° 68)](https://www.gob.pe/institucion/minsa/noticias/126083-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-13-489-en-el-peru-comunicado-n-68)
    2020-04-17
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 14
    420 en el Perú (Comunicado
    N° 69)](https://www.gob.pe/institucion/minsa/noticias/126136-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-14-420-en-el-peru-comunicado-n-69)
    2020-04-18
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 15
    628 en el Perú (Comunicado
    N° 70)](https://www.gob.pe/institucion/minsa/noticias/126658-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-15-628-en-el-peru-comunicado-n-70)
    2020-04-19
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 16
    325 en el Perú ( Comunicado
    N° 72)](https://www.gob.pe/institucion/minsa/noticias/126686-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-16-325-en-el-peru-comunicado-n-72)
    2020-04-20
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 17
    837 (Comunicado
    N° 73)](https://www.gob.pe/institucion/minsa/noticias/126735-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-17-837-comunicado-n-73)
    2020-04-21
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 19
    250 en el Perú (Comunicado
    N° 74)](https://www.gob.pe/institucion/minsa/noticias/127404-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-19-250-en-el-peru-comunicado-n-74)
    2020-04-22
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 20
    914 en el Perú ( Comunicado
    N° 75)](https://www.gob.pe/institucion/minsa/noticias/127667-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-20-914-en-el-peru-comunicado-n-75)
    2020-04-23
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 21
    648 en el Perú (Comunicado
    N° 76)](https://www.gob.pe/institucion/minsa/noticias/128059-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-21-648-en-el-peru-comunicado-n-76)
    2020-04-24
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 25
    331 en el Perú ( Comunicado
    N° 77)](https://www.gob.pe/institucion/minsa/noticias/131646-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-25-331-en-el-peru-comunicado-n-77)
    2020-04-25
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 27
    517 en el Perú (Comunicado
    N° 78)](https://www.gob.pe/institucion/minsa/noticias/131667-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-27-517-en-el-peru-comunicado-n-78)
    2020-04-26
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 28
    699 en el Perú (Comunicado
    N° 79)](https://www.gob.pe/institucion/minsa/noticias/140641-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-28-699-en-el-peru-comunicado-n-79)
    2020-04-27
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 31
    190 en el Perú (Comunicado
    N° 80)](https://www.gob.pe/institucion/minsa/noticias/141088-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-31-190-en-el-peru-comunicado-n-80)
    2020-04-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 33
    931 (Comunicado
    N° 81)](https://www.gob.pe/institucion/minsa/noticias/142136-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-33-931-comunicado-n-81)
    2020-04-29
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 36
    976 en el Perú ( Comunicado
    N° 82)](https://www.gob.pe/institucion/minsa/noticias/143118-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-36-976-en-el-peru-comunicado-n-82)
    2020-04-30
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 40
    459 en el Perú (Comunicado
    N° 84)](https://www.gob.pe/institucion/minsa/noticias/143593-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-40-459-en-el-peru-comunicado-n-84)
    2020-05-01
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 42
    534 (Comunicado
    N° 85)](https://www.gob.pe/institucion/minsa/noticias/143615-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-42-534-comunicado-n-85)
    2020-05-02
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 45
    928 en el Perú ( Comunicado
    N° 86)](https://www.gob.pe/institucion/minsa/noticias/143664-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-45-928-en-el-peru-comunicado-n-86)
    2020-05-03
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 47
    372 en el Perú (Comunicado
    N° 87)](https://www.gob.pe/institucion/minsa/noticias/143693-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-47-372-en-el-peru-comunicado-n-87)
    2020-05-04
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 51
    189 en el Perú (Comunicado
    N° 88)](https://www.gob.pe/institucion/minsa/noticias/147296-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-51-189-en-el-peru-comunicado-n-88)
    2020-05-05
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 54
    817 en el Perú ( Comunicado
    N° 89)](https://www.gob.pe/institucion/minsa/noticias/148899-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-54-817-en-el-peru-comunicado-n-89)
    2020-05-06
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 58
    526 en el Perú (Comunicado
    N° 90)](https://www.gob.pe/institucion/minsa/noticias/151042-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-58-526-en-el-peru-comunicado-n-90)
    2020-05-07
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 61
    847 en el Perú ( Comunicado
    N° 91)](https://www.gob.pe/institucion/minsa/noticias/151127-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-61-847-en-el-peru-comunicado-n-91)
    2020-05-08
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 65
    015 en el Perú ( Comunicado
    N° 95)](https://www.gob.pe/institucion/minsa/noticias/151163-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-65-015-en-el-peru-comunicado-n-95)
    2020-05-09
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 67
    307 en el Perú ( Comunicado
    N° 96)](https://www.gob.pe/institucion/minsa/noticias/151197-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-67-307-en-el-peru-comunicado-n-96)
    2020-05-10
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 68
    822 en el Perú ( Comunicado
    N° 97)](https://www.gob.pe/institucion/minsa/noticias/152560-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-68-822-en-el-peru-comunicado-n-97)
    2020-05-11
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 72
    059 en el Perú ( Comunicado
    N° 98)](https://www.gob.pe/institucion/minsa/noticias/152809-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-72-059-en-el-peru-comunicado-n-98)
    2020-05-12
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 76
    306 en el Perú ( Comunicado
    N° 99)](https://www.gob.pe/institucion/minsa/noticias/154047-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-76-306-en-el-peru-comunicado-n-99)
    2020-05-13
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 80
    604 en el Perú ( Comunicado
    N° 100)](https://www.gob.pe/institucion/minsa/noticias/154687-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-80-604-en-el-peru-comunicado-n-100)
    2020-05-14
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 84
    495 en el Perú ( Comunicado
    N° 101)](https://www.gob.pe/institucion/minsa/noticias/154736-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-84-495-en-el-peru-comunicado-n-101)
    2020-05-15
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 88
    541 en el Perú ( Comunicado
    N° 102)](https://www.gob.pe/institucion/minsa/noticias/156940-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-88-541-en-el-peru-comunicado-n-102)
    2020-05-16
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 92
    273 en el Perú ( Comunicado
    N° 103)](https://www.gob.pe/institucion/minsa/noticias/157471-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-92-273-en-el-peru-comunicado-n-103)
    2020-05-17
-   [Minsa: Casos confirmados por coronavirus COVID-19 ascienden a 94
    933 en el Perú ( Comunicado
    N° 104)](https://www.gob.pe/institucion/minsa/noticias/157506-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-94-933-en-el-peru-comunicado-n-104)
    2020-05-18
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 99
    483 en el Perú ( Comunicado
    N° 105)](https://www.gob.pe/institucion/minsa/noticias/157559-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-99-483-en-el-peru-comunicado-n-105)
    2020-05-19
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 104
    020 en el Perú ( Comunicado
    N° 106)](https://www.gob.pe/institucion/minsa/noticias/159364-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-104-020-en-el-peru-comunicado-n-106)
    2020-05-20
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 108
    769 en el Perú ( Comunicado
    N° 107)](https://www.gob.pe/institucion/minsa/noticias/162379-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-108-769-en-el-peru-comunicado-n-107)
    2020-05-21
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 111
    698 en el Perú ( Comunicado
    N° 108)](https://www.gob.pe/institucion/minsa/noticias/163116-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-111-698-en-el-peru-comunicado-n-108)
    2020-05-22
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 115
    754 ( Comunicado
    N° 109)](https://www.gob.pe/institucion/minsa/noticias/164292-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-115-754-comunicado-n-109)
    2020-05-23
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 119
    959 en el Perú ( Comunicado
    N° 110)](https://www.gob.pe/institucion/minsa/noticias/164455-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-119-959-en-el-peru-comunicado-n-110)
    2020-05-24
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 123
    979 en el Perú ( Comunicado
    N° 111)](https://www.gob.pe/institucion/minsa/noticias/165699-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-123-979-en-el-peru-comunicado-n-111)
    2020-05-25
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 129
    751 en el Perú ( Comunicado
    N° 112)](https://www.gob.pe/institucion/minsa/noticias/165778-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-129-751-en-el-peru-comunicado-n-112)
    2020-05-26
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 135
    905 en el Perú (Comunicado
    N° 113)](https://www.gob.pe/institucion/minsa/noticias/165852-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-135-905-en-el-peru-comunicado-n-113)
    2020-05-27
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 141
    779 en el Perú (Comunicado
    N° 114)](https://www.gob.pe/institucion/minsa/noticias/166078-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-141-779-en-el-peru-comunicado-n-114)
    2020-05-28
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 148
    285 en el Perú (Comunicado
    N°115)](https://www.gob.pe/institucion/minsa/noticias/167830-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-148-285-en-el-peru-comunicado-n-115)
    2020-05-29
-   [Minsa: Casos confirmados por Coronavirus COVID-19 ascienden a 155
    671 en el Perú (Comunicado
    N° 116)](https://www.gob.pe/institucion/minsa/noticias/168017-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-155-671-en-el-peru-comunicado-n-116)
    2020-05-30
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 164
    476 en el Perú (Comunicado
    N° 117)](https://www.gob.pe/institucion/minsa/noticias/168047-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-164-476-en-el-peru-comunicado-n-117)
    2020-05-31
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 170
    039 en el Perú (Comunicado
    N° 118)](https://www.gob.pe/institucion/minsa/noticias/168206-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-170-039-en-el-peru-comunicado-n-118)
    2020-06-01
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 174
    884 en el Perú ( Comunicado
    N° 119)](https://www.gob.pe/institucion/minsa/noticias/170945-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-174-884-en-el-peru-comunicado-n-119)
    2020-06-02
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 178
    914 en el Perú ( Comunicado
    N° 120)](https://www.gob.pe/institucion/minsa/noticias/176156-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-178-914-en-el-peru-comunicado-n-120)
    2020-06-03
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 183
    198 en el Perú (Comunicado
    N° 121)](https://www.gob.pe/institucion/minsa/noticias/177267-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-183-198-en-el-peru-comunicado-n-121)
    2020-06-04
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 187
    400 en el Perú (Comunicado
    N° 122)](https://www.gob.pe/institucion/minsa/noticias/181047-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-187-400-en-el-peru-comunicado-n-122)
    2020-06-05
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 191
    758 en el Perú ( Comunicado
    N° 123)](https://www.gob.pe/institucion/minsa/noticias/183570-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-191-758-en-el-peru-comunicado-n-123)
    2020-06-06
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 196
    515 en el Perú (Comunicado
    N° 124)](https://www.gob.pe/institucion/minsa/noticias/183657-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-196-515-en-el-peru-comunicado-n-124)
    2020-06-07
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 199
    696 en el Perú ( Comunicado
    N° 125)](https://www.gob.pe/institucion/minsa/noticias/184246-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-199-696-en-el-peru-comunicado-n-125)
    2020-06-08
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 203
    736 en el Perú (Comunicado
    N° 126)](https://www.gob.pe/institucion/minsa/noticias/185100-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-203-736-en-el-peru-comunicado-n-126)
    2020-06-09
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 208
    823 en el Perú (Comunicado
    N° 128)](https://www.gob.pe/institucion/minsa/noticias/185212-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-208-823-en-el-peru-comunicado-n-128)
    2020-06-10
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 214
    788 en el Perú (Comunicado
    N° 129)](https://www.gob.pe/institucion/minsa/noticias/186578-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-214-788-en-el-peru-comunicado-n-129)
    2020-06-11
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 220
    749 en el Perú (Comunicado
    N° 130)](https://www.gob.pe/institucion/minsa/noticias/186668-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-220-749-en-el-peru-comunicado-n-130)
    2020-06-12
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 225
    132 en el Perú (Comunicado
    N° 131)](https://www.gob.pe/institucion/minsa/noticias/186726-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-225-132-en-el-peru-comunicado-n-131)
    2020-06-13
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 229
    736 en el Perú (Comunicado
    N° 132)](https://www.gob.pe/institucion/minsa/noticias/186742-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-229-736-en-el-peru-comunicado-n-132)
    2020-06-14
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 232
    992 en el Perú (Comunicado
    N° 133)](https://www.gob.pe/institucion/minsa/noticias/187253-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-232-992-en-el-peru-comunicado-n-133)
    2020-06-15
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 237
    156 en el Perú (Comunicado
    N° 134)](https://www.gob.pe/institucion/minsa/noticias/187343-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-237-156-en-el-peru-comunicado-n-134)
    2020-06-16
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 240
    908 en el Perú (Comunicado
    N° 135)](https://www.gob.pe/institucion/minsa/noticias/187441-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-240-908-en-el-peru-comunicado-n-135)
    2020-06-17
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 244
    388 en el Perú (Comunicado
    N° 137)](https://www.gob.pe/institucion/minsa/noticias/187617-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-244-388-en-el-peru-comunicado-n-137)
    2020-06-18
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 247
    925 en el Perú (Comunicado
    N° 138)](https://www.gob.pe/institucion/minsa/noticias/187714-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-247-925-en-el-peru-comunicado-n-138)
    2020-06-19
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 251
    338 en el Perú (Comunicado
    N° 139)](https://www.gob.pe/institucion/minsa/noticias/187808-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-251-338-en-el-peru-comunicado-n-139)
    2020-06-20
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 254
    936 en el Perú (Comunicado
    N° 140)](https://www.gob.pe/institucion/minsa/noticias/187849-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-254-936-en-el-peru-comunicado-n-140)
    2020-06-21
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 257
    447 en el Perú (Comunicado
    N° 142)](https://www.gob.pe/institucion/minsa/noticias/188019-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-257-447-en-el-peru-comunicado-n-142)
    2020-06-22
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 260
    810 en el Perú (Comunicado
    N° 143)](https://www.gob.pe/institucion/minsa/noticias/188228-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-260-810-en-el-peru-comunicado-n-143)
    2020-06-23
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 264
    689 en el Perú (Comunicado
    N° 144)](https://www.gob.pe/institucion/minsa/noticias/188353-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-264-689-en-el-peru-comunicado-n-144)
    2020-06-24
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 268
    602 en el Perú (Comunicado
    N° 146)](https://www.gob.pe/institucion/minsa/noticias/188959-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-268-602-en-el-peru-comunicado-n-146)
    2020-06-25
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 272
    364 en el Perú (Comunicado
    N° 147)](https://www.gob.pe/institucion/minsa/noticias/189091-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-272-364-en-el-peru-comunicado-n-147)
    2020-06-26
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 275
    989 en el Perú (Comunicado
    N° 149)](https://www.gob.pe/institucion/minsa/noticias/189171-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-275-989-en-el-peru-comunicado-n-149)
    2020-06-27
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 279
    419 en el Perú (Comunicado
    N° 151)](https://www.gob.pe/institucion/minsa/noticias/189224-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-279-419-en-el-peru-comunicado-n-151)
    2020-06-28
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 282
    365 en el Perú (Comunicado
    N° 152)](https://www.gob.pe/institucion/minsa/noticias/189255-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-282-365-en-el-peru-comunicado-n-152)
    2020-06-29
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 285
    213 en el Perú (Comunicado
    N° 153)](https://www.gob.pe/institucion/minsa/noticias/189369-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-285-213-en-el-peru-comunicado-n-153)
    2020-06-30
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 288
    477 en el Perú (Comunicado
    N° 154)](https://www.gob.pe/institucion/minsa/noticias/189512-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-288-477-en-el-peru-comunicado-n-154)
    2020-07-01
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a 292
    004 en el Perú ( Comunicado
    N° 155)](https://www.gob.pe/institucion/minsa/noticias/189644-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-292-004-en-el-peru-comunicado-n-155)
    2020-07-02
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    295,599 en el Perú (Comunicado
    N° 156)](https://www.gob.pe/institucion/minsa/noticias/189954-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-295-599-en-el-peru-comunicado-n-156)
    2020-07-03
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    299,080 en el Perú (Comunicado
    N° 157)](https://www.gob.pe/institucion/minsa/noticias/192057-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-299-080-en-el-peru-comunicado-n-157)
    2020-07-04
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    302,718 en el Perú (Comunicado
    N° 158)](https://www.gob.pe/institucion/minsa/noticias/192090-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-302-718-en-el-peru-comunicado-n-158)
    2020-07-05
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    305,703 en el Perú (Comunicado
    N° 159)](https://www.gob.pe/institucion/minsa/noticias/192214-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-305-703-en-el-peru-comunicado-n-159)
    2020-07-06
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    309,278 en el Perú (Comunicado
    N° 160)](https://www.gob.pe/institucion/minsa/noticias/194395-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-309-278-en-el-peru-comunicado-n-160)
    2020-07-07
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    312,911 en el Perú (Comunicado
    N° 162)](https://www.gob.pe/institucion/minsa/noticias/195042-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-312-911-en-el-peru-comunicado-n-162)
    2020-07-08
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    316,448 en el Perú (Comunicado
    N° 164)](https://www.gob.pe/institucion/minsa/noticias/201526-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-316-448-en-el-peru-comunicado-n-164)
    2020-07-09
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    319,646 en el Perú (Comunicado
    N° 166)](https://www.gob.pe/institucion/minsa/noticias/201740-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-319-646-en-el-peru-comunicado-n-166)
    2020-07-10
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    322,710 en el Perú (Comunicado
    N° 167)](https://www.gob.pe/institucion/minsa/noticias/206493-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-322-710-en-el-peru-comunicado-n-167)
    2020-07-11
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    326,326 en el Perú (Comunicado
    N° 168)](https://www.gob.pe/institucion/minsa/noticias/206653-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-326-326-en-el-peru-comunicado-n-168)
    2020-07-12
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    330,123 en el Perú (Comunicado
    N° 169)](https://www.gob.pe/institucion/minsa/noticias/206859-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-330-123-en-el-peru-comunicado-n-169)
    2020-07-13
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    333,867 en el Perú (Comunicado
    N° 170)](https://www.gob.pe/institucion/minsa/noticias/208805-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-333-867-en-el-peru-comunicado-n-170)
    2020-07-14
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    337,724 en el Perú (Comunicado
    N° 172)](https://www.gob.pe/institucion/minsa/noticias/209134-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-337-724-en-el-peru-comunicado-n-172)
    2020-07-15
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    341,586 en el Perú (Comunicado
    N° 173)](https://www.gob.pe/institucion/minsa/noticias/212171-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-341-586-en-el-peru-comunicado-n-173)
    2020-07-16
-   [Minsa: Casos confirmados por Coronavirus Covid-19 ascienden a
    345,537 en el Perú (Comunicado
    N° 174)](https://www.gob.pe/institucion/minsa/noticias/212348-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-345-537-en-el-peru-comunicado-n-174)
    2020-07-17
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    349,500 en el Perú (Comunicado
    N° 175)](https://www.gob.pe/institucion/minsa/noticias/212409-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-349-500-en-el-peru-comunicado-n-175)
    2020-07-18
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    353,590 en el Perú (Comunicado
    N° 176)](https://www.gob.pe/institucion/minsa/noticias/212460-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-353-590-en-el-peru-comunicado-n-176)
    2020-07-19
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    357,681 en el Perú (Comunicado
    N° 177)](https://www.gob.pe/institucion/minsa/noticias/213880-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-357-681-en-el-peru-comunicado-n-177)
    2020-07-20
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 362
    087 en el Perú (Comunicado
    N° 179)](Minsa:%20Casos%20confirmados%20por%20coronavirus%20Covid-19%20ascienden%20a%20362%20087%20en%20el%20Perú%20(Comunicado%20N°%20179))
    2020-07-21
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 366
    550 en el Perú (Comunicado
    N° 180)](https://www.gob.pe/institucion/minsa/noticias/214828-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-366-550-en-el-peru-comunicado-n-180)
    2020-07-22
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    371,096 en el Perú (Comunicado
    N° 181)](https://www.gob.pe/institucion/minsa/noticias/215539-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-371-096-en-el-peru-comunicado-n-181)
    2020-07-23
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    375,961 en el Perú (Comunicado
    N° 182)](https://www.gob.pe/institucion/minsa/noticias/215609-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-375-961-en-el-peru-comunicado-n-182)
    2020-07-24
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    379,884 en el Perú (Comunicado
    N° 183)](https://www.gob.pe/institucion/minsa/noticias/215997-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-379-884-en-el-peru-comunicado-n-183)
    2020-07-25
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    384,797 en el Perú (Comunicado
    N° 186)](https://www.gob.pe/institucion/minsa/noticias/216085-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-384-797-en-el-peru-comunicado-n-186)
    2020-07-26
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    389,717 en el Perú (Comunicado
    N° 187)](https://www.gob.pe/institucion/minsa/noticias/216606-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-389-717-en-el-peru-comunicado-n-187)
    2020-07-27
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    395,005 en el Perú (Comunicado
    N° 189)](https://www.gob.pe/institucion/minsa/noticias/217502-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-395-005-en-el-peru-comunicado-n-189)
    2020-07-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    400,683 en el Perú (Comunicado
    N° 190)](https://www.gob.pe/institucion/minsa/noticias/217840-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-400-683-en-el-peru-comunicado-n-190)
    2020-07-29
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    407,492 en el Perú (Comunicado
    N° 191)](https://www.gob.pe/institucion/minsa/noticias/218573-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-407-492-en-el-peru-comunicado-n-191)
    2020-07-30
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    414,735 en el Perú (Comunicado
    N° 192)](https://www.gob.pe/institucion/minsa/noticias/232456-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-414-735-en-el-peru-comunicado-n-192)
    2020-07-31
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a
    422,183 en el Perú (Comunicado
    N° 193)](https://www.gob.pe/institucion/minsa/noticias/285675-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-422-183-en-el-peru-comunicado-n-193)
    2020-08-01
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 428
    850 en el Perú (Comunicado
    N° 194)](https://www.gob.pe/institucion/minsa/noticias/285932-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-428-850-en-el-peru-comunicado-n-194)
    2020-08-02
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 433
    100 en el Perú (Comunicado
    N° 195)](https://www.gob.pe/institucion/minsa/noticias/286023-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-433-100-en-el-peru-comunicado-n-195)
    2020-08-03
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 439
    890 en el Perú (Comunicado
    N° 196)](https://www.gob.pe/institucion/minsa/noticias/286196-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-439-890-en-el-peru-comunicado-n-196)
    2020-08-04
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 447
    624 en el Perú (Comunicado
    N°197)](https://www.gob.pe/institucion/minsa/noticias/286399-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-447-624-en-el-peru-comunicado-n-197)
    2020-08-05
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 455
    409 en el Perú (Comunicado
    N° 198)](https://www.gob.pe/institucion/minsa/noticias/286697-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-455-409-en-el-peru-comunicado-n-198)
    2020-08-06
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 463
    875 en el Perú (Comunicado
    N° 199)](https://www.gob.pe/institucion/minsa/noticias/286898-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-463-875-en-el-peru-comunicado-n-199)
    2020-08-07
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 471
    012 en el Perú (Comunicado
    N° 200)](https://www.gob.pe/institucion/minsa/noticias/286956-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-471-012-en-el-peru-comunicado-n-200)
    2020-08-08
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 478
    024 en el Perú (Comunicado
    N° 201)](https://www.gob.pe/institucion/minsa/noticias/286993-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-478-024-en-el-peru-comunicado-n-201)
    2020-08-09
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 483
    133 en el Perú (Comunicado
    N° 202)](https://www.gob.pe/institucion/minsa/noticias/287217-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-483-133-en-el-peru-comunicado-n-202)
    2020-08-10
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 489
    680 en el Perú (Comunicado
    N° 203)](https://www.gob.pe/institucion/minsa/noticias/287394-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-489-680-en-el-peru-comunicado-n-203)
    2020-08-11
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 498
    555 en el Perú (Comunicado
    N°204)](https://www.gob.pe/institucion/minsa/noticias/288677-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-498-555-en-el-peru-comunicado-n-204)
    2020-08-12
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 507
    996 en el Perú (Comunicado
    N°205)](https://www.gob.pe/institucion/minsa/noticias/292650-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-507-996-en-el-peru-comunicado-n-205)
    2020-08-13
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 516
    296 en el Perú (Comunicado
    N° 206)](https://www.gob.pe/institucion/minsa/noticias/293996-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-516-296-en-el-peru-comunicado-n-206)
    2020-08-14
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 525
    803 en el Perú (Comunicado
    N°207)](https://www.gob.pe/institucion/minsa/noticias/294082-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-525-803-en-el-peru-comunicado-n-207)
    2020-08-15
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 535
    946 en el Perú (Comunicado
    N°209)](https://www.gob.pe/institucion/minsa/noticias/294125-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-535-946-en-el-peru-comunicado-n-209)
    2020-08-16
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 541
    493 en el Perú (Comunicado
    N°210)](https://www.gob.pe/institucion/minsa/noticias/294332-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-541-493-en-el-peru-comunicado-n-210)
    2020-08-17
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 549
    321 en el Perú (Comunicado
    N° 211)](https://www.gob.pe/institucion/minsa/noticias/294481-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-549-321-en-el-peru-comunicado-n-211)
    2020-08-18
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 558
    420 en el Perú (Comunicado
    N°212)](https://www.gob.pe/institucion/minsa/noticias/294661-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-558-420-en-el-peru-comunicado-n-212)
    2020-08-19
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 567
    059 en el Perú (Comunicado
    N°213)](https://www.gob.pe/institucion/minsa/noticias/294925-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-567-059-en-el-peru-comunicado-n-213)
    2020-08-20
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 576
    067 en el Perú (Comunicado
    N°214)](https://www.gob.pe/institucion/minsa/noticias/295099-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-576-067-en-el-peru-comunicado-n-214)
    2020-08-21
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 585
    236 en el Perú (Comunicado
    N°215)](https://www.gob.pe/institucion/minsa/noticias/295188-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-585-236-en-el-peru-comunicado-n-215)
    2020-08-22
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 594
    326 en el Perú (Comunicado
    N°216)](https://www.gob.pe/institucion/minsa/noticias/295231-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-594-326-en-el-peru-comunicado-n-216)
    2020-08-23
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 600
    438 en el Perú (Comunicado
    N° 217)](https://www.gob.pe/institucion/minsa/noticias/295475-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-600-438-en-el-peru-comunicado-n-217)
    2020-08-24
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 607
    382 en el Perú (Comunicado
    N° 218)](https://www.gob.pe/institucion/minsa/noticias/295756-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-607-382-en-el-peru-comunicado-n-218)
    2020-08-25
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 613
    378 en el Perú (Comunicado
    N° 220)](https://www.gob.pe/institucion/minsa/noticias/296294-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-613-378-en-el-peru-comunicado-n-220)
    2020-08-26
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 621
    997 en el Perú (Comunicado
    N° 221)](https://www.gob.pe/institucion/minsa/noticias/296517-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-621-997-en-el-peru-comunicado-n-221)
    2020-08-27
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 629
    961 en el Perú (Comunicado
    N°222)](https://www.gob.pe/institucion/minsa/noticias/296816-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-629-961-en-el-peru-comunicado-n-222)
    2020-08-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 639
    435 en el Perú (Comunicado
    N°223)](https://www.gob.pe/institucion/minsa/noticias/296867-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-639-435-en-el-peru-comunicado-n-223)
    2020-08-29
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 647
    166 en el Perú (Comunicado
    N°224)](https://www.gob.pe/institucion/minsa/noticias/296927-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-647-166-en-el-peru-comunicado-n-224)
    2020-08-30
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 652
    037 en el Perú (Comunicado
    N°225)](https://www.gob.pe/institucion/minsa/noticias/297141-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-652-037-en-el-peru-comunicado-n-225)
    2020-08-31
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 657
    129 en el Perú (Comunicado
    N°226)](https://www.gob.pe/institucion/minsa/noticias/297365-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-657-129-en-el-peru-comunicado-n-226))
    2020-09-01
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 663
    437 en el Perú (Comunicado
    N°227)](https://www.gob.pe/institucion/minsa/noticias/297602-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-663-437-en-el-peru-comunicado-n-227)
    2020-09-02
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 670
    145 en el Perú (Comunicado
    N°228)](https://www.gob.pe/institucion/minsa/noticias/299532-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-670-145-en-el-peru-comunicado-n-228)
    2020-09-03
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 676
    848 en el Perú (Comunicado
    N°229)](https://www.gob.pe/institucion/minsa/noticias/300566-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-676-848-en-el-peru-comunicado-n-229)
    2020-09-04
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 683
    702 en el Perú (Comunicado
    N°230)](https://www.gob.pe/institucion/minsa/noticias/300624-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-683-702-en-el-peru-comunicado-n-230)
    2020-09-05
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 689
    977 en el Perú (Comunicado
    N°231)](https://www.gob.pe/institucion/minsa/noticias/300667-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-689-977-en-el-peru-comunicado-n-231)
    2020-09-06
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 691
    575 en el Perú (Comunicado
    N°232)](https://www.gob.pe/institucion/minsa/noticias/300806-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-691-575-en-el-peru-comunicado-n-232)
    2020-09-07
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 696
    190 en el Perú (Comunicado
    N°233)](https://www.gob.pe/institucion/minsa/noticias/301051-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-696-190-en-el-peru-comunicado-n-233)
    2020-09-08
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 702
    776 en el Perú (Comunicado
    N°234)](https://www.gob.pe/institucion/minsa/noticias/301400-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-702-776-en-el-peru-comunicado-n-234)
    2020-09-09
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 710
    067 en el Perú (Comunicado
    N°235)](https://www.gob.pe/institucion/minsa/noticias/302143-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-710-067-en-el-peru-comunicado-n-235)
    2020-09-10
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 716
    670 en el Perú (Comunicado
    N°236)](https://www.gob.pe/institucion/minsa/noticias/302328-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-716-670-en-el-peru-comunicado-n-236)
    2020-09-11 -[Minsa: Casos confirmados por coronavirus Covid-19
    ascienden a 722 832 en el Perú (Comunicado
    N°237)](https://www.gob.pe/institucion/minsa/noticias/302388-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-722-832-en-el-peru-comunicado-n-237)
    2020-09-12
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 729
    619 en el Perú (Comunicado
    N°238)](https://www.gob.pe/institucion/minsa/noticias/302422-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-729-619-en-el-peru-comunicado-n-238)
    2020-09-13
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 733
    860 en el Perú (Comunicado
    N°239)](https://www.gob.pe/institucion/minsa/noticias/302535-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-733-860-en-el-peru-comunicado-n-239)
    2020-09-14
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 738
    020 en el Perú (Comunicado
    N°240)](https://www.gob.pe/institucion/minsa/noticias/302685-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-738-020-en-el-peru-comunicado-n-240)
    2020-09-15
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 744
    400 en el Perú (Comunicado
    N°241)](https://www.gob.pe/institucion/minsa/noticias/302869-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-744-400-en-el-peru-comunicado-n-241)
    2020-09-16
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 750
    098 en el Perú (Comunicado
    N°242)](https://www.gob.pe/institucion/minsa/noticias/303065-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-750-098-en-el-peru-comunicado-n-242)
    2020-09-17
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 756
    412 en el Perú (Comunicado
    N°243)](https://www.gob.pe/institucion/minsa/noticias/303190-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-756-412-en-el-peru-comunicado-n-243)
    2020-09-18
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 762
    865 en el Perú (Comunicado
    N°244)](https://www.gob.pe/institucion/minsa/noticias/303251-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-762-865-en-el-peru-comunicado-n-244)
    2020-09-19
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 768
    895 en el Perú (Comunicado
    N°245)](https://www.gob.pe/institucion/minsa/noticias/303309-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-768-895-en-el-peru-comunicado-n-245)
    2020-09-20
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 772
    896 en el Perú (Comunicado
    N°247)](https://www.gob.pe/institucion/minsa/noticias/303420-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-772-896-en-el-peru-comunicado-n-247)
    2020-09-21
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 776
    546 en el Perú (Comunicado
    N°248)](https://www.gob.pe/institucion/minsa/noticias/303819-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-776-546-en-el-peru-comunicado-n-248)
    2020-09-22
-   [Minsa: casos confirmados por coronavirus Covid-19 ascienden a 782
    695 en el Perú (Comunicado
    N°249)](https://www.gob.pe/institucion/minsa/noticias/304238-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-782-695-en-el-peru-comunicado-n-249)
    2020-09-23
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 788
    930 en el Perú (Comunicado
    N°250)](https://www.gob.pe/institucion/minsa/noticias/304537-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-788-930-en-el-peru-comunicado-n-250)
    2020-09-24
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 794
    584 en el Perú (Comunicado
    N°251)](https://www.gob.pe/institucion/minsa/noticias/304668-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-794-584-en-el-peru-comunicado-n-251)
    2020-09-25
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 800
    142 en el Perú (Comunicado
    N°252)](https://www.gob.pe/institucion/minsa/noticias/304763-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-800-142-en-el-peru-comunicado-n-252)
    2020-09-26
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 805
    302 en el Perú (Comunicado
    N°253)](https://www.gob.pe/institucion/minsa/noticias/304800-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-805-302-en-el-peru-comunicado-n-253)
    2020-09-27
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 808
    714 en el Perú (Comunicado
    N°255)](https://www.gob.pe/institucion/minsa/noticias/304927-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-808-714-en-el-peru-comunicado-n-255)
    2020-09-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 811
    768 en el Perú (Comunicado
    N°256)](https://www.gob.pe/institucion/minsa/noticias/305113-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-811-768-en-el-peru-comunicado-n-256)
    2020-09-29
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 814
    829 en el Perú (Comunicado
    N°257)](https://www.gob.pe/institucion/minsa/noticias/305261-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-814-829-en-el-peru-comunicado-n-257)
    2020-09-30
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 818
    297 en el Perú (Comunicado
    N°258)](https://www.gob.pe/institucion/minsa/noticias/305443-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-818-297-en-el-peru-comunicado-n-258)
    2020-10-01
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 821
    564 en el Perú (Comunicado
    N°259)](https://www.gob.pe/institucion/minsa/noticias/305650-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-821-564-en-el-peru-comunicado-n-259)
    2020-10-02
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 824
    985 en el Perú (Comunicado
    N°260)](https://www.gob.pe/institucion/minsa/noticias/305728-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-824-985-en-el-peru-comunicado-n-260)
    2020-10-03
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 828
    169 en el Perú (Comunicado
    N°261)](https://www.gob.pe/institucion/minsa/noticias/305764-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-828-169-en-el-peru-comunicado-n-261)
    2020-10-04
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 829
    999 en el Perú (Comunicado
    N°262)](https://www.gob.pe/institucion/minsa/noticias/305876-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-829-999-en-el-peru-comunicado-n-262)
    2020-10-05
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 832
    929 en el Perú (Comunicado
    N°263)](https://www.gob.pe/institucion/minsa/noticias/306137-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-832-929-en-el-peru-comunicado-n-263)
    2020-10-06
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 835
    662 en el Perú (Comunicado
    N°264)](https://www.gob.pe/institucion/minsa/noticias/306292-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-835-662-en-el-peru-comunicado-n-264)
    2020-10-07
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 838
    614 en el Perú (Comunicado
    N°265)](https://www.gob.pe/institucion/minsa/noticias/306454-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-838-614-en-el-peru-comunicado-n-265)
    2020-10-08
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 843
    355 en el Perú (Comunicado
    N°266)](https://www.gob.pe/institucion/minsa/noticias/306625-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-843-355-en-el-peru-comunicado-n-266)
    2020-10-09
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 846
    088 en el Perú (Comunicado
    N°267)](https://www.gob.pe/institucion/minsa/noticias/306670-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-846-088-en-el-peru-comunicado-n-267)
    2020-10-10
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 849
    371 en el Perú (Comunicado
    N°268)](https://www.gob.pe/institucion/minsa/noticias/306750-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-849-371-en-el-peru-comunicado-n-268)
    2020-10-11
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 851
    171 en el Perú (Comunicado
    N°269)](https://www.gob.pe/institucion/minsa/noticias/306905-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-851-171-en-el-peru-comunicado-n-269)
    2020-10-12
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 853
    974 en el Perú (Comunicado
    N°270)](https://www.gob.pe/institucion/minsa/noticias/307057-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-853-974-en-el-peru-comunicado-n-270)
    2020-10-13
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 856
    951 en el Perú (Comunicado
    N°271)](https://www.gob.pe/institucion/minsa/noticias/307253-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-856-951-en-el-peru-comunicado-n-271)
    2020-10-14
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 859
    740 en el Perú (Comunicado
    N°272)](https://www.gob.pe/institucion/minsa/noticias/307424-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-859-740-en-el-peru-comunicado-n-272)
    2020-10-15
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 862
    417 en el Perú (Comunicado
    N°273)](https://www.gob.pe/institucion/minsa/noticias/307593-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-862-417-en-el-peru-comunicado-n-273)
    2020-10-16
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 865
    549 en el Perú (Comunicado
    N°274)](https://www.gob.pe/institucion/minsa/noticias/307686-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-865-549-en-el-peru-comunicado-n-274)
    2020-10-17
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 868
    675 en el Perú (Comunicado
    N°275)](https://www.gob.pe/institucion/minsa/noticias/307737-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-868-675-en-el-peru-comunicado-n-275)
    2020-10-18
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 870
    876 en el Perú (Comunicado
    N°276)](https://www.gob.pe/institucion/minsa/noticias/308949-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-870-876-en-el-peru-comunicado-n-276)
    2020-10-19
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 874
    118 en el Perú (Comunicado
    N°277)](https://www.gob.pe/institucion/minsa/noticias/309098-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-874-118-en-el-peru-comunicado-n-277)
    2020-10-20
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 876
    885 en el Perú (Comunicado
    N°279)](https://www.gob.pe/institucion/minsa/noticias/309280-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-876-885-en-el-peru-comunicado-n-279)
    2020-10-21
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 879
    876 en el Perú (Comunicado
    N°280)](https://www.gob.pe/institucion/minsa/noticias/309407-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-879-876-en-el-peru-comunicado-n-280)
    2020-10-22
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 883
    116 en el Perú (Comunicado
    N°281)](https://www.gob.pe/institucion/minsa/noticias/309541-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-883-116-en-el-peru-comunicado-n-281)
    2020-10-23
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 886
    214 en el Perú (Comunicado
    N°282)](https://www.gob.pe/institucion/minsa/noticias/309872-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-886-214-en-el-peru-comunicado-n-282)
    2020-10-24
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 888
    715 en el Perú (Comunicado
    N°283)](https://www.gob.pe/institucion/minsa/noticias/310237-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-888-715-en-el-peru-comunicado-n-283)
    2020-10-25
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 890
    574 en el Perú (Comunicado
    N°284)](https://www.gob.pe/institucion/minsa/noticias/310648-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-890-574-en-el-peru-comunicado-n-284)
    2020-10-26
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 892
    497 en el Perú (Comunicado
    N°285)](https://www.gob.pe/institucion/minsa/noticias/310781-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-892-497-en-el-peru-comunicado-n-285)
    2020-10-27
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 894
    928 en el Perú (Comunicado
    N°286)](https://www.gob.pe/institucion/minsa/noticias/311609-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-894-928-en-el-peru-comunicado-n-286)
    2020-10-28
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 897
    594 en el Perú (Comunicado
    N°287)](https://www.gob.pe/institucion/minsa/noticias/311753-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-897-594-en-el-peru-comunicado-n-287)
    2020-10-29
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 900
    180 en el Perú (Comunicado
    N°288)](https://www.gob.pe/institucion/minsa/noticias/311909-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-900-180-en-el-peru-comunicado-n-288)
    2020-10-30
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 902
    503 en el Perú (Comunicado
    N°289)](Minsa:%20Casos%20confirmados%20por%20coronavirus%20Covid-19%20ascienden%20a%20902%20503%20en%20el%20Perú%20(Comunicado%20N°289))
    2020-10-31
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 904
    911 en el Perú (Comunicado
    N°290)](https://www.gob.pe/institucion/minsa/noticias/312015-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-904-911-en-el-peru-comunicado-n-290)
    2020-11-01
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 906
    545 en el Perú (Comunicado
    N°291)](https://www.gob.pe/institucion/minsa/noticias/312156-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-906-545-en-el-peru-comunicado-n-291)
    2020-11-02
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 908
    902 en el Perú (Comunicado
    N°292)](https://www.gob.pe/institucion/minsa/noticias/312319-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-908-902-en-el-peru-comunicado-n-292)
    2020-11-03
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 911
    787 en el Perú (Comunicado
    N°293)](https://www.gob.pe/institucion/minsa/noticias/312599-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-911-787-en-el-peru-comunicado-n-293)
    2020-11-04
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 914
    722 en el Perú (Comunicado
    N°294)](https://www.gob.pe/institucion/minsa/noticias/312753-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-914-722-en-el-peru-comunicado-n-294)
    2020-11-05
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 917
    503 en el Perú (Comunicado
    N°295)](https://www.gob.pe/institucion/minsa/noticias/312909-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-917-503-en-el-peru-comunicado-n-295)
    2020-11-06
-   [Minsa: Casos confirmados por coronavirus Covid-19 ascienden a 920
    010 en el Perú (Comunicado
    N°298)](https://www.gob.pe/institucion/minsa/noticias/312978-minsa-casos-confirmados-por-coronavirus-covid-19-ascienden-a-920-010-en-el-peru-comunicado-n-298)
    2020-11-07

Recuperados
-----------

-   [Paciente cero con coronavirus fue dado de alta tras respetar
    aislamiento domiciliario
    recomendado](https://www.gob.pe/institucion/minsa/noticias/108961-paciente-cero-con-coronavirus-fue-dado-de-alta-tras-respetar-aislamiento-domiciliario-recomendado)
    2020-03-16
-   [Minsa: Casos confirmados por coronavirus COVID-19 son 635 en Perú
    (Comunicado
    N°36)](https://www.gob.pe/institucion/minsa/noticias/111543-minsa-casos-confirmados-por-coronavirus-covid-19-son-635-en-peru-comunicado-n-36)
    2020-03-27 (menciona el número de pacientes con alta)
-   [Minsa anuncia que 16 pacientes ya se han recuperado del
    Covid-19](https://www.gob.pe/institucion/minsa/noticias/111581-minsa-anuncia-que-16-pacientes-ya-se-han-recuperado-del-covid-19)
    2020-03-28

Fallecimientos
--------------

-   [Minsa lamenta el sensible fallecimiento del primer paciente a causa
    de infección COVID-19 (Comunicado
    N°20)](https://www.gob.pe/institucion/minsa/noticias/109580-minsa-lamenta-el-sensible-fallecimiento-del-primer-paciente-a-causa-de-infeccion-covid-19-comunicado-n-20)
    2020-03-19
    -   Hombre, 78 años, hipertensión, ingresó 2020-03-17 por
        insuficiencia respiratoria severa, falleció en hospital, Lima
-   [Minsa lamenta el sensible fallecimiento de dos personas por
    infección por COVID-19 (Comunicado
    N°21)](https://www.gob.pe/institucion/minsa/noticias/109603-minsa-lamenta-el-sensible-fallecimiento-de-dos-personas-por-infeccion-por-covid-19-comunicado-n-21)
    2020-03-19
    -   Hombre, 47 años, viaje a España, asma, obesidad, ingreso por
        insuficiencia respiratoria y shock séptico, falleció en
        hospital, Lima
    -   Hombre, 69 años, viaje a España, ingreso por cuadro
        respiratorio, falleció en domicilio, Lima
-   [Minsa lamenta el sensible fallecimiento de una persona por
    infección por COVID-19 (Comunicado
    N°22)](https://www.gob.pe/institucion/minsa/noticias/109639-minsa-lamenta-el-sensible-fallecimiento-de-una-persona-por-infeccion-por-covid-19-comunicado-n-22)
    2020-03-20
    -   Mujer, 75 años, viaje a España, ingreso por insuficiencia
        respiratoria y neumonía el 2020-03-19, falleció en hospital,
        Lima
-   [Minsa lamenta el sensible fallecimiento de una persona por
    infección por COVID-19 (Comunicado
    N°25)](https://www.gob.pe/institucion/minsa/noticias/109778-minsa-lamenta-el-sensible-fallecimiento-de-una-persona-por-infeccion-por-covid-19-comunicado-n-25)
    2020-03-21
    -   Hombre, 83 años, contacto con familiar procedente de Europa,
        ingreso por insuficiencia respiratoria y neumonía, falleció en
        hospital, Piura
-   [Minsa lamenta informar el sensible fallecimiento de dos personas
    por infección con COVID-19 (Comunicado
    N°30)](https://www.gob.pe/institucion/minsa/noticias/109930-minsa-lamenta-informar-el-sensible-fallecimiento-de-dos-personas-por-infeccion-con-covid-19-comunicado-n-30)
    2020-03-24
    -   Hombre, 38 años, obesidad, ingresó 2020-03-22 por insuficiencia
        respiratoria, falleció en hospital, Lima
    -   Mujer, 66 años, ingresó por insuficiencia respiratoria aguda y
        neumonía, falleció en hospital, La Libertad
-   [Minsa lamenta el sensible fallecimiento de dos personas por
    infección con Covid-19 (Comunicado
    N°32)](https://www.gob.pe/institucion/minsa/noticias/110050-minsa-lamenta-el-sensible-fallecimiento-de-dos-personas-por-infeccion-con-covid-19-comunicado-n-32)
    2020-03-25
    -   Hombre, 76 años, nacionalidad mexicana, insuficiencia
        respiratoria y comorbilidad, diabetes y enfermedad cardíaca
        preexistente, falleció en hospital, Cusco
    -   Home, 94 años, insuficiencia renal y bronquitis crónica,
        diabetes, falleció en hospital, Lima
-   [Minsa lamenta informar el sensible fallecimiento de dos personas
    por infección con COVID-19 (Comunicado
    N°35)](https://www.gob.pe/institucion/minsa/noticias/111529-minsa-lamenta-informar-el-sensible-fallecimiento-de-dos-personas-por-infeccion-con-covid-19-comunicado-n-35)
    2020-03-27
    -   Hombre, 56 años, insuficiencia respiratoria aguda-grave, ingresó
        el 2020-03-26 y falleció el mismo día en el hospital, La
        Libertad
    -   Hombre, 65 años, ingresó el 2020-03-21, falleció en el hospital
        el 2020-03-26, Lima
-   [Minsa lamenta informar el sensible fallecimiento de cinco personas
    por infección con COVID-19 (Comunicado
    N°37)](https://www.gob.pe/institucion/minsa/noticias/111566-minsa-lamenta-informar-el-sensible-fallecimiento-de-cinco-personas-por-infeccion-con-covid-19-comunicado-n-37)
    2020-03-28
    -   Hombre, 50 años, insuficiencia respiratoria aguda y neumonía,
        falleció en el hospital el 2020-03-26, Lambayeque
    -   Hombre, 66 años, insuficiencia respiratoria, sepsis y neumonía,
        falleció en el hospital el 2020-03-26, Lima
    -   Hombre, 43 años, insuficiencia respiratoria, sepsis y neumonía,
        obesidad, falleció en el hospital el 2020-03-27, Lima
    -   Hombre, 64 años, procedente de Hong Kong, falleció en su
        domicilio el 2020-03-27, Cusco
    -   Mujer, 60 años, insuficiencia respiratoria, shock séptico y
        neumonía, falleció en el hospital el 2020-03-27, Callao
-   [Minsa lamenta el sensible fallecimiento de dos personas por
    infección con COVID-19 (Comunicado
    N° 39)](https://www.gob.pe/institucion/minsa/noticias/111587-minsa-lamenta-el-sensible-fallecimiento-de-dos-personas-por-infeccion-con-covid-19-comunicado-n-39)
    2020-03-29
    -   Hombre, 91 años, neumonía, enfermedad renal crónica, falleció en
        el hospital el 2020-03-27, Lima
    -   Mujer, 66 años, neumonía, obesidad mórbida, falleción en
        hospital el 2020-03-28, Ancash
-   [El Ministerio de Salud lamenta informar el sensible fallecimiento
    de seis personas por infección con COVID-19
    (Comunicado 42)](https://www.gob.pe/institucion/minsa/noticias/111625-el-ministerio-de-salud-lamenta-informar-el-sensible-fallecimiento-de-seis-personas-por-infeccion-con-covid-19-comunicado-42)
    2020-03-30
    -   Hombre, 63 años, neumonía, obesidad, comorbilidad, diabetes
        mellitus y tuberculosis previa, falleció en el hospital el
        2020-03-30, Loreto.
    -   Mujer, 58 años, neumonía, antecedentes de neumonía, falleció en
        el hospital el 2020-03-29, Callao.
    -   Hombre, 56 años, obesidad, falleció en el hospital el
        2020-03-30, Loreto.
    -   Mujer, 81 años, neumonía, shock séptico, diabetes mellitus,
        falleció en el hospital el 2020-03-28, Lima.
    -   Mujer, 76 años, neumonía, antecedentes de HTA y desnutrición
        crónica, ingresó el 2020-03-26, falleció en el hospital el
        2020-03-29. Lima
    -   Mujer, 76 años, neumonía, enfermedaes preexistentes, ingresó el
        2020-03-26, falleció en el hospital el 2020-03-29. Lima
-   [Minsa lamenta el sensible fallecimiento de seis personas por
    infección con COVID-19 (Comunicado
    N°45)](https://www.gob.pe/institucion/minsa/noticias/111655-minsa-lamenta-el-sensible-fallecimiento-de-seis-personas-por-infeccion-con-covid-19-comunicado-n-45)
    2020-03-31
    -   Hombre, 26 años, neumonía, asma y obesidad, ingresó el
        2020-03-29, falleció en el hospital el 2020-03-29, Callao.
    -   Mujer, 74 años, neumomía, insuficiencia renal crónica y cirrosis
        hepática, ingresó el 2020-03-29, falleció en el hospital el
        2020-03-29, Lima.
    -   Hombre, 46 años, neumonía crónica, lumbalgia y alto consumo de
        alcohol, falleció el 2020-03-30 en su domicilio, Tumbes.
    -   Hombre, 53 años, neumonía crónica, ingresó el 2020-03-23,
        falleció en el hospital el 2020-03-30. Lima.
    -   Hombre, 60 años, infección respiratoria, neumonía atípica y
        shock séptico, ingresó el 2020-03-26, falleció en el hospital el
        2020-03-30, Lima.
    -   Hombre, 66 años, neumonía crónica, falleció en el hospital el
        2020-03-31, San Martín.
-   [Minsa lamenta el sensible fallecimiento de ocho personas por
    infección con COVID-19 (Comunicado
    N°47)](https://www.gob.pe/institucion/minsa/noticias/111724-minsa-lamenta-el-sensible-fallecimiento-de-ocho-personas-por-infeccion-con-covid-19-comunicado-n-47)
    2020-04-01
    -   Hombre, 75 años, neumonía, hipertensión y enfermedad cerebro
        cardiovascular, falleció el 2020-03-27 en el hospital, Lima.
    -   Hombre, 96 años, neumonía, falleció el 2020-03-29 en el
        hospital, Lima.
    -   Mujer, 83 años, neumonía, falleció el 2020-03-29 en el hospital,
        Lima.
    -   Hombre, 87 años, neumonía, hipertensión y enfermedad cerebro
        cardiovascular, falleció el 2020-03-29 en el hospital, Lima.
    -   Mujer, 59 años, neumonía, fibrosis pulmonar, falleció el
        2020-03-30 en el hospital, Lambayeque.
    -   Hombre, 60 años, neumonía, hipertensión y diabetes mellitus,
        falleció el 2020-03-30 en el hospital, Lima.
    -   Hombre, 73 años, neumonía, falleció el 2020-03-31 en el
        hospital, Callao.
    -   Hombre, 68 años, neumonía, falleció el 2020-03-31 en el
        hospital, Lima.
-   [Minsa lamenta el sensible fallecimiento de nueve personas por
    infección con COVID-19 (Comunicado
    N°48)](https://www.gob.pe/institucion/minsa/noticias/111750-minsa-lamenta-el-sensible-fallecimiento-de-nueve-personas-por-infeccion-con-covid-19-comunicado-n-48)
    2020-04-01
    -   Mujer, 69 años, insuficiencia respiratoria, diabetes mellitus e
        hipertensión arterial, falleció el 2020-03-29 en el hospital,
        Lambayeque.
    -   Hombre, 68 años, neumonía, falleció en el hospital el
        2020-03-31, Lima.
    -   Hombre, 60 años, neumonía, falleció en el hospital el
        2020-03-31, Lima.
    -   Mujer, 63 años, neumonía, falleció en el hospital el 2020-03-31,
        Lima.
    -   Hombre, 59 años, neumonía, falleció en el hospital el
        2020-03-31, Lima.
    -   Hombre, 26 años, insuficiencia respiratoria y neumonía, falleció
        en el hospital el 2020-03-30, Lima.
    -   Hombre, 89 años, insuficiencia respiratoria y neumonía, falleció
        en el hospital el 2020-03-31, Arequipa.
    -   Hombre, 59 años, insuficiencia cardiorrespiratoria, diabetes
        mellitus y hemodializado, falleció en el hospital el 2020-03-31,
        La Libertad.
    -   Mujer, 65 años, sintomatología respiratoria, obesidad y
        diabetes, falleció en el hospital el 2020-03-31, Lima.
-   [Minsa lamenta el sensible fallecimiento de ocho personas por
    infección con COVID-19 (Comunicado
    N°50)](https://www.gob.pe/institucion/minsa/noticias/111777-minsa-lamenta-el-sensible-fallecimiento-de-ocho-personas-por-infeccion-con-covid-19-comunicado-n-50)
    2020-04-02
    -   Hombre, 57 años, insuficiencia respiratoria y neumonía, falleció
        en el hospital 2020-03-30, Junín.
    -   Hombre, 77 años, insuficiencia respiratoria y neumonía, falleció
        en el hospital el 2020-03-31, Lima.
    -   Mujer, 73 años, neumonía, contacto con familiar positivo a
        COVID-19. falleció en el hospital el 2020-04-01, Lima.
    -   Mujer, 58 años, neumonía, hipertensión arterial, falleció en el
        hospital el 2020-04-01, Tumbes.
    -   Hombre, 73 años, diabetes mellitus, hipertensión arterial e
        insuficiencia renal, falleció en el hospital el 2020-04-01,
        Lima.
    -   Hombre, 60 años, infección respiratoria aguda y neumonía,
        falleció en el hospital el 2020-04-01, Lima.
    -   Hombre, 65 años, neumonía y shock séptico, falleció en el
        hospital el 2020-04-01, Lima.
    -   Mujer, 67 años, insuficiencia respiratoria aguda, obesidad,
        falleció en el hospital el 2020-04-01, Lima.
