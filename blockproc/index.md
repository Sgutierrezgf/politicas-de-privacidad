---
title: Política de privacidad — blockproc
---

# Política de privacidad de blockproc

[English version](./en)

**Última actualización:** 12 de noviembre de 2026

Esta política describe cómo la aplicación **blockproc** (paquete
`com.segutdev.blockproc`), desarrollada por segutdev, trata la información
del usuario y del dispositivo.

## 1. Resumen

blockproc es una app de bienestar digital que te permite limitar el uso de
las apps que vos elegís, interponiendo un momento de reflexión y un reto de
preguntas antes de abrirlas. **Toda la información se procesa y se guarda
únicamente en tu dispositivo.** blockproc no tiene cuentas de usuario, no
envía datos a ningún servidor, no incluye publicidad ni herramientas de
analítica, y no comparte información con terceros.

## 2. Datos que la app usa

blockproc no recopila datos personales: nada de lo que se describe abajo
sale de tu dispositivo ni llega al desarrollador.

- **Lista de apps instaladas:** se usa solo para que elijas qué apps querés limitar.
- **Uso de apps (qué app está en primer plano):** se consulta en el propio
  dispositivo para detectar cuándo abrís una app que vos mismo limitaste y
  aplicar el bloqueo. No se genera un historial ni se envía a ningún lugar.
- **Tu configuración:** los bloqueos que creás (apps, horarios, duración,
  modo extremo), los mensajes de enfoque y de bloqueo que escribís, el
  idioma elegido y el estado de cada bloqueo en curso. Se guardan
  localmente para que la app funcione, incluso después de reiniciar el teléfono.
- **Respuestas a los retos:** las preguntas vienen de un banco incluido en
  la app y tus respuestas solo se usan en el momento para decidir si se
  concede el acceso; no se envían a ningún lugar.

## 3. Permisos del dispositivo

- **Acceso a datos de uso** (`PACKAGE_USAGE_STATS`): detectar en el
  dispositivo qué app está abierta, para aplicar los bloqueos que configuraste.
- **Ver apps con ícono de inicio** (declaraciones `<queries>` de Android,
  sin el permiso `QUERY_ALL_PACKAGES`): mostrarte la lista de apps para que
  elijas cuáles limitar.
- **Mostrar sobre otras apps** (`SYSTEM_ALERT_WINDOW`): mostrar la pantalla
  de reflexión y el reto por encima de la app bloqueada.
- **Servicio en primer plano y notificaciones** (`FOREGROUND_SERVICE`,
  `FOREGROUND_SERVICE_SPECIAL_USE`, `POST_NOTIFICATIONS`): mantener la
  detección activa con una notificación visible y avisarte antes de que
  empiece un bloqueo programado.
- **Iniciar al encender el dispositivo** (`RECEIVE_BOOT_COMPLETED`) y
  **mantener el dispositivo activo** (`WAKE_LOCK`): retomar los bloqueos
  guardados después de un reinicio.
- **Acceso a internet y vibración** (`INTERNET`, `VIBRATE`): permisos
  normales que declara el framework de la app (React Native / Expo).
  blockproc no realiza conexiones de red ni envía ningún dato.

blockproc no usa el Servicio de Accesibilidad, ni accede a tu ubicación,
contactos, cámara, micrófono, fotos o archivos.

## 4. Compartición con terceros

blockproc **no comparte, vende ni transfiere** ningún dato a terceros.
No integra SDKs de publicidad, analítica ni seguimiento.

## 5. Almacenamiento, seguridad y retención

Todos los datos se guardan en el almacenamiento privado de la app en tu
dispositivo, protegido por el sistema Android, al que otras apps no pueden
acceder. Se conservan mientras la app esté instalada.

## 6. Eliminación de datos

Podés borrar todos los datos en cualquier momento eliminando tus bloqueos
desde la app, usando *Ajustes de Android > Apps > blockproc > Almacenamiento
> Borrar datos*, o desinstalando la app. Como el desarrollador no recibe ni
almacena ninguna información tuya, no hay datos que borrar en servidores.

## 7. Menores de edad

blockproc no está dirigida específicamente a menores de 13 años y no
recopila datos personales de ningún usuario, incluidos menores.

## 8. Cambios en esta política

Si la forma en que la app trata la información cambia, actualizaremos esta
página y la fecha de "Última actualización" antes de publicar la nueva versión.

## 9. Contacto

Si tenés preguntas sobre esta política, escribí a: **segutierrezdev@gmail.com**
