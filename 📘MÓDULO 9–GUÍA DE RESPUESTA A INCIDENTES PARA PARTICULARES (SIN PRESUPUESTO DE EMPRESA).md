# 📘 MÓDULO 9 – GUÍA DE RESPUESTA A INCIDENTES PARA PARTICULARES (SIN PRESUPUESTO DE EMPRESA)

**Condor2026 – Análisis de amenazas digitales**

> *“No importa cómo entró el problema. Importa cómo lo sacas y cómo evitas que vuelva.”*

---

## Índice

1. ¿Qué es un incidente de seguridad y por qué necesitas un plan?  
2. Tipos de incidentes que puedes sufrir como particular  
- Cuenta robada (correo, redes, banco)  
- Dispositivo infectado con malware  
- Filtración o publicación de datos personales (doxxing)  
- Estafa con transferencia bancaria o tarjeta  
- Suplantación de identidad  
- Acoso digital o sextorsión  
3. Fases de la respuesta a incidentes (adaptado para una persona)  
- Preparación (hacer antes de que pase)  
- Identificación (darme cuenta de que algo va mal)  
- Contención (parar el daño inmediato)  
- Erradicación (eliminar la causa)  
- Recuperación (volver a la normalidad)  
- Lecciones aprendidas (no volver a caer)  
4. Preparación: lo que debes tener listo hoy (por si pasa mañana)  
5. Identificación: señales de que algo está mal  
6. Contención paso a paso según el incidente  
- Incendio 1: Te roban la cuenta de correo  
- Incendio 2: Tu ordenador está infectado  
- Incendio 3: Publican tu dirección o datos íntimos  
- Incendio 4: Te estafan con una transferencia  
- Incendio 5: Se hacen pasar por ti para pedir dinero a tus contactos  
- Incendio 6: Te extorsionan con fotos íntimas  
7. Erradicación: limpiar el dispositivo o recuperar cuentas  
8. Recuperación: restaurar backups, cambiar credenciales, avisar a contactos  
9. Lecciones aprendidas: el informe de una página para ti mismo  
10. Simulaciones formativas: practica la respuesta sin estar en crisis  
11. Herramientas gratuitas para cada fase  
12. Ejercicios prácticos para prepararte  
13. Conclusión y recursos  

---

## 1. ¿Qué es un incidente de seguridad y por qué necesitas un plan?

Un **incidente de seguridad** es cualquier evento que compromete la confidencialidad, integridad o disponibilidad de tu información o dispositivos. En cristiano: que alguien entra donde no debe, roba tus datos, te bloquea el ordenador, o te suplanta.

La mayoría de la gente reacciona con pánico: apagan el ordenador a golpes, cambian contraseñas desde el mismo dispositivo infectado, o llaman a un “técnico amigo” que a veces empeora las cosas.

Un **plan de respuesta a incidentes** es un conjunto de pasos escritos que sabes seguir aunque estés nervioso. Como las instrucciones de emergencia en un avión. No necesitas memorizarlas, pero sabes dónde están.

**Ventajas de tener un plan:**  
- Actúas más rápido.  
- No olvidas pasos críticos (como guardar pruebas).  
- Reduces el daño económico y emocional.  
- Puedes delegar (enseñar el plan a un familiar).

---

## 2. Tipos de incidentes que puedes sufrir como particular

| Incidente | Síntomas típicos | Gravedad |
|-----------|------------------|-----------|
| **Cuenta robada** | No puedes entrar, te llegan correos de reinicio no solicitados, amigos ven mensajes raros desde tu cuenta | Alta (pueden acceder a otras cuentas) |
| **Dispositivo infectado** | Va lento, ventanas emergentes, cambios en el navegador, archivos cifrados (ransomware) | Muy alta (pérdida de datos) |
| **Doxxing** | Publican tu dirección, teléfono, fotos íntimas en foros o redes | Muy alta (peligro físico) |
| **Estafa con transferencia** | Enviaste dinero a un falso vendedor, falso familiar, falsa inversión | Alta (pérdida económica) |
| **Suplantación** | Tus amigos te dicen que recibieron mensajes tuyos pidiendo dinero, o descubres cuentas falsas a tu nombre | Media (reputación) |
| **Acoso / sextorsión** | Alguien te amenaza con publicar fotos íntimas si no pagas o haces algo | Muy alta (psicológica) |

Cada uno requiere una respuesta diferente. El plan general es el mismo, pero adaptaremos los pasos.

---

## 3. Fases de la respuesta a incidentes (adaptado para una persona)

Estas fases vienen del estándar NIST, pero las he simplificado para alguien en casa.

### Fase 0 – Preparación (hacer antes)
Tener copias de seguridad, contactos de emergencia, un pendrive de rescate.

### Fase 1 – Identificación
Detectar que algo va mal. ¿Es real o es un falso positivo?

### Fase 2 – Contención
Actuar rápido para que el problema no empeore. Desconectar internet, cambiar contraseñas desde otro dispositivo, avisar al banco.

### Fase 3 – Erradicación
Limpiar el malware, recuperar el control de la cuenta, eliminar datos publicados.

### Fase 4 – Recuperación
Restaurar backups, notificar a contactos, recuperar el acceso normal.

### Fase 5 – Lecciones aprendidas
Analizar qué falló y cómo evitarlo. Anotarlo.

---

## 4. Preparación: lo que debes tener listo hoy (por si pasa mañana)

No esperes a estar en crisis. Dedica una hora a hacer esto:

### 4.1 Copias de seguridad actualizadas
- Tus documentos importantes deben estar en la nube (Google Drive, OneDrive, iCloud) Y en un disco externo.  
- Verifica que las copias se hacen automáticamente al menos una vez a la semana.

### 4.2 Un dispositivo de emergencia limpio
- Un móvil viejo o un ordenador portátil que sepas que está libre de malware.  
- En él, ten acceso a tus cuentas principales (correo, banco) con contraseñas guardadas en un gestor.  
- Si tu equipo principal se infecta, podrás cambiar contraseñas desde este de emergencia.

### 4.3 Contactos de emergencia escritos (no solo en el móvil)
- Número de tu banco (el oficial, no el que te dan por llamada).  
- Número de tu proveedor de correo (Google tiene asistencia, aunque es limitada).  
- Número de la policía (no solo 112, sino la comisaría más cercana con delitos telemáticos).  
- Contacto de una persona de confianza que te ayude técnicamente.

### 4.4 Un pendrive de rescate
- Descarga una ISO de Windows o Linux (ej: Ubuntu Live USB).  
- Crea un USB booteable con Rufus (Windows) o Etcher.  
- Si tu ordenador no arranca por malware, podrás arrancar desde el USB y rescatar archivos.

### 4.5 Un gestor de contraseñas con copia de seguridad
- Exporta tu base de datos del gestor de contraseñas a un archivo cifrado y guárdalo en el USB de rescate (fuera de línea).  
- Así, si pierdes el acceso al gestor, puedes importarlo manualmente.

### 4.6 Un código de recuperación de 2FA impreso
- Cuando actives 2FA en tus cuentas, te dan códigos de recuperación (10 números). **Imprímelos y guárdalos en un cajón seguro.** No los guardes solo en el móvil.

### 4.7 Una lista de tus cuentas críticas
- Escribe en un papel: correo principal, cuenta del banco, cuentas de redes importantes, dominio de tu web si tienes. Anota el método de recuperación (teléfono, correo alternativo).

No es paranoia. Es un seguro.

---

## 5. Identificación: señales de que algo está mal

No todas las alertas son reales. A veces es un falso positivo. Pero si ves varias de estas, actúa.

### Señales de cuenta robada
- No puedes iniciar sesión con tu contraseña habitual.  
- Recibes un correo de “restablecimiento de contraseña” que no pediste.  
- Tus amigos te dicen que recibieron spam o mensajes raros desde tu cuenta.  
- Ves dispositivos desconocidos en “actividad reciente” de tu correo.

### Señales de malware en el ordenador
- El ordenador va muy lento sin razón aparente.  
- Aparecen ventanas emergentes incluso sin navegador abierto.  
- Cambian tu página de inicio del navegador.  
- El antivirus se desactiva solo.  
- Archivos se vuelven inaccesibles o cambian su extensión (ransomware).  
- El disco duro trabaja constantemente sin que tú hagas nada.

### Señales de suplantación o doxxing
- Te etiquetan en publicaciones extrañas.  
- Recibes llamadas o mensajes de desconocidos preguntando por cosas íntimas.  
- Alguien te envía una captura de pantalla de un perfil falso con tus fotos.  
- Apareces en resultados de búsqueda con datos que no publicaste.

### Señales de estafa ya consumada
- Ves un cargo en tu cuenta bancaria que no reconoces.  
- Transferiste dinero a alguien y ahora no responde.  
- Te llaman de “tu banco” para confirmar una operación que no hiciste.

Ante la duda, **asume que es real y pasa a contención**. Es mejor actuar de más que de menos.

---

## 6. Contención paso a paso según el incidente

Aquí tienes planes específicos para cada tipo de incendio. Imprime esta sección si quieres tenerla a mano.

### 🔥 Incendio 1: Te roban la cuenta de correo

**Objetivo:** Recuperar el control y evitar que accedan a otras cuentas.

**Pasos (hazlo desde un dispositivo limpio, no el infectado):**

1. **Intenta recuperar la contraseña** usando “¿olvidaste tu contraseña?”. Si el atacante cambió el correo de recuperación, usa la opción “no tengo acceso a ese correo”. Google y Microsoft tienen formularios de recuperación.  
2. **Si aún no puedes**, contacta con el soporte del proveedor (Gmail: cuenta de recuperación; Outlook: formulario). Puede tardar horas o días.  
3. **Mientras tanto, cambia todas las contraseñas** de servicios vinculados a ese correo (banco, redes, etc.) desde otro dispositivo. Usa un gestor de contraseñas.  
4. **Activa 2FA en todo** (incluyendo el correo cuando lo recuperes).  
5. **Revisa las reglas de reenvío** en el correo (los atacantes suelen poner reenvío para seguir recibiendo tus correos). Desactiva cualquier regla desconocida.  

---

### 🔥 Incendio 2: Tu ordenador está infectado (sospechas de malware)

**Objetivo:** Evitar que el malware se extienda o robe más datos.

**Pasos:**

1. **Desconecta internet** inmediatamente (cable Ethernet o desactivar WiFi). Esto evita que el malware envíe tus datos o reciba órdenes.  
2. **No apagues el ordenador** todavía (puedes perder la oportunidad de analizarlo).  
3. **Si ves un mensaje de ransomware** (“tus archivos están cifrados, paga bitcoin”), **no pagues**. No hay garantía de que te devuelvan los archivos.  
4. **Si tienes un segundo dispositivo limpio**, desde él cambia todas tus contraseñas (por si el malware robó credenciales).  
5. **Arranca el ordenador en modo seguro** (sin red) y ejecuta un análisis con Windows Defender offline o Malwarebytes.  
6. **Si el malware no se limpia**, o si es ransomware, la opción más segura es **formatear e instalar el sistema desde cero** (ver erradicación).  

---

### 🔥 Incendio 3: Publican tu dirección o datos íntimos (doxxing)

**Objetivo:** Minimizar la exposición y proteger tu seguridad física.

**Pasos (ya vimos en Módulo 5, aquí resumen):**

1. **No alimentes el fuego**: no respondas, no compartas el enlace.  
2. **Captura todo** (pantallazos, URLs).  
3. **Denuncia el contenido** en cada plataforma (opción “doxxing” o “información privada”).  
4. **Cambia tus contraseñas** por si el atacante tiene acceso a más.  
5. **Avisa a tu entorno** (familia, trabajo) para que ignoren mensajes sospechosos.  
6. **Si hay peligro físico**, contacta a la policía. Considera quedarte en otro lugar unos días si publicaron tu dirección.  

---

### 🔥 Incendio 4: Te estafan con una transferencia bancaria

**Objetivo:** Intentar recuperar el dinero y evitar más pérdidas.

**Pasos:**

1. **Llama inmediatamente a tu banco** (número oficial). Explica que hiciste una transferencia a un estafador. A veces pueden cancelar si aún no se ha procesado (en Bizum o transferencias rápidas, es más difícil).  
2. **Si fue con tarjeta de crédito**, solicita el contracargo (chargeback).  
3. **Si fue con criptomonedas**, lamentablemente es irreversible. Puedes rastrear la transacción en el blockchain, pero recuperarlo es casi imposible.  
4. **Denuncia a la policía** con los datos del estafador (cuenta, nombre, conversaciones).  
5. **Cambia las contraseñas** de la banca online (por si el estafador tiene acceso).  

---

### 🔥 Incendio 5: Suplantan tu identidad (cuentas falsas o mensajes en tu nombre)

**Objetivo:** Detener la suplantación y advertir a tus contactos.

**Pasos:**

1. **Recopila pruebas** (capturas del perfil falso, mensajes que te reenvían).  
2. **Denuncia el perfil falso** en la red social correspondiente.  
3. **Publica un aviso** (si la suplantación está activa) desde tu cuenta real: “Alguien está suplantándome. No hagas caso a mensajes que pidan dinero o datos”.  
4. **Si usaron tu nombre para estafar a otros**, presenta una denuncia policial para desligarte.  
5. **Refuerza la seguridad de tus cuentas** (2FA, contraseña nueva) para que no puedan robarte la real.  

---

### 🔥 Incendio 6: Extorsión con fotos íntimas (sextorsión)

**Objetivo:** No pagar, cortar comunicación, conseguir ayuda.

**Pasos:**

1. **No pagues.** Si pagas, pedirán más. Nunca se acaba.  
2. **No sigas hablando con el extorsionador.** Bloquéalo.  
3. **Guarda pruebas** (capturas de las amenazas, el perfil, el número).  
4. **Denuncia a la policía** (es un delito grave).  
5. **Si las fotos ya están en alguna plataforma**, solicita su retirada inmediata (todas tienen políticas contra contenido íntimo no consentido).  
6. **Habla con alguien de confianza.** No lleves la vergüenza solo. Hay líneas de ayuda (en España: 016 para violencia digital, o asociaciones como Alia2).  

---

## 7. Erradicación: limpiar el dispositivo o recuperar cuentas

Después de contener, hay que eliminar la causa.

### Para malware (ordenador o móvil):
- **Opción 1 (simple):** Ejecuta Windows Defender offline (desde configuración > seguridad > análisis offline). Reinicia y que analice antes de arrancar Windows.  
- **Opción 2 (completa pero segura):** Formatea e instala el sistema operativo desde cero. Antes, rescata tus archivos personales desde un USB booteable (pero solo los que estés seguro de que no están infectados).  
- **Para móvil:** Restablece a valores de fábrica (backup solo de fotos y contactos, no de apps desconocidas).

### Para cuentas robadas:
- Una vez recuperes el acceso, cierra todas las sesiones activas (opción “cerrar sesión en todos los dispositivos”).  
- Elimina cualquier regla de reenvío, filtro o dirección de recuperación que no reconozcas.  
- Cambia la contraseña otra vez (por si acaso).  
- Activa 2FA si no lo tenías.

### Para datos publicados (doxxing):
- No puedes “borrar” internet, pero sí puedes hacer que desaparezcan de los resultados de búsqueda (en la UE, derecho al olvido). Usa el formulario de Google para eliminar URLs.  
- Contacta a los administradores de los foros/sitios donde aparecen los datos. A veces colaboran.

---

## 8. Recuperación: volver a la normalidad

Una vez contenido y erradicado:

1. **Restaura tus datos** desde las copias de seguridad (asegúrate de que la copia no esté infectada).  
2. **Vuelve a instalar tus aplicaciones** (descarga desde webs oficiales).  
3. **Revisa que todo funciona** (correo, redes, banco).  
4. **Notifica a tus contactos** si fue necesario (ej: “ya recuperé mi cuenta de Instagram, todo normal”).  
5. **Tómate un respiro.** Has pasado por una situación estresante. Es normal sentirse vulnerable.

---

## 9. Lecciones aprendidas: el informe de una página para ti mismo

Escribe en un documento (físico o digital) lo siguiente:

- **¿Qué pasó?** (breve descripción del incidente).  
- **¿Cómo me di cuenta?** (señales).  
- **¿Qué falló?** (contraseña débil, falta de 2FA, backup no actualizado, hice clic en un enlace sospechoso…).  
- **¿Qué hice bien?** (desconecté rápido, usé dispositivo limpio, avisé al banco).  
- **¿Qué haré para que no vuelva a pasar?** (ej: activaré 2FA, haré backups semanales, no abriré enlaces de SMS).  

Este informe te servirá para mejorar tu preparación. Revisítalo cada 6 meses.

---

## 10. Simulaciones formativas: practica la respuesta sin estar en crisis

### Simulación 1 – “He perdido mi móvil y tengo 2FA allí”

**Escenario:** Te quedas sin móvil (robo, pérdida). Necesitas acceder a tus cuentas.

**Ejercicio (con papel, no real):**  
- ¿Dónde tienes los códigos de recuperación impresos?  
- ¿Puedes recuperar tu cuenta de Google usando el correo alternativo?  
- ¿Tienes otro dispositivo con sesión iniciada?  

Si respondiste “no sé” a alguna, es momento de prepararlo.

### Simulación 2 – Recibes un correo de “tu banco” con un enlace

**Ejercicio:** Tú mismo te envías un correo con un enlace a una página segura (ej: un artículo de noticias). Practica:  
1. No hacer clic directamente.  
2. Pasar el ratón por encima para ver el destino.  
3. Si no lo reconoces, abrir el navegador en privado y escribir la URL del banco manualmente.  

Luego pide a un familiar que haga lo mismo.

### Simulación 3 – El USB de rescate

**Ejercicio:** Crea realmente un USB booteable con Linux (Ubuntu) o con Windows Installation Media. Arranca desde él (sin instalar) y comprueba que puedes ver tus archivos. Así sabrás que funciona si algún día lo necesitas.

---

## 11. Herramientas gratuitas para cada fase

| Fase | Herramienta | Propósito |
|------|-------------|------------|
| **Preparación** | Bitwarden, Keepass | Gestor de contraseñas |
| | Google Drive / OneDrive | Backup en la nube |
| | Rufus / Etcher | Crear USB booteable |
| **Identificación** | Have I Been Pwned | Ver si tu correo está en filtraciones |
| | VirusTotal | Analizar enlace o archivo sospechoso |
| **Contención** | (ninguna herramienta, solo acción) | Desconectar red, cambiar contraseñas |
| **Erradicación** | Windows Defender Offline | Análisis sin arrancar Windows |
| | Malwarebytes Free | Escaneo adicional |
| | Formateo desde USB | Limpieza total |
| **Recuperación** | Copias de seguridad | Restaurar datos |
| **Lecciones** | Documento de texto | Anotar aprendizajes |

---

## 12. Ejercicios prácticos para prepararte

### Ejercicio 1 – Prepara tu kit de emergencia

Dedica una hora hoy a:
1. Imprimir los códigos de recuperación de 2FA de tu correo y banco. Guárdalos en un sobre en un cajón.  
2. Crear un USB booteable de Linux o Windows.  
3. Escribir en una tarjeta los contactos de emergencia (banco, policía, persona de confianza).  
4. Verificar que tus backups automáticos están funcionando.

### Ejercicio 2 – Simula una cuenta robada

Pídele a un amigo que cambie temporalmente la contraseña de una cuenta no crítica (ej: una cuenta de una red social secundaria que no uses). Tú debes recuperarla usando el método de “olvidé mi contraseña” y el correo alternativo. Practica sin pánico.

### Ejercicio 3 – El plan de acción escrito

Redacta un documento de una página titulado “QUÉ HACER SI…” con instrucciones breves para los 3 incidentes más probables en tu caso (ej: pierdo el móvil, me roban el correo, veo un cargo extraño en el banco). Ponlo en un lugar accesible (no solo en el ordenador).

### Ejercicio 4 – Revisión de la configuración de seguridad

Revisa la configuración de tu cuenta de Google (myaccount.google.com/security). Asegúrate de que tienes:
- 2FA activado.  
- Teléfono y correo de recuperación actualizados.  
- Dispositivos conocidos (elimina los antiguos).  
- Contraseña segura (puedes usar la comprobación de Google).

Haz lo mismo con tu banco y redes principales.

### Ejercicio 5 – Ensayo con un familiar

Explícale a un familiar de confianza (o a tu pareja) qué hacer si tú sufres un incidente y no puedes reaccionar (ej: estás de viaje). Dale una copia de tu plan de emergencia y los contactos clave.

---

## 13. Conclusión y recursos

Tener un plan de respuesta a incidentes es como tener un seguro de hogar: esperas no usarlo nunca, pero si ocurre algo, bendices haberlo preparado.

**Resumen ejecutivo (lo que debes hacer hoy):**

1. **Prepara tu kit:** códigos de recuperación impresos, USB de rescate, contactos escritos, backups activos.  
2. **Aprende la secuencia:** Contener (desconectar, cambiar contraseñas desde otro dispositivo) → Erradicar (limpiar o formatear) → Recuperar (backups) → Aprender.  
3. **Practica una simulación** al mes (puede ser de 5 minutos).  
4. **No te culpes si fallas.** Lo importante es reaccionar rápido, no ser perfecto.

**Recursos adicionales:**

- **INCIBE – Guía de respuesta a incidentes para ciudadanos** (descargable).  
- **Google Security Checkup** (myaccount.google.com/security).  
- **Microsoft Security Dashboard** (account.microsoft.com/security).  
- **Have I Been Pwned** (monitorización continua).  
- **Línea de ayuda para víctimas de ciberdelitos:** 017 (en España) o tu policía local.

---

**Condor2026** – Especialista en OSINT, privacidad digital y análisis de amenazas.

---
