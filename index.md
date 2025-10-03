# Consultas SQL con su respectiva explicación y consulta.
- [Consultas SQL con su respectiva explicación y consulta.](#consultas-sql-con-su-respectiva-explicación-y-consulta)
	- [Introducción](#introducción)
	- [Consultas de expedientes:](#consultas-de-expedientes)
		- [Consulta migración expedientes y su primer tomo:](#consulta-migración-expedientes-y-su-primer-tomo)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta)
			- [Consulta:](#consulta)
		- [Consulta migración expedientes 2018](#consulta-migración-expedientes-2018)
			- [Ejemplo consulta:](#ejemplo-consulta)
			- [Consulta:](#consulta-1)
		- [Expedientes que han sido cambiados](#expedientes-que-han-sido-cambiados)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-1)
			- [Consulta:](#consulta-2)
			- [Consulta para los expedientes que han sido tocados por Juan José:](#consulta-para-los-expedientes-que-han-sido-tocados-por-juan-josé)
			- [Consulta para los expedientes que han sido tocados por Juan José de la versión 00:](#consulta-para-los-expedientes-que-han-sido-tocados-por-juan-josé-de-la-versión-00)
		- [Ubicaciones topográficas de determinados expedientes:](#ubicaciones-topográficas-de-determinados-expedientes)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-2)
			- [Consulta:](#consulta-3)
	- [Consultas de historias laborales:](#consultas-de-historias-laborales)
		- [Consulta de todos los documentos cargados en historias laborales](#consulta-de-todos-los-documentos-cargados-en-historias-laborales)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-3)
			- [Consulta:](#consulta-4)
	- [Consultas TRD](#consultas-trd)
		- [Listado áreas](#listado-áreas)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-4)
			- [Consulta:](#consulta-5)
	- [Consultas correspondencia y PQRSD](#consultas-correspondencia-y-pqrsd)
		- [Correspondencia de entrada (Reporte)](#correspondencia-de-entrada-reporte)
			- [Ejemplo del reporte:](#ejemplo-del-reporte)
			- [Consulta para obtener las áreas:](#consulta-para-obtener-las-áreas)
			- [Consulta para la correspondencia:](#consulta-para-la-correspondencia)
		- [Correspondencia de salida (Reporte)](#correspondencia-de-salida-reporte)
			- [Ejemplo del reporte:](#ejemplo-del-reporte-1)
			- [Consulta:](#consulta-6)
		- [Formularios de entrada o salida de PQRSD cuya entidad liquidada diga "FRAUDE"](#formularios-de-entrada-o-salida-de-pqrsd-cuya-entidad-liquidada-diga-fraude)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-5)
			- [Consulta:](#consulta-7)
		- [Correspondencia de organismos de control - Entrada](#correspondencia-de-organismos-de-control---entrada)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-6)
			- [Consulta:](#consulta-8)
		- [Correspondencia de organismos de control - Salida](#correspondencia-de-organismos-de-control---salida)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-7)
			- [Consulta:](#consulta-9)
		- [Reporte de Documentos Radicados en 2024 con Fecha de Almacenamiento y Medio de envío](#reporte-de-documentos-radicados-en-2024-con-fecha-de-almacenamiento-y-medio-de-envío)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-8)
			- [Consulta:](#consulta-10)
		- [Solicitud de histórico de atenciones por canal telefónico y Buzón PQSD](#solicitud-de-histórico-de-atenciones-por-canal-telefónico-y-buzón-pqsd)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-9)
			- [Consulta para los de salida:](#consulta-para-los-de-salida)
			- [Consulta para los de entrada:](#consulta-para-los-de-entrada)
		- [Informe para publicar en datos abiertos reporte de PQRS](#informe-para-publicar-en-datos-abiertos-reporte-de-pqrs)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-10)
			- [Consulta:](#consulta-11)
	- [Informes útiles para el DGC](#informes-útiles-para-el-dgc)
		- [Documentos sin código de expediente](#documentos-sin-código-de-expediente)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-11)
			- [Consulta:](#consulta-12)
		- [Cantidad de documentos en cada tipo documental](#cantidad-de-documentos-en-cada-tipo-documental)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-12)
			- [Consulta:](#consulta-13)
		- [Inventario de Documentos Electrónicos de Conservación Total](#inventario-de-documentos-electrónicos-de-conservación-total)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-13)
			- [Consulta:](#consulta-14)
		- [Cantidad de documentos cargados con extensiones](#cantidad-de-documentos-cargados-con-extensiones)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-14)
			- [Consulta:](#consulta-15)
		- [Llave confidencial de historias laborales](#llave-confidencial-de-historias-laborales)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-15)
			- [Consulta:](#consulta-16)
		- [Listado de todos los documentos cuya llave confidencial sea diferente a PUBLICA](#listado-de-todos-los-documentos-cuya-llave-confidencial-sea-diferente-a-publica)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-16)
			- [Consulta:](#consulta-17)
		- [Notificaciones pendientes por enviar](#notificaciones-pendientes-por-enviar)
			- [Consulta:](#consulta-18)
		- [Reporte de Documentos por Expediente con Información de Radicado y Medio de Recepción/Envío](#reporte-de-documentos-por-expediente-con-información-de-radicado-y-medio-de-recepciónenvío)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-17)
			- [Consulta:](#consulta-19)
		- [Cantidad de documentos cargados a las series entre julio 2023 y julio 2024](#cantidad-de-documentos-cargados-a-las-series-entre-julio-2023-y-julio-2024)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-18)
			- [Consulta:](#consulta-20)
		- [Cantidad de documentos cargados a las subseries entre julio 2023 y julio 2024](#cantidad-de-documentos-cargados-a-las-subseries-entre-julio-2023-y-julio-2024)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-19)
			- [Consulta:](#consulta-21)
		- [Identificar documentos que deben ser considerados para la transferencia - SUBSERIES](#identificar-documentos-que-deben-ser-considerados-para-la-transferencia---subseries)
			- [Correo de solicitud:](#correo-de-solicitud)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-20)
			- [Consulta:](#consulta-22)
		- [Generación de inventario de expedientes por número de caja en OnBase](#generación-de-inventario-de-expedientes-por-número-de-caja-en-onbase)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-21)
			- [Consulta:](#consulta-23)
		- [Cantidad de radicados en la cola de los usuarios](#cantidad-de-radicados-en-la-cola-de-los-usuarios)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-22)
			- [Consulta:](#consulta-24)
		- [Cálculo de fecha de eliminación de expedientes según suma de gestión y subseries](#cálculo-de-fecha-de-eliminación-de-expedientes-según-suma-de-gestión-y-subseries)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-23)
			- [Consulta con tomos completos:](#consulta-con-tomos-completos)
			- [Consulta sin tomos:](#consulta-sin-tomos)
			- [Consulta con tomos versión 00:](#consulta-con-tomos-versión-00)
		- [Documentos vitales](#documentos-vitales)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-24)
			- [Consulta:](#consulta-25)
	- [Informes para flujos](#informes-para-flujos)
		- [Contratos/ordenes - Reporte obtener todos los documentos asociados a una orden](#contratosordenes---reporte-obtener-todos-los-documentos-asociados-a-una-orden)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-25)
			- [Consulta:](#consulta-26)
		- [Contratos/ordenes - Reporte obtener estado de las necesidades, cola y paso siguiente](#contratosordenes---reporte-obtener-estado-de-las-necesidades-cola-y-paso-siguiente)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-26)
			- [Consulta:](#consulta-27)
		- [Contratos/ordenes - Reporte obtener keyword "Volvería a contratar"](#contratosordenes---reporte-obtener-keyword-volvería-a-contratar)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-27)
			- [Consulta:](#consulta-28)
		- [Ayudas de memoria DTI - Consulta e inventario de ayudas de memoria en OnBase](#ayudas-de-memoria-dti---consulta-e-inventario-de-ayudas-de-memoria-en-onbase)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-28)
			- [Consulta:](#consulta-29)
		- [Conciliaciones contables DIF - Reporte](#conciliaciones-contables-dif---reporte)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-29)
			- [Consulta:](#consulta-30)
	- [Informes para otras áreas:](#informes-para-otras-áreas)
		- [Verificación de comprobantes contables cargados en el año 2024 (DIF)](#verificación-de-comprobantes-contables-cargados-en-el-año-2024-dif)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-30)
			- [Consulta:](#consulta-31)
		- [Reporte facturas (DAI)](#reporte-facturas-dai)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-31)
			- [Consulta:](#consulta-32)
		- [Reporte facturas (DIF)](#reporte-facturas-dif)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-32)
			- [Consulta:](#consulta-33)
	- [Otras soluciones:](#otras-soluciones)
		- [Actas de junta directiva (temas)](#actas-de-junta-directiva-temas)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-33)
			- [Consulta:](#consulta-34)
		- [Actas de junta directiva (participantes)](#actas-de-junta-directiva-participantes)
			- [Ejemplo de la consulta:](#ejemplo-de-la-consulta-34)
			- [Consulta:](#consulta-35)

## Introducción
El presente documento va a estar dividido según categorías o áreas

## Consultas de expedientes:
### Consulta migración expedientes y su primer tomo:
Realiza la consulta de TODOS los expedientes con los campos existentes con su primer tomo
#### Ejemplo de la consulta:
| Area | PrefijoArea | Serie | Subserie | Nombre | NumeroExpediente | EstadoExpediente | FechaInicial | FechaFinal | Descripcion | Clasificaciondelainformacion | Confidencial | EstadoPrestamo | FechaFinCentral | FechaFinGestion | FrecuenciaConsulta | UnidadConservacion | Ingresado | NoIdentificacion | Folios | SiglaAreaHistorica | CreadoPor | FechaCreacion | objectid | activestatus | revisiondate | revisionby | Tomo | FechaInicialTomo | FechaFinalTomo | Deposito | Bloque | Cuerpo | Bandeja | Observaciones | FolioInicial | FolioFinal | Caja | Paquete | Rollo | Posicion | objidTomo | fk1131 | activestatusTomo |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01-1000 | DIR | 01-1000-900 | 01-1000-900-99 | BC. AGRARIO S.A - COMITE DIRECTIVO NACIONAL DE CREDITO - CORRESPONDENCIA 2009 | 6 | ACTIVO | 00:00.0 | 00:00.0 | NULL | PUBLICA | PUBLICA | DISPONIBLE | NULL | NULL | BAJA | Carpeta híbrida | C | 2009 | 9 | NULL | MANAGER | 22:42.3 | 27227 | 0 | 26:23.6 | DGCPU1 | 1 | 00:00.0 | 00:00.0 | D1 | B2 | C6 | B3 || 1 | 9 | NULL | NULL | NULL | NULL | 68369 | 27227 | 0 |
| 01-1000 | DIR | 01-1000-900 | 01-1000-900-99 | BC. AGRARIO - JUNTA DIRECTIVA CORRESPONDENCIA 2009 | 7 | ACTIVO | 00:00.0 | 00:00.0 | NULL | PUBLICA | PUBLICA | DISPONIBLE | NULL | NULL | BAJA | Carpeta híbrida | C | 2009 | 28 | NULL | MANAGER | 22:42.7 | 27229 | 0 | 30:54.6 | DGCPU1 | 1 | 00:00.0 | 00:00.0 | D1 | B2 | C6 | B3 || 1 | 28 | NULL | NULL | NULL | NULL | 68370 | 27229 | 0 |
| 01-1000 | DIR | 01-1000-900 | 01-1000-900-99 | BC. AGRARIO - CONTROL INTERNO 2009 | 8 | ACTIVO | 00:00.0 | 00:00.0 | NULL | PUBLICA | PUBLICA | DISPONIBLE | NULL | NULL | BAJA | Carpeta híbrida | C | 2009 | 66 | NULL | MANAGER | 22:43.1 | 27231 | 0 | 25:48.2 | DGCPU1 | 1 | 00:00.0 | 00:00.0 | D1 | B2 | C6 | B3 || 1 | 66 | NULL | NULL | NULL | NULL | 68371 | 27231 | 0 |

#### Consulta:
```sql
--Consulta migración expedientes y su primer tomo:
select *
from
(select 
	a.attr1002 as Area,
	a.attr1091 as PrefijoArea,
	s.attr1044 as Serie,
	sb.attr1047 as Subserie,
	e.attr1052 as Nombre,
	e.attr1043 as NumeroExpediente, 
	e.attr1109 as EstadoExpediente,
	e.attr1053 as FechaInicial,
	e.attr1054 as FechaFinal,
	m.memo as Descripcion,
	e.attr1057 as Clasificaciondelainformacion,
	e.attr1135 as Confidencial,
	e.attr1056 as EstadoPrestamo,
	e.attr1118 as FechaFinCentral,
	e.attr1117 as FechaFinGestion,
	e.attr1134 as FrecuenciaConsulta,
	e.attr1055 as UnidadConservacion,
	e.attr1137 as Ingresado,
	e.attr1142 as NoIdentificacion,
	e.attr1143 as Folios,
	e.attr1196 as SiglaAreaHistorica,
	o.rmcreatedBy as CreadoPor,
	o.createddate as FechaCreacion,
	e.objectid,
	e.activestatus,
	e.revisiondate,
	e.revisionby
from hsi.rmobjectinstance1010 e left outer join hsi.rmmemo m on m.memoid = e.mk1058
join hsi.rmobjecto on e.objectid = o.objectid
left outer join hsi.rmobjectinstance1013 sb on e.fk1051 = sb.objectID
left outer join hsi.rmobjectinstance1012 s on sb.fk1050 = s.objectID
left outer join hsi.rmobjectinstance1003 a on s.fk1090 = a.objectid
where e.activestatus = 0
) as a
left outer join
(select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
where (t.attr1123 = '1' or t.attr1123 = '.1' or t.attr1123 = '<1' or t.attr1123 = '0.1' or t.attr1123 = '01' or t.attr1123 = 'A1' or t.attr1123 = 'm1')
and t.activestatus = 0
and t.fk1131 in (
	select fk1131
	from hsi.rmobjectinstance1023 t
	where (t.attr1123 = '1' or t.attr1123 = '.1' or t.attr1123 = '<1' or t.attr1123 = '0.1' or t.attr1123 = '01' or t.attr1123 = 'A1' or t.attr1123 = 'm1')
	and t.activestatus = 0
	group by fk1131
	having count (*) = 1)


Union all


select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
where (t.attr1123 = '1' or t.attr1123 = '.1' or t.attr1123 = '<1' or t.attr1123 = '0.1' or t.attr1123 = '01' or t.attr1123 = 'A1' or t.attr1123 = 'm1')
and t.activestatus = 0
--and m.memo not like 'Primer Tomo (Autocreado)'
and ((t.attr1126 not like '00' or t.attr1126 <> null)
	or (attr1197 not like '00' or attr1197 not like '0' or t.attr1198 not like '00' or t.attr1198 not like '0')
	or (t.attr1199 not like '00' or t.attr1199 not like '0' or t.attr1200 not like '00' or t.attr1200 not like '0')
	or (m.memo not like 'Primer Tomo (Autocreado)'))
and fk1131 not in(
	select fk1131
	from hsi.rmobjectinstance1023 t
	where (t.attr1123 = '1' or t.attr1123 = '.1' or t.attr1123 = '<1' or t.attr1123 = '0.1' or t.attr1123 = '01' or t.attr1123 = 'A1' or t.attr1123 = 'm1')
	and t.activestatus = 0
	group by fk1131
	having count (*) = 1)
)
as b on a.objectid = b.fk1131

```

### Consulta migración expedientes 2018
Saber todos los expedientes del 2018 tener información sobre: area, serie, subserie, fecha creación, fecha modificación (última) de cada tomo y expediente, todos los tomos de cada expediente.

#### Ejemplo consulta:
Area|PrefijoArea|Serie|Subserie|Nombre|NumeroExpediente|EstadoExpediente|FechaInicial|FechaFinal|Descripcion|Clasificaciondelainformacion|Confidencial|EstadoPrestamo|FechaFinCentral|FechaFinGestion|FrecuenciaConsulta|UnidadConservacion|Ingresado|NoIdentificacion|Folios|SiglaAreaHistorica|CreadoPor|FechaCreacion|objectid|activestatus|UltimoEvento|UsuarioUltimoEvento|cantidadDocumentos|FechaUltimaModificacion|UsuarioModifico|Tomo|FechaInicialTomo|FechaFinalTomo|Deposito|Bloque|Cuerpo|Bandeja|Observaciones|FolioInicial|FolioFinal|Caja|Paquete|Rollo|Posicion|objidTomo|fk1131|activestatusTomo|CreadoPorTomo|FechaCreacionTomo|FechaUltimaModificacionTomo|UsuarioModificoTomo
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
01-1000 |DIR|01-1000-900|01-1000-900-99 |BC. AGRARIO - JUNTA DIRECTIVA SESION No. 388 ENE 29 (1 DE 2) 2009|1|ACTIVO|2009-02-27 00:00:00.000|2009-03-18 00:00:00.000|NULL|PUBLICA|PUBLICA |DISPONIBLE|NULL|NULL|BAJA|Carpeta híbrida |C|2009|65|NULL|MANAGER|2016-05-10 07:22:35.630|27216|0|2024-12-17 11:36:46.930|DGCPU1|5|2024-12-17 11:36:46.967|DGCPU1|1|2009-02-27 00:00:00.000|2009-03-18 00:00:00.000|D1|B2 |C6 |B3 ||1|65|NULL|NULL|NULL|NULL|68364|27216|0|MANAGER|2016-05-10 11:26:10.890|2024-12-17 11:36:45.873|DGCPU1
01-1000 |DIR|01-1000-900|01-1000-900-99 |BC. AGRARIO - JUNTA DIRECTIVA SESION No. 391 FEB 26 2009|5|ACTIVO|2009-02-26 00:00:00.000|2009-02-26 00:00:00.000|NULL|PUBLICA|PUBLICA |Disponible|NULL|NULL|BAJA|Carpeta híbrida |C|2009|84|NULL|MANAGER|2016-05-10 07:22:41.770|27225|0|2024-12-17 12:22:32.593|DGCPU1|2|2024-12-17 12:22:32.600|DGCPU1|1|2009-02-26 00:00:00.000|2009-02-26 00:00:00.000|D1|B2 |C6 |B3 ||1|97|NULL|NULL|NULL|NULL|68368|27225|0|MANAGER|2016-05-10 11:26:11.207|2024-12-17 12:22:31.570|DGCPU1
01-1000 |DIR|01-1000-900|01-1000-900-99 |BC. AGRARIO S.A - COMITE DIRECTIVO NACIONAL DE CREDITO - CORRESPONDENCIA 2009 |6|ACTIVO|2009-03-05 00:00:00.000|2009-07-14 00:00:00.000|NULL|PUBLICA|PUBLICA |DISPONIBLE|NULL|NULL|BAJA|Carpeta híbrida |C|2009|9|NULL|MANAGER|2016-05-10 07:22:42.273|27227|0|2024-12-17 11:26:23.607|DGCPU1|2|2024-12-17 11:26:23.613|DGCPU1|1|2009-03-05 00:00:00.000|2009-07-14 00:00:00.000|D1|B2 |C6 |B3 ||1|9|NULL|NULL|NULL|NULL|68369|27227|0|MANAGER|2016-05-10 11:26:11.337|2024-05-03 11:12:50.427|ALEJANDRO@GIGA.UNO
01-1000 |DIR|01-1000-900|01-1000-900-99 |BC. AGRARIO - JUNTA DIRECTIVA CORRESPONDENCIA 2009 |7|ACTIVO|2009-01-13 00:00:00.000|2009-04-02 00:00:00.000|NULL|PUBLICA|PUBLICA |DISPONIBLE|NULL|NULL|BAJA|Carpeta híbrida |C|2009|28|NULL|MANAGER|2016-05-10 07:22:42.737|27229|0|2024-12-17 11:30:54.630|DGCPU1|2|2024-12-17 11:30:54.640|DGCPU1|1|2009-01-13 00:00:00.000|2009-04-02 00:00:00.000|D1|B2 |C6 |B3 ||1|28|NULL|NULL|NULL|NULL|68370|27229|0|MANAGER|2016-05-10 11:26:11.430|2024-12-17 11:30:53.580|DGCPU1
01-1000 |DIR|01-1000-900|01-1000-900-99 |BC. AGRARIO - CONTROL INTERNO 2009|8|ACTIVO|2009-01-29 00:00:00.000|2009-01-29 00:00:00.000|NULL|PUBLICA|PUBLICA |DISPONIBLE|NULL|NULL|BAJA|Carpeta híbrida |C|2009|66|NULL|MANAGER|2016-05-10 07:22:43.053|27231|0|2024-12-17 12:25:48.167|DGCPU1|2|2024-12-17 12:25:48.173|DGCPU1|1|2009-01-29 00:00:00.000|2009-01-29 00:00:00.000|D1|B2 |C6 |B3 ||1|66|NULL|NULL|NULL|NULL|68371|27231|0|MANAGER|2016-05-10 11:26:11.527|2024-12-17 12:25:47.303|DGCPU1

#### Consulta:
```sql

select 
	a.attr1002 as Area,
	a.attr1091 as PrefijoArea,
	s.attr1044 as Serie,
	sb.attr1047 as Subserie,
	e.attr1052 as Nombre,
	e.attr1043 as NumeroExpediente, 
	e.attr1109 as EstadoExpediente,
	e.attr1053 as FechaInicial,
	e.attr1054 as FechaFinal,
	m.memo as Descripcion,
	e.attr1057 as Clasificaciondelainformacion,
	e.attr1135 as Confidencial,
	e.attr1056 as EstadoPrestamo,
	e.attr1118 as FechaFinCentral,
	e.attr1117 as FechaFinGestion,
	e.attr1134 as FrecuenciaConsulta,
	e.attr1055 as UnidadConservacion,
	e.attr1137 as Ingresado,
	e.attr1142 as NoIdentificacion,
	e.attr1143 as Folios,
	e.attr1196 as SiglaAreaHistorica,
	o.rmcreatedBy as CreadoPor,
	o.createddate as FechaCreacion,
	e.objectid,
	e.activestatus,
	e.revisiondate as UltimoEvento,
	e.revisionby as UsuarioUltimoEvento,
	b.cantidadDocumentos,
	c.transactiondate as FechaUltimaModificacion,
	c.username as UsuarioModifico,
	
	t.*
from hsi.rmobjectinstance1010 e left outer join hsi.rmmemo m on m.memoid = e.mk1058
join hsi.rmobjecto on e.objectid = o.objectid
left outer join hsi.rmobjectinstance1013 sb on e.fk1051 = sb.objectID
left outer join hsi.rmobjectinstance1012 s on sb.fk1050 = s.objectID
left outer join hsi.rmobjectinstance1003 a on s.fk1090 = a.objectid
left outer join 
(select count(hsi.keygroupdata219.kg169) as cantidadDocumentos, hsi.keygroupdata219.kg169 as NumeroExpediente 
from hsi.keygroupdata219 join hsi.itemdata on hsi.itemdata.itemnum = hsi.keygroupdata219.itemnum
where hsi.itemdata.status = 0
group by kg169) as b on b.NumeroExpediente = e.attr1043
outer apply (select top 1 username, transactiondate, objectid from hsi.rmobjecthistory a where e.objectid = a.objectid
order by transactiondate desc) as c
left outer join (select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo,
	o.rmcreatedby as CreadoPorTomo,
	o.createdDate as FechaCreacionTomo,
	d.transactiondate as FechaUltimaModificacionTomo,
	d.username as UsuarioModificoTomo
	
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
left outer join hsi.rmobject o on t.objectid = o.objectid
outer apply (select top 1 username, transactiondate, objectid from hsi.rmobjecthistory a where t.objectid = a.objectid
order by transactiondate desc) as d
where t.activestatus = 0


) as t on t.fk1131=e.objectid
where e.activestatus = 0

```

### Expedientes que han sido cambiados
Este reporte permite identificar los expedientes que han tenido modificaciones en los campos de registro. Para cada expediente se muestra:

- El valor inicial
- El valor final
- La fecha en que se realizó el cambio
#### Ejemplo de la consulta:
Nombre|NumeroExpediente|CreadoPor|FechaCreacion|UltimoEvento|UsuarioUltimoEvento|startvalue|endvalue|transactiondate
-|-|-|-|-|-|-|-|-|
2004 CONTRATO No. A14-2004 DE PRESTACIÓN DE SERVICIOS AESCA ASESORÍA JURÍDICA LABORAL (15/07/2004)|9705 |MANAGER |2016-05-10 08:25:12.047|2025-09-27 22:56:58.837|UNITYSCHED|4/23/2021|5/10/2021|2021-05-10 16:05:52.367
2021 PQRSD PETICIONES QUEJAS RECLAMOS SUGERENCIAS Y DENUNCIAS ENERO A DICIEMBRE |66204|JLUQUE|2021-01-05 08:44:11.303|2025-09-04 11:01:26.637|JGARCIA2|5/7/2021 |5/10/2021|2021-05-10 09:45:33.310
2021 FACTURAS MAYO|66436|VSUNS |2021-04-30 19:09:06.317|2025-09-19 11:32:07.923|JGARCIA2|5/7/2021 |5/10/2021|2021-05-10 09:57:06.443
#### Consulta:
```sql
select
	e.attr1052 as Nombre,
	e.attr1043 as NumeroExpediente, 
	o.rmcreatedBy as CreadoPor,
	o.createddate as FechaCreacion,
	e.revisiondate as UltimoEvento,
	e.revisionby as UsuarioUltimoEvento,
	hsi.rmobjecthistory.startvalue,
	hsi.rmobjecthistory.endvalue,
	hsi.rmobjecthistory.transactiondate


from hsi.rmobjectinstance1010 e left outer join hsi.rmmemo m on m.memoid = e.mk1058
join hsi.rmobject  o on e.objectid = o.objectid
left outer join hsi.rmobjectinstance1013 sb on e.fk1051 = sb.objectID
left outer join hsi.rmobjectinstance1012 s on sb.fk1050 = s.objectID
left outer join hsi.rmobjectinstance1003 a on s.fk1090 = a.objectid
left outer join hsi.rmobjecthistory  on e.objectid = hsi.rmobjecthistory.objectid
```
#### Consulta para los expedientes que han sido tocados por Juan José:
```sql
select e.attr1043, sb.attr1047
from hsi.rmobjectinstance1010 e 
left outer join hsi.rmobjectinstance1013 sb on e.fk1051 = sb.objectID

where e.revisionBy like 'JGARCIA2' and e.activeStatus = 0 
```

#### Consulta para los expedientes que han sido tocados por Juan José de la versión 00:
```sql
select e.attr1043, sb.attr1047
from hsi.rmobjectinstance1010 e 
left outer join hsi.rmobjectinstance1013 sb on e.fk1051 = sb.objectID

where e.revisionBy like 'JGARCIA2' and e.activeStatus = 0 and attr1047 like '00-%'
```

### Ubicaciones topográficas de determinados expedientes:
Obtiene la ubicación topográfica de los expedientes que se encuentran en el where
#### Ejemplo de la consulta:
fechafinal|fechainicial|NumExpediente|NombreExpediente|Localizacion|Tomo|FechaInicialTomo|FechaFinalTomo|Deposito|Bloque|Cuerpo|Bandeja|Observaciones|FolioInicial|FolioFinal|Caja|Paquete|Rollo|Posicion|objidTomo|fk1131|activestatusTomo
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
2006-12-06 00:00:00.000|2006-02-15 00:00:00.000|54544|2006 SGR RESOLUCIONES DIRECTOR 2006 |-|1 |2006-02-15 00:00:00.000|2006-12-06 00:00:00.000|00|00|00|00|NULL|1|69|CD04445 |16 |838|1560 |371165|371164|0
2000-12-31 00:00:00.000|2000-01-01 00:00:00.000|32623|2000 RESOLUCIONES - DIRECTOR FOGAFIN|-|1 |2000-01-01 00:00:00.000|2000-12-31 00:00:00.000|00|00|00|00|ADMINISTRATIVO|1|87|CD01388 |14 |357|935|329020|329019|0
#### Consulta:
```sql
select attr1054 as  fechafinal, attr1053 as fechainicial, attr1043 as NumExpediente, attr1052 as NombreExpediente, attr1196 Localizacion, tomo.*
from rmobjectinstance1010 expe
left outer join (select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
where t.activestatus = 0) as tomo on tomo.fk1131 = expe.objectid
where (attr1043 like '54544' or attr1043 like '32623')
and expe.activeStatus = 0
```
_**La consulta obtiene los expedientes que se encuentren en el where basándose en el número, para cambiarlo se agrega o se modifican los existentes**_`or attr1043 like '32624'`


## Consultas de historias laborales:
### Consulta de todos los documentos cargados en historias laborales
Esta consulta genera un listado completo con el número de identificación, nombre y apellido y el itemnum de cada documento asociado. Esto permite, por ejemplo, exportar a Excel y calcular el promedio de cuántos documentos hay cargados por persona.

#### Ejemplo de la consulta:
cc|itemnum|NombreyApellido|itemnumb
-|-|-|-
52976441|1841368|YULY CATHERINE AYALA URRIAGO|1841368
53002054|1842533|DIANA CAROLINA NIÑO CUBILLOS|1842533
41955540|1842555|MARCELA BEJARANO QUINTERO |1842555
41955540|1842561|MARCELA BEJARANO QUINTERO |1842561

#### Consulta:
```sql
Select *
From
(select keyvaluechar as cc, itemnum from hsi.keyitem159 where itemnum in
(select itemnum
from hsi.itemdata
where itemtypenum in
(select itemtypenum from hsi.doctype where itemtypegroupnum = 202))) as a

join

(select keyvaluechar as NombreyApellido, itemnum as itemnumb from hsi.keyitem233 where itemnum in
(select itemnum
from hsi.itemdata
where itemtypenum in
(select itemtypenum from hsi.doctype where itemtypegroupnum = 202))) as b
on a.itemnum = b.itemnumb
```

## Consultas TRD
### Listado áreas
Presenta un listado de todas las áreas con su respectivo código.
#### Ejemplo de la consulta:
Área|Código
-|-
SUBDIRECCION DE MECANISMOS DE RESOLUCION|03-4000 
SUBDIRECCION DE OPERACIONES|00-0300 
SUBDIRECCION DE OPERACIONES|00-3000 
SUBDIRECCION DE OPERACIONES Y ADMINISTRATIVA|01-3000 
SUBDIRECCION DE RECUPERACION DE ACTIVOS|00-0500 

#### Consulta:
```sql
select distinct A.attr1001 as Área, A.attr1002 as Código
from hsi.rmObjectInstance1003 A
left join hsi.rmObjectInstance1025 T on T.objectID = A.fk1180
where A.activeStatus = 0
```



## Consultas correspondencia y PQRSD

### Correspondencia de entrada (Reporte)
Este reporte, disponible en Unity, permite visualizar un listado de las áreas involucradas en las comunicaciones. Incluye filtros que facilitan:

- Identificar quiénes han sido los destinatarios.
- Contar cuántas comunicaciones ha recibido cada persona en un período determinado.
- Analizar cuánta correspondencia proviene de remitentes específicos.
- Consultar una tabla detallada con toda la información relevante para análisis o exportación.

#### Ejemplo del reporte:
![Reporte](image.png)

#### Consulta para obtener las áreas:
```sql
select distinct A.attr1001 as Área, A.attr1001 
from hsi.rmObjectInstance1003 A
left join hsi.rmObjectInstance1025 T on T.objectID = A.fk1180
where A.activeStatus = 0
```
#### Consulta para la correspondencia:
```sql
select f.foldernum Foldernum
,radicado.keyvaluechar Radicado
,fecharadicado.keyvaluetod Fecha
,asunto.keyvaluechar Asunto
,remitenteExterno.keyvaluechar Remitente
,remitenteEntidad.keyvaluechar EntidadRemitente
,destinatarioInterno.keyvaluechar Destinatario
,destinatarioArea.keyvaluechar AreaDestinatario
,fecharadicado.foldernum as foldernumRadicado
from hsi.folder f
left join hsi.folderkey105 radicado on radicado.foldernum = f.foldernum
left join hsi.folderkey108 fecharadicado on fecharadicado.foldernum = f.foldernum
left join hsi.folderkey154 asunto on asunto.foldernum = f.foldernum
left join hsi.folderkey191 remitenteExterno on remitenteexterno.foldernum = f.foldernum
left join hsi.folderkey114 remitenteEntidad on remitenteentidad.foldernum = f.foldernum
left join hsi.folderkey121 destinatarioInterno on destinatarioInterno.foldernum = f.foldernum
left join hsi.folderkey124 destinatarioArea on destinatarioArea.foldernum = f.foldernum
where status = 0
and foldertypenum = 108
and destinatarioArea.keyvaluechar in (
select A.attr1001 --areas
from hsi.rmObjectInstance1003 A
left join hsi.rmObjectInstance1025 T on T.objectID = A.fk1180
where A.activeStatus = 0
and attr1001 in (@{AREA})
AND fecharadicado.keyvaluetod BETWEEN @{fechaIni} AND @{fechaFin}
)
```

### Correspondencia de salida (Reporte)
Este reporte, disponible en Unity, permite visualizar un listado de las áreas involucradas en las comunicaciones salientes. Incluye filtros que facilitan:

- Identificar quiénes han sido los remitentes.
- Contar cuántas comunicaciones se han enviado a cada persona en un período determinado.
- Analizar cuánta correspondencia tiene determinados destinatarios.
- Consultar una tabla detallada con toda la información relevante para análisis o exportación de la correspondencia de salida.
#### Ejemplo del reporte:
![parametros](image-1.png)
![reporte](image-2.png)

#### Consulta:
```sql
select f.foldernum Foldernum
,radicado.keyvaluechar Radicado
,fecharadicado.keyvaluetod Fecha
,asunto.keyvaluechar Asunto
,destinatarioEntidad.keyvaluechar DestinatarioEntidad
,destinatarioExternoNombre.keyvaluechar DestinatarioNombre
,remitenteArea.keyvaluechar remitenteArea
,remitenteInternoNombre.keyvaluechar remitenteInternoNombre
from hsi.folder f
left join hsi.folderkey106 radicado on radicado.foldernum = f.foldernum
left join hsi.folderkey108 fecharadicado on fecharadicado.foldernum = f.foldernum
left join hsi.folderkey154 asunto on asunto.foldernum = f.foldernum
left join hsi.folderkey120 destinatarioEntidad on destinatarioEntidad.foldernum = f.foldernum
left join hsi.folderkey190 destinatarioExternoNombre on destinatarioExternoNombre.foldernum = f.foldernum
left join hsi.folderkey125 remitenteArea on remitenteArea.foldernum = f.foldernum
left join hsi.folderkey109 remitenteInternoNombre on remitenteInternoNombre.foldernum = f.foldernum
where status = 0
and foldertypenum = 109
and remitenteArea.keyvaluechar in (
select A.attr1001
from hsi.rmObjectInstance1003 A
left join hsi.rmObjectInstance1025 T on T.objectID = A.fk1180
where A.activeStatus = 0
and A.attr1002 like '%'+(select SUBSTRING(attr1002,3,5) 
from hsi.rmObjectInstance1003 A
left join hsi.rmObjectInstance1025 T on T.objectID = A.fk1180
where A.activeStatus = 0
and rtrim(attr1001) like rtrim(@{AREA}))
AND fecharadicado.keyvaluetod BETWEEN @{fechaIni} AND @{fechaFin}
)

```

### Formularios de entrada o salida de PQRSD cuya entidad liquidada diga "FRAUDE"
Este reporte permite identificar los formularios de entrada o salida del sistema PQRS en los que la entidad liquidada ha sido registrada con el valor "Fraude". Su objetivo es facilitar el análisis y seguimiento de casos relacionados con posibles irregularidades, permitiendo filtrar y consultar:

#### Ejemplo de la consulta:
itemnum|keyvaluechar|keysetnum
3711107|FRAUDE FOGAFÍN |0
3605362|FRAUDE FOGAFÍN-DAVIVIENDA|0
3800139|FRAUDE FOGAFÍN |0
3771444|FRAUDE FOGAFÍN |0
3700237|FRAUDE DAVIVIENDA - FOGAFÍN |0
#### Consulta:
```sql
select k.* from hsi.itemdata d
left outer join hsi.doctype t on t.itemtypenum = d.itemtypenum
left outer join hsi.keyitem148 k on k.itemnum = d.itemnum
where t.itemtypenum = 128 and k.keyvaluechar like '%Fraude%' and d.datestored > '20250101'
```
_**La consulta obtiene los documentos que hayan sido cargados después del 01/01/2025, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_

### Correspondencia de organismos de control - Entrada
Este reporte extrae todos los registros de correspondencia de entrada recibida en OnBase desde las siguientes entidades:

- Superintendencia Financiera de Colombia
- DIAN
- Contraloría General de la República
- Secretaría de Hacienda Distrital

Incluye los campos: radicado, fecha, remitente (área y nombre), destinatario (entidad y nombre). Permite analizar el flujo de comunicaciones recibidas por la entidad desde organismos externos.
#### Ejemplo de la consulta:
num	radicado|fecha|asunto|EntidadRemitente|NombreRemitente|AreaRemitente|nombreDestinatario|nombreArea
-|-|-|-|-|-|-|-
3333949|2024-E-007517|2024-09-25 12:14:52.000|PROBLEMAS TÉCNICOS DCV|BANCO DE LA REPUBLICA DE COLOMBIA|SERVICIO AL CLIENTE DFV||MARITZA JANIOTH PRIETO NIÑO |DEPARTAMENTO DE OPERACIONES DE TESORERIA
3337517|2024-E-007621|2024-09-27 16:26:25.000|SOLICITUD DE INFORMACION 4392|FISCALÍA GENERAL DE LA NACIÓN|JHON JAIRO VALENCIA RAMIREZ||LUIS EFRÉN CAMACHO MORENO|DEPARTAMENTO JURÍDICO
3337682|2024-E-007627|2024-09-27 17:01:24.000|2024136680-003-000 - 1121 ATENCIÓN AL CIUDADANO - PQRSF - 39 RESPUESTA FINAL E - RESPUESTA A SU COMUNICACIÓN DEL 2024-09-19 08:24|SUPERINTENDENCIA FINANCIERA DE COLOMBIA|MYRIAM MARLENY BERNAL MUNEVAR||WILLIAM ALBERTO ERIRA TRUJILLO|DEPARTAMENTO DE GESTION DE CONTENIDOS 
3341436|2024-E-007736|2024-10-01 17:22:05.000|2024136794-001-000 - 454 SOLICITUD DE INFORMACIÓN ESPORÁDICA - 39 RESPUESTA FINAL E - INFORMAR SI EN EL PERÍODO COMPRENDIDO ENTRE EL 1 DE ABRIL AL 30 DE JUNIO DE 2024, ALGÚN ESTABLECIMIENTO DE CRÉDITO FUE OBJETO DE UN INSTITUTO DE SALVAMENTO|SUPERINTENDENCIA FINANCIERA DE COLOMBIA|ANA CECILIA QUINTERO ACERO ||JOSÉ VICENTE GONZÁLEZ CRUZ|DEPARTAMENTO DEL SISTEMA DE SEGURO DE DEPÓSITOS
3345999|2024-E-007840|2024-10-04 16:56:27.000|2024144838-001-000 - 454 SOLICITUD DE INFORMACIÓN ESPORÁDICA - INFORME CON FECHAS DESDE Y HASTA: 1. REVISOR FISCAL (PRINCIPAL Y SUPLENTE) VIGENTE Y POSESIONADO ANTE ESA ENTIDAD. 2. REVISOR FISCAL (PRINCIPAL Y SUPLENTE) INMEDIATAMENTE ANTERIORES”.|SUPERINTENDENCIA FINANCIERA DE COLOMBIA|MYRIAM MARLENY BERNAL MUNEVAR||MARÍA ELIZABETH GUERRA GARCÍA |DEPARTAMENTO DE INFORMACION FINANCIERA
3342712|2024-E-007770|2024-10-02 16:47:06.000|RESPUESTA RADICADO 2024ER239700O1 SOBRETASA BOMBERIL DECRETO NO. 279 15AGO2024|SECRETARIA DISTRITAL DE HACIENDA DE BOGOTÁ|DIRECCIÓN DISTRITAL DE IMPUESTOS DE BOGOTÁ||MARÍA ELIZABETH GUERRA GARCÍA |DEPARTAMENTO DE INFORMACION FINANCIERA
#### Consulta:
```sql
--ENTRADA

select hsi.itemdata.itemnum as num,
hsi.keyitem105.keyvaluechar as radicado,
hsi.keyitem108.keyvaluetod as fecha,
hsi.keyitem154.keyvaluechar as asunto,
hsi.keygroupdata193.kg114 as EntidadRemitente,
hsi.keygroupdata193.kg191 as NombreRemitente,
hsi.keygroupdata193.kg125 as AreaRemitente,
hsi.keygroupdata199.kg121 as nombreDestinatario,
hsi.keygroupdata199.kg124 as nombreArea


from hsi.itemdata
left outer join hsi.keyitem105 on hsi.itemdata.itemnum = hsi.keyitem105.itemnum
left outer join hsi.keyitem108 on hsi.itemdata.itemnum = hsi.keyitem108.itemnum
left outer join hsi.keyitem154 on hsi.itemdata.itemnum = hsi.keyitem154.itemnum
left outer join hsi.keygroupdata193 on hsi.itemdata.itemnum = hsi.keygroupdata193.itemnum
left outer join hsi.keygroupdata199 on hsi.itemdata.itemnum = hsi.keygroupdata199.itemnum
where hsi.itemdata.itemtypenum = 102 and
(hsi.keygroupdata193.kg114 like '%super%financi%' 
or hsi.keygroupdata193.kg114 like '%dian%'
or hsi.keygroupdata193.kg114 like '%dire%imp%adu%'
or hsi.keygroupdata193.kg114 like '%contralor%gene%'
or hsi.keygroupdata193.kg114 like '%secretar%hac%dis%'
or hsi.keygroupdata193.kg114 like '%ban%rep%'
or hsi.keygroupdata193.kg114 like '%min%edu%'
or hsi.keygroupdata193.kg114 like '%secre%hacienda%'
or hsi.keygroupdata193.kg114 like '%fiscal%gene%nac%'
or hsi.keygroupdata193.kg114 like '%conta%gene%nac%'
or hsi.keygroupdata193.kg114 like '%min%hac%'
or hsi.keygroupdata193.kg114 like '%proc%nac%'
or hsi.keygroupdata193.kg114 like '%vicepr%colom%'
)
and datestoredbetween '20240731' AND '20241231' --CAMBIAR LA FECHA SEGÚN REQUERIDO
```
_**La consulta obtiene los documentos que hayan sido cargados entre el 31/07/2024 y el 31/12/2024, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_

### Correspondencia de organismos de control - Salida
Descripción:
Este reporte presenta la **correspondencia de salida** registrada en OnBase dirigida a las siguientes entidades:

- Superintendencia Financiera de Colombia
- DIAN
- Contraloría General de la República
- Secretaría de Hacienda Distrital

Incluye los campos: radicado, fecha, remitente (área y nombre), destinatario (entidad y nombre). Facilita el seguimiento de comunicaciones oficiales enviadas por la entidad a organismos externos.
#### Ejemplo de la consulta:
num|radicado|fecha|asunto|nombreRemitente|areaRemitente|destinatarioEntidad|destinatarioNombre|destinatarioArea
-|-|-|-|-|-|-|-|-
3213806|2024-S-003387 |2024-08-02 08:57:33.000|OFICIO MENSUAL OBRAS INCONCLUSAS|DINA MARÍA OLMOS APONTE |SUBDIRECCION CORPORATIVA|CONTRALORÍA GENERAL DE LA REPÚBLICA ||
3222120|2024-S-003455 |2024-08-05 11:31:09.000|CIRCULARIZACIÓN OPERACIONES RECIPROCAS DE LA ECP BOGOTÁ DC. A 30 DE JUNIO DE 2024 - SECRETARIA DISTRITAL DE HACIENDA|SUSAN YEIMY GÓMEZ |DEPARTAMENTO DE INFORMACION FINANCIERA|SECRETARIA DISTRITAL DE HACIENDA|KELLY TATIANA CERVERA HORTA |
3323901|2024-S-004312 |2024-09-19 09:35:16.000|202408 BALANCE FOGAFIN BANREP |WILBER SALVADOR ESPITIA PEÑA|DEPARTAMENTO DE INFORMACION FINANCIERA|BANCO DE LA REPUBLICA ||
3337147|2024-S-004457 |2024-09-27 14:43:35.000|RESPUESTA SOLICITUD DE INFORMACIÓN 2024EE0178164|VICENTE GAMBOA BERNAL |DEPARTAMENTO DE GESTIÓN DE OTROS ACTIVOS|CONTRALORÍA GENERAL DE LA NACIÓN|GLORIA INÉS CALVO MONTOYA |CONTRALORA PROVINCIAL – EJECUTIVA DE AUDITORIA
3339823|2024-S-004507 |2024-10-01 08:48:59.000|SOLICITUD CREACIÓN CUENTAS CONTABLES PARA REFLEJAR LAS OPERACIONES DE RECUPERACIÓN Y RESOLUCIÓN DE FOGAFÍN|IVÁN HERNANDO ROMERO PÉREZ|SUBDIRECCION FINANCIERA Y OPERATIVA |CONTADURÍA GENERAL DE LA NACIÓN |ROCIO PEREZ SOTELO|SUBCONTADORA GENERAL Y DE INVESTIGACIÓN 
#### Consulta:
```sql
--SALIDA

select hsi.itemdata.itemnum as num,
hsi.keyitem106.keyvaluechar as radicado,
hsi.keyitem108.keyvaluetod as fecha,
hsi.keyitem154.keyvaluechar as asunto,
hsi.keygroupdata201.kg109 as nombreRemitente,
hsi.keygroupdata201.kg125 as areaRemitente,
hsi.keygroupdata194.kg120 as destinatarioEntidad,
hsi.keygroupdata194.kg190 as destinatarioNombre,
hsi.keygroupdata194.kg124 as destinatarioArea

from hsi.itemdata
left outer join hsi.keyitem106 on hsi.itemdata.itemnum = hsi.keyitem106.itemnum
left outer join hsi.keyitem108 on hsi.itemdata.itemnum = hsi.keyitem108.itemnum
left outer join hsi.keyitem154 on hsi.itemdata.itemnum = hsi.keyitem154.itemnum
left outer join hsi.keygroupdata201 on hsi.itemdata.itemnum = hsi.keygroupdata201.itemnum
left outer join hsi.keygroupdata194 on hsi.itemdata.itemnum = hsi.keygroupdata194.itemnum


where hsi.itemdata.itemtypenum = 103 and
(hsi.keygroupdata194.kg120 like '%super%financi%' 
or hsi.keygroupdata194.kg120 like '%dian%'
or hsi.keygroupdata194.kg120 like '%dire%imp%adu%'
or hsi.keygroupdata194.kg120 like '%contralor%gene%'
or hsi.keygroupdata194.kg120 like '%secretar%hac%dis%'
or hsi.keygroupdata194.kg120 like '%ban%rep%'
or hsi.keygroupdata194.kg120 like '%min%edu%'
or hsi.keygroupdata194.kg120 like '%secre%hacienda%'
or hsi.keygroupdata194.kg120 like '%fiscal%gene%nac%'
or hsi.keygroupdata194.kg120 like '%conta%gene%nac%'
or hsi.keygroupdata194.kg120 like '%min%hac%'
or hsi.keygroupdata194.kg120 like '%proc%nac%'
)
and datestored  between '20240731' AND '20241231'--CAMBIAR LA FECHA SEGÚN REQUERIDO
```
_**La consulta obtiene los documentos que hayan sido cargados entre el 31/07/2024 y el 31/12/2024, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_

### Reporte de Documentos Radicados en 2024 con Fecha de Almacenamiento y Medio de envío
Este reporte permite consultar todos los documentos que han sido radicados durante el año 2024, incluyendo información clave para su trazabilidad y análisis. Los datos extraídos incluyen:

- Fecha de almacenamiento
- Medio de recepción (para documentos entrantes)
- Medio de envío (para documentos salientes)

#### Ejemplo de la consulta:
itemnum|itemname|datestored|TipopDoc|NumeroExpediente|RadicadoEntrada|medioRecepcion|RadicadoSalida|EnvioMedio
-|-|-|-|-|-|-|-|-
3525100|<b>2024-E-010096</b><g></g><r></r> [02-4800-127-04] - <A>68455</A> Comunicaciones enviadas y recibidas - Procesos de transmisión - 2024 PROCESO TRANSMISIÓN FORMATO DE DEPOSITOS INDIVIDUALES PARA PAGO SEGURO DE DEPÓSITOS|2024-12-13 17:06:29.503|Comunicaciones enviadas y recibidas - Procesos de transmisión |68455|2024-E-010096 |E-MAIL|NULL|NULL
3525101|Formulario de Correspondencia de Entrada <R>VENCIDO</R> <b>2024-E-010096</b><g></g><r></r> - <A>ASIGNADO</A> - 12/13/2024 5:13:04 PM - De: ALEJANDRA CORREA AREIZA |2024-12-13 17:06:35.493|Formulario de Correspondencia de Entrada|NULL|2024-E-010096 |E-MAIL|NULL|NULL
3186453|<b>2024-E-005681</b><g></g><r></r> [02-2300-035-00] - <A>68654</A> Petición - DRC - 2024 PQRSD RELACIONAMIENTO CIUDADANO ABRIL A DICIEMBRE - DEPARTAMENTO DE RELACIONAMIENTO CIUDADANO |2024-07-25 10:50:59.000|Petición - DRC|68654|2024-E-005681 |NULL|NULL|NULL
3213864|<b>2024-E-005983</b><g></g><r></r> [02-4800-127-04] - <A>68455</A> Comunicaciones enviadas y recibidas - Procesos Pago del Seguro - 2024 PROCESO TRANSMISIÓN FORMATO DE DEPOSITOS INDIVIDUALES PARA PAGO SEGURO DE DEPÓSITOS |2024-08-02 13:59:57.127|Comunicaciones enviadas y recibidas - Procesos Pago del Seguro|68455|2024-E-005983 |E-MAIL|NULL|NULL
3213865|Formulario de Correspondencia de Entrada <R></R> <b>2024-E-005983</b><g></g><r></r> - <A>ASIGNADO</A> - 8/2/2024 2:38:46 PM - De: ANDRES CONSUEGRA |2024-08-02 13:59:57.860|Formulario de Correspondencia de Entrada|NULL|2024-E-005983 |E-MAIL|NULL|NULL
#### Consulta:
```sql
select i.itemnum, i.itemname, i.datestored, dt.itemtypename as TipopDoc, hsi.keygroupdata219.kg169 as NumeroExpediente,
r.keyvaluechar as RadicadoEntrada, entrada.medioRecepcion as medioRecepcion, rs.keyvaluechar as RadicadoSalida, salida.EnvioMedio
from hsi.itemdata i 
left outer join hsi.doctype dt on i.itemtypenum = dt.itemtypenum
left outer join hsi.keygroupdata219 on i.itemnum = hsi.keygroupdata219.itemnum
left outer join hsi.keyitem105 r on i.itemnum = r.itemnum
left outer join hsi.keyitem106 rs on i.itemnum = rs.itemnum
 
left outer join (
select hsi.keygroupdata132.kg189 as EnvioMedio, rs.keyvaluechar
from hsi.itemdata i
left outer join hsi.keygroupdata132 on i.itemnum = hsi.keygroupdata132.itemnum
left outer join hsi.keyitem106 rs on i.itemnum = rs.itemnum
where i.itemtypenum = 103
) as salida on salida.keyvaluechar = rs.keyvaluechar
 
left outer join (
select mr.keyvaluechar as medioRecepcion, r.keyvaluechar as RadicadoEntrada
from hsi.itemdata i
left outer join hsi.keyitem138 mr on i.itemnum = mr.itemnum
left outer join hsi.keyitem105 r on i.itemnum = r.itemnum
where i.itemtypenum = 102
) as entrada on entrada.RadicadoEntrada = r.keyvaluechar
 
WHERE i.status = 0 and r.keyvaluechar like '%2024-E%' or rs.keyvaluechar like '%2024-S%'
```
_**Para cambiar el año en la última líneas se cambia el 2024 por el año que deseen**_

### Solicitud de histórico de atenciones por canal telefónico y Buzón PQSD
Reporte para un análisis detallado de las atenciones históricas brindadas por el Fondo a través de los canales telefónico y Buzón PQSD, 
La información será utilizada para identificar usuarios únicos, calcular promedios de duración de atención y generar otros indicadores relevantes.
Los campos requeridos en el archivo son los siguientes:

- Número radicado OB
- Fecha de la atención
- Hora inicio de la atención (hora radicado entrada)
- Hora fin de la atención (hora último radicado de salida)
- Número de documento del peticionario
- Nombres y apellidos del peticionario
- Correo electrónico del peticionario
- Teléfono del peticionario
- Respuesta a la pregunta de tratamiento de datos personales (solo aplica para Buzón PQSD)
- Nombre del operador que atendió la petición

#### Ejemplo de la consulta:
atendido|rs|re|fecha
LINA ALEJANDRA SARMIENTO ROSADO |2025-S-004904 |2025-E-007643 |2025-10-02 15:54:26.000
JHOAN DAVID SUÁREZ VARGAS |2025-S-004922 |2025-E-007650 |2025-10-03 11:11:47.000
JHOAN DAVID SUÁREZ VARGAS |2025-S-004916 |2025-E-007651 |2025-10-03 09:29:31.000
#### Consulta para los de salida:
```sql
WITH RankedData AS (
    SELECT 
        atendido.keyvaluechar AS atendido,
        rs.keyvaluechar AS rs,
        re.keyvaluechar AS re,
        fr.keyvaluetod AS fecha,
        ROW_NUMBER() OVER (PARTITION BY re.keyvaluechar ORDER BY fr.keyvaluetod DESC) AS row_num
    FROM itemdata i
    LEFT OUTER JOIN keyitem105 re ON re.itemnum = i.itemnum
    LEFT OUTER JOIN keyitem282 atendido ON atendido.itemnum = i.itemnum
    LEFT OUTER JOIN keyitem106 rs ON rs.itemnum = i.itemnum
    LEFT OUTER JOIN keyitem108 fr ON fr.itemnum = i.itemnum
    WHERE i.itemtypenum = 136
)
SELECT atendido, rs, re, fecha
FROM RankedData
WHERE row_num = 1
ORDER BY re;
```
#### Consulta para los de entrada:
```sql
select 
mr.keyvaluechar MedioRecepcion,
re.keyvaluechar RadicadoEntrada,
fr.keyvaluetod FechaRadicadoEntrada,
id.keyvaluechar NoIdentificacion,
ren.keyvaluechar PeticionarioNombreApellido,
remail.keyvaluechar PeticionarioEmail,
t.keyvaluechar Telefono,
m.keyvaluechar Movil


from itemdata i

left outer join keyitem105 re on re.itemnum = i.itemnum
left outer join keyitem108 fr on fr.itemnum = i.itemnum
left outer join keyitem194 id on id.itemnum = i.itemnum
left outer join keyitem191 ren on ren.itemnum = i.itemnum
left outer join keyitem110 remail on remail.itemnum = i.itemnum
left outer join keyitem195 t on t.itemnum = i.itemnum
left outer join keyitem138 mr on mr.itemnum = i.itemnum
left outer join keyitem425 m on m.itemnum = i.itemnum

where i.itemtypenum = 128
```

### Informe para publicar en datos abiertos reporte de PQRS
Este informe tiene como finalidad presentar a la ciudadanía los casos de PQRS que han sido respondidos de manera definitiva, es decir, se muestra únicamente la última respuesta enviada desde OnBase para cada caso.
Además, los enlaces incluidos en el reporte toman la comunicación del padre de respuesta y la presentan como propia, garantizando una visualización clara y directa del contenido final.
El informe incluye los siguientes campos:

- Radicado → corresponde al campo RadicadoEntrada
- Fecha de radicación → FechaRadicado
- Medio de recepción → CanalRadicacion
- Radicado de salida → RadicadoSalida
- Fecha de respuesta → FechaRespuesta
- Tiempo de respuesta (horas) → tiempoRespuesta_HH
#### Ejemplo de la consulta:
RadicadoEntrada|FechaRadicado|CanalRadicacion|Tipo|SubTipo|Entidad|RadicadoSalida|FechaRespuesta|tiempo_rta/HH
-|-|-|-|-|-|-|-|-
2025-E-006782 |2025-09-01 07:37:43.000|PÁGINA WEB|DERECHOS DE PETICIÓN|SEGURO DE DEPÓSITOS |FOGAFÍN |2025-S-004368 |2025-09-01 12:13:45.000|0
2025-E-006783 |2025-09-01 09:09:09.000|CORREO ELECTRÓNICO|DERECHOS DE PETICIÓN|SEGURO DE DEPÓSITOS |FOGAFÍN |2025-S-004371 |2025-09-01 16:11:48.000|0
2025-E-006785 |2025-09-01 09:18:36.000|CORREO ELECTRÓNICO|DERECHOS DE PETICIÓN - PROCESOS LIQUIDATORIOS |SOLICITUD INFORMACIÓN |COOPERATIVA FINANCIERA SOLIDARIOS |2025-S-004472 |2025-09-08 14:17:23.000|5
2025-E-006787 |2025-09-01 09:33:57.000|ATENCIÓN TELEF?NICA|DERECHOS DE PETICIÓN|OTRAS ENTIDADES |BANCO SERFINANZA S.A. |2025-S-004361 |2025-09-01 09:33:59.000|0
2025-E-006788 |2025-09-01 09:36:24.000|CHAT|DERECHOS DE PETICIÓN|OTRAS ENTIDADES |LULO BANK S.A.|2025-S-004362 |2025-09-01 09:36:26.000|0
#### Consulta:
```sql

--DATOS ABIERTOS YUJED PQRS DEFINITIVA
select t.Radicado as [RadicadoEntrada],
t.Fecha as [FechaRadicado],
case
	when t.Medio like 'E-MAIL' then 'CORREO ELECTRÓNICO'
	when t.Medio like 'PERSONAL' then 'ATENCIÓN PRESENCIAL'
	when t.Medio like 'PORTAL' then 'PÁGINA WEB'
	when t.Medio like 'SIRI' then 'CORREO ELECTRÓNICO'
	when t.Medio like 'TELEFONICO' then 'ATENCIÓN TELEF�NICA'
	when t.Medio like 'FISICO' then 'CARTA'
	when t.Medio like 'CHAT' then 'CHAT'
end as [CanalRadicacion],
t.Tipo,
t.SubTipo,
t.Entidad,
t.Radicado_Sal as [RadicadoSalida],
t.fecha_rta as [FechaRespuesta],
(
    DATEDIFF(DAY, t.Fecha, t.fecha_rta) -
    -- Restar fines de semana
    (DATEDIFF(WEEK, t.Fecha, t.fecha_rta) * 2) -
    -- Ajuste para el día de inicio si es domingo
    CASE WHEN DATEPART(WEEKDAY, t.Fecha) = 1 THEN 1 ELSE 0 END -
    -- Ajuste para el día final si es s�bado
    CASE WHEN DATEPART(WEEKDAY, t.fecha_rta) = 7 THEN 1 ELSE 0 END -
    -- Restar días festivos que caen en días hábiles
    (
        SELECT COUNT(*)
        FROM [OnBase].hsi.businessholiday bh
        WHERE bh.startdate >= t.Fecha
          AND bh.startdate <= t.fecha_rta
          AND DATEPART(WEEKDAY, bh.startdate) NOT IN (1, 7) -- Excluir festivos que caen en domingo(1) o s�bado(7)
    )
) AS 'tiempo_rta/HH'
from

(--Consulta final completa radicado de salida (Normal)
SELECT
    RadicadoEntrada.Keyvaluechar AS 'Radicado',
    kw108.Keyvaluetod AS 'Fecha',
    kw138.Keyvaluechar AS 'Medio',
    kw137.Keyvaluechar AS 'Tipo',
    kw155.Keyvaluechar AS 'SubTipo',
    kw148.Keyvaluechar AS 'Entidad',

    
    salida.Radicado_Sal, 
    salida.fecha_rta
FROM [OnBase].hsi.itemdata i
JOIN [OnBase].hsi.keyitem105 RadicadoEntrada ON RadicadoEntrada.itemnum = i.itemnum
JOIN [OnBase].hsi.keyitem108 kw108 ON kw108.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem138 kw138 ON kw138.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem137 kw137 ON kw137.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem148 kw148 ON kw148.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem155 kw155 ON kw155.itemnum = i.itemnum

--Busca el radicado de salida correspondiente y trae �nicamente el m�s reciente (la �ltima respusta)
OUTER APPLY (
    SELECT TOP 1 
        RadicadoSalida.keyvaluechar AS Radicado_Sal,
        kw108.keyvaluetod AS fecha_rta
    FROM [OnBase].hsi.itemdata i2
    JOIN [OnBase].hsi.keyitem105 RadicadoEntrada2 ON RadicadoEntrada2.itemnum = i2.itemnum
    JOIN [OnBase].hsi.keyitem108 kw108 ON kw108.itemnum = i2.itemnum
    LEFT JOIN [OnBase].hsi.keyitem106 RadicadoSalida ON RadicadoSalida.itemnum = i2.itemnum
    WHERE i2.status = 0 
      AND i2.itemtypenum = 136
      AND RadicadoEntrada2.keyvaluechar = RadicadoEntrada.keyvaluechar
    ORDER BY kw108.keyvaluetod DESC
) AS salida
WHERE i.status = 0 
  AND i.itemtypenum = 128
  and salida.Radicado_Sal is not null

union all

  --consulta para los enlaces (hijos enlaza con padres)
Select re.keyvaluechar, completa.fecha, completa.Medio, completa.Tipo, completa.SubTipo, completa.EntidadLGA Entidad, completa.Radicado_Sal, completa.fecha_rta
from keyitem692 enlace
left outer join keyitem105 as re on enlace.itemnum = re.itemnum
left outer join(
SELECT
    RadicadoEntrada.Keyvaluechar AS 'Radicado',
    kw108.Keyvaluetod AS 'Fecha',
    kw138.Keyvaluechar AS 'Medio',
    kw137.Keyvaluechar AS 'Tipo',
    kw155.Keyvaluechar AS 'SubTipo',
	kw148.Keyvaluechar AS 'EntidadLGA',

    
	
    salida.Radicado_Sal, 
    salida.fecha_rta
FROM [OnBase].hsi.itemdata i
JOIN [OnBase].hsi.keyitem105 RadicadoEntrada ON RadicadoEntrada.itemnum = i.itemnum
JOIN [OnBase].hsi.keyitem108 kw108 ON kw108.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem138 kw138 ON kw138.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem137 kw137 ON kw137.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem148 kw148 ON kw148.itemnum = i.itemnum
LEFT JOIN [OnBase].hsi.keyitem155 kw155 ON kw155.itemnum = i.itemnum


--Busca el radicado de salida correspondiente y trae �nicamente el m�s reciente (la �ltima respusta)
OUTER APPLY (
    SELECT TOP 1 
        RadicadoSalida.keyvaluechar AS Radicado_Sal,
        kw108.keyvaluetod AS fecha_rta
    FROM [OnBase].hsi.itemdata i2
    JOIN [OnBase].hsi.keyitem105 RadicadoEntrada2 ON RadicadoEntrada2.itemnum = i2.itemnum
    JOIN [OnBase].hsi.keyitem108 kw108 ON kw108.itemnum = i2.itemnum
    LEFT JOIN [OnBase].hsi.keyitem106 RadicadoSalida ON RadicadoSalida.itemnum = i2.itemnum
    WHERE i2.status = 0 
      AND i2.itemtypenum = 136
      AND RadicadoEntrada2.keyvaluechar = RadicadoEntrada.keyvaluechar
    ORDER BY kw108.keyvaluetod DESC
) AS salida
WHERE i.status = 0 
  AND i.itemtypenum = 128
  and salida.Radicado_Sal is not null
) as completa on completa.Radicado = enlace.keyvaluechar) as t
--where DATEPART(YEAR,t.Fecha)= datepart(year,getdate())
where t.fecha > '20250901' --CAMBIAR FECHA SEGÚN NECESIDAD
--and t.Radicado like '%2025-E-007293%'
```
_**La consulta obtiene los documentos que hayan sido cargados después del 01/09/2025, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_


## Informes útiles para el DGC
### Documentos sin código de expediente
Muestra a qué documentos les falta del código del expediente
#### Ejemplo de la consulta:
itemnum|CodExpediente|itemname|datestored
-|-|-|-
4031453|NULL|<b></b><g></g><r></r> [03-2200-195-00] - <A>70891</A> Formato revelación de inversiones - DTH Historias Laborales - HISTORIA LABORAL-1010208025-ANDRÉS FELIPE QUINTANA RAMÍREZ|2025-09-10 17:23:27.000
4023396|NULL|<b></b><g>2025-S-004455</g><r></r> [02-2200-043-06] - <A>66914</A> Comunicaciones enviadas y recibidas - DGH Historias Laborales - HISTORIA LABORAL-52476956-MARÍA LUCRECIA RODRÍGUEZ CASTELLANOS |2025-09-08 09:06:18.963
4023404|NULL|<b>2025-E-006964</b><g></g><r></r> [03-3300-073-00] - <A>71483</A> Anexos de factura - 2025 FACTURAS SEPTIEMBRE - DEPARTAMENTO DE INFORMACIÓN FINANCIERA |2025-09-08 09:07:50.470
4023380|NULL|PQRSD - Solicitud Concepto - 2025-E-006785 - <G>RESPUESTA ENVIADA</G>|2025-09-08 08:44:29.500
#### Consulta:
```sql
select hsi.itemdata.itemnum, hsi.keyitem169.keyvaluechar as CodExpediente, hsi.itemdata.itemname, hsi.itemdata.datestored
from hsi.itemdata left outer join hsi.keyitem169 on hsi.keyitem169.itemnum = hsi.itemdata.itemnum
where hsi.itemdata.itemtypegroupnum <> 1 and hsi.keyitem169.keyvaluechar is null 
and hsi.itemdata.datestored > '20250901'
```
_**La consulta obtiene los documentos que hayan sido cargados después del 01/09/2025, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_

### Cantidad de documentos en cada tipo documental
Recuento de todos los documentos cargados por tipo documental
#### Ejemplo de la consulta:
itemtypename|cuenta
-|-
Acción de Tutela|526
Acta bienes dados de baja - cierre|5
Acta comité de Auditoría|36
#### Consulta:
```sql
--CUENTA LA CANTIDAD DE DOCUMENTOS EN CADA TIPO DOCUMENTAL
select hsi.doctype.itemtypenum, count(hsi.doctype.itemtypenum) as cuenta from hsi.doctype 
left outer join hsi.itemdata on hsi.doctype.itemtypenum = hsi.itemdata.itemtypenum
where hsi.itemdata.status = 0
group by hsi.doctype.itemtypenum

```

### Inventario de Documentos Electrónicos de Conservación Total
_Corte al 30 de junio de 2023_
Esta consulta permite conocer los documentos electrónicos clasificados como de conservación total, con información actualizada al 30 de junio de 2023. Permite identificar atributos clave de cada documento, tales como:
- Serie documental
- Subserie documental
- Tipo documental
- Departamento responsable del documento


#### Ejemplo de la consulta:

#### Consulta:
```sql
select com.*, d.itemnum, d.datestored
from hsi.itemdata d
right outer join 
(select trd.attr1170 as TRD, a.attr1002 as codArea, a.attr1001 as nomArea,
s.attr1044 as codSerie, s.attr1045 as nomSerie,
sb.attr1047 as codSubs, sb.attr1048 as nomSubs, sb.attr1106 dispFin, t.attr1098 as codTipo, t.attr1101 as nombreTipo, ob.attr1069 as nombreOB, ob.attr1068 as idOB
from 
hsi.rmobjectinstance1022 t
left outer join hsi.rmobjectinstance1015 ob on t.fk1099 = ob.objectID
left outer join hsi.rmobjectinstance1013 sb on t.fk1100 = sb.objectID
left outer join hsi.rmobjectinstance1012 s on sb.fk1050 = s.objectID
left outer join hsi.rmobjectinstance1003 a on s.fk1090 = a.objectID
left outer join hsi.rmobjectinstance1033 trd on a.fk1180 = trd.objectID
where trd.attr1170 like '%2%' and sb.attr1106 like'%Conservación%' and t.activestatus = 0) com on d.itemtypenum = com.idOB
where d.status = 0
```

### Cantidad de documentos cargados con extensiones
Muestra la cantidad de documentos que fueron cargados y los agrupa por extensiones
#### Ejemplo de la consulta:
ext|cant
-|-
.docx |102635
.dvf|14
.emf|12
.err|1
.fpp|1
.FST|2
.icw|3
#### Consulta:
```sql
select e.ext, count(e.ext) as cant
from (select substring(filepath,CHARINDEX('.',filepath,len(filepath)-5),10) as ext from hsi.itemdatapage) as e
group by e.ext
```

### Llave confidencial de historias laborales
En algunos casos, por error, las historias laborales se cargan con la llave confidencial marcada como "Confidencial" en lugar de "Pública". Cuando esto ocurre, el documento queda restringido y no puede ser consultado por los usuarios, lo que puede afectar la disponibilidad de la información.

Es importante verificar que el valor de la keyword esté correctamente diligenciado como "Pública" para asegurar el acceso adecuado a los documentos, para esto sirve esta consulta, muestra todos los documentos que tienen la llave confidencial diligenciada.

Para solucionarlo, es necesario abrir con el usuario manager el unity, buscar el itemnum y modificar la llave de confidencial

#### Ejemplo de la consulta:
itemnum|keyvaluechar|keysetnum
2929798|CONFIDENCIAL |0
2929800|CONFIDENCIAL |0
2929811|CONFIDENCIAL |0
2945398|CONFIDENCIAL |0
#### Consulta:
```sql
select k.* from hsi.itemdata d
left outer join hsi.doctype t on t.itemtypenum = d.itemtypenum
left outer join hsi.keyitem398 k on k.itemnum = d.itemnum
where t.itemtypegroupnum = 202 and k.keyvaluechar like 'CONFIDENCIAL'
```

### Listado de todos los documentos cuya llave confidencial sea diferente a PUBLICA
Si el documento tiene en la llave confidencial un texto diferente a PUBLICA no podrá ser recuperado desde el unity a menos que sea con el usuario MANAGER. Este reporte permite identificar estos documentos.
#### Ejemplo de la consulta:
itemnum|kg167|kg166|kg168|kg102|kg171|kg103|kg374|kg193|kg169|kg141|kg435|keyvaluechar
-|-|-|-|-|-|-|-|-|-|-|-|-
2945562|01-2200 |DEPARTAMENTO DE GESTION HUMANA|01-2200-043|HISTORIAS LABORALES |01-2200-043-06 |HISTORIAS LABORALES EMPLEADOS DE PLANTA |01-2200-043-06-93 |CORRESPONDENCIA ENVIADA Y RECIBIDA|16837|HISTORIA LABORAL-51905477-NANCY STELLA QUIROGA VELASCO|01 |CONFIDENCIAL 
2946215|01-2200 |DEPARTAMENTO DE GESTION HUMANA|01-2200-043|HISTORIAS LABORALES |01-2200-043-06 |HISTORIAS LABORALES EMPLEADOS DE PLANTA |01-2200-043-06-93 |CORRESPONDENCIA ENVIADA Y RECIBIDA|16828|HISTORIA LABORAL-1010172474-MANUEL SEBASTIÁN DÍAZ LÓPEZ |01 |CONFIDENCIAL 
2946349|01-2200 |DEPARTAMENTO DE GESTION HUMANA|01-2200-043|HISTORIAS LABORALES |01-2200-043-06 |HISTORIAS LABORALES EMPLEADOS DE PLANTA |01-2200-043-06-10 |CERTIFICADOS DE ESTUDIOS|16837|HISTORIA LABORAL-51905477-NANCY STELLA QUIROGA VELASCO|01 |CONFIDENCIAL 
3042679|01-2200 |DEPARTAMENTO DE GESTION HUMANA|01-2200-043|HISTORIAS LABORALES |01-2200-043-06 |HISTORIAS LABORALES EMPLEADOS DE PLANTA |01-2200-043-06-10 |CERTIFICADOS DE ESTUDIOS|16824|HISTORIA LABORAL-1013610765-LAURA XIMENA CIFUENTES ALBA |01 |CONFIDENCIAL 
3042891|01-2200 |DEPARTAMENTO DE GESTION HUMANA|01-2200-043|HISTORIAS LABORALES |01-2200-043-06 |HISTORIAS LABORALES EMPLEADOS DE PLANTA |01-2200-043-06-67 |CERTIFICADO DE INGRESOS Y RETENCIONES |16824|HISTORIA LABORAL-1013610765-LAURA XIMENA CIFUENTES ALBA |01 |CONFIDENCIAL 
#### Consulta:
```sql
select clasificacion.*, confidencial.keyvaluechar from hsi.keyitem398 confidencial
left outer join hsi.keygroupdata219 clasificacion on clasificacion.itemnum = confidencial.itemnum
where keyvaluechar not like 'PUBLICA'
```

### Notificaciones pendientes por enviar
Cuando se pausan las notificaciones o hay un error con el SMTP las notificaciones de OnBase quedan represadas y se pueden consultar con esta consulta.
#### Consulta:
```sql
SELECT
DQ.DISTREQUESTNUM AS ID_PETICION,
DQ.REQUESTDATE AS FECHAHR,
RTRIM(EQ.DISTSUBJECT) AS ASUNTO,
EQ.BODY AS MENSAJE,
CASE DQ.REQUESTSTATUS 
WHEN -1 THEN 'FALLIDO'
WHEN 0 THEN 'OK'
ELSE '' END AS ESTADO,
(STUFF((
SELECT ';'+RTRIM(EQR.EMAILUSERPART) + '@' + RTRIM(EQR.DOMAIN)
FROM HSI.EMAILQUEUERECIP EQR
WHERE EQR.DISTREQUESTNUM = DQ.DISTREQUESTNUM AND EQR.RECIPIENTTYPE = 1
FOR XML PATH('')
),1,1,'' )) AS PARA,
(STUFF((
SELECT ';'+RTRIM(EQR.EMAILUSERPART) + '@' + RTRIM(EQR.DOMAIN)
FROM HSI.EMAILQUEUERECIP EQR
WHERE EQR.DISTREQUESTNUM = DQ.DISTREQUESTNUM AND EQR.RECIPIENTTYPE = 2
FOR XML PATH('')
),1,1,'' )) AS CC,
(STUFF((
SELECT ';'+RTRIM(EQR.EMAILUSERPART) + '@' + RTRIM(EQR.DOMAIN)
FROM HSI.EMAILQUEUERECIP EQR
WHERE EQR.DISTREQUESTNUM = DQ.DISTREQUESTNUM AND EQR.RECIPIENTTYPE = 3
FOR XML PATH('')
),1,1,'' )) AS CCO
FROM HSI.EMAILQUEUE EQ
INNER JOIN HSI.DISTRIBUTIONQUEUE DQ ON EQ.DISTREQUESTNUM = DQ.DISTREQUESTNUM
```

### Reporte de Documentos por Expediente con Información de Radicado y Medio de Recepción/Envío
Este reporte permite consultar todos los documentos asociados a un expediente específico, incluyendo información clave para su trazabilidad. En particular, se extraen los siguientes datos:

- Número de radicado del documento
- Medio de recepción (para documentos entrantes)
- Medio de envío (para documentos salientes)

El objetivo es facilitar el seguimiento de las comunicaciones documentales, identificar el canal utilizado y apoyar procesos de auditoría o gestión documental.
#### Ejemplo de la consulta:
itemnum|itemname|datestored|TipopDoc|NumeroExpediente|RadicadoEntrada|medioRecepcion|RadicadoSalida|EnvioMedio
-|-|-|-|-|-|-|-|-
3695382|<b></b><g>2025-S-000519</g><r></r> [03-3001-023-00] - <A>70937</A> Acuse de recibo correspondencia - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCHIVO |2025-02-04 14:47:51.137|Acuse de recibo correspondencia |70937|NULL|NULL|2025-S-000519 |CERTIMAIL 
3695438|<b></b><g>2025-S-000519</g><r></r> [03-3001-023-00] - <A>70937</A> Acuse de recibo correspondencia - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCHIVO |2025-02-04 15:06:54.057|Acuse de recibo correspondencia |70937|NULL|NULL|2025-S-000519 |CERTIMAIL 
3703784|<b></b><g>2025-S-000708</g><r></r> [03-3001-023-00] - <A>70937</A> Acuse de recibo correspondencia - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCHIVO |2025-02-13 10:53:39.867|Acuse de recibo correspondencia |70937|NULL|NULL|2025-S-000708 |FISICO
3711991|<b>2025-E-001274</b><g></g><r></r> [03-3002-079-00] - <A>70937</A> Póliza de cumplimiento y garantía - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCHIV|2025-02-18 13:43:42.077|Póliza de cumplimiento y garantía |70937|2025-E-001274 |E-MAIL|NULL|NULL
3711992|<b>2025-E-001274</b><g></g><r></r> [03-3002-079-00] - <A>70937</A> Póliza de cumplimiento y garantía - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCHIV|2025-02-18 13:44:11.193|Póliza de cumplimiento y garantía |70937|2025-E-001274 |E-MAIL|NULL|NULL
3695546|<b>2025-E-000890</b><g></g><r></r> [03-3002-079-00] - <A>70937</A> Documentos del proponente - ordenes - 2025 ORDEN 1112/2025 MEMORY CORP SAS CUSTODIAR - PRESERVAR Y ATENDER LAS CONSULTAS DE CAJAS DE REFERENCIA X200 Y X300 QUE CONTIENEN DOCUMENTOS DE ARCH|2025-02-04 15:49:32.220|Documentos del proponente - ordenes |70937|2025-E-000890 |E-MAIL|NULL|NULL
#### Consulta:
```sql
select i.itemnum, i.itemname, i.datestored, dt.itemtypename as TipopDoc, hsi.keygroupdata219.kg169 as NumeroExpediente,
r.keyvaluechar as RadicadoEntrada, entrada.medioRecepcion as medioRecepcion, rs.keyvaluechar as RadicadoSalida, salida.EnvioMedio
from hsi.itemdata i 
left outer join hsi.doctype dt on i.itemtypenum = dt.itemtypenum
left outer join hsi.keygroupdata219 on i.itemnum = hsi.keygroupdata219.itemnum
left outer join hsi.keyitem105 r on i.itemnum = r.itemnum
left outer join hsi.keyitem106 rs on i.itemnum = rs.itemnum

left outer join (
select hsi.keygroupdata132.kg189 as EnvioMedio, rs.keyvaluechar
from hsi.itemdata i
left outer join hsi.keygroupdata132 on i.itemnum = hsi.keygroupdata132.itemnum
left outer join hsi.keyitem106 rs on i.itemnum = rs.itemnum
where i.itemtypenum = 103
) as salida on salida.keyvaluechar = rs.keyvaluechar

left outer join (
select mr.keyvaluechar as medioRecepcion, r.keyvaluechar as RadicadoEntrada
from hsi.itemdata i
left outer join hsi.keyitem138 mr on i.itemnum = mr.itemnum
left outer join hsi.keyitem105 r on i.itemnum = r.itemnum
where i.itemtypenum = 102
) as entrada on entrada.RadicadoEntrada = r.keyvaluechar

WHERE hsi.keygroupdata219.kg169 like  @{NumeroExpediente} and i.status = 0
```

### Cantidad de documentos cargados a las series entre julio 2023 y julio 2024
Obtiene la cantidad de documentos cargados en las series entre un periodo de tiempo
#### Ejemplo de la consulta:

| Serie       | Nombre de la Serie             | Cantidad de Documentos Cargados |
|-------------|--------------------------------|----------------------------------|
| 01-2100-001 | ACCIONES CONSTITUCIONALES      | 72                               |
| 02-2100-001 | ACCIONES CONSTITUCIONALES      | 770                              |
| 01-2000-003 | ACTAS                          | 0                                |
| 01-2100-003 | ACTAS                          | 0                                |
| 01-2200-003 | ACTAS                          | 6                                |
#### Consulta:
```sql
SELECT
    s.attr1044 AS Serie, s.attr1045 as NombreSerie,
    COUNT(i.itemnum) AS CantidadDocsCargados
FROM 
    hsi.rmObjectInstance1012 s
	
LEFT OUTER JOIN 
    hsi.keygroupdata219 c ON s.attr1044 = c.kg168
LEFT OUTER JOIN 
    hsi.itemdata i ON c.itemnum = i.itemnum 
    AND i.datestored > '2023-07-01'  --CAMBIAR FECHAS SEGÚN NECESIDAD
    AND i.datestored <= '2024-07-31' --CAMBIAR FECHAS SEGÚN NECESIDAD
    AND i.itemtypegroupnum NOT IN (1, 292, 295) 
    AND i.status = 0

where s.attr1044 like '01-%' or s.attr1044 like '02-%' and s.activeStatus=0 --EL 01 O 02 PERTENECE A LA VERSIÓN DE TABLA, SI SE NECESITA PARA LA 03 SERÍA or s.attr1044 like '03-%'
GROUP BY 
    s.attr1044, s.attr1045;
```
_**Se deben cambiar las fechas según lo necesario**_

### Cantidad de documentos cargados a las subseries entre julio 2023 y julio 2024
Obtiene la cantidad de documentos cargados en las subseries entre un periodo de tiempo
#### Ejemplo de la consulta:

SubSerie|NombreSerie|CantidadDocsCargados
-|-|-
01-2100-001-01 |ACCIONES DE CUMPLIMIENTO|0
02-2100-001-01 |ACCIONES DE CUMPLIMIENTO|0
01-2100-001-03 |ACCIONES DE GRUPO |11
02-2100-001-03 |ACCIONES DE GRUPO |0
#### Consulta:
```sql
SELECT 
    s.attr1047 AS SubSerie, s.attr1048 as NombreSerie,
    COUNT(i.itemnum) AS CantidadDocsCargados
FROM 
    hsi.rmObjectInstance1013 s
	
LEFT OUTER JOIN 
    hsi.keygroupdata219 c ON s.attr1047 = c.kg171
LEFT OUTER JOIN 
    hsi.itemdata i ON c.itemnum = i.itemnum 
    AND i.datestored > '2023-07-01' --CAMBIAR FECHAS SEGÚN NECESIDAD
    AND i.datestored <= '2024-07-31' --CAMBIAR FECHAS SEGÚN NECESIDAD
    AND i.itemtypegroupnum NOT IN (1, 292, 295) 
    AND i.status = 0

where s.attr1047 like '01-%' or s.attr1047 like '02-%' and s.activeStatus=0 --EL 01 O 02 PERTENECE A LA VERSIÓN DE TABLA, SI SE NECESITA PARA LA 03 SERÍA or s.attr1044 like '03-%'
GROUP BY 
    s.attr1047, s.attr1048;	

```
_**Se deben cambiar las fechas según lo necesario**_

### Identificar documentos que deben ser considerados para la transferencia - SUBSERIES
El objetivo es identificar los documentos que deben ser considerados para transferencia, basándose en el tiempo de gestión definido para cada subserie.

Para cada subserie, se calcula el período de revisión de documentos de la siguiente manera:

- Se toma el **tiempo de gestión** de la subserie.
- Se retrocede esa cantidad de años desde el año actual.
- Luego, se retrocede **un año adicional** para definir el intervalo de búsqueda.
- Por ejemplo, si el tiempo de gestión es de 2 años, se retrocede a 2022, y luego a 2021. El período de revisión será del **01/07/2021 al 31/07/2022**.

Este informe contiene la información de todos los documentos que fueron cargados en el período correspondiente de cada subserie.

- `AñoInicio`: Año desde julio en que inicia el período de revisión.
- `AñoFin`: Año hasta julio en que finaliza el período de revisión.
- `TiempoGestión`: Tiempo de gestión de los documentos.
- 
#### Correo de solicitud:
Buenas tardes,
De acuerdo con lo discutido en la reunión Foco del mes pasado, les comparto los informes solicitados para la transferencia.
El informe solicitado consistía en calcular el tiempo de gestión de la subserie y retroceder en el tiempo la cantidad exacta de años correspondientes a ese período de gestión. Luego, se debe retroceder un año adicional para definir el intervalo en el que se buscarán los documentos cuya fecha corresponda a dicho período
Por ejemplo, si el tiempo de retención es de 2 años, retrocedemos a 2022, y a partir de ahí retrocedemos un año más (2021). El período a considerar para buscar los documentos cargados basándose en la fecha del documento sería del 01/07/2021 al 31/07/2022. 

Primer informe:
-	“Subseries”: Contiene la información de todos los documentos que fueron cargados en el periodo correspondiente de cada subserie
o	AñoInicio= Es el año que indica desde julio de qué año empieza el periodo para la revisión de los documentos
o	AñoFin Es el año que indica hasta julio de qué año termina el periodo para la revisión de los documentos
o	TiempoGestión= Es el tiempo de gestión de los documentos
-	“Tipos Documentales”: Contiene la información de todos los documentos que fueron cargados en el periodo correspondiente de cada subserie
o	AñoInicio= Es el año que indica desde julio de qué año empieza el periodo para la revisión de los documentos
o	AñoFin Es el año que indica hasta julio de qué año termina el periodo para la revisión de los documentos
o	TiempoGestión= Es el tiempo de gestión de los documentos

Quedo atenta cualquier duda adicional,

#### Ejemplo de la consulta:
codigoSerie|nombreSubserie|totalDocsCargados|anioInicio|anioFin|TiempoGestion
-|-|-|-|-|-
02-1100-085-01 |PLAN ANUAL DE AUDITORIA INTERNA |10|2021|2022|2
02-2001-035-00 |DERECHOS DE PETICIÓN|198|2022|2023|1
02-2001-045-11 |INFORMES ANUALES DE GESTION DEL FONDO |6|2022|2023|1
02-2001-118-01 |AYUDAS DE MEMORIA GRUPO ASESOR DE COMUNICACIONES|0|2022|2023|1
02-2001-123-01 |INVESTIGACIONES CRISIS FINANCIERA |0|2022|2023|1
#### Consulta:
```sql
--SUBSERIES
DECLARE @codigo NVARCHAR(255), @subserie NVARCHAR(255), @gestion int, @anio int

IF OBJECT_ID('tempdb..#Resultados') IS NOT NULL
    DROP TABLE #Resultados

CREATE TABLE #Resultados (
    codigoSerie NVARCHAR(255), 
	nombreSubserie NVARCHAR(255), 
    totalDocsCargados INT,
	anioInicio INT,
	anioFin INT,
	TiempoGestion INT
)

-- Definir el cursor
DECLARE resultados CURSOR FOR
SELECT attr1047 AS codigo, attr1088 AS gestion, sb.attr1048 as subserie
FROM hsi.rmobjectinstance1013 sb
WHERE LEFT(attr1047, 3) = '02-' and sb.activeStatus = 0 --VERSION DE TABLA

-- Abrir el cursor
OPEN resultados

-- Obtener el primer registro
FETCH NEXT FROM resultados INTO @codigo, @gestion, @subserie

-- Recorrer los resultados
WHILE @@FETCH_STATUS = 0
BEGIN
    -- Aquí puedes hacer lo que necesites con cada registro
	set @anio = 2024

	set @anio = @anio - @gestion
	
	INSERT INTO #Resultados (codigoSerie, nombreSubserie, totalDocsCargados, anioInicio, anioFin, TiempoGestion)
    select @codigo codigoSerie, @subserie nombreSubserie, count(i.itemnum) totalDocsCargados, @anio-1 anioInicio, @anio anioFin, @gestion TiempoGestion from hsi.keygroupdata219 c 
	left outer join hsi.itemdata i on i.itemnum = c.itemnum
	where i.status=0 and i.itemdate <= CAST(@anio AS NVARCHAR(4))+'-07-31' and i.itemdate > CAST(@anio-1 AS NVARCHAR(4))+'-07-01' and c.kg171=@codigo

    -- Obtener el siguiente registro
    FETCH NEXT FROM resultados INTO @codigo, @gestion, @subserie
END

-- Cerrar y liberar el cursor
CLOSE resultados
DEALLOCATE resultados


SELECT * FROM #Resultados
```
_**IMPORTANTE: Cambiar la versión de la tabla**_


### Generación de inventario de expedientes por número de caja en OnBase
Se solicita amablemente la colaboración para generar, a través de OnBase, un inventario de los expedientes asociados a los números de caja que se encuentran detallados en el archivo Excel adjunto.
El inventario debe contener la siguiente información por cada expediente identificado:

- Número de expediente
- Nombre del expediente
- Número de caja

#### Ejemplo de la consulta:
NumExpediente|NombreExpediente|Caja|Descripcion|attr1047|attr1196
-|-|-|-|-|-
14570|2014 ANEXOS DE ACTAS DE JUNTA DIRECTIVA FOGAFIN SESION 19 AGOSTO|CD04771 |2014 ANEXOS DE ACTAS DE JUNTA DIRECTIVA FOGAFIN SESION 19 AGOSTO (49611)|01-2000-003-39 |Conservacion Total Memory
18093|1990 ANEXOS DE ACTAS JUNTA DIRECTIVA FOGAFIN-18624|CD00652 |00-0100|DIRECCION GENERAL|00-0100-001|ACTAS|00-0100-001-01|Actas Junta Directiva|531|00-0100-001-01 |Conservacion Total Memory
18105|1993 ANEXOS DE ACTAS JUNTA DIRECTIVA FOGAFIN -19394 |CD00726 |00-0200|SECRETARIA GENERAL|00-0200-002|ACTAS|00-0200-002-03|Actas Junta Directiva|1299|00-0200-002-03 |Conservacion Total Memory
18109|1997 AUXILIAR DEL MAYOR - INDICADORES DE ESTABLECIMIENTO DE CREDITO C.A.V. (18109)|CD00826 |00-3100|DEPARTAMENTO DE LIQUIDACIONES|00-3100-019|INFORMES|00-3100-019-04|INFORMES DE ENTIDADES EN LIQUIDACION|3005|00-3100-019-04 |-
18114|1991 ANEXOS DE ACTAS JUNTA DIRECTIVA FOGAFIN -18822 |CD00001 |00-0200|SECRETARIA GENERAL|00-0200-002|ACTAS|00-0200-002-03|Actas Junta Directiva|727|00-0200-002-03 |Conservacion Total Memory
18115|1991 ANEXOS DE ACTAS JUNTA DIRECTIVA FOGAFIN -18821 |CD00001 |00-0200|SECRETARIA GENERAL|00-0200-002|ACTAS|00-0200-002-03|Actas Junta Directiva|726|00-0200-002-03 |Conservacion Total Memory
#### Consulta:
```sql
select e.attr1043 as NumExpediente, e.attr1052 as NombreExpediente, e.attr1266 as Caja, m.memo as Descripcion, sb.attr1047, e.attr1196
from hsi.rmObjectInstance1010 e
left outer join hsi.rmmemo m on m.memoid = e.mk1058
left outer join hsi.rmObjectInstance1013 sb on sb.objectID = e.fk1051
where e.activeStatus = 0 and e.attr1266 is not Null and e.attr1266 not like '%Fisico en Fo%' and e.attr1266 not like '-' --and sb.attr1047 like '00-%'
```

### Cantidad de radicados en la cola de los usuarios
Muestra la cantidad total de comunicaciones que tienen los usuarios en la bandeja de entrada:
#### Ejemplo de la consulta:
keyvaluechar|total
DRIVERA |585
ADIAZ |517
HQUIMBAYO |394
#### Consulta:
```sql
select keyvaluechar, count (keyvaluechar) as total
from itemlc w
left outer join keyxitem184 k on w.itemnum = k.itemnum
left outer join keytable184 a on k.keywordnum = a.keywordnum
where w.statenum =105
group by keyvaluechar
order by  total desc
```

### Cálculo de fecha de eliminación de expedientes según suma de gestión y subseries
Reporte que calcula la fecha de eliminación de los expedientes, considerando la suma de los tiempos de gestión en el archivo de gestión y el archivo central, así como las subseries de eliminación correspondientes.
El cálculo se realiza sumando los años definidos en cada etapa (gestión + central + eliminación) y aplicando esta suma a la fecha final (FF) del expediente, obteniendo así la fecha estimada de eliminación.

#### Ejemplo de la consulta:
codigo|sumGestion|objectInstanceID|fechafinal|fechainicial|fechaEliminacion|NumExpediente|NombreExpediente|Localizacion|Tomo|FechaInicialTomo|FechaFinalTomo|Deposito|Bloque|Cuerpo|Bandeja|Observaciones|FolioInicial|FolioFinal|Caja|Paquete|Rollo|Posicion|objidTomo|fk1131|activestatusTomo
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
01-2100-095-05 |10|3141|2009-12-31 00:00:00.000|2007-01-01 00:00:00.000|2019|4058 |RAMIREZ GIRALDO MANUEL 2007 |NULL|2 |2005-05-23 00:00:00.000|2008-06-20 00:00:00.000|D4|B1|C5|B4|NULL|213|384|NULL|NULL|NULL|NULL|684031|35328|0
01-2100-095-05 |10|3141|2009-12-31 00:00:00.000|2007-01-01 00:00:00.000|2019|4058 |RAMIREZ GIRALDO MANUEL 2007 |NULL|4 |2010-07-26 00:00:00.000|2018-01-30 00:00:00.000|D4|B1|C5|B4|NULL|555|835|NULL|NULL|NULL|NULL|684033|35328|0
01-2100-095-05 |10|3141|2009-12-31 00:00:00.000|2009-01-01 00:00:00.000|2019|4007 |RINCON PARRA PRIMITIVO 2009 |NULL|3 |2006-10-12 00:00:00.000|2006-12-12 00:00:00.000|D4|B1|C5|B5|NULL|334|498|NULL|NULL|NULL|NULL|684096|35227|0
01-2100-095-05 |10|3141|2009-12-31 00:00:00.000|2009-01-01 00:00:00.000|2019|4007 |RINCON PARRA PRIMITIVO 2009 |NULL|4 |2008-06-23 00:00:00.000|2011-03-16 00:00:00.000|D4|B1|C5|B5|NULL|499|689|NULL|NULL|NULL|NULL|684097|35227|0
#### Consulta con tomos completos:
```sql
select ss.*, attr1054 as  fechafinal, attr1053 as fechainicial, (year(attr1054) + ss.sumGestion) as fechaEliminacion, attr1043 as NumExpediente, attr1052 as NombreExpediente, attr1196 Localizacion, tomo.*
from rmobjectinstance1010 expe
right outer join (select attr1047 as codigo, (attr1088 + attr1089) as sumGestion, objectInstanceID from rmObjectInstance1013
where attr1106 like 'Eliminación') as ss on expe.fk1051 = ss.objectInstanceID
left outer join (select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
where t.activestatus = 0) as tomo on tomo.fk1131 = expe.objectid
where year(attr1053) >= 1997
 
```
#### Consulta sin tomos:
```sql
select ss.*, attr1054 as  fechafinal, attr1053 as fechainicial, (year(attr1054) + ss.sumGestion) as fechaEliminacion, attr1043 as NumExpediente, attr1052 as NombreExpediente, attr1196 Localizacion
from rmobjectinstance1010 expe
right outer join (select attr1047 as codigo, (attr1088 + attr1089) as sumGestion, objectInstanceID from rmObjectInstance1013
where attr1106 like 'Eliminación') as ss on expe.fk1051 = ss.objectInstanceID
where year(attr1053) >= 1997 and expe.activeStatus = 0 and (year(attr1054) + ss.sumGestion) < 2028
order by fechaEliminacion desc
```

#### Consulta con tomos versión 00:
```sql
select ss.*, attr1054 as  fechafinal, attr1053 as fechainicial, attr1043 as NumExpediente, attr1052 as NombreExpediente, attr1196 Localizacion, tomo.*
from rmobjectinstance1010 expe
right outer join (select attr1047 as codigo, (attr1088 + attr1089) as sumGestion, objectInstanceID from rmObjectInstance1013
where attr1047 like '00-0000-002-01' or attr1047 like '00-0000-002-06' or attr1047 like '00-0000-004-00' or attr1047 like '00-0000-031-00' or attr1047 like '00-0011-034-00' or attr1047 like '00-0101-028-07' or attr1047 like '00-0101-052-00' or attr1047 like '00-0101-055-00' or attr1047 like '00-0110-012-06' or attr1047 like '00-0110-012-08' or attr1047 like '00-0110-026-07' or attr1047 like '00-0120-028-01' or attr1047 like '00-0120-028-02' or attr1047 like '00-0120-028-04' or attr1047 like '00-0120-028-11' or attr1047 like '00-0120-043-00' or attr1047 like '00-0120-050-00' or attr1047 like '00-0120-061-00' or attr1047 like '00-0120-062-00' or attr1047 like '00-0120-063-00' or attr1047 like '00-0121-028-06' or attr1047 like '00-0121-028-09' or attr1047 like '00-0121-028-10' or attr1047 like '00-0121-028-12' or attr1047 like '00-0121-028-13' or attr1047 like '00-0121-028-14' or attr1047 like '00-0121-028-15' or attr1047 like '00-0121-028-16' or attr1047 like '00-0121-028-17' or attr1047 like '00-0121-028-18' or attr1047 like '00-0121-030-03' or attr1047 like '00-0122-028-03' or attr1047 like '00-0122-030-02' or attr1047 like '00-0122-039-03' or attr1047 like '00-0122-041-00' or attr1047 like '00-0122-054-00' or attr1047 like '00-0200-026-11' or attr1047 like '00-0200-026-13' or attr1047 like '00-0201-062-00' or attr1047 like '00-0202-003-02' or attr1047 like '00-0202-028-08' or attr1047 like '00-0202-053-00' or attr1047 like '00-0210-010-00' or attr1047 like '00-0210-017-01' or attr1047 like '00-0210-017-02' or attr1047 like '00-0210-017-03' or attr1047 like '00-0210-017-04' or attr1047 like '00-0210-017-05' or attr1047 like '00-0210-017-06' or attr1047 like '00-0210-036-00' or attr1047 like '00-0302-020-00' or attr1047 like '00-0302-033-01' or attr1047 like '00-0302-033-02' or attr1047 like '00-0302-040-00' or attr1047 like '00-0310-009-00' or attr1047 like '00-0310-019-00' or attr1047 like '00-0310-051-00' or attr1047 like '00-0500-042-05' or attr1047 like '00-0000-002-01' or attr1047 like '00-0000-002-06' or attr1047 like '00-0000-004-00' or attr1047 like '00-0000-026-06' or attr1047 like '00-0000-031-00' or attr1047 like '00-0301-014-02' or attr1047 like '00-0301-019-00' or attr1047 like '00-0301-026-06' or attr1047 like '00-0301-026-12' or attr1047 like '00-0301-038-01' or attr1047 like '00-0301-051-00' or attr1047 like '00-0301-065-00' or attr1047 like '00-0302-019-00' or attr1047 like '00-0302-020-00' or attr1047 like '00-0302-026-06' or attr1047 like '00-0302-026-12' or attr1047 like '00-0302-033-01' or attr1047 like '00-0302-033-02' or attr1047 like '00-0302-040-00' or attr1047 like '00-1000-045-01' or attr1047 like '00-1100-003-33' or attr1047 like '00-1100-003-35' or attr1047 like '00-1100-003-37' or attr1047 like '00-1100-045-01' or attr1047 like '00-1100-045-23' or attr1047 like '00-1100-045-25' or attr1047 like '00-2100-019-01' or attr1047 like '00-2100-019-03' or attr1047 like '00-2100-035-35' or attr1047 like '00-2100-045-01' or attr1047 like '00-2100-045-05' or attr1047 like '00-2100-099-99' or attr1047 like '00-2200-007-00' or attr1047 like '00-2200-033-00' or attr1047 like '00-2200-043-07' or attr1047 like '00-2200-097-01' or attr1047 like '00-2200-097-03' or attr1047 like '00-2200-097-05' or attr1047 like '00-2200-109-00' or attr1047 like '00-2300-023-01' or attr1047 like '00-2300-049-03' or attr1047 like '00-2300-049-09' or attr1047 like '00-2300-049-13' or attr1047 like '00-2300-049-15' or attr1047 like '00-2300-049-17' or attr1047 like '00-2300-049-19' or attr1047 like '00-2300-049-21' or attr1047 like '00-2300-049-23' or attr1047 like '00-2300-049-25' or attr1047 like '00-2300-053-05' or attr1047 like '00-2300-053-07' or attr1047 like '00-2300-113-00' or attr1047 like '00-3100-013-00' or attr1047 like '00-3100-049-01' or attr1047 like '00-3100-049-05' or attr1047 like '00-3100-049-11' or attr1047 like '00-3100-053-03' or attr1047 like '00-3100-083-00' or attr1047 like '00-3100-085-05' or attr1047 like '00-3100-087-00' or attr1047 like '00-3100-103-00' or attr1047 like '00-3100-115-00' or attr1047 like '00-3200-009-00' or attr1047 like '00-3200-059-00' or attr1047 like '00-3200-067-01' or attr1047 like '00-3200-067-03' or attr1047 like '00-3300-005-01' or attr1047 like '00-3300-015-00' or attr1047 like '00-3300-021-01' or attr1047 like '00-3300-031-01' or attr1047 like '00-3300-031-03' or attr1047 like '00-3300-031-05' or attr1047 like '00-3300-031-07' or attr1047 like '00-3300-031-09' or attr1047 like '00-3300-031-11' or attr1047 like '00-3300-031-13' or attr1047 like '00-3300-031-15' or attr1047 like '00-3300-037-00' or attr1047 like '00-3300-035-00' or attr1047 like '00-3300-045-01' or attr1047 like '00-3300-063-01' or attr1047 like '00-3300-063-03' or attr1047 like '00-3300-073-00' or attr1047 like '00-3400-005-03' or attr1047 like '00-3400-045-01' or attr1047 like '00-3400-045-23' or attr1047 like '00-3400-049-07' or attr1047 like '00-3400-065-00' or attr1047 like '00-3400-081-00' or attr1047 like '00-3400-089-01' or attr1047 like '00-3400-089-03' or attr1047 like '00-3500-005-05' or attr1047 like '00-3500-111-03' or attr1047 like '00-4100-045-07' or attr1047 like '00-4100-045-09' or attr1047 like '00-4110-041-00' or attr1047 like '00-4110-045-13' or attr1047 like '00-4110-45 -23' or attr1047 like '00-4300-045-19' or attr1047 like '00-4200-045-15' or attr1047 like '00-4200-045-17' or attr1047 like '00-5200-043-01' or attr1047 like '00-5200-043-03' or attr1047 like '00-1000-045-01' or attr1047 like '00-1100-003-33' or attr1047 like '00-1100-003-35' or attr1047 like '00-1100-003-37' or attr1047 like '00-1100-045-01' or attr1047 like '00-1100-045-23' or attr1047 like '00-1100-045-25' or attr1047 like '00-2100-019-01' or attr1047 like '00-2100-019-03' or attr1047 like '00-2100-045-01' or attr1047 like '00-2100-045-05' or attr1047 like '00-2100-099-99' or attr1047 like '00-2200-007-00' or attr1047 like '00-2200-033-00' or attr1047 like '00-2200-043-07' or attr1047 like '00-2200-045-07' or attr1047 like '00-2200-049-01' or attr1047 like '00-2200-097-01' or attr1047 like '00-2200-097-03' or attr1047 like '00-2200-097-05' or attr1047 like '00-2200-109-00' or attr1047 like '00-2300-023-01' or attr1047 like '00-2300-049-03' or attr1047 like '00-2300-049-09' or attr1047 like '00-2300-049-13' or attr1047 like '00-2300-049-15' or attr1047 like '00-2300-049-17' or attr1047 like '00-2300-049-19' or attr1047 like '00-2300-049-21' or attr1047 like '00-2300-049-23' or attr1047 like '00-2300-049-25' or attr1047 like '00-2300-053-05' or attr1047 like '00-2300-053-07' or attr1047 like '00-2300-113-00' or attr1047 like '00-3300-005-01' or attr1047 like '00-3300-015-00' or attr1047 like '00-3300-021-01' or attr1047 like '00-3300-021-02' or attr1047 like '00-3300-021-03' or attr1047 like '00-3300-021-04' or attr1047 like '00-3300-021-05' or attr1047 like '00-3300-021-06' or attr1047 like '00-3300-021-07' or attr1047 like '00-3300-031-01' or attr1047 like '00-3300-031-03' or attr1047 like '00-3300-031-05' or attr1047 like '00-3300-031-07' or attr1047 like '00-3300-031-09' or attr1047 like '00-3300-031-11' or attr1047 like '00-3300-031-13' or attr1047 like '00-3300-031-15' or attr1047 like '00-3300-039-00' or attr1047 like '00-3300-045-01' or attr1047 like '00-3300-049-01' or attr1047 like '00-3300-049-02' or attr1047 like '00-3300-049-03' or attr1047 like '00-3300-073-00' or attr1047 like '00-3200-049-31' or attr1047 like '00-3200-049-43' or attr1047 like '00-3100-003-19' or attr1047 like '00-3100-003-21' or attr1047 like '00-3100-013-00' or attr1047 like '00-3100-049-01' or attr1047 like '00-3100-049-05' or attr1047 like '00-3100-049-11' or attr1047 like '00-3100-053-03' or attr1047 like '00-3100-083-00' or attr1047 like '00-3100-085-05' or attr1047 like '00-3100-087-00' or attr1047 like '00-3100-103-00' or attr1047 like '00-3100-115-00' or attr1047 like '00-3100-119-00' or attr1047 like '00-3500-005-05' or attr1047 like '00-3500-111-03' or attr1047 like '00-3500-111-09' or attr1047 like '00-3400-005-03' or attr1047 like '00-3400-037-00' or attr1047 like '00-3400-045-01' or attr1047 like '00-3400-045-23' or attr1047 like '00-3400-045-13' or attr1047 like '00-3400-041-00' or attr1047 like '00-3400-049-07' or attr1047 like '00-3400-063-01' or attr1047 like '00-3400-063-03' or attr1047 like '00-3400-065-00' or attr1047 like '00-3400-081-00' or attr1047 like '00-3400-089-01' or attr1047 like '00-3400-089-03' or attr1047 like '00-4200-045-15' or attr1047 like '00-4200-045-17' or attr1047 like '00-4100-045-07' or attr1047 like '00-4100-045-09' or attr1047 like '00-4300-045-19' or attr1047 like '00-5600-043-01' or attr1047 like '00-5600-043-03' or attr1047 like '00-5600-035-00' or attr1047 like '00-5800-045-01' or attr1047 like '00-2200-007-00' or attr1047 like '00-2200-033-00' or attr1047 like '00-2200-043-07' or attr1047 like '00-2200-045-01' or attr1047 like '00-2200-097-05' or attr1047 like '00-2200-109-00'
) as ss on expe.fk1051 = ss.objectInstanceID
left outer join (select t.attr1123 as Tomo,
	t.attr1124 as FechaInicialTomo,
	t.attr1125 as FechaFinalTomo,
	t.attr1126 as Deposito,
	t.attr1127 as Bloque,
	t.attr1128 as Cuerpo,
	t.attr1129 as Bandeja,
	m.memo as Observaciones,
	t.attr1133 as FolioInicial,
	t.attr1144 as FolioFinal,
	t.attr1197 as Caja,
	t.attr1198 as Paquete,
	t.attr1199 as Rollo,
	t.attr1200 as Posicion,
	t.objectid as objidTomo,
	t.fk1131,
	t.activestatus as activestatusTomo
from hsi.rmobjectinstance1023 t left outer join hsi.rmmemo m on m.memoid = t.mk1130
where t.activestatus = 0) as tomo on tomo.fk1131 = expe.objectid
where year(attr1053) >= 1997
```

### Documentos vitales
Se obtiene información de los documentos vitales con su respectivo path para su descarga, codificación, nombre, expediente y fecha de almacenamiento.
Es importante aclarar que en esta consulta NO se tienen en cuenta los SADE y viene con los números de expediente que me brindaron en su momento
#### Ejemplo de la consulta:
itemnum|itemname|datestored|itemdate|CodExpediente|fullpath|itemnum|kg167|kg166|kg168|kg102|kg171|kg103|kg374|kg193|kg169|kg141|kg435|filesize
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
850806|<b></b><g></g><r></r> [02-2000-003-39] - <A>17540</A> Acta de Junta Directiva - 2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 23 JUNIO 2015- 453 - 201506 - ACTA DE JUNTA DIRECTIVA SESION JUNIO 23 DE 2015 |2017-09-15 17:35:27.753|2015-06-23 00:00:00.000|17540|\\VM-ONBASE2-PRD\OnBase$\SGR2000\V1\0\292226.pdf|850806|02-2000 |SUBDIRECCION CORPORATIVA|02-2000-003|ACTAS |02-2000-003-39 |ACTAS DE JUNTA DIRECTIVA|02-2000-003-39-59 |ACTA|17540|2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 23 JUNIO 2015|02 |2344820
850808|<b></b><g></g><r></r> [02-2000-003-39] - <A>17539</A> Acta de Junta Directiva - 2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 20 MAYO 2015- 452 - 201505 - ACTA DE JUNTA DIRECTIVA SESION MAYO 20 DE 2015 |2017-09-15 17:39:07.923|2015-05-20 00:00:00.000|17539|\\VM-ONBASE2-PRD\OnBase$\SGR2000\V1\0\292229.pdf|850808|02-2000 |SUBDIRECCION CORPORATIVA|02-2000-003|ACTAS |02-2000-003-39 |ACTAS DE JUNTA DIRECTIVA|02-2000-003-39-59 |ACTA|17539|2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 20 MAYO 2015 |02 |3081702
850809|<b></b><g></g><r></r> [02-2000-003-39] - <A>17538</A> Acta de Junta Directiva - 2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 22 ABRIL 2015- 451 - 201504 - ACTA DE JUNTA DIRECTIVA SESION ABRIL 22 DE 2015 |2017-09-15 17:41:02.057|2015-04-22 00:00:00.000|17538|\\VM-ONBASE2-PRD\OnBase$\SGR2000\V1\0\292230.pdf|850809|02-2000 |SUBDIRECCION CORPORATIVA|02-2000-003|ACTAS |02-2000-003-39 |ACTAS DE JUNTA DIRECTIVA|02-2000-003-39-59 |ACTA|17538|2015 ACTAS DE JUNTA DIRECTIVA FOGAFÍN SESIÓN 22 ABRIL 2015|02 |2292084
#### Consulta:
```sql
select distinct i.itemnum, i.itemname, i.datestored, i.itemdate, ltrim(rtrim(c.kg169)) as CodExpediente, ltrim(rtrim(pp.lastuseddrive))+ltrim(rtrim(p.filepath)) fullpath, c.*, p.filesize
from hsi.itemdata i 
right outer join hsi.keygroupdata219 c on c.itemnum = i.itemnum
left outer join itemdatapage p on p.itemnum = i.itemnum
left outer join hsi.physicalplatter pp on pp.diskgroupnum = p.diskgroupnum and pp.logicalplatternum = p.logicalplatternum
where (c.kg169 IN ('17531','17533','17535','17536','17537','17538','17539','17540','17541','17542','17543','17544','17545','17546','59322','60607','60609','60610','60611','60612','60613','60615','60616','60617','60618','61855','61856','61857','61858','61859','61860','61861','61862','61865','61866','64487','100069','16734','16757','16758','16759','16760','16762','16766','16768','16769','16776','16779','16780','16781','16783','16784','16785','16798','16800','16801','16802','16804','16823','16824','16827','16828','16831','16833','16834','16835','16836','16838','16841','16844','16845','16850','16852','16854','16855','16856','16858','17447','63781','65403','68216','48744','66132','66342','67773','68645','18007','48974','65390','65979','66418','67775','17210','17211','17520','17521','17522','17523','17524','17525','17526','17527','17528','17529','17767','17862','17885','17886','17887','17912','17940','17966','17979','18055','48721','48723','48724','48725','48726','48727','48728','48729','48730','48731','48732','48733','63655','63682','63718','63762','63793','63970','64348','64956','65257','65348','65375','65456','65513','65540','65572','65593','65619','65727','66060','66061','66062','66063','66064','66065','66066','66067','66068','66069','66070','66241','66242','66243','66244','66245','66246','66247','66248','66249','66250','66251','66252','67829','67843','67971','67981','67997','68000','68020','68021','68022','68023','68024','68025','68488','68582','68647','68648','70461','70496','70540','17883','48976','65267','65980','67933','68653','48932','65265','66431','67607','67817','17711','48852','63875','65661','66255','67785','68469','17764','17855','65418','66200','66767','49006','49100','49109','62838','63618','63712','63763','63828','63850','64977','65256','65278','65279','65383','65384','65391','65396','65402','65535','65537','65538','65554','65574','65579','65591','65592','65644','65692','65763','65807','65851','65983','66022','66044','66133','66134','66164','66165','66168','66179','66199','66215','66341','66361','66380','66408','66409','66410','66422','66424','66425','66485','66851','67358','67421','67423','67424','67443','67464','67470','67477','67498','67651','67653','67654','67703','68032','68083','68084','68085','68088','68122','68137','68148','68163','68299','68312','68313','68322','68325','68328','68335','68336','68337','68342','68345','68354','68362','68368','68369','68370','68377','68520','68537','68596','68597','68598','68622','68651','68666','70456','99741','100041','17352','17419','17461','17569','17570','17841','17842','17844','17845','17864','17930','63635','63861','65404','65515','65527','65576','66076','66085','66119','66914','67456','67692','67694','67724','67799','68017','68147','68255','68320','68330','68332','68343','68661','70494','70545','70562','17919','17960','48924','48925','63882','63960','65662','66356','67450','67518','68464','70497','70498','48921','48770','67624','68449','68079','48977','48978','67072','67803','68568','48853','66980','67776','67807','66981','67868','68259','49126','66403','17722','17807','48954','48955','48956','48957','48958','63640','63928','63929','63930','65746','65747','65748','65749','65788','65789','65809','66073','66077','66123','66148','66202','66211','66218','66220','66330','66331','67061','67479','67511','67512','67513','67696','67976','68413','68446','68447','68448','70541','48959','65705','65813','65814','66931','67778','68142','68549','68306','47632','48791','48792','48793','48794','48795','48796','48797','48798','48799','48800','48801','48802','48803','48804','48805','48806','48807','48808','48809','66221','66222','66223','66224','66233','66234','66235','66237','66238','66256','66257','66317','66318','66319','66325','66326','66327','66328','66333','66430','66827','67582','67605','67647','67648','67657','67658','67668','67669','67675','67676','67677','67678','67681','67682','67695','67701','67702','67714','67719','67951','68429','68430','68431','68432','68443','68465','68466','68525','68526','68529','68591','68592','68655','48789','48790','66230','66231','66232','66777','67791','67845','68544','67995','48962','66188','66340','67637','68548','59313','65551','65552','65967','66355','67811','68569','48838','48839','48840','48841','48842','48843','48844','48845','48846','48847','48848','48849','65907','65908','65909','65910','65911','65912','65913','65914','65915','65916','65917','65918','66552','66553','66554','66555','66556','66557','66558','66559','66560','66561','66562','66563','67737','67738','67739','67740','67741','67742','67743','67744','67745','67746','67747','67748','68560','68609','68630','70548','70549','70550','48869','48870','48871','48872','48873','48875','48876','48877','48878','48879','48881','48882','65919','65920','65921','65922','65923','65924','65925','65926','65927','65928','65929','65930','66486','66487','66488','66489','66490','66491','66492','66493','66494','66495','66496','66497','67725','67726','67727','67728','67729','67730','67731','67732','67733','67734','67735','67736','68566','70491','70577','70579','66648','66649','66650','66651','66652','66653','66654','66655','66656','66657','66658','66659','66660','66661','66662','66663','66664','66665','66666','66667','66668','66669','66670','66671','67749','67750','67751','67752','67753','67754','67755','67756','67757','67759','67760','17754','17763','17773','17774','17798','17800','17801','17802','17811','17838','17839','17857','17866','17890','17962','48941','48942','48943','48944','48945','48946','48947','48948','48949','48950','48951','48952','48953','49115','63705','63856','63950','63975','63977','63994','64172','64204','64205','64562','64950','64953','64955','65356','65761','65762','65765','65766','65798','65802','65803','65819','65822','65849','65943','65985','65986','66024','66090','66228','66229','66288','66289','66332','66339','66343','66388','66392','66395','66404','66405','66411','66419','67496','67666','67679','67780','67782','67783','67826','67846','67856','67881','67882','67883','67908','68004','68420','68442','68531','68532','68533','68534','68535','68539','68583','68605','68606','68607','68612','17038','70615','70661','70629','70654'))
and i.status=0  and i.datestored<'20250101' and p.docrevnum = i.maxdocrev and pp.physicalplatternum <> 2 and i.itemtypenum not in (2255, 102, 103, 104, 127) and i.itemtypegroupnum not in (1, 294, 102)
```
_**Se excluyen los índices (294), reportes y dummy(1) y SADE (102)**_
_**Los expedientes son los que me entregaron en su momento, se pueden agregar o quitar**_


## Informes para flujos
### Contratos/ordenes - Reporte obtener todos los documentos asociados a una orden
Este reporte permite consultar toda la información relacionada con una necesidad, partiendo del número de la orden asociada. A través del vínculo entre orden y necesidad, se extraen todos los datos registrados en el sistema sobre la necesidad correspondiente, facilitando:

- La trazabilidad entre orden y necesidad.
- La revisión completa de los atributos y documentos vinculados.
- El análisis de solicitudes y procesos asociados a cada orden.
#### Ejemplo de la consulta:
itemnum|datestored|itemname|itemtypename
-|-|-|-
3508070|2024-12-10 12:36:25.950|Formulario evaluacion final - 12/10/2024 |Formulario evaluacion final 
3057009|2024-05-24 14:03:20.793|<r>Remitente:-Fecha Comunicación:<D1></r><b> Radicador:PFUENTES Radicado No: 2024-E-003872</b> |Correo Electrónico de entrada 
3057010|2024-05-24 14:03:21.367|Formulario de Correspondencia de Entrada <R>VENCIDO</R> <b>2024-E-003872</b><g></g><r></r> - <A>TRAMITADO</A> - 24/5/2024 14:14:11 - De: GUILLERMO VALENZUELA|Formulario de Correspondencia de Entrada
#### Consulta:
```sql

-- basandose en el numero de la orden, tomar el de la necesidad y traer todo lo de la necesidad
DECLARE @necesidad NVARCHAR(255);

SELECT TOP 1 @necesidad = hsi.keyitem242.keyvaluechar
FROM hsi.itemdata
LEFT OUTER JOIN hsi.keyitem243 ON hsi.keyitem243.itemnum = hsi.itemdata.itemnum
LEFT OUTER JOIN hsi.keyitem242 ON hsi.keyitem242.itemnum = hsi.itemdata.itemnum
WHERE hsi.keyitem243.keyvaluechar LIKE '1059'; --CAMBIAR POR EL NÚMERO DE ORDEN QUE SE DESEE

	-- Ahora @necesidad contiene el valor de la consulta
PRINT @necesidad;

select hsi.itemdata.itemnum, hsi.itemdata.datestored, hsi.itemdata.itemname, hsi.doctype.itemtypename from hsi.itemdata
left outer join hsi.keyitem243 on hsi.keyitem243.itemnum = hsi.itemdata.itemnum
left outer join hsi.keyitem242 on hsi.keyitem242.itemnum = hsi.itemdata.itemnum
left outer join hsi.doctype on hsi.itemdata.itemtypenum = hsi.doctype.itemtypenum
where hsi.keyitem242.keyvaluechar like @necesidad
```
_**Es necesario cambiar el número de orden por el que deseen**_ `WHERE hsi.keyitem243.keyvaluechar LIKE '1059'; --CAMBIAR POR EL NÚMERO DE ORDEN QUE SE DESEE`

### Contratos/ordenes - Reporte obtener estado de las necesidades, cola y paso siguiente
Este reporte muestra el estado de la necesidad, la cola donde se encuentra y expone para quién está asignado o, en su defecto, qué se encuentra esperando para continuar el flujo.
#### Ejemplo de la consulta:
Identificador|Etapa|Cola|No. Necesidad|Tipo necesidad|Tipo de contrato|No. Contrato|No. Orden|Objeto|Razón social proponente seleccionado|Jefe interesado|Fecha ingreso|Asignado
-|-|-|-|-|-|-|-|-|-|-|-|-
2269154|Ordenes/Contratos - 6. Postcontrato |Postcontrato|2438|CONTRATO|CONTRATOS DE PRESTACIÓN DE SERVICIOS|C-005-2023 |NULL|PRESTAR LOS SERVICIOS DE SOPORTE TÉCNICO, MANTENIMIENTO Y ACTUALIZACIÓN DE ONBASE.|GIGA COLOMBIA SAS |WILLIAM ALBERTO ERIRA TRUJILLO|2023-06-28 12:03:46.493|WERIRA
2347867|Ordenes/Contratos - 6. Postcontrato |Postcontrato|2443|ORDEN |NULL|NULL|1015|PROVEER EL SERVICIO DE ARRENDAMIENTO PARA LA UTILIZACIÓN DEL SOFTWARE ISOLUCIÓN CON USUARIOS ILIMITADOS, SOPORTE, MANTENIMIENTO CORRECTIVO, ACTUALIZACIONES DE VERSIÓN Y SEIS (6) HORAS DE CAPACITACIÓN SOBRE EL FUNCIONAMIENTO DE LA HERRAMIENTA.|ISOLUCIÓN SISTEMAS INTEGRADOS DE GESTIÓN S.A|ANDREA RUIZ RODRIGUEZ |2023-08-11 18:09:09.110|ARUIZ 
2347867|Ordenes/Contratos - 6. Postcontrato |Postcontrato|2443|ORDEN |NULL|NULL|1015|PROVEER EL SERVICIO DE ARRENDAMIENTO PARA LA UTILIZACIÓN DEL SOFTWARE ISOLUCIÓN CON USUARIOS ILIMITADOS, SOPORTE, MANTENIMIENTO CORRECTIVO, ACTUALIZACIONES DE VERSIÓN Y SEIS (6) HORAS DE CAPACITACIÓN SOBRE EL FUNCIONAMIENTO DE LA HERRAMIENTA.|ISOLUCIÓN SISTEMAS INTEGRADOS DE GESTIÓN S.A|ANDREA RUIZ RODRIGUEZ |2023-08-11 18:09:09.110|CRODRIGUEZ
#### Consulta:
```sql
--Reporte asignacion flujo contratos:
DECLARE @asignado NVARCHAR(50)

SELECT distinct
    lc.contentnum [Identificador], 
    ciclo.lifecyclename [Etapa], 
    cola.statename [Cola], 
    nn.keyvaluechar AS [No. Necesidad], 
    kt.keyvaluechar AS [Tipo necesidad], 
    ktc.keyvaluechar AS [Tipo de contrato],
	kCon.keyvaluechar as [No. Contrato],
	kOrd.keyvaluechar as [No. Orden],
	o.keyvaluechar as [Objeto],
	kRS.keyvaluechar as [Razón social proponente seleccionado],
    ji.keyvaluechar AS [Jefe interesado],
	lc.transdate as [Fecha ingreso],
	
	
    CASE 
        --Necesidad
		WHEN lc.statenum in (258, 282, 253, 243, 265, 281, 245, 270, 266, 260, 239, 248, 264, 241,261, 256, 244, 269, 277) THEN usernameActual.keyvaluechar 
        WHEN lc.statenum = 276 THEN 'Jurídico' 
		WHEN lc.statenum in (238, 263) THEN 'Revisión comité' 
		WHEN lc.statenum in (251, 279) THEN aprobador.keyvaluechar 
		
		--Invitacion
		WHEN lc.statenum in (267, 259) and ktg.keyvaluechar = 'GC_SG_DDA' then 'SG-A'
		WHEN lc.statenum in (267, 259) and ktg.keyvaluechar = 'GC_SG_ROP' then 'SG-SI'
		WHEN lc.statenum in (267, 259) and ktg.keyvaluechar = 'GC_SG_TalentoHumano' then 'SG-SST'
		WHEN lc.statenum in (267, 259) then ktg.keyvaluechar


		WHEN lc.statenum = 237 THEN 'Esperando que se radique la propuesta'

		--contrato
		WHEN lc.statenum = 286 THEN 'Elaboración contrato por parte de jurídico'
		WHEN lc.statenum = 246 THEN 'Esperando el email de remisión proyecto de contrato'
		WHEN lc.statenum = 232 THEN 'Ajustes borrador contrato por parte de jurídico'
		WHEN lc.statenum = 255 THEN 'Ajustes borrador orden por parte de DDA'
		WHEN lc.statenum = 240 THEN 'Elaboración orden por parte de DDA'
		WHEN lc.statenum = 316 THEN 'Revisión del borrador de la orden por parte de jurídico'
		WHEN lc.statenum = 275 THEN 'Contrato rechazado'
		WHEN lc.statenum = 272 THEN 'Pendiente aprobación pólizas jurídico'
		WHEN lc.statenum = 285 THEN 'Pendiente ajustes pólizas contratista'
		WHEN lc.statenum = 273 THEN 'Creación del otrosí por parte del DDA'
		WHEN lc.statenum = 287 THEN 'Creación del otrosí por parte del DJU'
		WHEN lc.statenum = 278 THEN 'Ajustar otrosí orden por parte del DDA'
		WHEN lc.statenum = 234 THEN 'Ajustar otrosí contrato por parte del DJU'
		WHEN lc.statenum = 257 THEN 'Pendiente firmas por parte del DDA'
		WHEN lc.statenum = 268 THEN 'Pendiente firmas por parte del DJU'

		--Otrosí

		WHEN lc.statenum = 335 THEN 'Pendiente aprobación pólizas jurídico'
		WHEN lc.statenum = 336 THEN 'En espera del otrosí y de la póliza (si es necesaria)'
		WHEN lc.statenum = 334 THEN 'En espera aprobación minuta otrosí jurídico'

        ELSE NULL 
    END AS [Asignado]
FROM 
    hsi.workitemlc lc
LEFT OUTER JOIN 
    hsi.keyitem242 nn ON nn.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyitem232 o ON o.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyxitem522 n ON n.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyxitem524 tc ON tc.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyitem654 ji ON ji.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyitem208 aprobador ON aprobador.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keyxitem543 gestion ON gestion.itemnum = lc.contentnum


LEFT OUTER JOIN 
    hsi.keyitem450 usernameActual ON usernameActual.itemnum = lc.contentnum
LEFT OUTER JOIN 
    hsi.keytable522 kt ON kt.keywordnum = n.keywordnum
LEFT OUTER JOIN 
    hsi.keytable524 ktc ON ktc.keywordnum = tc.keywordnum
LEFT OUTER JOIN 
    hsi.keytable543 ktg ON ktg.keywordnum = gestion.keywordnum
LEFT OUTER JOIN 
    hsi.lcstate cola ON cola.statenum = lc.statenum
LEFT OUTER JOIN 
    hsi.lifecycle ciclo ON ciclo.lcnum = lc.lcnum


--numero de contrato y orden
left outer join 
	hsi.keyitem231 kCon on kCon.itemnum = lc.contentnum

left outer join 
	hsi.keyitem243 kOrd on kOrd.itemnum = lc.contentnum

-- Razón social
left outer join
	hsi.keyitem544 kRS on kRS.itemnum = lc.contentnum

WHERE 
    lc.lcnum IN (130, 133, 131, 134, 132, 135, 137) 
    AND lc.statenum IN (
	--Necesidad
	258, 276, 238, 251,
	--invitacion
	267, 282, 253, 237,
	--Propuesta
	243,
	--evaluacion
	259, 265, 281,
	--Contrato/orden
	245, 286, 270, 266, 246, 232, 260, 255, 240, 316, 263, 275, 279, 239, 272, 285, 248, 264,
	--Postcontrato
	241,
	--Otrosí
	261, 256, 273, 287, 244, 278, 234, 257, 268, 269, 277, 336, 335,334
	)
```

### Contratos/ordenes - Reporte obtener keyword "Volvería a contratar"
Obtiene esta keyword de la evaluación final.
#### Ejemplo de la consulta:
itemnum|itemname|Fecha del documento|Voler a contratar|Nombre Supervisor|Número de contrato|NoNecesidad|No. Orden|Objeto|Razón Social
-|-|-|-|-|-|-|-|-|-
2803862|Formulario evaluacion final - 1/12/2024|2024-01-12 08:50:09.513|SI|ANDREA RUIZ RODRIGUEZ |NULL|2427|1008|REALIZAR AUDITORÍA DE SEGUIMIENTO 1 DE LOS SISTEMAS DE GESTIÓN DE CALIDAD Y AMBIENTAL Y, DE SEGUIMIENTO 2 AL SISTEMA DE GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN, BAJO LAS NORMAS ISO 9001:2015,ISO 14001:2015 E ISO 27001:2013, RESPECTIVAMENTE, EN MODAL|CERTIFICATION QUALITY RESOURCES SAS 
3125206|Formulario evaluacion final - 6/13/2024|2024-06-13 08:48:13.243|NULL|ANDREA RUIZ RODRIGUEZ |NULL|2427|1008|REALIZAR AUDITORÍA DE SEGUIMIENTO 1 DE LOS SISTEMAS DE GESTIÓN DE CALIDAD Y AMBIENTAL Y, DE SEGUIMIENTO 2 AL SISTEMA DE GESTIÓN DE SEGURIDAD DE LA INFORMACIÓN, BAJO LAS NORMAS ISO 9001:2015,ISO 14001:2015 E ISO 27001:2013, RESPECTIVAMENTE, EN MODAL|CERTIFICATION QUALITY RESOURCES SAS 
3205901|Formulario evaluacion final - 7/31/2024|2024-07-31 08:54:30.093|SI|MARÍA PAULA DÍAZ CAÑÓN|NULL|2428|1010|REALIZACIÓN DE EXÁMENES MÉDICOS EMPRESARIALES CON ÉNFASIS OSTEOMUSCULAR - DE INGRESO Y/O DE RETIRO Y OPTOMETRÍA Y EXÁMENES PSICOSENSOMÉTRICOS PARA EL CONDUCTOR.|COMPENSAR 
#### Consulta:
```sql
SELECT itd.itemnum, itd.itemname, itd.itemdate [Fecha del documento], ki719_disp.keyvaluechar AS [Voler a contratar], ki139_disp.keyvaluechar AS [Nombre Supervisor], ki231_disp.keyvaluechar AS [Número de contrato], ki242_disp.keyvaluechar AS [NoNecesidad], ki243_disp.keyvaluechar AS [No. Orden], form.Objeto, form.[Razón Social]
FROM hsi.itemdata itd
LEFT OUTER JOIN hsi.keyitem686 ki719_disp ON itd.itemnum = ki719_disp.itemnum
LEFT OUTER JOIN hsi.keyitem139 ki139_disp ON itd.itemnum = ki139_disp.itemnum
LEFT OUTER JOIN hsi.keyitem231 ki231_disp ON itd.itemnum = ki231_disp.itemnum
LEFT OUTER JOIN hsi.keyitem242 ki242_disp ON itd.itemnum = ki242_disp.itemnum
LEFT OUTER JOIN hsi.keyitem243 ki243_disp ON itd.itemnum = ki243_disp.itemnum
JOIN hsi.keyitem398 ki398_0 ON itd.itemnum = ki398_0.itemnum
JOIN hsi.doctype dtype ON itd.itemtypenum = dtype.itemtypenum
LEFT OUTER JOIN (
  SELECT DISTINCT nn.keyvaluechar AS NoNecesidad, 
                  kRS.keyvaluechar AS [Razón Social], 
                  o.keyvaluechar AS [Objeto]
  FROM hsi.itemdata i
  RIGHT OUTER JOIN hsi.keyitem242 nn ON nn.itemnum = i.itemnum
  LEFT OUTER JOIN hsi.keyitem544 kRS ON kRS.itemnum = i.itemnum
  LEFT OUTER JOIN hsi.keyitem232 o ON o.itemnum = i.itemnum
  WHERE i.itemtypenum IN (2221, 2238) AND i.status = 0
) AS form ON form.NoNecesidad = ki242_disp.keyvaluechar


WHERE (itd.itemtypenum = 2226) AND ((itd.status = 0)) AND (itd.itemnum = ki398_0.itemnum) AND (ki398_0.keyvaluechar = 'PUBLICA') AND (itd.itemtypenum = dtype.itemtypenum)	and itd.status = 0

```

### Ayudas de memoria DTI - Consulta e inventario de ayudas de memoria en OnBase
Con el fin de facilitar el seguimiento y control de las ayudas de memoria creadas en OnBase, se solicita la generación de un informe o vista que permita consultar de manera centralizada esta información. Actualmente no se cuenta con un mecanismo que permita visualizar el estado de las ayudas sin realizar búsquedas individuales o solicitar apoyo al DGC.
El reporte debe incluir las siguientes columnas:

- Número de acta
- Tipo de cambio (normal o emergencia)
- Estado actual en el flujo de aprobación
- Fecha de ingreso a bandeja (Transdate) → en caso de que la ayuda no haya sido finalizada, este campo debe mostrar null
- Identificación de ayudas cargadas manualmente sin formulario
#### Ejemplo de la consulta:
itemnum|Fecha creación|Tipo de cambio|Estado|Aprobaciones Pendientes|Fecha finalización aprobaciones|En bandeja desde|NumDoc|Código expediente|Nombre Expediente|No Acta
-|-|-|-|-|-|-|-|-|-|-
3966861|2025-08-13 15:03:29.400|NORMAL|Finalizado|Finalizó aprobaciones|2025-09-22 10:00:30.400|NULL|4044747|70929|2025 AYUDAS DE MEMORIA GESTIÓN DE CAMBIOS TECNOLOGÍA|050 
3898978|2025-07-14 08:25:41.680|NORMAL|Finalizado|Finalizó aprobaciones|2025-09-22 11:52:34.173|NULL|4045038|70929|2025 AYUDAS DE MEMORIA GESTIÓN DE CAMBIOS TECNOLOGÍA|049 
#### Consulta:
```sql
select 
    i.itemnum as itemnum,
    i.datestored as [Fecha creación],
    tipo.keyvaluechar as [Tipo de cambio], 
    case 
        when lc.statenum is NULL then 'Finalizado'
        else 'En proceso aprobaciones'
    end as Estado,
    case 
        when lc.statenum is NULL then 'Finalizó aprobaciones'
        when apr.keyvaluechar IS NULL then s.statename
        when apr.keyvaluechar is not null then apr.keyvaluechar
    end as [Aprobaciones Pendientes],
	 case 
        when lc.statenum is NULL then di.datestored
        else NULL
    end as [Fecha finalización aprobaciones],
	lc.transdate as [En bandeja desde],
    doc.itemnum as NumDoc,
    doc.kg169 as [Código expediente],
    doc.kg141 as [Nombre Expediente],
    acta.keyvaluechar as [No Acta]
    
from hsi.itemdata i
left outer join hsi.keyitem578 apr on apr.itemnum = i.itemnum
left outer join hsi.keyitem577 tipo on tipo.itemnum = i.itemnum
left outer join hsi.workitemlc lc on lc.contentnum = i.itemnum
left outer join hsi.lcstate s on s.statenum = lc.statenum
left outer join hsi.keyitem227 acta on acta.itemnum = i.itemnum
left outer join (
    select i.itemnum, k.keyvaluebig as dochandle, g.kg169, g.kg141
    from hsi.itemdata i
    left outer join hsi.keyitem19 k on k.itemnum = i.itemnum
    left outer join hsi.keygroupdata219 g on i.itemnum = g.itemnum
    where i.itemtypenum = 1945 and i.status = 0
) as doc on doc.dochandle = i.itemnum
left outer join hsi.itemdata di on doc.itemnum = di.itemnum
where i.itemtypenum = 2274

UNION ALL


select 
    NULL as itemnum,
    NULL as [Fecha creación],
    NULL as [Tipo de cambio],
    NULL as Estado,
    NULL as [Aprobaciones Pendientes],
	NULL as [Fecha finalización aprobaciones],
	NULL as [En bandeja desde],
    i.itemnum as NumDoc,
    g.kg169 as [Código expediente],
    g.kg141 as [Nombre Expediente],
    k.keyvaluechar as [No Acta]
    
from hsi.itemdata i
left outer join hsi.keyitem310 k on i.itemnum = k.itemnum
left outer join hsi.keyitem19 dh on dh.itemnum = i.itemnum
left outer join hsi.keygroupdata219 g on i.itemnum = g.itemnum
where i.itemtypenum = 1945 and dh.keyvaluebig is NULL
```

### Conciliaciones contables DIF - Reporte
Permite ver el estado de las conciliaciones contables que se encuentran en el flujo
#### Ejemplo de la consulta:
Fecha de creación|Periodo|Nombre de la conciliación|Tipo conciliación|Tiene soporte|Estado|Aprobador|Fecha de finalización|En cola desde|Código expediente|Nombre expediente|Última acción|itemnum
-|-|-|-|-|-|-|-|-|-|-|-|-
2025-10-02 10:29:51.860|202508|CONCILIACIONES DE COBERTURA |NULL|Sí|Pendiente|Pendiente jefe DIF|NULL|2025-10-02 10:31:24.827|70842|2025 CONCILIACIONES DE COBERTURA|ENVIO APROBACIONES|4081292
2025-09-22 15:33:45.123|202508|CONCILIACIONES DE INVERSIONES |CONCILIACION INVERSIONES TITULO DEUDA SEGURO DEPOSITO |Sí|Pendiente|Pendiente jefe DIF|NULL|2025-09-22 15:54:15.337|70839|2025 CONCILIACIONES DE INVERSIONES|ENVIO APROBACIONES|4045690
2025-09-16 15:55:05.170|202508|CONCILIACIONES FONDOS INTERBANCARIOS|NULL|Sí|Pendiente|Pendiente jefe DIF|NULL|2025-09-16 16:56:05.403|71153|2025 CONCILIACIONES FONDOS INTERBANCARIOS |ENVIO APROBACIONES|4039755
#### Consulta:
```sql
select * from (
select
	i.datestored [Fecha de creación],
	p.keyvaluechar [Periodo],
	c.keyvaluechar [Nombre de la conciliación],
	
	case
		when asu.keyvaluechar Is not null then asu.keyvaluechar
		else d.keyvaluechar
	end as [Tipo conciliación],
	case		
		WHEN EXISTS (
					SELECT 1 
					FROM hsi.keyitem19 d 
					JOIN hsi.keyitem154 a ON d.itemnum = a.itemnum
					WHERE d.keyvaluebig = i.itemnum 
					  AND i.status = 0 
					  AND a.keyvaluechar LIKE 'SOPORTE%'
				) THEN 'Sí'
		ELSE 'No'
	end as [Tiene soporte],
	case
		when lc.itemnum IS not NULL then 'Pendiente'
		else 'Finalizado'
	end as [Estado],
	case
		when lc.statenum = 342 then 'Pendiente envio: '+us.keyvaluechar
		when lc.statenum = 343 then cc.kg186
		when lc.statenum = 344 then 'Pendiente jefe DIF'
		else 'Finalizado'
	end as [Aprobador],
	fin.exittime [Fecha de finalización],
	lc.transdate [En cola desde],
	g.kg169 [Código expediente],
	g.kg141 [Nombre expediente],
	e.keyvaluechar [Última acción],
	i.itemnum
		
from hsi.itemdata i
	left outer join hsi.keyitem413 p on p.itemnum = i.itemnum
	
	left outer join hsi.keyitem691 c on c.itemnum = i.itemnum
	left outer join hsi.itemlc lc on lc.itemnum = i.itemnum
	left outer join hsi.keyrecorddata125 cc on cc.itemnum = i.itemnum
	left outer join (select itemnum, keyvaluechar from hsi.keyxitem373 x
					right outer join hsi.keytable373 us on  x.keywordnum = us.keywordnum) as us on us.itemnum = i.itemnum
	left outer join (select exittime, itemnum from hsi.wflog where statenumto = 0 and exittime <> '1964-01-01 00:00:00.000') as fin on fin.itemnum = i.itemnum
	left outer join hsi.keygroupdata219 g on i.itemnum = g.itemnum
	left outer join hsi.keyitem134 e on e.itemnum = i.itemnum
	left outer join hsi.keyitem289 asu on asu.itemnum = i.itemnum
	left outer join hsi.keyitem177 d on d.itemnum = i.itemnum

where itemtypenum = 2507 and i.status = 0 and i.datestored > '20250101' -- Cambiar fecha según sea necesario
) as sub
where sub.Aprobador is not null
```
_**La consulta obtiene los documentos que hayan sido cargados después del 01/01/2025, si se desea cambiar esta fecha recuerde que el formato es AAAAMMDD**_

## Informes para otras áreas:
### Verificación de comprobantes contables cargados en el año 2024 (DIF)

Este informe tiene como objetivo identificar los comprobantes contables que han sido cargados durante el año 2024, con el fin de detectar posibles faltantes en los diferentes meses y realizar el respectivo cargue de la información pendiente.
El reporte incluye los siguientes campos clave para facilitar la revisión y análisis:

- Contabilidad (Fondo)
- Tipo de comprobante (Tipo documental)
- Número de comprobante
- Año
- Mes

#### Ejemplo de la consulta:
Identificador del documento|Tipo documental|Fecha del documento|Fecha cuando se cargó el documento|Contabilidad (Fondo)|Número comprobante|Año|Mes
-|-|-|-|-|-|-|-
2895021|INVE Movimiento de Inversiones|2024-01-01 09:27:18.000|2024-02-27 09:27:18.000|01 FONDO ADMINISTRADOR|1 |2024|1 
2895064|CGCO Comprobantes Contables |2024-01-01 09:27:23.000|2024-02-27 09:27:23.000|02 SEGURO DE DEPOSITO |11|2024|1 
2895065|CGCO Comprobantes Contables |2024-01-01 09:27:23.000|2024-02-27 09:27:23.000|02 SEGURO DE DEPOSITO |12|2024|1 
2895066|CGCO Comprobantes Contables |2024-01-01 09:27:23.000|2024-02-27 09:27:23.000|02 SEGURO DE DEPOSITO |2 |2024|1 
2895272|INVE Movimiento de Inversiones|2024-01-01 09:27:36.000|2024-02-27 09:27:36.000|02 SEGURO DE DEPOSITO |114 |2024|1 
2895269|INVE Movimiento de Inversiones|2024-01-01 09:27:36.000|2024-02-27 09:27:36.000|02 SEGURO DE DEPOSITO |1 |2024|1 
2895270|INVE Movimiento de Inversiones|2024-01-01 09:27:36.000|2024-02-27 09:27:36.000|02 SEGURO DE DEPOSITO |10|2024|1 
#### Consulta:
```sql
select i.itemnum [Identificador del documento], d.itemtypename [Tipo documental], i.itemdate [Fecha del documento],
i.datestored [Fecha cuando se cargó el documento], fondo.keyvaluechar [Contabilidad (Fondo)], num.keyvaluechar [Número comprobante], anio.keyvaluesmall [Año], mes.keyvaluechar [Mes]
from itemdata i
left outer join doctype d on d.itemtypenum = i.itemtypenum
left outer join keyitem283 fondo on fondo.itemnum = i.itemnum
left outer join keyitem248 num on num.itemnum = i.itemnum
left outer join keyitem239 anio on anio.itemnum = i.itemnum
left outer join keyitem250 mes on mes.itemnum = i.itemnum
where i.itemtypegroupnum = 121 and i.itemdate >'01-01-2024' and i.status=0 --CAMBIAR AÑO SEGÚN NECESIDAD
order by i.itemdate
```
_**La consulta obtiene los documentos que hayan sido cargados después del 01/01/2024, si se desea cambiar esta fecha recuerde cambiar el año**_

### Reporte facturas (DAI)
Trae información sobre las facturas que han sido tramitadas en cierto periodo de tiempo
Campos:
- NIT del beneficiario
- Nombre del beneficiario
- Radicados en OnBase (uno correspondiente a la factura en formato XML y otro para los documentos de parafiscales)
- Valor incluido IVA
- Número de documento soporte (número de factura)
- Observaciones
- Link de acceso al cliente web

#### Ejemplo de la consulta:
Radicado de entrada|Nit|Razon Social|Valor|Asunto|link|Tipo de documento|itemnum
-|-|-|-|-|-|-|-
2025-E-000023 |830115054 |SET-ICAP FX S.A |3667461|FACTURA ELECTRONICA SET-ICAP FX S.A 20559 |http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-000023&FT=108&clienttype=html|Factura|3561539
2025-E-000043 |860002400 |LA PREVISORA S.A. COMPAÑIA DE SEGUROS |7130219|FACTURA ELECTRONICA LA PREVISORA S.A. COMPAÑIA DE SEGUROS 70OR27827 |http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-000043&FT=108&clienttype=html|Factura|3567515
2025-E-000045 |860002400 |LA PREVISORA S.A. COMPAÑIA DE SEGUROS |158449|FACTURA ELECTRONICA LA PREVISORA S.A. COMPAÑIA DE SEGUROS 70OR27826 |http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-000045&FT=108&clienttype=html|Factura|3567566
2025-E-000053 |800015163 |COMPURENT SAS |2380000|FACTURA ELECTRONICA COMPURENT SAS FECR204067|http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-000053&FT=108&clienttype=html|Factura|3568113
#### Consulta:
```sql
select r.keyvaluechar [Radicado de entrada], n.keyvaluechar Nit, e.keyvaluechar [Razon Social] , v.keyvaluebig Valor, asunto.asunto Asunto,
CONCAT('http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx', 
       CHAR(63), 
       'KT105_0_0_0=', 
       CAST(RTRIM(r.keyvaluechar) AS VARCHAR(255)), 
       '&FT=108&clienttype=html') AS link
,
case 
	when i.itemtypenum = 735 then 'Factura'
	Else 'Parafiscales'
end [Tipo de documento], i.itemnum
from hsi.itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem275 n on i.itemnum = n.itemnum
left outer join keyitem393 e on i.itemnum = e.itemnum
left outer join keyitem246 v on i.itemnum = v.itemnum
left outer join (select r.keyvaluechar radicado, a.keyvaluechar [asunto] from itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem154 a on i.itemnum = a.itemnum
where i.itemtypenum = 102) asunto on asunto.radicado = r.keyvaluechar

where i.itemtypenum in (735, 1433) and i.itemdate > '20250101' --CAMBIAR FECHA SEGÚN SEA NECESARIO


union

select r.keyvaluechar [Radicado de entrada], n.keyvaluechar Nit, e.keyvaluechar [Razon Social] , v.keyvaluebig Valor, asunto.asunto Asunto,
CONCAT('http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx', 
       CHAR(63), 
       'KT105_0_0_0=', 
       CAST(RTRIM(r.keyvaluechar) AS VARCHAR(255)), 
       '&FT=108&clienttype=html') AS link
,'XML Factura' [Tipo de documento], i.itemnum
from hsi.itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem275 n on i.itemnum = n.itemnum
left outer join keyitem393 e on i.itemnum = e.itemnum
left outer join keyitem246 v on i.itemnum = v.itemnum
left outer join (select r.keyvaluechar radicado, a.keyvaluechar [asunto] from itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem154 a on i.itemnum = a.itemnum
where i.itemtypenum = 102) asunto on asunto.radicado = r.keyvaluechar
left outer join itemdatapage p on p.itemnum = i.itemnum

where i.itemtypenum in (1478) and p.filetypenum = 32 and i.itemdate > '20250101' --CAMBIAR FECHA SEGÚN SEA NECESARIO
```
### Reporte facturas (DIF)
Informe para DIF de facturas, que incluya únicamente los siguientes tipos de documentos:

- Facturas
- Notas débito
- Notas crédito

Es importante que el informe excluya cualquier archivo en formato XML, y se limite a los documentos que cuenten con descripción gráfica.
Este informe permitirá mejorar la trazabilidad y gestión de los documentos asociados a procesos financieros, conforme a los lineamientos definidos.

#### Ejemplo de la consulta:
Radicado de entrada|Destinatario area|Nit|Razon Social|Tipo de documento|Numero de la factura|Fecha emisión|Fecha de recepción del documento|Estado|Estado Factura Electrónica|Asunto|link|itemnum
-|-|-|-|-|-|-|-|-|-|-|-|-
2025-E-007655 |DEPARTAMENTO JURÍDICO |900949400 |ALVAREZ LIEVANO LASERNA S.A.S.|Factura|FEVP15198|2025-10-03 00:00:00.000|2025-10-03 11:37:32.623|ASIGNADO|NULL|FACTURA ELECTRONICA ALVAREZ LIEVANO LASERNA S.A.S. FEVP15198|http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-007655&FT=108&clienttype=html|4087184
2025-E-007653 |DEPARTAMENTO DE GESTION DE INVERSIONES|900182389 |CAMARA DE RIESGO CENTRAL DE CONTRAPARTE DE COLOMBIA S.A.|Factura|FVE45448 |2025-10-03 00:00:00.000|2025-10-03 10:32:45.750|ASIGNADO|NULL|FACTURA ELECTRONICA CAMARA DE RIESGO CENTRAL DE CONTRAPARTE DE COLOMBIA S.A. FVE45448 |http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-007653&FT=108&clienttype=html|4086852
2025-E-007660 |DEPARTAMENTO DE DESARROLLO ADMINISTRATIVO |1020807822|MARIA GUADALUPEPENSO MONSALVO |Factura|7754 |2025-10-01 00:00:00.000|2025-10-03 12:17:41.133|ASIGNADO|NULL|FACTURA SOLICITUD DE LEGALIZACIÓN DE GASTOS DE VIAJE MARIA GUADALUPEPENSO MONSALVO N. 7754|http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx?KT105_0_0_0=2025-E-007660&FT=108&clienttype=html|4087368
#### Consulta:
```sql
-- INFORME FACTURAS DIF
select top 10 r.keyvaluechar [Radicado de entrada], asunto.area [Destinatario area], n.keyvaluechar Nit, e.keyvaluechar [Razon Social],
case 
	when i.itemtypenum = 735 then 'Factura'
	when i.itemtypenum = 1780 then 'Nota Débito'
	Else 'Nota Crédito'
end [Tipo de documento],

nf.keyvaluechar [Numero de la factura], fe.keyvaluedate [Fecha emisión], i.datestored [Fecha de recepción del documento], asunto.estado Estado, asunto.estadows [Estado Factura Electrónica], asunto.asunto Asunto,
CONCAT('http://vm-onbase1-prd/AppNet/FolderPop/FolderPop.aspx', 
       CHAR(63), 
       'KT105_0_0_0=', 
       CAST(RTRIM(r.keyvaluechar) AS VARCHAR(255)), 
       '&FT=108&clienttype=html') AS link
,
i.itemnum
from hsi.itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem275 n on i.itemnum = n.itemnum
left outer join keyitem393 e on i.itemnum = e.itemnum
left outer join keyitem246 v on i.itemnum = v.itemnum
left outer join keyitem392 nf on nf.itemnum = i.itemnum
left outer join keyitem390 fe on fe.itemnum = i.itemnum
left outer join (select r.keyvaluechar radicado, a.keyvaluechar [asunto], d.kg124 area, e.keyvaluechar estado, ws.keyvaluechar estadows from itemdata i
left outer join keyitem105 r on i.itemnum = r.itemnum
left outer join keyitem154 a on i.itemnum = a.itemnum
left outer join keygroupdata199 d on d.itemnum = i.itemnum
left outer join keyitem134 e on i.itemnum = e.itemnum
left outer join keyitem516 ws on i.itemnum = ws.itemnum
where i.itemtypenum = 102) asunto on asunto.radicado = r.keyvaluechar

where i.itemtypenum in (735, 1780, 1779) and i.datestored > '20250101' --between @{FechaIni} and @{FechaFin} 
```

## Otras soluciones:
### Actas de junta directiva (temas)
Este reporte permite consultar los temas abordados por la Junta Directiva, utilizando filtros específicos sobre los asuntos tratados
#### Ejemplo de la consulta:
NoActa|Asunto|CodExpediente|Tema
-|-|-|-|
91|91. 18 de mayo de 1989|10398|Contratación de Asesor para la reglamentación del programa de Privatización 
110|110. 9 de octubre de 1990|10399|Proyecto de Decreto sobre Reprivatización 
111|111. 19 de noviembre de 1990 |10399|Estrategia y Cronograma de Reprivatización
#### Consulta:
```sql
select acta.attr1255 as NoActa,
acta.attr1254 as Asunto,
acta.attr1256 as CodExpediente,
tema.attr1260 as Tema
from hsi.rmobjectinstance1057 as acta
left outer join hsi.rmobjectinstance1058 as tema on tema.fk1295 = acta.objectid
where tema.attr1260 like '%'+@{Tema}+'%'
```
_**El @{Tema} es un parámetro del reporte dentro del unity, si se desea probar la consulta sería:**_ `like '%privatiz%'`


### Actas de junta directiva (participantes)
Este reporte permite consultar los participantes abordados por la Junta Directiva, utilizando filtros específicos sobre los asuntos tratados
#### Ejemplo de la consulta:
NoActa|Asunto|CodExpediente|Tema
-|-|-|-|
91|91. 18 de mayo de 1989|10398|Contratación de Asesor para la reglamentación del programa de Privatización 
110|110. 9 de octubre de 1990|10399|Proyecto de Decreto sobre Reprivatización 
111|111. 19 de noviembre de 1990 |10399|Estrategia y Cronograma de Reprivatización
#### Consulta:
```sql
select acta.attr1255 as NoActa,
acta.attr1254 as Asunto,
acta.attr1256 as CodExpediente,
1010 as OnIdClase,
part.attr1264 as NombreParticipante,
part.attr1265 as Cargo

from hsi.rmobjectinstance1057 as acta
left outer join hsi.rmobjectinstance1059 as paso on acta.objectid = paso.fk1296
left outer join hsi.rmobjectinstance1060 as part on part.objectid = paso.fk1297

where part.attr1264 like '%'+@{Nombre}+'%'
```
_**El @{Nombre} es un parámetro del reporte dentro del unity, si se desea probar la consulta sería:**_ `like '%juli%'`
