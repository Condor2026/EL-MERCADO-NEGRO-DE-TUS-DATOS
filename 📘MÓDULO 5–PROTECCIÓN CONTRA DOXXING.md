# 📘 MÓDULO 5 – PROTECCIÓN CONTRA DOXXING

**Condor2026** – Análisis de amenazas digitales**

> *“Que sepan quién eres no significa que deban saber dónde vives.”*

---

## Índice

1. ¿Qué es el doxxing y por qué da tanto miedo?  
2. Diferencia entre doxxing, leak y acoso digital  
3. ¿Qué tipo de datos suelen publicarse en un doxxing?  
4. Cómo se recopila la información (técnicas OSINT que ya conoces)  
5. Simulaciones formativas: cómo se construye un doxxing sin dañar  
6. Señales de que pueden estar preparando un doxxing contra ti  
7. Qué hacer en las primeras 24 horas si ya te han doxxeado  
- Paso 1: No alimentar el fuego  
- Paso 2: Recopilar pruebas  
- Paso 3: Actuar sobre las plataformas  
- Paso 4: Proteger tus cuentas  
- Paso 5: Contactar a autoridades  
- Paso 6: Apoyo psicológico y red de confianza  
8. Estrategias preventivas (antes de que ocurra)  
- Segmentación de identidades  
- Minimización de datos públicos  
- Uso de domicilios y teléfonos alternativos  
- Monitorización continua  
9. Herramientas gratuitas para prevenir y reaccionar  
10. Ejercicios prácticos para blindarte  
11. Conclusión y recursos  

---

## 1. ¿Qué es el doxxing y por qué da tanto miedo?

**Doxxing** (de “docs” → documents) es la publicación malintencionada de información privada o personal de una persona en internet sin su consentimiento, con el objetivo de hostigar, intimidar, avergonzar o poner en peligro a esa persona.

Puede incluir:

- Dirección de casa o trabajo.  
- Número de teléfono personal.  
- Nombres de familiares y sus datos.  
- Fotos íntimas o privadas.  
- Historial médico, financiero o legal.  
- Geolocalización en tiempo real.

**¿Por qué da tanto miedo?**  
Porque transforma el acoso virtual en un peligro físico real. Personas han tenido que mudarse, cambiar de trabajo, o han sufrido ataques en su domicilio. En casos extremos, ha llevado al suicidio.

El doxxing no es un “timo de internet”. Es un delito en muchos países (acoso, revelación de secretos, amenazas). Pero la prevención sigue siendo la mejor defensa.

---

## 2. Diferencia entre doxxing, leak y acoso digital

| Término | Qué significa | Ejemplo |
|---------|---------------|---------|
| **Leak (filtración)** | Datos privados salen a la luz por un hackeo, error o filtración interna, no necesariamente con intención de dañar a una persona concreta. | Una empresa filtra nombres y emails de clientes. |
| **Doxxing** | Alguien investiga y publica información personal *específica* de una persona para causarle daño. | Publican en un foro: “Esta es la dirección de la activista X”. |
| **Acoso digital** | Conducta repetida que hostiga a través de medios electrónicos. El doxxing suele ser el *inicio* del acoso. | Después de publicar su teléfono, cientos de personas le llaman para insultar. |

Un doxxing puede partir de una filtración (leak) o de investigación OSINT deliberada.

---

## 3. ¿Qué tipo de datos suelen publicarse en un doxxing?

Clasificación por gravedad:

**Bajo riesgo (molestia):**  
- Correo electrónico.  
- Nombre de usuario en redes.  
- Edad o ciudad genérica.

**Riesgo medio (acoso intensificado):**  
- Número de teléfono.  
- Lugar de trabajo.  
- Nombres de familiares.  
- Fotos públicas sacadas de contexto.

**Riesgo alto (peligro físico):**  
- Dirección exacta (casa, piso).  
- Horarios habituales.  
- Número de DNI / Pasaporte.  
- Datos bancarios.  
- Geolocalización en tiempo real.  
- Contraseñas (para tomar cuentas).  
- Fotos íntimas.

Los atacantes suelen empezar con datos de bajo riesgo y, si consiguen más, escalan.

---

## 4. Cómo se recopila la información (técnicas OSINT que ya conoces)

Esto ya lo vimos en el Módulo 3 (huella digital). Un doxxer usa exactamente las mismas técnicas:

- Búsqueda avanzada en Google con tu nombre, correo o alias.  
- Have I Been Pwned para correos filtrados.  
- Búsqueda inversa de imágenes para encontrar perfiles falsos o fotos tuyas.  
- Análisis de redes sociales (incluso las privadas pueden tener fugas si aceptas a cualquiera).  
- Registros públicos (propiedades, empresas, padrones filtrados).  
- Whois de dominios que hayas registrado.  
- Contactar a tus amigos haciéndose pasar por alguien conocido (ingeniería social).  
- Herramientas de OSINT como Sherlock, Maigret (para encontrar cuentas por alias).  
- Bases de datos filtradas (muchas circulan en Telegram o foros).

La buena noticia: **si tú puedes hacer este autoreconocimiento, también puedes bloquear las principales vías**.

---

## 5. Simulaciones formativas: cómo se construye un doxxing sin dañar

En un entorno educativo (para que entiendas el proceso sin hacer daño a nadie), se puede simular:

**Simulación 1 – El perfil público excesivo**

- Se elige un voluntario (con su consentimiento).  
- Se recopila información pública de él en 30 minutos.  
- Se le muestra un informe: “Esto es lo que cualquiera puede saber de ti con solo tu nombre y ciudad”.  
- Luego se le enseña a reducir esa exposición.

**Simulación 2 – El enemigo imaginario**

- El formador propone un escenario: “Eres un activista que ha molestado a un grupo radical. Usando solo tu alias `@panda_intel`, intenta encontrar tu número de teléfono en 20 minutos”.  
- Los participantes buscan en redes, filtraciones, foros.  
- Al final, se discute qué pudo haber evitado la filtración.

**Simulación 3 – El doxxing simulado en un entorno controlado**

- Se crea un perfil falso con datos ficticios.  
- Se publica un “doxxing simulado” en un servidor privado (solo para entrenamiento).  
- Los participantes deben seguir el protocolo de respuesta como si fuera real.  
- Luego se analiza qué funcionó y qué no.

Esto se hace en talleres de seguridad para periodistas y activistas. Tú puedes adaptarlo a tu formación.

---

## 6. Señales de que pueden estar preparando un doxxing contra ti

Antes de la publicación masiva, suele haber **señales previas**:

- Recibes mensajes extraños preguntando datos personales (ingeniería social).  
- Alguien intenta agregarte a grupos de Telegram o Discord donde se comparten doxxings.  
- Notas intentos de inicio de sesión en tus cuentas (revisa “actividad reciente”).  
- Amigos te dicen que alguien les preguntó por ti.  
- Aparecen comentarios hostiles en tus redes preguntando “¿dónde vives?” o “¿dónde trabajas?”.  
- Alguien te envía capturas de información tuya que no debería tener (como si quisiera asustarte).

Si detectas estas señales, **activa el protocolo preventivo** (ver sección 8).

---

## 7. Qué hacer en las primeras 24 horas si ya te han doxxeado

Lo más importante: **no reacciones con pánico, pero actúa rápido**. El tiempo juega en contra porque la información se replica.

### Paso 1 – No alimentar el fuego

- No respondas al doxxer. No le des la satisfacción.  
- No compartas el enlace donde publicaron tus datos (aunque sea para denunciarlo, porque lo difundes más).  
- No hagas declaraciones públicas impulsivas.  
- Si necesitas avisar a amigos o familiares, hazlo por privado y con calma.

### Paso 2 – Recopilar pruebas

- Capturas de pantalla (incluyendo URL, fecha, hora).  
- Si es un foro, guarda el código fuente de la página (Ctrl+U).  
- Anota el nombre de usuario del atacante (aunque sea falso).  
- Guarda cualquier mensaje relacionado.  
- Estas pruebas sirven para denunciar.

### Paso 3 – Actuar sobre las plataformas

- **Denuncia el contenido** en cada plataforma donde aparezca (Twitter, Facebook, Instagram, TikTok, foros, Telegram, Discord). Usa la opción “doxxing”, “acoso” o “información privada”.  
- Si la plataforma tiene un canal de urgencia para casos de peligro físico (algunas lo tienen), úsalo.  
- Pide a amigos de confianza que también denuncien (pero sin orquestar ataques masivos).

### Paso 4 – Proteger tus cuentas

- Cambia todas tus contraseñas (prioriza correo, banco, redes). Usa un gestor de contraseñas.  
- Activa o renueva el 2FA en todo.  
- Revoca sesiones activas en dispositivos desconocidos.  
- Si publicaron tu número de teléfono, considera usar un contestador automático o filtrar llamadas (apps como Truecaller pueden bloquear spam, pero cuidado con su privacidad).

### Paso 5 – Contactar a autoridades

- En España: Policía Nacional (grupo de delitos telemáticos) o Guardia Civil. Presenta las pruebas.  
- El doxxing puede ser delito de **revelación de secretos** (art. 197 CP) y **acoso** (art. 172 ter).  
- Si hay amenazas de muerte o violencia de género, es más grave.  
- Guarda copia de la denuncia.

### Paso 6 – Apoyo psicológico y red de confianza

- No pases por esto solo. Habla con alguien de confianza.  
- Si el acoso es intenso, desconéctate unos días.  
- Busca grupos de apoyo para víctimas de acoso digital (ej: en España, la Fundación Alia2).  
- Recuerda: el doxxing dice más del atacante que de ti.

---

## 8. Estrategias preventivas (antes de que ocurra)

La prevención es el 90% del trabajo. Haz esto **antes** de que alguien intente doxxearte.

### Segmentación de identidades

- Usa **un alias para redes sociales públicas** (no tu nombre real).  
- Un **alias para foros y comentarios**.  
- Tu **nombre real solo para LinkedIn, trabajo, banco**.  
- No cruces estas identidades (ej: no publiques tu email personal en un foro donde usas alias).

### Minimización de datos públicos

- Revisa la configuración de privacidad de todas tus redes (Módulo 3).  
- Elimina fotos donde se vea tu número de casa, matrícula de coche, o documentos.  
- No publiques tu ubicación en tiempo real ni planes de viaje.  
- Usa **direcciones de correo diferentes** para cada servicio (SimpleLogin, Firefox Relay).  
- Para registros de dominios, usa servicios de WHOIS privado (casi todos los proveedores lo ofrecen gratis).

### Domicilios y teléfonos alternativos

- Si eres activista, periodista o perfil de riesgo, usa un **apartado de correos** en lugar de tu domicilio real.  
- Teléfono secundario (prepago) para servicios que pidan verificación.  
- No des tu teléfono real en formularios web; usa servicios temporales (ej: recibir-sms-online.info, pero solo para cuentas no importantes).

### Monitorización continua

- Google Alerts con tu nombre, tu alias, tu teléfono.  
- Revisar Have I Been Pwned mensualmente.  
- Buscar tu nombre en foros conocidos por doxxing (como Kiwi Farms, ciertos subreddits, etc.) con precaución.  
- Si alguien ya te ha amenazado, usa servicios de monitorización de la deep web (pagos, pero hay opciones gratuitas limitadas como IntelX).

### Crear “ruido” (dilución)

- Si ya hay información tuya pública que no puedes eliminar, crea más información falsa o irrelevante con tu nombre.  
- Ejemplo: perfiles en redes con tu nombre pero sin foto real, publicaciones sobre hobbies genéricos.  
- Así, cuando alguien busque tu nombre, encontrará contenido no sensible mezclado.

---

## 9. Herramientas gratuitas para prevenir y reaccionar

| Herramienta | Uso | Enlace |
|-------------|------|--------|
| **Google Alerts** | Monitorizar tu nombre, correo, teléfono | google.com/alerts |
| **Have I Been Pwned** | Saber si tu correo está en filtraciones | haveibeenpwned.com |
| **SimpleLogin / Firefox Relay** | Alias de correo para no exponer el real | simplelogin.io |
| **Namechk** | Ver en qué sitios está usado tu alias | namechk.com |
| **Whois Privacy Protection** | Ocultar datos en dominios | (lo da tu registrador) |
| **Epieos** (gratis limitado) | Buscar datos asociados a un email o teléfono | epieos.com |
| **IntelX** (versión gratuita limitada) | Buscar tu email en bases de datos filtradas | intelx.io |
| **RedBot** (extensión navegador) | Monitorizar actividad sospechosa en redes | (buscar en Chrome Web Store) |
| **Captura de pantalla + archivo** | Guardar pruebas (no es herramienta, pero esencial) | (usa Fn+Impr Pant) |

**Para denunciar:** En cada plataforma, busca “Reportar doxxing” o “Reportar información privada”. Guarda el número de ticket.

---

## 10. Ejercicios prácticos para blindarte

### Ejercicio 1 – La auditoría de riesgos

Haz una lista de todas las plataformas donde usas tu nombre real. Para cada una, responde:  
- ¿Es necesario que sea mi nombre real? (Ejemplo: en LinkedIn sí; en un foro de coches, no).  
- ¿Puedo cambiar el nombre a un alias? (Muchas plataformas lo permiten).  
- ¿Puedo ocultar mi teléfono o correo de la vista pública?

Luego, cambia lo que puedas. Anota los cambios.

### Ejercicio 2 – El test del desconocido

Pídele a un amigo que no conozca tus datos privados que intente encontrar tu dirección o teléfono usando solo tu nombre y ciudad (sin pagar). Tú observas qué encuentra. Si lo encuentra, ya sabes qué información eliminar.

### Ejercicio 3 – Simula una respuesta a doxxing

Escribe un pequeño plan de 5 pasos en una nota:  
1. A quién llamo primero (un amigo, la policía, un abogado).  
2. Qué cuentas cambio de contraseña.  
3. Cómo contacto a las plataformas.  
4. Dónde guardo las pruebas.  
5. Qué hago si siento miedo (un número de apoyo psicológico).

Tenerlo escrito reduce el pánico.

### Ejercicio 4 – Limpieza de fotos

Revisa tus últimas 50 fotos públicas en Instagram, Facebook o Twitter. Busca:  
- Direcciones visibles (letreros de calle, números de portal).  
- Matrículas de coche.  
- Documentos o pantallas de ordenador.  
- Geolocalización en los metadatos (usa una app para borrar EXIF antes de subir).  

Borra o edita las que expongan datos.

### Ejercicio 5 – Configura el “modo de crisis” en tus redes

Algunas redes permiten bloquear temporalmente a cualquiera que no sea amigo. Practica cómo activar:  
- **Twitter:** Ajustes > Privacidad > “Proteger mis Tweets”.  
- **Instagram:** Cuenta privada + restringir cuentas nuevas.  
- **Facebook:** “Ver como público” y ajustar “¿Quién puede enviarme solicitudes de amistad?”.  
- **WhatsApp:** Ajustes > Privacidad > “Nadie” para foto de perfil y “Mis contactos” para última conexión.

Saber hacer esto rápido es vital.

---

## 11. Conclusión y recursos

El doxxing es una de las experiencias más angustiosas en internet porque convierte lo digital en físico. Pero **no eres un objetivo indefenso**. Con preparación, puedes reducir drásticamente las probabilidades y, si ocurre, actuar con eficacia.

**Tu plan de acción a partir de hoy:**

1. **Prevención** (esta semana):  
- Haz el autoreconocimiento del Módulo 3.  
- Segmenta identidades (alias vs real).  
- Oculta teléfono y dirección en todas partes.  
- Configura Google Alerts.

2. **Monitorización** (cada mes):  
- Have I Been Pwned.  
- Búsqueda rápida de tu nombre en Google.

3. **Preparación** (única vez):  
- Redacta tu plan de respuesta al doxxing.  
- Guarda los enlaces de denuncia de cada plataforma.

4. **Si ocurre**:  
- No alimentar.  
- Recopilar pruebas.  
- Denunciar en plataformas y policía.  
- Cambiar contraseñas.  
- Apoyarte en tu red.

**Recursos gratuitos adicionales:**

- **StopDoxxing** (proyecto comunitario): guías y apoyo.  
- **EFF – Doxxing prevention guide** (en inglés, muy completo).  
- **Líneas de ayuda** (en España: 017 para ciberseguridad, 016 para violencia de género si el doxxing tiene esa motivación).  
- **Alia2 Foundation** – ayuda a víctimas de acoso digital.

---

**Condor2026** – Especialista en OSINT, privacidad digital y análisis de amenazas.

---
