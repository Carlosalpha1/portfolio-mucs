---
title: "Recopilación"
permalink: /sic/
author_profile: true
toc: true
progress: false
---

# Sistemas de Información para la Ciberseguridad

La ciberseguridad es un tema crítico en la actualidad, ya que las amenazas cibernéticas continúan evolucionando y representando un riesgo constante para los sistemas de información. Para proteger los activos digitales y asegurar la confidencialidad, integridad y disponibilidad de la información, es esencial contar con herramientas y técnicas adecuadas. Por tanto, esta asignatura se ha centrado en abordar todos aquellos temas generales necesarios para proteger la información como IDS/IPS, SIEM y honeypots entre otros.

## Despliegue de IDS
Los sistemas de detección de intrusiones (IDS) son herramientas que permiten identificar y alertar sobre posibles amenazas y actividades maliciosas en la red. Snort y Suricata son dos de los IDS utilizados en la asignatura. Snort es un IDS de código abierto y ampliamente utilizado que se basa en reglas para detectar patrones de tráfico de red sospechoso. Suricata, por otro lado, es un IDS de código abierto y de alta velocidad que ofrece capacidades avanzadas de inspección de paquetes y detección de amenazas.

El despliegue de IDS como Snort y Suricata implica varias etapas, como la instalación y configuración de los sensores de IDS en la red, la definición de reglas y políticas de detección, la configuración de alertas y notificaciones, y la monitorización y análisis de los eventos generados por los sensores. Además, se deben considerar aspectos como la ubicación estratégica de los sensores en la red, la configuración adecuada de las reglas para minimizar falsos positivos y falsos negativos, y la actualización regular de las reglas y firmas de detección para mantener el IDS actualizado frente a las últimas amenazas.

## IPS
Los Sistemas de Prevención de Intrusos (IPS) son una evolución de los IDS que van más allá de la detección, ya que también pueden tomar acciones proactivas para bloquear o mitigar las amenazas identificadas. Los IPS pueden ser implementados como dispositivos independientes o como funcionalidades integradas en Firewalls o dispositivos de red.

El despliegue de IPS implica la instalación y configuración de los dispositivos de prevención de intrusiones en la red, la definición de políticas de prevención, y la monitorización y análisis de los eventos generados por los IPS. Al igual que con los IDS, es importante considerar la ubicación estratégica de los IPS en la red, la configuración adecuada de las políticas de prevención para evitar falsos positivos y falsos negativos, y la actualización regular de las políticas de prevención para mantener el IPS actualizado frente a las últimas amenazas

## SIEM

El SIEM (Security Information and Event Management) es una solución de seguridad informática que se utiliza para recopilar, correlacionar y analizar los datos de seguridad de diferentes fuentes en una organización. Los datos de seguridad pueden incluir registros de firewall, registros de sistemas de detección de intrusiones (IDS) y sistemas de prevención de intrusiones (IPS), registros de sistemas operativos, registros de aplicaciones y cualquier otro registro de actividad de red o de sistema.

La principal función del SIEM es proporcionar una visión general de la situación de seguridad de la organización, identificar las amenazas y responder rápidamente a las incidencias de seguridad. Para ello, los datos de seguridad se recopilan y se almacenan en un repositorio centralizado donde se pueden analizar y correlacionar para detectar patrones de comportamiento sospechosos.

En la asignatura se ha visto ElasticSearch y AlienVault para poner en práctica los conceptos vistos teóricamente.

## Firewalls de Última Generación
Los firewalls de última generación también han sido un tema importante en la asignatura, ya que son una pieza clave en la protección de los sistemas informáticos. Estos firewalls no solo bloquean el tráfico no deseado, sino que también analizan el tráfico permitido en busca de comportamientos sospechosos. Además, pueden integrarse con otros sistemas de seguridad, como SIEM, para ofrecer una protección más completa.

## HoneyPots

Por último, se ha abordado el tema de los honeypots, que son sistemas diseñados para atraer a los atacantes y permitir a los administradores de seguridad estudiar su comportamiento y aprender sobre las técnicas de ataque utilizadas. Los honeypots no son sistemas de producción reales, sino sistemas aislados que se utilizan exclusivamente para fines de investigación.

En conclusión, la asignatura de Sistemas de Información para la Ciberseguridad ha sido fundamental para comprender la importancia de proteger los sistemas informáticos y los datos que se almacenan en ellos. Los temas vistos, como IDS, IPS, SIEM, firewalls de última generación y honeypots, son herramientas vitales para la protección de los sistemas y la detección de posibles amenazas.