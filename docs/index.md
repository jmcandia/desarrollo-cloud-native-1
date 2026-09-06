# Desarrollo Cloud Native I

En este curso aprenderemos a diseñar y desarrollar soluciones modernas utilizando principios y tecnologías **Cloud Native**. Exploraremos cómo construir sistemas distribuidos capaces de comunicarse, escalar y adaptarse a diferentes necesidades de carga y disponibilidad.

Comenzaremos trabajando con la **gestión de APIs** y la **identidad y seguridad**, aprendiendo a publicar, proteger y consumir servicios de manera segura. Conoceremos conceptos como **API Management**, **Identity as a Service (IDaaS)**, **OAuth 2.0** y **OpenID Connect (OIDC)**, y veremos cómo integrarlos en aplicaciones y servicios.

Luego nos enfocaremos en la **comunicación asíncrona**, aprendiendo cómo utilizar colas de mensajes para desacoplar componentes y distribuir el trabajo entre distintos servicios. Trabajaremos con tecnologías de mensajería y analizaremos cuándo resulta conveniente utilizar comunicación síncrona o asíncrona.

Finalmente, exploraremos el **streaming de datos y el procesamiento de eventos**, utilizando tecnologías como **Apache Kafka** para trabajar con grandes volúmenes de información que necesitan ser procesados y distribuidos de manera continua.

Durante el curso construiremos soluciones de manera progresiva, combinando conceptos, ejercicios guiados y actividades prácticas. El objetivo es que no solo aprendamos a utilizar determinadas herramientas, sino que comprendamos **por qué y cuándo utilizar cada una**, desarrollando criterios que podamos aplicar posteriormente en distintos proyectos y entornos tecnológicos.

---

## Capítulo 1: Configurando API Manager e Identity as a Service

En este capítulo aprenderemos a trabajar con **API Management** y servicios de **Identity as a Service**, dos componentes habituales en arquitecturas modernas basadas en la nube.

Comenzaremos entendiendo qué problemas resuelven estas tecnologías y qué papel cumplen dentro de una arquitectura distribuida. Luego configuraremos un API Manager para publicar y gestionar servicios, y un servicio de identidad para administrar usuarios y controlar el acceso a los recursos.

También aprenderemos a integrar autenticación y autorización en nuestras aplicaciones utilizando **OAuth 2.0** y **OpenID Connect**, comprendiendo cómo estos estándares permiten proteger APIs y servicios sin tener que implementar desde cero todos los mecanismos de seguridad.

**¿Qué aprenderemos?**

Al finalizar este capítulo seremos capaces de:

- Comprender el propósito y funcionamiento de un **API Manager**.
- Configurar un API Manager para publicar y gestionar APIs.
- Comprender el papel de un servicio **Identity as a Service** dentro de una arquitectura Cloud Native.
- Configurar usuarios, roles, permisos y mecanismos de autenticación.
- Utilizar **OAuth 2.0** y **OpenID Connect** para implementar autenticación y autorización.
- Integrar un API Manager y un servicio de identidad con una aplicación.
- Proteger APIs y controlar el acceso a los servicios que desarrollaremos.
- Integrar estos componentes en una aplicación desplegada en la nube.

---

## Capítulo 2: Desarrollando soluciones con colas de mensajes

En este capítulo aprenderemos a utilizar **mensajería asíncrona** para resolver problemas de comunicación entre componentes de sistemas distribuidos.

Primero conoceremos las diferencias entre la comunicación síncrona y asíncrona y veremos por qué, en determinadas situaciones, no es conveniente que un servicio tenga que esperar una respuesta inmediata de otro.

Luego trabajaremos con **colas de mensajes**, configurando productores y consumidores y desarrollando componentes capaces de enviar y procesar mensajes de manera independiente. También veremos cómo este tipo de comunicación puede ayudarnos a desacoplar servicios, distribuir cargas de trabajo y construir aplicaciones más escalables y resilientes.

Utilizaremos tecnologías de mensajería como **RabbitMQ**, aunque el objetivo principal será comprender los conceptos y patrones que existen detrás de estas soluciones.

**¿Qué aprenderemos?**

Al finalizar este capítulo seremos capaces de:

- Comprender las diferencias entre comunicación síncrona y asíncrona.
- Identificar situaciones en las que resulta conveniente utilizar mensajería asíncrona.
- Comprender el funcionamiento de las colas de mensajes.
- Configurar un sistema de mensajería para trabajar con aplicaciones y servicios.
- Implementar productores y consumidores de mensajes.
- Integrar colas de mensajes con nuestros servicios.
- Administrar y monitorear colas y mensajes.
- Utilizar mensajería asíncrona para desacoplar componentes y distribuir cargas de trabajo.
- Desplegar los componentes necesarios para una solución de mensajería en un entorno Cloud.

---

## Capítulo 3: Desarrollando soluciones con streaming de datos

En este capítulo iremos un paso más allá de las colas de mensajes para conocer el **streaming de datos** y el procesamiento continuo de eventos.

Aprenderemos qué diferencia a un sistema de streaming de una cola de mensajes tradicional y en qué situaciones resulta conveniente utilizar este modelo. Trabajaremos con **Apache Kafka** para producir, distribuir y consumir flujos de eventos, explorando escenarios en los que necesitamos procesar grandes cantidades de información de manera continua.

También analizaremos conceptos relacionados con escalabilidad, distribución de datos, rendimiento y procesamiento en tiempo real o cercano al tiempo real.

**¿Qué aprenderemos?**

Al finalizar este capítulo seremos capaces de:

- Comprender los fundamentos del streaming de datos.
- Diferenciar la mensajería tradicional del procesamiento basado en streams.
- Identificar situaciones en las que una arquitectura de streaming resulta conveniente.
- Configurar una plataforma de streaming de datos.
- Implementar productores y consumidores de eventos.
- Procesar y distribuir grandes volúmenes de información.
- Integrar streaming de datos con aplicaciones y servicios distribuidos.
- Aplicar estrategias para mejorar el rendimiento y la escalabilidad.
- Administrar una plataforma de streaming de acuerdo con diferentes escenarios de uso.

---

## ¿Cómo abordaremos el curso?

A lo largo del curso iremos construyendo nuestros conocimientos de manera progresiva. Partiremos desde los conceptos fundamentales y avanzaremos hacia escenarios donde tendremos que integrar diferentes componentes para construir soluciones distribuidas.

La metodología combinará **explicaciones conceptuales, demostraciones, ejercicios guiados y actividades prácticas**. La idea es que aprendamos haciendo y que cada nueva tecnología tenga un propósito claro dentro de las soluciones que construiremos.

Más que memorizar configuraciones o comandos específicos, buscaremos comprender **los problemas que estas tecnologías resuelven, sus ventajas y limitaciones, y los criterios que debemos considerar para utilizarlas correctamente**.

De esta manera, al finalizar el curso tendremos una visión más completa de cómo se construyen e integran aplicaciones y servicios en arquitecturas modernas **Cloud Native**.
