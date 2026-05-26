# Integración de TutorLMS Pro con WordPress y WooCommerce

Caso de estudio técnico sobre la implementación de una plataforma LMS profesional integrada con WordPress, WooCommerce y TutorLMS Pro.

> Proyecto freelance remunerado realizado para un cliente real.  
> Por motivos de confidencialidad, este repositorio no incluye credenciales, datos del cliente, código propietario ni capturas con información sensible.

---

## Resumen del proyecto

El objetivo del proyecto fue transformar una web educativa existente en una plataforma de formación online con venta de cursos, acceso restringido para usuarios compradores y gestión autónoma de contenidos por parte del cliente.

La solución se implementó sobre WordPress, WooCommerce y TutorLMS Pro, configurando el flujo completo desde la compra del curso hasta el acceso del alumno al contenido formativo.

---

## Mi rol

**Integrador web / Técnico WordPress & WooCommerce**

Responsabilidades principales:

- Instalación y configuración de TutorLMS Pro.
- Integración de TutorLMS Pro con WooCommerce.
- Configuración de productos virtuales vinculados a cursos.
- Revisión del flujo de compra y acceso del usuario.
- Configuración de vídeos protegidos mediante Vimeo Business.
- Trabajo en entorno de staging antes del despliegue final.
- Pruebas funcionales del recorrido completo del usuario.
- Documentación técnica para que el cliente pudiera gestionar la plataforma de forma autónoma.

---

## Tecnologías utilizadas

- **CMS:** WordPress
- **E-commerce:** WooCommerce
- **LMS:** TutorLMS Pro
- **Vídeo:** Vimeo Business
- **Hosting:** SiteGround
- **Entorno de pruebas:** Staging
- **Pruebas:** Sandbox, navegación en incógnito, validación de acceso de usuario
- **Documentación:** Manual técnico de uso y despliegue

---

## Problema inicial

El cliente necesitaba convertir una web educativa en una academia online capaz de vender cursos digitales y controlar automáticamente el acceso al contenido.

Los principales retos eran:

- Vincular correctamente productos de WooCommerce con cursos de TutorLMS Pro.
- Evitar que usuarios sin compra accedieran a contenido premium.
- Proteger vídeos formativos frente a accesos no autorizados.
- Probar el flujo completo antes de pasarlo a producción.
- Dejar una documentación clara para que el cliente pudiera subir nuevos cursos sin depender constantemente de soporte técnico.

---

## Solución implementada

### 1. Integración LMS + WooCommerce

Se configuró TutorLMS Pro junto con WooCommerce para que los cursos pudieran venderse como productos digitales.

El flujo implementado fue:

1. El usuario visita la página del curso.
2. Añade el curso al carrito.
3. Completa el proceso de compra.
4. WooCommerce valida el pedido.
5. El usuario obtiene acceso al curso correspondiente.
6. El curso aparece disponible en su área de usuario.

---

### 2. Configuración de productos y cursos

Se creó una estructura de relación entre productos de WooCommerce y cursos de TutorLMS Pro.

Cada curso quedó vinculado a su producto correspondiente, permitiendo gestionar:

- Precio.
- Disponibilidad.
- Acceso del usuario.
- Visibilidad del curso.
- Contenido gratuito o restringido.

---

### 3. Control de acceso al contenido

Se configuraron restricciones para que solo los usuarios autorizados pudieran acceder al contenido completo del curso.

También se habilitaron vistas previas gratuitas en determinadas lecciones, permitiendo mostrar contenido de muestra sin desbloquear el curso completo.

---

### 4. Integración de vídeo protegido

Los vídeos del curso se gestionaron mediante Vimeo Business.

Se configuraron restricciones de inserción por dominio para que los vídeos solo pudieran visualizarse desde la web autorizada del cliente.

---

### 5. Trabajo en entorno staging

Antes de aplicar cambios en producción, el proyecto se trabajó en un entorno de staging.

Esto permitió:

- Probar configuraciones sin afectar a la web principal.
- Validar el flujo de compra.
- Revisar accesos de usuario.
- Comprobar la visualización de los cursos.
- Reducir riesgos antes de la migración final.

---

## Pruebas realizadas

Se realizaron pruebas funcionales sobre el recorrido completo del usuario:

- Compra de curso en entorno de pruebas.
- Acceso posterior al área de usuario.
- Validación de cursos desbloqueados.
- Comprobación de contenido restringido.
- Revisión de vistas previas gratuitas.
- Pruebas de navegación en modo incógnito.
- Verificación de visualización de vídeos embebidos.
- Revisión del funcionamiento en staging.

---

## Documentación entregada

Como parte del proyecto, se elaboró una guía técnica para el cliente con el procedimiento de gestión de la plataforma.

La documentación incluía:

- Creación de nuevos cursos.
- Organización de módulos y lecciones.
- Vinculación de cursos con productos de WooCommerce.
- Subida e inserción de vídeos.
- Configuración de vistas previas.
- Checklist básico antes de publicar un curso.
- Recomendaciones para trabajar primero en staging.

---

## Capturas

Las capturas disponibles se encuentran en la carpeta [`CAPTURAS`](./CAPTURAS).

Por confidencialidad, se han omitido o anonimizado capturas que pudieran mostrar datos del cliente, usuarios, credenciales, marca comercial o información sensible.

---

## Qué aprendí

Este proyecto me permitió trabajar en un caso real de integración web, combinando configuración técnica, pruebas funcionales y documentación para cliente.

Aprendizajes principales:

- Integración práctica entre WordPress, WooCommerce y TutorLMS Pro.
- Importancia de trabajar en staging antes de modificar producción.
- Validación del flujo completo de usuario en proyectos e-commerce.
- Control de acceso a contenido digital.
- Protección básica de contenido audiovisual.
- Documentación técnica orientada a usuarios no técnicos.
- Comunicación con cliente y entrega de una solución funcional.

---

## Estado del proyecto

Proyecto implementado correctamente en entorno de staging y preparado para su paso a producción por parte del cliente.

---

## Confidencialidad

Este repositorio funciona como caso de estudio profesional.

No se incluyen:

- Credenciales.
- Datos personales.
- Información privada del cliente.
- Código propietario.
- Base de datos.
- URLs privadas.
- Capturas con información sensible.

La finalidad del repositorio es documentar el proceso técnico y demostrar la experiencia adquirida durante la integración.
