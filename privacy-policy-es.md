---
layout: default
title: Política de Privacidad
---

# Política de Privacidad — Yuli

**Última actualización:** 30 de marzo de 2026

Yuli ("nosotros" o "nuestro") opera la aplicación móvil Yuli (la "App"). Esta Política de Privacidad explica cómo recopilamos, usamos, almacenamos y protegemos tu información personal cuando usas la App.

Al usar Yuli, aceptas la recopilación y uso de información según lo descrito en esta política.

---

## 1. Información que Recopilamos

### 1.1 Información que proporcionas directamente

| Tipo de dato | Propósito | Almacenamiento |
|---|---|---|
| Selección de grupo de edad | Determinar funciones y contenido apropiados para tu edad | En el dispositivo (cifrado) |
| Fechas del ciclo/período | Seguimiento del ciclo y predicciones | En el dispositivo (cifrado) |
| Síntomas y estados de ánimo | Seguimiento de salud y detección de patrones | En el dispositivo (cifrado) |
| Registros de actividad sexual | Seguimiento de fertilidad e información de salud | En el dispositivo (cifrado) |
| Datos de embarazo | Acompañamiento del embarazo y guía semana a semana | En el dispositivo (cifrado) |
| Entradas del registro de salud | Diario personal de salud (condiciones, tratamientos) | En el dispositivo (cifrado) |
| Notas | Notas personales vinculadas al calendario | En el dispositivo (cifrado) |
| Citas | Programación de citas médicas y recordatorios | En el dispositivo (cifrado) |
| Medicamentos | Seguimiento de medicamentos y recordatorios | En el dispositivo (cifrado) |
| Mensajes de chat con IA | Conversaciones con el asistente de salud de la app | En el dispositivo (cifrado) |

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

- Proporcionar seguimiento del ciclo, predicciones e información de salud
- Detectar patrones de salud y alertarte sobre posibles irregularidades
- Ofrecer contenido y funciones apropiados para tu edad
- Procesar compras dentro de la app y gestionar suscripciones
- Autenticar tu cuenta (si decides iniciar sesión)
- Proporcionar consultas de salud con inteligencia artificial (cuando esté disponible)

**No** usamos tus datos para publicidad, perfilado ni ningún propósito ajeno a la funcionalidad principal de la App.

---

## 3. Almacenamiento y Seguridad de Datos

### 3.1 Arquitectura local primero

Todos tus datos de salud (ciclos, síntomas, estados de ánimo, actividad sexual, datos de embarazo, registros de salud, notas, citas, medicamentos e historial de chat con IA) se almacenan **exclusivamente en tu dispositivo** en una base de datos cifrada.

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

**No** compartimos tus datos de salud (ciclos, síntomas, estados de ánimo, actividad sexual, datos de embarazo, etc.) con ningún servicio de terceros.

---

## 5. Privacidad de Menores (Cumplimiento COPPA)

Yuli toma en serio la privacidad de los menores.

- Durante el proceso de incorporación, los usuarios seleccionan su grupo de edad. Si un usuario indica que es menor de 13 años, se aplican protecciones adicionales:
  - Se requiere **consentimiento parental** antes de la recopilación de datos
  - **Recopilación mínima de datos** — las funciones de análisis y chat con IA se desactivan
  - **Sin publicidad comportamental**
  - **Las funciones inapropiadas para su edad se ocultan** (seguimiento de actividad sexual, funciones de comunidad, servicios de ubicación)
  - Se aplican **filtros de seguridad de contenido reforzados** a todo el contenido
- Los padres o tutores pueden contactarnos en el correo indicado abajo para revisar, eliminar o rechazar la recopilación adicional de datos de su hijo/a.

Cumplimos con la Ley de Protección de la Privacidad Infantil en Internet (COPPA) y las regulaciones internacionales equivalentes.

---

## 6. Tus Derechos

### 6.1 Acceder a tus datos

Puedes ver todos los datos almacenados por la App directamente en la interfaz de la App.

### 6.2 Exportar tus datos

Puedes exportar tus datos en formato **JSON** o **CSV** desde Ajustes → Exportar datos.

### 6.3 Eliminar tus datos

Puedes eliminar permanentemente todos tus datos en cualquier momento desde Ajustes. Esta acción es irreversible y elimina todos los datos almacenados localmente.

### 6.4 Eliminar tu cuenta

Si iniciaste sesión con Google, puedes cerrar sesión y eliminar tu cuenta desde Ajustes. Esto elimina la asociación entre tu cuenta de Google y la App.

### 6.5 Derechos RGPD (Unión Europea)

Si resides en el Espacio Económico Europeo, tienes derecho a:

- **Acceder** a tus datos personales
- **Rectificar** datos inexactos
- **Suprimir** tus datos ("derecho al olvido")
- **Portar** tus datos (mediante exportación JSON/CSV)
- **Oponerte** al tratamiento de datos
- **Retirar el consentimiento** en cualquier momento

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

Yuli actualmente **no** muestra ningún anuncio. Si se introduce publicidad en el futuro, esta política se actualizará, y los anuncios nunca se mostrarán a usuarios que hayan indicado ser menores de 13 años.

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

Podemos actualizar esta Política de Privacidad de vez en cuando. Los cambios se publicarán dentro de la App y en esta URL, con la fecha de "Última actualización" revisada. Te recomendamos revisar esta política periódicamente.

---

## 11. Contáctanos

Si tienes preguntas, inquietudes o solicitudes sobre esta Política de Privacidad o tus datos, contáctanos:

**Correo electrónico:** privacy@yuli.app

---

*Esta política de privacidad está disponible en [English](privacy-policy) y [Español](privacy-policy-es).*
