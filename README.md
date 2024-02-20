# FHW-TrabajoAuditoriaCPD

# 1  TAREA 1. Auditoria del CPD actual (sin HW)
Desarrollar un informe en el que se analicen diferentes aspectos del CPD del departamento indicando qué es adecuado y qué sería mejorable.
El análisis se debe hacer de las diferentes secciones en el diseño de un CPD, tal y como puedes ver en esta hoja de cálculo (plantilla indicada arriba)
Debéis concretar items o características a analizar en cada apartado de los indicados. Entre todos se deben analizar mínimo 25 requerimientos .
Crear un doc  compartido  con el equipo Y CON LA PROFESORA mctripiana@iesgrancapitan.org (recomendación : compartir en solo Lectura)
El documento debe incluir , por cada item a auditar,  la situación actual del CPD y la mejora que se recomienda.

Ej:
1. Estándar o Tier 
- Estado actual:  no cumple ninguno
- Recomendado: estandar  X  nivel Y

En este formato o formato tipo tabla.   
         

 # 2  TAREA 2. Análisis del Hw de nuestro CPD.
## 2.1 Crear una tabla describiendo cada elemento Hw del CPD. P.ej:

Dispositivo       | Función                            | Modelo seleccionado           |   Observaciones
----------------------------------------------------------------------------------------------------------
Armario Rack 42U  |  Soporte metálico destinado        | Rack 19 I600 42U 600 x 600     |
                  |  a alojar equipamiento electrónico,
                  |  informático y de comunicaciones.

## 2.2.  Diseño del armario de nuestro CPD
Puedes utilizar las herramientas:
- EdrawMax (Herramienta instalable) 
    https://www.edrawsoft.com/es/download-edrawmax.html
- Lucid APP  (Herramienta online)
    https://lucid.app

# 3. TAREAS 3. Diseño de un nuevo CPD
Mediante el uso de una herramienta de diseño asistido se pide el diseño del un  nuevo armario/bastidor (42U) con las siguientes características:
- Dos patch panels (1U) de 24 bocas RJ45.
- Dos switches (1U) de 24 bocas.
- Cada switch va conectado a su patch panel correspondiente.
- Cada switch debe tener las bocas a Gigabit y 2 bocas de fibra para unir ambos switches en cascada.
- El switch es gestionable
- Un SAI (UPS) de 3U conectada a todos los servidores y switches,
- Un KVM (1U) para monitorizar los distintos servidores
- Un servidor de almacenamiento tipo SAN (3U).
- Un servidor como controlador de dominio (1U).
- Un servidor para albergar máquinas virtuales (tipo Blade) con 4 servidores en total (4U)
- Un servidor Firewall (1U).
- Un router de comunicaciones conectados a ambos switches.
IMPORTANTE: Asignar nombre a cada uno de los elementos del armario rack.

Puedes utilizar las herramientas:
- EdrawMax (Herramienta instalable) 
    https://www.edrawsoft.com/es/download-edrawmax.html
- Lucid APP  (Herramienta online)
    https://lucid.app



 # 4 Elección de los elementos de comunicaciones anteriores (tarea 3).
Elaborar un cuadro como el que se detalla a continuación con cada uno de los componentes de comunicaciones integrados en el armario rack del ejercicio anterior:
- Dos patch panels (1U) de 24 bocas RJ45.
- Dos switches (1U) de 24 bocas.
    - Cada switch va conectado a su patch panel correspondiente.
    - Cada switch debe tener las bocas a Gigabit y 2 bocas de fibra para unir ambos switches en cascada.
    - El switch es gestionable
- Un SAI (UPS) de 3U conectada a todos los servidores y switches,
- Un router de comunicaciones conectados a ambos switches.

Dispositivo       | Función                            | Modelo seleccionado         |   Precio
--------------------------------------------------------------------------------------------------
Armario Rack 42U  |  Soporte metálico destinado        | Rack 19 I600 42U 600 x 600
                  |  a alojar equipamiento electrónico,
                  |  informático y de comunicaciones.

IMPORTANTE: Es recomendable utilizar páginas especializadas para encontrar los modelos de los diferentes dispositivos como las siguientes:
https://www.rackonline.es
https://www.ingesdata.com


 # 5   Elección de los elementos de servidor y almacenamiento  anteriores (tarea 3).
Elaborar un cuadro como el que se detalla a continuación con cada uno de los componentes de comunicaciones integrados en el armario rack del ejercicio anterior:
- Un servidor de almacenamiento tipo SAN (3U).
    Nota: recordar la diferencia entre SAN, NAS, DAS .  
- Un servidor como controlador de dominio (1U).
- Un servidor para albergar máquinas virtuales (tipo Blade) con 4 servidores en total (4U)
- Un servidor Firewall (1U).

Ejemplo: 

Dispositivo         | Función                            | Modelo seleccionado            |   Precio
------------------------------------------------------------------------------------------------------
Servidor Blade XX   | NAS para copias de seguridad       | Blade de 4 unidades en RAID 1  |
                    |  
Servidor torre YY   | Windows Server                     |                                |
                      Controlador de dominio 

Es recomendable utilizar páginas especializadas para encontrar los modelos de los diferentes dispositivos como las siguientes:
https://www.rackonline.es
https://www.ingesdata.com

                  

# ANEXO. Desarrollo del proyecto con SCRUM
## I. Equipo y roles
## II. Reuniones realizadas (events)
## III. Documentos: 
- link al backlog del equipo  -- no olvidar compartir con mctripiana@iesgrancapitan.org --
- Añadir (compartir en drive, link) cualquier otro documento que sea necesario
