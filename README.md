# Rhino Gym E-Business Platform

## Descripción

Rhino Gym E-Business Platform es una solución de comercio electrónico desarrollada para apoyar la transformación digital de un gimnasio local mediante la implementación de una plataforma web basada en WordPress y WooCommerce.

El sistema permite la promoción de servicios, la comercialización de membresías y productos deportivos, la gestión de clientes y la automatización de procesos comerciales mediante herramientas de marketing digital y comercio electrónico.

Este proyecto fue desarrollado como parte de la asignatura **Electiva Profesional en Ingeniería de Software** de la Corporación Universitaria del Caribe (CECAR).

---

## Objetivos

* Implementar una plataforma E-Business para Rhino Gym.
* Facilitar la venta en línea de membresías y productos.
* Mejorar la presencia digital del gimnasio.
* Aplicar metodologías ágiles de desarrollo de software.
* Utilizar herramientas de control de versiones e integración continua.

---

## Tecnologías Utilizadas

### Backend y CMS

* WordPress
* WooCommerce

### Infraestructura

* Docker
* Docker Compose

### Base de Datos

* MySQL 8.0

### Administración

* phpMyAdmin

### Control de Versiones

* Git
* GitHub

### Integración Continua

* GitHub Actions

---

## Arquitectura del Proyecto

La solución se encuentra contenerizada mediante Docker Compose y está compuesta por los siguientes servicios:

### WordPress

Aplicación principal encargada de la gestión de contenidos y funcionalidades de comercio electrónico.

### MySQL

Base de datos relacional utilizada para almacenar la información del sistema.

### phpMyAdmin

Herramienta web para la administración y monitoreo de la base de datos.

---

## Estructura del Proyecto

```text
rhino-gym-ebusiness/
│
├── docker-compose.yml
├── README.md
├── .gitignore
└── docs/
```

---

## Despliegue Local

### Requisitos

* Docker Desktop
* Docker Compose
* Git

### Clonar repositorio

```bash
git clone https://github.com/MiguelAnMarquez/rhino-gym-ebusiness
cd rhino-gym-ebusiness
```

### Iniciar servicios

```bash
docker compose up -d
```

### Acceder a la aplicación

WordPress:

```text
http://localhost:8080
```

phpMyAdmin:

```text
http://localhost:8081
```

---

## Metodología de Desarrollo

Para el desarrollo del proyecto se utilizó el marco de trabajo Scrum, organizando las funcionalidades mediante Product Backlog e implementación incremental por Sprints.

Las funcionalidades fueron priorizadas según su impacto en el negocio y distribuidas en diferentes iteraciones de desarrollo.

---

## Integración Continua

El proyecto implementa un flujo básico de Integración Continua mediante GitHub Actions.

Cada vez que se realiza un cambio en las ramas principales del repositorio, se ejecuta automáticamente una validación del proyecto con el fin de mantener la consistencia de la configuración y apoyar el proceso de desarrollo colaborativo.

---

## Funcionalidades Implementadas

* Página principal del gimnasio.
* Catálogo de servicios.
* Venta de membresías.
* Venta de productos deportivos.
* Carrito de compras.
* Checkout de compra.
* Integración con redes sociales.
* Optimización SEO básica.
* Gestión de productos mediante WooCommerce.
* Administración de usuarios y pedidos.

---

## Autores

* Luis Miguel Acuña Rodríguez
* Lucía Carolina Arroyo Figueroa
* Miguel Ángel Márquez Cabarcas

Corporación Universitaria del Caribe – CECAR

Ingeniería de Sistemas

Electiva Profesional en Ingeniería de Software

2026
