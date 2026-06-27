# MANUAL AVANZADO DE PREVENCIÓN DE PHISHING  
**Condor2026 – Análisis de amenazas digitales**

> *“Conocer cómo se construye una trampa no te convierte en trampero. Te convierte en alguien que sabe por dónde no caminar.”*

---

## Índice del módulo

1. ¿Por qué el phishing sigue funcionando?  
2. Anatomía del engaño: cómo se simula un ataque  
- 2.1 Correo electrónico fraudulento  
- 2.2 SMS y mensajería instantánea  
- 2.3 Llamadas telefónicas (vishing)  
- 2.4 Redes sociales y perfiles falsos  
- 2.5 Códigos QR maliciosos  
- 2.6 Phishing dirigido (spear phishing y whaling)  
3. Señales específicas por canal (listas de verificación)  
4. Herramientas gratuitas para verificar sospechas  
5. Simulaciones: cómo se entrenan las empresas (y por qué funcionan)  
6. Protocolo paso a paso si caíste  
7. Ejercicios prácticos para entrenar tu criterio  

---

## 1. ¿Por qué el phishing sigue funcionando?

No porque la gente sea “ignorante”.  
Sino porque los atacantes explotan **sesgos cognitivos**:

- **Autoridad** → “Soy el banco / la policía / soporte de Microsoft”  
- **Urgencia** → “En una hora perderás tu cuenta”  
- **Escasez** → “Últimas 10 plazas para reclamar tu reembolso”  
- **Reciprocidad** → “Te hemos bonificado 50€, confirma tus datos”  
- **Miedo** → “Han accedido a tus cuentas desde otro país”  
- **Curiosidad** → “Alguien publicó un video sobre ti”

El phishing no es un fallo técnico. Es un fallo en la gestión de la confianza.  
Y la única defensa real es **entrenar el ojo y la paciencia**.

---

## 2. Anatomía del engaño: cómo se simula un ataque

Voy a explicarte cómo se construye una simulación de phishing **en entornos de formación profesional**. Esto es lo que hacen empresas de ciberseguridad para educar a empleados. No voy a darte herramientas para atacar, sino para que reconozcas el esqueleto de un engaño.

### 2.1 Correo electrónico fraudulento

**Simulación típica en formación:**

- Se clona el diseño visual de un banco, plataforma de envíos (Correos, DHL), red social o servicio cloud (Google, Microsoft, Dropbox).  
- Se compra un dominio parecido: `rnbanco.com` en lugar de `rnbanco.es`, `paypal-security.net` en lugar de `paypal.com`.  
- Se configura un formulario falso que recolecta credenciales o datos personales.  
- Se envía el correo masivamente (o a un grupo reducido en simulaciones controladas).  

**Lo que tú ves**  
- Remitente: `"Banco Río" <notificaciones@rnbanco.com>`  
- Asunto: `"Alerta de seguridad: nuevo dispositivo vinculado"`  
- Cuerpo: logo oficial, botón rojo de “Verificar actividad”, enlace acortado.  

**Qué ocurre si haces clic en la simulación formativa:**  
- Se te redirige a una página que te dice: “Esto era una simulación. Así es como podrías haber sido engañado. Aprende las señales.”  
- No se guardan tus datos. Solo se registra que hiciste clic para fines de entrenamiento.

**En un ataque real:**  
- Tus credenciales van directamente al atacante.  
- En segundos intentan acceder a tu banco, correo o redes.

### 2.2 SMS y mensajería instantánea (smishing)

**Simulación:**  
- Se envía un SMS desde un número que suplanta a una empresa legítima (ej: “Correos: tu paquete está retenido por falta de datos”).  
- Se acorta una URL maliciosa usando servicios como bit.ly o generadores personalizados.  
- El mensaje incluye una promesa o amenaza: “Confirma aquí para evitar devolución”.

**Ejemplo de SMS realista (simulado):**  
> `[MIBANCO] Hemos detectado un cargo de 800€ en Madrid. Si no fuiste tú, cancela aquí: mibanco-seguro.com/cancelar`  

**Qué aprender en la simulación:**  
- El dominio `mibanco-seguro.com` no es el oficial (`mibanco.com` o `mibanco.es`).  
- Los bancos nunca envían enlaces en SMS para cancelar operaciones.

### 2.3 Llamadas telefónicas (vishing)

Aquí no hay enlaces. Hay **ingeniería social vocal**.

**Simulación típica en formación:**  
- Un formador llama a un empleado simulando ser “soporte técnico de TI” o “el banco”.  
- Dice: “Hemos detectado actividad sospechosa. Para confirmar tu identidad, dime el código que acabas de recibir por SMS.”  

Ese código es, en realidad, el **2FA** de la víctima. Si lo da, el atacante entra.

**¿Cómo se simula sin dañar?**  
- Se le dice a la persona al inicio: “Esta es una simulación. No des datos reales. Pero responde como si lo fuera. Luego analizamos.”  
- Al final se explica: “El código que te pedí era tu token de acceso. Si lo hubieras dado, habrían tomado tu cuenta.”

**Versión en ataque real:**  
- El atacante llama, suplanta una identidad de confianza (bombero, policía, técnico, empleado de banco).  
- Te piden: instalar un programa de acceso remoto, leer un código, transferir dinero, etc.  
- Usan tono profesional y datos tuyos obtenidos de filtraciones previas.

### 2.4 Redes sociales y perfiles falsos

**Simulación:**  
- Se crea un perfil falso de “amiga de una amiga” o “empresa de inversión”.  
- Se contacta al objetivo con una oferta, un concurso, o un mensaje de “estafa de la herencia”.  
- Se envía un enlace a “confirmar identidad para recibir premio”.

**Versión educativa:**  
- Un formador te envía un mensaje por LinkedIn o Instagram desde un perfil clon.  
- Pregunta: “¿Viste que saliste en esta nota? Mira el enlace.”  
- El enlace lleva a una página de advertencia: “Esto es una simulación. Verifica siempre quién te escribe antes de hacer clic.”

### 2.5 Códigos QR maliciosos (QRishing)

Cada vez más común. El atacante pega un código QR sobre uno legítimo (menú restaurante, cartel de parking, factura).  
Tú escaneas sin mirar → te lleva a un sitio falso que pide datos o descarga malware.

**Simulación formativa:**  
- Se coloca un QR en la sala de descanso de una oficina: “Escanea para ver el menú semanal.”  
- Al escanear, muestra: “Si esto fuera real, tu dispositivo podría estar comprometido. Revisa siempre la URL antes de abrir.”

### 2.6 Phishing dirigido (spear phishing y whaling)

**Spear phishing:** ataque personalizado. Investigan tus intereses, tu empresa, tus contactos.  
**Whaling:** ataque a altos ejecutivos.

**Simulación:**  
- El formador investiga información pública de un empleado (cargo, proyectos, jefe directo).  
- Envía un correo que parece del CEO o del departamento de RRHH: “Hola, adjunto tienes la nómina revisada. Contraseña temporal: tu fecha de nacimiento.”  

Al abrir el adjunto simulado, el empleado ve: “Esto fue un ejercicio de concienciación. No abras documentos ejecutables inesperados, incluso si parecen venir de tu jefe.”

---

## 3. Señales específicas por canal (listas de verificación)

Imprime mentalmente estas listas. Ante cualquier mensaje sospechoso, haz el chequeo.

### 📧 Correo electrónico

- [ ] ¿El remitente muestra el dominio completo? (`@paypal.com` vs `@paypal-soporte.net`)  
- [ ] ¿El asunto genera urgencia o miedo injustificado?  
- [ ] ¿El saludo es genérico (“Estimado usuario”) en lugar de tu nombre real?  
- [ ] ¿Hay errores de ortografía, mayúsculas aleatorias o mala gramática?  
- [ ] ¿El enlace visible es diferente al destino real? (pon el ratón encima sin hacer clic)  
- [ ] ¿Te piden contraseña, DNI, números de tarjeta o código 2FA?  
- [ ] ¿El adjunto es un .exe, .js, .scr, .zip con contraseña o un PDF que pide habilitar macros?  

### 📱 SMS o WhatsApp

- [ ] ¿El número es normal (móvil particular) o un número corto de empresa conocido?  
- [ ] ¿El enlace está acortado (bit.ly, tinyurl, etc.) sin posibilidad de ver destino?  
- [ ] ¿Te piden que “confirmes datos” o “actualices tu cuenta”?  
- [ ] ¿El mensaje viene de un número que no está en tu agenda y no esperas ningún paquete/aviso?  

### 📞 Llamada telefónica

- [ ] ¿Te piden que hagas algo inmediato (instalar software, hacer una transferencia, dar un código)?  
- [ ] ¿La persona te presiona: “si no lo haces ahora, perderás dinero/acceso”?  
- [ ] ¿Te llama un “banco” pero te pide tu PIN, número de tarjeta completo o contraseña?  
- [ ] ¿Te ofrecen un premio o una devolución de impuestos que no solicitaste?  
- [ ] ¿El interlocutor sabe datos públicos tuyos (dirección, nombre completo) y los usa para ganar confianza?  
- [ ] ¿Te piden que no cuelgues mientras haces algo en tu ordenador? (técnica de retención)  

### 📸 Códigos QR

- [ ] ¿Está pegado sobre otro código original? (mira bordes, rasgaduras)  
- [ ] ¿El código QR te lleva a una URL inesperada o demasiado larga?  
- [ ] ¿La página resultante pide credenciales, permisos de ubicación o instalación de app?  

---

## 4. Herramientas gratuitas para verificar sospechas

No confíes en tu curiosidad. Usa estos recursos antes de hacer clic.

| Herramienta | Qué hace | Cómo usarla |
|-------------|----------|--------------|
| **VirusTotal** | Analiza enlaces y archivos con decenas de antivirus | Copia el enlace sospechoso y pégalo en virustotal.com |
| **Urlscan.io** | Muestra captura de pantalla de la página sin que tú la abras | Introduce la URL; verás si es formulario falso |
| **Have I Been Pwned** | Comprueba si tu correo apareció en filtraciones | Introduce tu email; si sale, cámbialo y activa 2FA |
| **Google Safe Browsing** | Testea enlaces reportados como maliciosos | Pega la URL en `transparencyreport.google.com/safe-browsing/search` |
| **Extensión “Phishing Detector”** (navegador) | Alerta sobre dominios sospechosos | Instala solo una de confianza y revisa config |

Para llamadas: si “tu banco” te llama, **cuelga y llama al número oficial del banco** (el de la tarjeta o web). No uses el que te dieron por teléfono.

---

## 5. Simulaciones: cómo se entrenan las empresas (y por qué funcionan)

Las organizaciones responsables contratan servicios como **KnowBe4**, **Proofpoint**, **Lumu** o **Gophish** (open source). Estas plataformas envían correos simulados a los empleados sin aviso previo. Si el empleado hace clic, se le redirige a una página formativa y se registra el incidente.

**Ejemplo de flujo de una simulación profesional:**

1. El administrador elige una plantilla (UPS, Microsoft, recursos humanos, etc.).  
2. Se programa el envío para un día y hora concreta.  
3. Los empleados reciben el correo.  
4. Quienes pinchan ven una pantalla que dice:  
> “Acabas de caer en una simulación de phishing. Las señales que fallaste fueron: [lista]. Aquí te explicamos cómo detectarlo la próxima vez.”  
5. El responsable de seguridad recibe un informe anónimo (o no anónimo si hay política educativa).  
6. Se organizan microformaciones para los departamentos con más clics.

**¿Por qué es ético?**  
Porque no se roban datos, no se instala malware, y el objetivo es **educar sin castigar**. Las mejores empresas incluso celebran a quienes reportan el phishing simulado.

**Tú como particular puedes simularlo en casa** (para ti mismo o tu familia):  
- Pídele a un amigo técnico que te envíe un correo falso con un enlace a una página que él controle y que te muestre “¡trampa!” al hacer clic.  
- Haz el ejercicio de identificar las señales sin miedo a consecuencias reales.

---

## 6. Protocolo paso a paso si caíste

No importa si eres el más precavido. Un mal día, prisa o cansancio puede hacerte fallar. Lo importante es la **respuesta rápida**.

### Paso 1 – Corta la comunicación
- Cierra el navegador, la app de mensajes o cuelga la llamada.  
- Desconecta el dispositivo de internet (wifi y datos móviles) si descargaste algo.

### Paso 2 – Cambia tus contraseñas
- Hazlo desde **otro dispositivo limpio** (no el que usaste para caer).  
- Prioriza: correo electrónico principal → banco → redes sociales → resto.  
- Usa contraseñas diferentes y fuertes (gestor de contraseñas).

### Paso 3 – Activa o renueva 2FA
- Si no tenías doble autenticación, actívala.  
- Si la tenías, revoca sesiones activas (en la configuración de seguridad de cada servicio).

### Paso 4 – Contacta al servicio suplantado
- Si diste datos de tarjeta: llama al banco (número oficial). Solicita cancelación o bloqueo.  
- Si diste credenciales de Google, Microsoft, etc.: entra en “dispositivos conectados” y elimina los desconocidos.  
- Si hiciste clic en un enlace sin dar datos: es suficiente con cambiar contraseñas por si hubiera malware de sesión (token hijacking).

### Paso 5 – Escanea tu dispositivo
- Usa Windows Defender (viene incluido), Malwarebytes Free, o Kaspersky Free.  
- Haz un análisis completo. Si encuentras algo, aísla el equipo y pide ayuda profesional.

### Paso 6 – Denuncia (opcional pero útil)
- En España: Oficina de Seguridad del Internauta (OSI), Policía Nacional (grupo de delitos telemáticos) o Guardia Civil.  
- Guarda capturas de pantalla, encabezados del correo, número del SMS, fecha y hora.  
- Ayudará a otros si el atacante es conocido.

### Paso 7 – No te castigues
El phishing está diseñado por equipos de psicólogos e ingenieros. Cualquiera puede caer. Lo que demuestra inteligencia es **actuar rápido y aprender**.

---

## 7. Ejercicios prácticos para entrenar tu criterio

### Ejercicio 1 – Analiza tu bandeja de spam
Abre tu carpeta de correo no deseado. Elige 5 mensajes. Para cada uno, responde por escrito:

- ¿Qué emoción intenta provocar? (miedo, curiosidad, premio)  
- ¿El remitente tiene un dominio legítimo? (busca una letra cambiada o un guión extra)  
- ¿El enlace (sin hacer clic) lleva a un dominio conocido? Usa `urlscan.io` si quieres verlo con seguridad.  

### Ejercicio 2 – Crea tu propia “regla de oro”
Redacta una frase corta que te digas a ti mismo antes de hacer clic en cualquier enlace de correo/mensaje. Ejemplo:  
> “¿Espero esto? ¿Es oficial? ¿Puedo entrar desde el navegador sin el enlace?”  

Pon esa frase como fondo de pantalla de tu móvil durante una semana.

### Ejercicio 3 – Simulación casera con un amigo
Pídele a una persona de confianza que te envíe un correo o SMS que parezca real pero no lo sea. Tú debes detectar tres señales antes de responder o hacer clic. Él te dará la solución.  

### Ejercicio 4 – Pon a prueba tu banco
Llama al número oficial de tu entidad y pregunta: “¿Me podrían llamar ustedes algún día pidiéndome un código por teléfono?” La respuesta siempre es **NO**. Si algún día “te llama el banco” pidiendo datos, ya sabes: cuelga.

### Ejercicio 5 – Inspecciona los QR de tu barrio
Cuando veas un código QR en un restaurante, parking o cartel, obsérvalo antes de escanear:  
- ¿Tiene pegatinas encima?  
- ¿La dirección URL que aparece al enfocar (sin abrir) es la esperada? (Muchos lectores QR muestran el enlace antes de abrirlo).  

Si tienes dudas, escribe la URL manualmente en el navegador o pregunta al local.

---

## Conclusión del módulo

El phishing no es un problema de inteligencia. Es un problema de **automatización del engaño**. Los atacantes envían miles de millones de intentos porque saben que, con la presión o el descuido, alguien picará.

Tu defensa no es ser paranóico. Es ser **metódico**:

1. **Pausa** antes del clic.  
2. **Verifica** por otro canal.  
3. **Protege** con 2FA y gestor de contraseñas.  
4. **Actúa rápido** si fallaste.  

Y si quieres ir un paso más allá, **aprende a reconocer cómo se simulan estos ataques** en entornos profesionales. Ese conocimiento rompe la magia del engaño.

---
**Condor2026** - **SpectrumSecurity** - Especialista en OSINT, privacidad digital y análisis de amenazas.  
---
*MÓDULO 1 de 24.*
---
