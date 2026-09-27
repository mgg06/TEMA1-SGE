<h1 align="center" style="color: #FF1493; font-weight: bold;">Análisis Empresarial: Caso 03 - Mensajería "Rapidísimo"</h1>

<div align="center">
  <img src="https://img.shields.io/badge/Desarrollo_de_Aplicaciones_Multiplataforma-FF1493?style=for-the-badge" alt="DAM" />
  <img src="https://img.shields.io/badge/Módulo-Sistemas_de_Gestión_Empresarial-FF69B4?style=for-the-badge" alt="Módulo" />
  <img src="https://img.shields.io/badge/Instituto-DAVANTE-FFB6C1?style=for-the-badge&logoColor=white" alt="Instituto" />
</div>

<br>

<h3 align="center" style="color: #DB7093;">Diagnóstico integral y propuesta de arquitectura tecnológica para la transformación digital de una empresa de reparto urbano.</h3>

<hr style="border: 2px solid #FFB6C1; border-radius: 5px;">

## <span style="color: #FF1493;">1. Introducción y Contexto del Caso</span>

Este repositorio contiene la Tarea de Evaluación del Tema 1, centrada en el análisis exhaustivo de **"Rapidísimo"**. Esta empresa de mensajería urgente opera en la ciudad con una flota de 25 trabajadores repartiendo en bicicleta y motocicleta. 

A pesar de su volumen de trabajo, la empresa mantiene una infraestructura tecnológica completamente obsoleta. Todo el negocio se sostiene sobre llamadas telefónicas y un grupo de WhatsApp, lo que está generando un descontrol absoluto: los mensajes se pierden, se envían dos repartidores a la misma dirección y es imposible medir la carga de trabajo real de la plantilla. Además, se enfrentan a un reto crítico: varias tiendas locales de comercio electrónico exigen integrar sus sistemas para automatizar los pedidos, amenazando con irse a la competencia si no se les ofrece una solución moderna.

<hr style="border: 1px solid #FFB6C1;">

## <span style="color: #FF1493;">2. Objetivos del Proyecto</span>

El propósito de este análisis es aplicar la teoría de sistemas de gestión empresarial a un caso real para:
*   Identificar las carencias organizativas de cada departamento.
*   Diagnosticar la causa técnica detrás de los fallos diarios.
*   Proponer el software corporativo adecuado (Back Office y Front Office).
*   Diseñar una arquitectura de red capaz de soportar integraciones con terceros.
*   Mapear los flujos de comunicación electrónica del negocio.

<hr style="border: 1px solid #FFB6C1;">

## <span style="color: #FF1493;">3. Estructura del Análisis</span>

El documento principal (entregado en formato PDF) desarrolla en profundidad las siguientes secciones:

### <b style="color: #C71585;">A. Organización Departamental</b>
Se detalla la estructura interna de la empresa, analizando las funciones de áreas clave como **Dirección, Ventas y Atención al Cliente, Logística, Recursos Humanos, Administración y Finanzas, Marketing, Almacén y Compras**. Se expone cómo la falta de digitalización bloquea el rendimiento de cada uno de estos sectores.

### <b style="color: #C71585;">B. Diagnóstico Operativo (Síntoma y Causa Raíz)</b>
Se abandona la visión superficial de los problemas para entenderlos como fallos estructurales derivados de la desconexión de los datos.

| Síntoma Identificado | Causa Raíz Técnica |
| :--- | :--- |
| **Repartos duplicados y caos logístico.** | Ausencia de una base de datos centralizada. La información no tiene estados automatizados. |
| **Desconocimiento de la carga de trabajo.** | Nula interconexión de módulos. Los datos de Recursos Humanos no se cruzan con los de Logística. |
| **Incapacidad para recibir pedidos automáticos.** | Aislamiento tecnológico de los sistemas, impidiendo la comunicación con ordenadores externos. |

### <b style="color: #C71585;">C. Solución Tecnológica: ERP y CRM</b>
Se justifica técnicamente la necesidad de implementar un ecosistema dual:
> <b style="color: #FF69B4;">ERP (Back Office):</b> Necesario por su capacidad de mantener una **base de datos centralizada** y ofrecer una **estructura modular e integrada**, conectando las rutas de logística con la disponibilidad del personal.
> 
> <b style="color: #FF69B4;">CRM (Front Office):</b> Imprescindible por su **orientación a la gestión comercial** para retener a las tiendas de e-commerce, y su capacidad de **analizar datos históricos** para anticiparse a los picos de demanda en la ciudad.

### <b style="color: #C71585;">D. Arquitectura del Sistema (SOA)</b>
Se descarta el modelo tradicional Cliente-Servidor por ser cerrado y limitar el software a la red interna de la oficina. En su lugar, se propone y justifica una **Arquitectura Orientada a Servicios (SOA)**. Esta es la única vía técnica para abrir la plataforma mediante servicios web, permitiendo que las páginas de los comercios electrónicos transmitan los pedidos directamente al sistema de la mensajería sin intervención manual.

### <b style="color: #C71585;">E. Flujos de E-Business</b>
Clasificación de los canales de información digital implementados en la nueva arquitectura:
*   <b style="color: #DB7093;">Flujo B2B (Business to Business):</b> La conexión automática entre los servidores de las tiendas online y el nuevo ERP de la mensajería.
*   <b style="color: #DB7093;">Flujo B2C (Business to Consumer):</b> La relación con el cliente particular que solicita un servicio urgente o recibe un paquete en su domicilio.
*   <b style="color: #DB7093;">Flujo B2E (Business to Employee):</b> La coordinación digital entre la oficina central y los terminales móviles de los 25 mensajeros en la calle.

<hr style="border: 1px solid #FFB6C1;">

## <span style="color: #FF1493;">4. Conclusión del Caso</span>

La modernización tecnológica de "Rapidísimo" no es una simple mejora estética, sino una cuestión de supervivencia empresarial. Eliminar el uso del teléfono y los chats no oficiales para dar paso a un sistema ERP/CRM basado en arquitectura SOA es el único camino para garantizar la escalabilidad del negocio, rentabilizar los recursos y asegurar los contratos fijos con el comercio electrónico local.

<hr style="border: 1px solid #FFB6C1;">

## <span style="color: #FF1493;">5. Autora del Proyecto</span>

<p style="color: #C71585; font-weight: bold;">Marta</p>
<p><i>Estudiante de Desarrollo de Aplicaciones Multiplataforma</i></p>

*   **Tecnologías de control de versiones:** Git / GitHub
*   **Diseño de la presentación de datos:** Markdown avanzado, HTML/CSS estructurado.
*   **Centro de Estudios:** Instituto MEDAC, Sevilla.
*   **Fecha:** Septiembre 2026

<div align="center">
  <img src="https://img.shields.io/badge/Estado_del_Proyecto-Completado_y_Revisado-FF1493?style=for-the-badge" alt="Estado" />
</div>
