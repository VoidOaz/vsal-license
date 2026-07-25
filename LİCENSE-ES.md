===============================================================================
LICENCIA VETERAN DE CÓDIGO FUENTE DISPONIBLE (VSAL)
Versión 1.2 – Licencia genérica de software de código fuente disponible y auditable
===============================================================================

Copyright (c) 2026 Berkay Kesgin / VoidOaz. Todos los derechos reservados.

-------------------------------------------------------------------------------
PREÁMBULO Y PROPÓSITO
-------------------------------------------------------------------------------
El presente Acuerdo de Licencia ("Licencia") es un contrato legal entre el Autor
(VoidOaz) y cualquier persona física, entidad u organización que acceda,
inspeccione, compile o evalúe el Software ("Licenciatario" o "Usted").

El Autor ha creado y desarrollado el Software para proporcionar total
transparencia del código fuente, auditoría de seguridad estática y verificación
operacional a administradores de servidores, desarrolladores e investigadores
de seguridad.

El Autor retiene todos los derechos de propiedad intelectual, derechos de autor
y derechos patrimoniales sobre el Software. El acceso al Código Fuente se
concede únicamente bajo los términos, condiciones y limitaciones expresas
definidas en esta Licencia.

ESTE SOFTWARE SE PROPORCIONA BAJO UN MODELO DE "CÓDIGO FUENTE DISPONIBLE". NO
ES SOFTWARE DE CÓDIGO ABIERTO (SEGÚN LO DEFINE LA OPEN SOURCE INITIATIVE), NO
ES SOFTWARE LIBRE NI ES DE DOMINIO PÚBLICO. EL ACCESO AL CÓDIGO FUENTE SE
CONCEDE EXCLUSIVAMENTE CON FINES DE AUDITORÍA, INSPECCIÓN Y PRUEBAS NO
COMERCIALES SEGÚN LO AQUÍ ESPECIFICADO.


===============================================================================
SECCIÓN 1 – DEFINICIONES
===============================================================================

1.1 "Autor" significa Berkay Kesgin (VoidOaz), único creador y titular de los
derechos de autor del Software.

1.2 "Software" significa el conjunto completo de archivos de código fuente,
bytecode compilado (.jar, .class), configuraciones de compilación, archivos
de recursos, documentación y algoritmos proporcionados en este paquete.

1.3 "Código Fuente" significa los archivos de programación legibles por humanos
(incluidos Java, XML y scripts de compilación) que componen el Software.

1.4 "Binario" o "Ejecutable Compilado" significa los archivos de bytecode (.jar)
o ejecutables generados a partir del Código Fuente.

1.5 "Auditoría" o "Inspección" significa la revisión no destructiva de solo
lectura o el análisis estático realizado para verificar la seguridad, el
rendimiento y la ausencia de código malicioso.

1.6 "Entorno de Producción" significa cualquier instancia de servidor activa,
pública, conectada a la red o comercial (incluidas redes de servidores
Minecraft, proxies o contenedores) accesible para usuarios finales o jugadores.

1.7 "Prueba Local No Comercial" significa ejecutar el Software exclusivamente
en una máquina privada, fuera de línea, no pública o en un entorno local
(localhost) sin aceptar pagos financieros, donaciones o beneficios comerciales.

1.8 "Canal de Distribución Autorizado" significa plataformas, sitios web o
repositorios mantenidos oficialmente o autorizados expresamente por escrito por
el Autor.

1.9 "Obra Derivada" significa cualquier software o módulo que incorpore
directamente, copie o reutilice partes sustanciales del Código Fuente real
del Software. Las implementaciones independientes de funcionalidades similares
que no copien el Código Fuente del Software no se consideran Obras Derivadas.

1.10 "Clave de Licencia" o "Protocolo de Validación" significa un token, clave
o protocolo de validación en línea proporcionado por el Autor para autorizar la
ejecución en entornos de producción.


===============================================================================
SECCIÓN 2 – USOS PERMITIDOS (TRANSPARENCIA Y AUDITORÍA)
===============================================================================

2.1 Inspección del Código Fuente
Sujeto al cumplimiento de esta Licencia, el Autor le otorga un derecho no
exclusivo, intransferible y limitado para ver, leer e inspeccionar el Código
Fuente. Este derecho es perpetuo respecto de la versión específica del Código
Fuente a la que haya accedido, incluso si la Licencia se rescinde posteriormente
por otros motivos, siempre que no lo redistribuya contraviniendo la Sección 4.

2.2 Auditoría de Seguridad y Análisis Estático
Se le permite plenamente ejecutar herramientas de análisis estático de código,
escáneres de seguridad y software de perfilado local sobre el Código Fuente para
verificar el rendimiento y la integridad de la seguridad.

2.3 Publicación de Informes de Auditoría
Puede publicar revisiones técnicas independientes o informes de auditoría de
seguridad, siempre que:
(a) Los informes sean técnicos y objetivos;
(b) Las vulnerabilidades se traten de acuerdo con la Sección 8 de esta
    Licencia;
(c) El informe no reproduzca archivos fuente completos más allá de extractos
    de código razonables necesarios para ilustrar los hallazgos.

2.4 Comentarios y Contribuciones de la Comunidad
Si envía informes de errores, avisos de seguridad o contribuciones de código al
Autor, concede al Autor un derecho perpetuo, mundial y no exclusivo para
incorporar y comercializar dichos comentarios dentro del Software. A cambio, el
Autor se compromete a reconocer públicamente y atribuir la autoría al colaborador
en la documentación del proyecto, el archivo CREDITS o un mecanismo equivalente
de atribución pública mantenido junto con el repositorio oficial del Software.
Este reconocimiento se mantendrá mientras la contribución incorporada siga
formando parte del Software.


===============================================================================
SECCIÓN 3 – EJECUCIÓN EN PRODUCCIÓN Y USO COMERCIAL
===============================================================================

3.1 Requisito de Licencia Comercial
Ejecutar, alojar o poner en marcha el Binario compilado (.jar) en cualquier
Entorno de Producción requiere una Licencia Comercial válida o autorización
expresa obtenida directamente del Autor o a través de un Canal de Distribución
Autorizado.

3.2 Evaluación Local No Comercial
Se le concede un privilegio limitado para ejecutar el Software estrictamente
para Pruebas Locales No Comerciales. Este privilegio cesa inmediatamente si el
servidor se vuelve públicamente accesible o genera ingresos/donaciones
comerciales.


===============================================================================
SECCIÓN 4 – RESTRICCIONES DE REDISTRIBUCIÓN Y COMPILACIÓN DE CÓDIGO
===============================================================================

4.1 Reutilización y Extracción Literal de Código
No puede copiar, extraer, duplicar ni redistribuir el Código Fuente real o los
archivos de clase de este Software en otros proyectos públicos o comerciales sin
el consentimiento por escrito del Autor.

4.2 Restricciones de Redistribución
No puede alojar, revender, sublicenciar ni distribuir el Código Fuente o los
Binarios compilados en plataformas de intercambio de archivos de terceros o
repositorios públicos no autorizados.

4.3 Autocompilación
La autocompilación del Código Fuente en binarios ejecutables (.jar) se permite
estrictamente para depuración local, educación y verificación de que el Binario
oficial coincide con el Código Fuente público (por ejemplo, mediante una
comparación de compilación reproducible). Queda prohibido implementar binarios
autocompilados en cualquier Entorno de Producción sin un acuerdo comercial
válido.


===============================================================================
SECCIÓN 5 – DERECHOS DE PROPIEDAD INTELECTUAL
===============================================================================

5.1 Propiedad
Todos los derechos, títulos e intereses sobre el Software, incluidos el código
fuente, la marca y los activos originales, pertenecen exclusivamente al Autor
(Berkay Kesgin / VoidOaz).

5.2 Conservación de Avisos
No debe eliminar, ocultar ni alterar los avisos de derechos de autor, créditos
de autor o encabezados de atribución incrustados en los archivos de Código
Fuente. Esta obligación no se extiende al filtrado ordinario de registros del
servidor ni a la supresión de la salida de la consola realizada por herramientas
de administración de servidores, siempre que los encabezados del código fuente
subyacente permanezcan intactos.


===============================================================================
SECCIÓN 6 – BIBLIOTECAS Y DEPENDENCIAS DE TERCEROS
===============================================================================

6.1 Alcance
Esta Licencia se aplica exclusivamente al código original escrito por el Autor.
Las bibliotecas de terceros o API de código abierto (como Spigot, Paper,
Velocity, Jackson, Guava, etc.) a las que haga referencia el Software seguirán
rigiéndose por sus respectivas licencias de código abierto.


===============================================================================
SECCIÓN 7 – INTEGRIDAD DEL SOFTWARE Y VALIDACIÓN DE LICENCIA
===============================================================================

7.1 Garantía de Integridad
El Autor asegura que las versiones oficiales distribuidas a través de Canales
Autorizados están libres de keyloggers ocultos, ransomware destructivo o código
malicioso de borrado de datos.

7.2 Validación Asíncrona de Licencia
El Software puede incluir un protocolo de red ligero y asíncrono para validar
las claves de licencia de producción activas. Este proceso comunica únicamente
metadatos operativos básicos: la clave de licencia, un hash criptográfico con
sal (SHA-256) de la dirección IP pública del servidor (que no revela la IP en
texto plano), la versión del software y la versión de Java en tiempo de
ejecución. No se recopila, almacena ni transmite ningún dato personal del
usuario final, registro de chat, datos de jugadores ni contenido de la base de
datos.


===============================================================================
SECCIÓN 8 – DIVULGACIÓN RESPONSABLE DE VULNERABILIDADES
===============================================================================

8.1 Notificación Confidencial
Si descubre una vulnerabilidad de seguridad durante la inspección del código
fuente, acepta informarla de forma privada al Autor antes de hacerla pública.

8.2 Plazo de Resolución y Divulgación Responsable
Se concede al Autor un plazo de 30 días para inspeccionar y parchear el problema
notificado. Si una vulnerabilidad está siendo explotada activamente en la
naturaleza ("día cero"), se aplica un plazo de notificación reducido de 7 días
antes de que se puedan publicar avisos técnicos por seguridad pública. En todos
los casos, la divulgación debe coordinarse para que los usuarios tengan acceso
a un parche antes de que los detalles técnicos se difundan ampliamente.


===============================================================================
SECCIÓN 9 – RESCISIÓN Y RECURSOS LEGALES
===============================================================================

9.1 Rescisión Automática
Sus derechos para ejecutar, compilar para despliegue o usar de cualquier otro
modo el Software (excepto el derecho perpetuo de inspección del código fuente
otorgado en la Sección 2.1) se rescinden automáticamente si incumple cualquier
término sustancial de esta Licencia.

9.2 Consecuencias de la Rescisión
Tras la rescisión, debe cesar toda ejecución del Software en producción y local,
eliminar todos los binarios compilados utilizados en violación y destruir
cualquier copia no autorizada del Código Fuente obtenida fuera del canal de
inspección permitido. El derecho perpetuo a conservar e inspeccionar el Código
Fuente públicamente disponible con fines históricos/de auditoría sobrevive a la
rescisión, siempre que no lo redistribuya ulteriormente.

9.3 Recursos Legales
La ejecución comercial no autorizada, la sublicencia no autorizada o el robo
deliberado de código constituyen incumplimiento de contrato e infracción de
derechos de autor. El Autor se reserva todos los derechos para emprender
acciones legales, medidas cautelares y notificaciones de retirada por derechos
de autor conforme a las leyes aplicables.


===============================================================================
SECCIÓN 10 – LEY APLICABLE Y JURISDICCIÓN
===============================================================================

10.1 Ley Aplicable
La presente Licencia se regirá e interpretará de conformidad con las leyes de
la República de Turquía, sin tener en cuenta sus disposiciones sobre conflictos
de leyes.


===============================================================================
SECCIÓN 11 – EXENCIÓN DE GARANTÍAS Y LIMITACIÓN DE RESPONSABILIDAD
===============================================================================

11.1 Exención de Garantías
EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O
IMPLÍCITA. EN NINGÚN CASO EL AUTOR SERÁ RESPONSABLE DE RECLAMACIÓN ALGUNA, DAÑO,
PÉRDIDA DE DATOS U OTRA RESPONSABILIDAD QUE SURJA DEL USO O MANIPULACIÓN DEL
SOFTWARE.

11.2 Limitación de Responsabilidad
EN LA MÁXIMA MEDIDA PERMITIDA POR LA LEY APLICABLE, EL AUTOR NO SERÁ RESPONSABLE
DE DAÑOS INDIRECTOS, INCIDENTALES, ESPECIALES O CONSECUENTES (INCLUYENDO PÉRDIDA
DE BENEFICIOS, INTERRUPCIÓN DE NEGOCIO O PÉRDIDA DE DATOS), INCLUSO SI SE HA
ADVERTIDO DE LA POSIBILIDAD DE TALES DAÑOS.


===============================================================================
SECCIÓN 12 – DIVISIBILIDAD
===============================================================================

12.1 Si cualquier disposición de esta Licencia fuera considerada inválida o
inejecutable por un tribunal de jurisdicción competente, dicha disposición se
aplicará en la máxima medida permitida para dar efecto a la intención de las
partes, y las disposiciones restantes de esta Licencia permanecerán en pleno
vigor y efecto.


===============================================================================
FIN DE LOS TÉRMINOS DE LA LICENCIA – VSAL v1.2
===============================================================================
