---
title: "Recopilación"
permalink: /segof/recopilatorio
author_profile: true
toc: true
progress: false
---

# Seguridad Ofensiva

En la asignatura de Seguridad Ofensiva, se han abordado varios temas importantes, como el reconocimiento, acceso inicial, phishing, Metasploit, ejecución, escalada de privilegios, acceso a credenciales de Windows y el marco de MITRE ATT&CK. Estos temas son fundamentales para entender y aplicar técnicas de hacking ético y pruebas de penetración con el objetivo de asegurar la seguridad de los sistemas.

El **reconocimiento** es la primera fase del ciclo de vida de un ataque cibernético. En esta etapa, los atacantes recopilan información sobre el objetivo, como identificar los sistemas operativos utilizados, los puertos abiertos, las direcciones IP, los nombres de dominio y otra información pública disponible. Esta información es crucial para los atacantes, ya que les permite identificar posibles vulnerabilidades y brechas de seguridad en los sistemas objetivo. Además, el reconocimiento también puede incluir la búsqueda de información sobre empleados y posibles objetivos para el phishing. Las herramientas que hemos utilizado han sido Shodan, Censys, Nmap entre otros.

El **Acceso Inicial** es la siguiente fase en un ataque cibernético, donde los atacantes intentan obtener acceso no autorizado a los sistemas objetivo. Esto puede implicar el uso de técnicas como la explotación de vulnerabilidades conocidas, el uso de contraseñas débiles o robadas, el acceso a sistemas sin protección o la ingeniería social para obtener información de acceso. Una vez que los atacantes logran el acceso inicial, pueden establecer una presencia en el sistema objetivo y avanzar a fases posteriores del ataque. Las herramientas utilizadas han sido **gobuster**, **hydra**, **John The Ripper**, entre otros.

El **phishing** es una técnica común utilizada por los atacantes para engañar a los usuarios y obtener información confidencial, como nombres de usuario, contraseñas o datos de tarjetas de crédito. Los atacantes pueden enviar correos electrónicos o mensajes de texto falsificados que parecen ser legítimos y persuadir a los usuarios para que revelen información sensible o hagan clic en enlaces maliciosos. El phishing puede ser altamente efectivo y es importante que los profesionales de seguridad ofensiva estén capacitados para identificar y prevenir este tipo de ataques. Las herramientas utilizadas han sido **SocialPhish** y **GoPhish**

**Metasploit** es una framework de prueba de penetración ampliamente utilizada que permite a los profesionales de seguridad ofensiva identificar y explotar vulnerabilidades en sistemas informáticos y redes. Ofrece una amplia gama de módulos y exploits que se pueden utilizar para llevar a cabo pruebas de penetración de forma controlada y ética.

La **Ejecución** es una fase crítica en un ataque cibernético, donde los atacantes buscan ejecutar código malicioso en los sistemas objetivo con el objetivo de obtener acceso a datos confidenciales o controlar los sistemas de forma remota. Esto puede implicar la ejecución de malware, backdoors o scripts maliciosos para obtener un mayor control sobre el sistema comprometido. Las herramientas que se han utilizado ha sido **PowerShell**, **LinEnum**, **winPEAS.exe**, entre otros.

La **Escalada de privilegios** es una técnica utilizada por los atacantes para aumentar los privilegios de usuario y obtener acceso a recursos y datos más sensibles. Esto puede involucrar la explotación de vulnerabilidades en el sistema operativo o aplicaciones, la obtención de credenciales de administrador o la manipulación de permisos de usuario. Para abordar este tema, se han utilizado técnicas a modo de Prueba de Concepto como el aprovechamiento de los bits SetUID, las tareas de cron, los permisos sudo, etc.

El **acceso a credenciales de Windows** es otra técnica utilizada por los atacantes para obtener acceso a sistemas Windows. Esto puede involucrar la obtención de contraseñas en texto claro almacenadas en archivos o bases de datos, o el uso de técnicas de hash dumping para obtener hashes de contraseñas almacenadas en el sistema. Una vez que los atacantes obtienen las credenciales, pueden utilizarlas para realizar ataques adicionales en la red. Tambíen se han abordado varios tipos de ataques sobre Directorio Activo, como por ejemplo *Golden Ticket Attack*

**MITRE ATT&CK** es un marco de referencia ampliamente utilizado para la evaluación y mejora de la seguridad informática que se ha ido tomando como referencia a lo largo de este curso. Este marco describe una serie de tácticas y técnicas utilizadas por los atacantes para comprometer sistemas y redes. El marco se utiliza para evaluar la efectividad de las soluciones de seguridad existentes y para identificar posibles brechas de seguridad.

En conclusión, la asignatura de Seguridad Ofensiva ha sido esencial para comprender los fundamentos del hacking ético y las pruebas de penetración. Los temas de reconocimiento, acceso inicial, phishing, Metasploit, ejecución, escalada de privilegios, acceso a credenciales de Windows y el marco de MITRE ATT&CK son fundamentales para entender cómo se llevan a cabo los ataques cibernéticos y cómo prevenirlos.




