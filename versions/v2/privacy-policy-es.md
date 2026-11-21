---
layout: default
title: Política de Privacidad
---

# Política de Privacidad — Yuli

**Última actualización:** 31 de agosto de 2026

**Versión del documento:** 2

Yuli ("nosotros" o "nuestro") opera la aplicación móvil Yuli (la "App"). Esta Política de Privacidad explica cómo recopilamos, usamos, almacenamos y protegemos tu información personal cuando usas la App.

Este aviso explica las prácticas de datos de Yuli. Confirmar que lo leíste no constituye un consentimiento general para toda forma de tratamiento. Cuando Yuli dependa del consentimiento para un tratamiento opcional, lo solicitará por separado para una finalidad específica y proporcionará una forma de retirarlo.

---

## 1. Información que Recopilamos

### 1.1 Información que proporcionas directamente

| Tipo de dato | Propósito | Almacenamiento |
|---|---|---|
| Selección de grupo de edad | Determinar funciones y contenido apropiados para tu edad | En el dispositivo (cifrado) |
| Fechas del ciclo/período | Seguimiento del ciclo y predicciones | En el dispositivo (cifrado) |
| Síntomas y estados de ánimo | Seguimiento del ciclo y del bienestar, y detección de patrones | En el dispositivo (cifrado) |
| Notas | Notas personales de bienestar vinculadas al calendario | En el dispositivo (cifrado) |
| Mensajes del asistente | Conversaciones con el asistente de bienestar local de la app | En el dispositivo (cifrado) |
| Alertas de patrones del ciclo | Hallazgos y recordatorios sobre patrones del ciclo | En el dispositivo (cifrado) |
| Datos de mascota y economía | Crecimiento, vestuario, habitación y monedas | En el dispositivo (cifrado) |

### 1.2 Información recopilada a través de servicios de terceros

| Tipo de dato | Servicio | Propósito |
|---|---|---|
| Correo electrónico, nombre, foto de perfil | Firebase Authentication (inicio de sesión con Google) | Creación de cuenta e inicio de sesión |
| Historial de compras, estado de suscripción | RevenueCat | Procesamiento de compras dentro de la app y gestión de suscripciones |

### 1.3 Información que NO recopilamos

- **No** recopilamos la ubicación de tu dispositivo (GPS) sin tu consentimiento explícito
- **No** recopilamos análisis ni telemetría de uso que incluyan información de identificación personal (PII)
- **No** te rastreamos a través de otras apps o sitios web
- **No** vendemos tus datos a terceros

---

## 2. Cómo Usamos Tu Información

Usamos tu información únicamente para:

- Proporcionar seguimiento del ciclo menstrual, predicciones e información de bienestar
- Detectar patrones del ciclo y recordártelos
- Ofrecer contenido y funciones apropiados para tu edad
- Procesar compras dentro de la app y gestionar suscripciones
- Autenticar tu cuenta (si decides iniciar sesión)
- Proporcionar un asistente de bienestar local dentro de la app

**No** usamos tus datos para publicidad, perfilado ni ningún propósito ajeno a la funcionalidad principal de la App.

---

## 3. Almacenamiento y Seguridad de Datos

### 3.1 Arquitectura local primero

Todos tus datos del ciclo y de bienestar (ciclos, síntomas, estados de ánimo, notas e historial del asistente) se almacenan **exclusivamente en tu dispositivo** en una base de datos cifrada.

### 3.2 Cifrado

- **En reposo**: Todos los datos locales están cifrados con **SQLCipher (AES-256-CBC)**. La clave de cifrado se genera a partir del almacenamiento seguro de tu dispositivo (Android Keystore / iOS Keychain) y nunca se transmite ni se almacena en texto plano.
- **En tránsito**: Todas las comunicaciones de red usan cifrado **HTTPS/TLS 1.2+**.

### 3.3 Bloqueo opcional de la app

Puedes activar un bloqueo por PIN o biométrico (huella dactilar, rostro) para prevenir el acceso no autorizado a la App en tu dispositivo.

---

## 4. Servicios de Terceros

Yuli integra los siguientes servicios de terceros, cada uno regulado por sus propias políticas de privacidad:

| Servicio | Propósito | Datos compartidos | Política de privacidad |
|---|---|---|---|
| **Firebase Authentication** (Google) | Inicio de sesión con cuenta de Google | Correo electrónico, nombre, foto de perfil | [Privacidad de Firebase](https://firebase.google.com/support/privacy) |
| **RevenueCat** | Gestión de compras y suscripciones dentro de la app | Recibos de compra, estado de suscripción | [Privacidad de RevenueCat](https://www.revenuecat.com/privacy/) |

**No** compartimos tus datos del ciclo y de bienestar (ciclos, síntomas, estados de ánimo, notas, etc.) con ningún servicio de terceros.

---

## 5. Privacidad de Menores (Cumplimiento COPPA)

Yuli está dirigida a usuarios de al menos 13 años. La App solicita el grupo de edad antes de ofrecer la autenticación de cuenta o pedir información personal.

- Si un usuario indica que es menor de 13 años, la creación de la cuenta se detiene y Yuli no solicita el inicio de sesión con Google ni el correo de un padre o tutor.
- Yuli no recopila deliberadamente información personal de menores de 13 años.
- Si descubrimos que recibimos información personal de un menor de 13 años, la eliminaremos. Un padre o tutor puede contactarnos mediante el correo indicado abajo.

Si la audiencia objetivo de Yuli cambia en el futuro, actualizaremos la App, esta política y el proceso de consentimiento parental aplicable antes de permitir que menores de 13 años creen cuentas.

---

## 6. Tus Derechos

### 6.1 Acceder a tus datos

Puedes ver todos los datos almacenados por la App directamente en la interfaz de la App.

### 6.2 Exportar tus datos

Desde Ajustes puedes exportar como **JSON** todas las categorías que Yuli guarda en su base de datos cifrada del dispositivo: perfil y preferencias, ciclos y días de ciclo, síntomas, estados de ánimo, notas, datos de mascota/economía, mensajes del asistente y alertas de patrones del ciclo. La exportación JSON se crea a partir de una única captura coherente de la base de datos y falla en vez de generar deliberadamente un archivo incompleto. También puedes exportar únicamente los registros de ciclos como **CSV**. Las exportaciones no incluyen los metadatos de la cuenta de Firebase, la clave de cifrado de la base de datos, el estado de las notificaciones programadas ni los registros de compras y suscripciones conservados por Google, Apple o RevenueCat.

### 6.3 Eliminar tus datos

Elige **Ajustes → Datos → Eliminar datos locales** para borrar permanentemente todas las filas de la base de datos de Yuli en tu dispositivo, incluidos registros del ciclo y de bienestar, preferencias, progreso de la mascota y archivos de exportación de Yuli creados anteriormente. La App también cancela sus notificaciones locales programadas y cierra tu sesión. Esta acción irreversible no elimina tu cuenta de Firebase ni los registros conservados por Google, Apple o RevenueCat.

### 6.4 Eliminar tu cuenta

Elige **Eliminar cuenta** debajo de tu cuenta en Ajustes para eliminar permanentemente tu cuenta de Firebase Authentication. Yuli te pide volver a autenticarte con Google antes de eliminarla; después borra las filas de la base de datos y los archivos de exportación de Yuli guardados en el dispositivo y cancela las notificaciones locales programadas. Los registros de compras y suscripciones conservados por Google Play, Apple o RevenueCat se rigen por esos servicios y Yuli no los elimina. La aplicación actual no tiene sincronización en la nube; todos los registros cubiertos por este control son registros locales de la base de datos.

### 6.5 Derechos RGPD (Unión Europea)

Si resides en el Espacio Económico Europeo, tienes derecho a:

- **Acceder** a tus datos personales
- **Rectificar** datos inexactos
- **Suprimir** tus datos ("derecho al olvido")
- **Portar** todas las categorías que Yuli guarda en tu dispositivo mediante la exportación JSON descrita arriba
- **Oponerte** al tratamiento de datos
- **Retirar el consentimiento** en cualquier momento cuando el tratamiento dependa de este

### 6.6 Derechos CCPA (California)

Si resides en California:

- Tienes derecho a saber qué información personal recopilamos
- Tienes derecho a eliminar tu información personal
- **No** vendemos información personal — "No vender mi información personal" no aplica, pero incluimos esta declaración según lo requerido

---

## 7. Retención de Datos

- **Datos en el dispositivo**: Se conservan hasta que los elimines o desinstales la App
- **Datos de Firebase Authentication**: Se conservan mientras tu cuenta exista. Puedes eliminar tu cuenta en cualquier momento
- **Datos de compras en RevenueCat**: Se conservan según la política de retención de RevenueCat para gestionar suscripciones y restaurar compras

---

## 8. Publicidad

Yuli actualmente **no** muestra ningún anuncio. Si se introduce publicidad en el futuro, esta política y las protecciones de edad de la App se actualizarán antes de habilitar anuncios.

---

## 9. Sincronización en la Nube (Función Futura)

Una versión futura de Yuli podría ofrecer sincronización en la nube opcional. Si se implementa:

- La sincronización en la nube será **solo por elección del usuario** — nunca activada por defecto
- Todos los datos serán **cifrados de extremo a extremo** antes de salir de tu dispositivo
- El servidor solo almacenará datos cifrados y nunca tendrá acceso a tus datos de salud en texto plano
- Podrás revocar la sincronización y eliminar todos los datos del servidor en cualquier momento

Esta política se actualizará antes de que se lance cualquier función de sincronización en la nube.

---

## 10. Cambios a Esta Política de Privacidad

Podemos actualizar esta Política de Privacidad de vez en cuando. Los cambios se publicarán dentro de la App y en esta URL, con la versión del documento y la fecha de "Última actualización" revisadas. Yuli exige una revisión dentro de la app antes de reanudar el uso normal cuando un cambio material afecta finalidades de tratamiento, categorías de datos, destinatarios, retención, derechos del usuario u otras prácticas sustantivas. Las correcciones editoriales no activan otra revisión. Las copias inmutables de las versiones publicadas permanecen disponibles en el repositorio público de documentos legales.

---

## 11. Contáctanos

Si tienes preguntas, inquietudes o solicitudes sobre esta Política de Privacidad o tus datos, contáctanos:

**Correo electrónico:** privacy@yuli.app

---

*Esta política de privacidad está disponible en [English](privacy-policy.html) y [Español](privacy-policy-es.html).*
