# 🌐 Proyecto: Diseño de Red Corporativa | Corporate Network Design

Este repositorio contiene el proyecto integral de diseño e implementación de una infraestructura de red para una empresa tecnológica. El diseño sigue la metodología **Top-Down Network Design** para garantizar una arquitectura escalable, segura y eficiente, orientada a objetivos de negocio y técnicos. [Ver el enunciado del proyecto](./Enunciado.pdf)

---

## 🇪🇸 Descripción del Proyecto (Español)

### 🚀 Resumen
Se ha diseñado desde cero una red corporativa multi-sede capaz de soportar operaciones críticas, teletrabajo y servicios de alta disponibilidad, cumpliendo con los estándares de seguridad y gestionabilidad actuales.

### 🏗️ Arquitectura de Red
La infraestructura se divide en tres localizaciones geográficas:
* **Sede Principal (Campus):** Un edificio central con **200 puestos fijos** que alberga el clúster de servidores de alta disponibilidad (almacenamiento y cómputo).
* **Sede Remota B1:** Oficina con **50 puestos fijos** que integra los cinco departamentos de la empresa.
* **Sede Remota B2:** Oficina pequeña con **10 puestos fijos**, diseñada exclusivamente bajo el protocolo **IPv6** para los departamentos de Investigación y Cursos.

### 🛠️ Requisitos e Implementación
* **Segmentación Departamental:** Investigación, Comercial, Ventas, Cursos y Soporte Técnico.
* **Seguridad y Control de Acceso:** * El clúster de servidores es de acceso restringido (solo Investigación y Soporte Técnico).
    * Implementación de comunicaciones seguras y cifradas.
    * Mecanismos de monitorización y detección de eventos de seguridad.
* **Conectividad Avanzada:** * Exposición pública de la web corporativa.
    * Soporte para **teletrabajadores** mediante accesos remotos seguros.
    * Redes habilitadas para invitados y trabajadores internos en todas las sedes.
* **Rendimiento:** Planificación para picos de tráfico de **1 Mbps** por usuario.

---

## 🇺🇸 Project Overview (English)

### 🚀 Summary
This project involves the from-scratch design of a multi-site corporate network capable of supporting critical operations, teleworking, and high-availability services, meeting modern security and manageability standards.

### 🏗️ Network Architecture
The infrastructure is divided into three main geographical locations:
* **Main Campus:** A central building with **200 fixed workstations**, housing the high-availability server cluster (storage and computing).
* **Remote Branch B1:** Office with **50 fixed workstations** supporting all five corporate departments.
* **Remote Branch B2:** Small office with **10 fixed workstations**, operating exclusively under **IPv6** for the Research and Training departments.

### 🛠️ Requirements & Implementation
* **Departmental Segmentation:** Research, Commercial, Sales, Training, and Technical Support.
* **Security & Access Control:** * Restricted server cluster access (limited to Research and Tech Support).
    * Implementation of end-to-end secure and encrypted communications.
    * Monitoring mechanisms and security event detection tools.
* **Advanced Connectivity:** * Public hosting of the corporate website.
    * Secure access for **remote workers** via the Internet.
    * Guest and internal user networks enabled across all sites.
* **Performance:** Network planning for peak traffic of **1 Mbps** per fixed user.

---

## 📊 Especificaciones Técnicas / Technical Specs

| Característica / Feature | Detalle / Detail |
| :--- | :--- |
| **Metodología / Methodology** | Top-Down Network Design (Oppenheimer) |
| **Simulación / Simulation** | Cisco Packet Tracer / GNS3 |
| **Protocolos IP / IP Protocols** | IPv4 & IPv6 (Native B2) |
| **Servicios / Services** | DHCP, VPN, High Availability, Web Server |
| **Objetivos / Main Goals** | Escalabilidad, Seguridad y Disponibilidad |

