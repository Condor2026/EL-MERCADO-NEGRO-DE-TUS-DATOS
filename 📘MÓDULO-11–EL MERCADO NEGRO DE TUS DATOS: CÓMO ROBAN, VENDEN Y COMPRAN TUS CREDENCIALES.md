# 📘 MÓDULO 11 – EL MERCADO NEGRO DE TUS DATOS: CÓMO ROBAN, VENDEN Y COMPRAN TUS CREDENCIALES

**Condor2026 – Ciberseguridad para humanos**

> *"Tus datos no los roba un hacker genial. Los roba un sistema. Y hoy vas a aprender cómo funciona."*

---

## 📖 Índice de contenidos

1. **La historia de Marta** (y cómo perdió su vida digital en una noche)  
2. **¿Qué son los datos robados?** (credenciales, cookies, huellas, documentos)  
3. **El viaje de una contraseña robada** (desde tu ordenador hasta el comprador final)  
4. **Métodos de robo que usan los cibercriminales**  
- 4.1 Filtraciones masivas (breaches)  
- 4.2 Malware roba-credenciales (Stealers)  
- 4.3 Phishing y suplantación  
- 4.4 Reutilización de contraseñas (el error más común)  
- 4.5 SIM swapping y robo de 2FA  
- 4.6 Ataques a empresas y filtraciones internas  
5. **El mercado negro: dónde y cómo se venden tus datos**  
- 5.1 Foros oscuros (Tor)  
- 5.2 Canales de Telegram y Discord  
- 5.3 Mercados en la web clara disfrazados  
- 5.4 El precio de tus cuentas (tabla de precios real)  
6. **Historias de víctimas** (traumas reales, anonimizados)  
- Caso 1: La streamer a la que vaciaron la cuenta  
- Caso 2: El médico que perdió la confianza de sus pacientes  
- Caso 3: La adolescente extorsionada con sus fotos  
- Caso 4: El autónomo que quebró por un robo de credenciales  
7. **Cómo saber si ya estás en el mercado negro**  
- Herramientas gratuitas  
- Búsqueda manual avanzada  
- Señales de que tu cuenta está circulando  
8. **Acciones concretas para protegerte hoy** (sin paranoia)  
9. **Glosario para no perderse**  
10. **Ejercicios prácticos**  
11. **Conclusión y recursos**

---

## 1. La historia de Marta (y cómo perdió su vida digital en una noche)

**Nombre real:** Marta G., 34 años, arquitecta, madre de dos niños.  
**Perfil digital:** Usaba la misma contraseña desde la universidad. No sabía qué era el 2FA. Pensaba que el "hackeo" solo pasaba en las películas.

**El martes 12 de marzo, Marta hizo tres cosas que parecían inocentes:**

- Abrió un correo de "su banco" que decía: *"Su tarjeta ha sido bloqueada por un intento de fraude. Confirme sus datos aquí."* (era phishing).  
- Tenía la misma contraseña (`Marta_1989`) en 12 cuentas diferentes.  
- No tenía activada la verificación en dos pasos.

**Lo que pasó esa noche (mientras ella dormía):**

1. Un cibercriminal compró su contraseña en un mercado negro por **2,35 dólares** (la contraseña venía de una filtración de LinkedIn de 2016 que Marta nunca supo).  
2. Con esa contraseña, el criminal entró a su correo de Gmail (la contraseña funcionaba).  
3. Desde el correo, reinició la contraseña de su cuenta de Amazon, su cuenta de Instagram, y su cuenta de Wallapop.  
4. En Amazon, compró 1.800€ en tarjetas regalo (fáciles de convertir en criptomonedas).  
5. En Wallapop, publicó un iPhone 15 Pro falso (con fotos de otro anuncio) por 400€. Recibió 3 pagos por Bizum (personas reales que perdieron su dinero).  
6. En Instagram, cambió la foto por una de una modelo, cambió el nombre, y empezó a seguir a sus contactos. Una semana después, contactó a su mejor amiga haciéndose pasar por Marta: *"Cariño, estoy de viaje y me han robado la cartera. ¿Me puedes hacer un Bizum urgente?"*. La amiga le envió 300€.

**El despertar de Marta:**

- A las 7 AM, su teléfono explotó: mensajes del banco, de Amazon, de su amiga, de clientes que habían visto publicaciones raras en su Instagram.  
- Su cuenta bancaria: -1.800€ (más descubierto).  
- Su cuenta de Amazon: bloqueada por actividad sospechosa (pero el daño estaba hecho).  
- Su reputación: una clienta le escribió: *"Marta, ¿por qué me estás pidiendo dinero? Pensé que éramos amigas"*.  
- Su salud mental: crisis de ansiedad, insomnio, dos semanas de baja laboral.

**Lo que Marta no sabía:** Su contraseña llevaba **7 años circulando en el mercado negro**. Solo faltaba que alguien la comprara y la usara.

---

## 2. ¿Qué son los datos robados? (credenciales, cookies, huellas, documentos)

No solo hablamos de contraseñas. Los cibercriminales roban y venden:

| Tipo de dato | Ejemplo | Para qué sirve | Precio aprox (en negro) |
|--------------|---------|----------------|--------------------------|
| **Credenciales de acceso** | `usuario: Marta_1989` | Entrar a tu correo, redes, bancos | 0,50€ – 5€ |
| **Combolists** | `email:contraseña` en listados masivos | Ataques automáticos por relleno de credenciales | 10€ – 100€ (millones de registros) |
| **Cookies de sesión** | Archivos que guardan que ya has iniciado sesión | Entrar a tu cuenta sin necesidad de contraseña | 2€ – 20€ (depende del servicio) |
| **Datos bancarios** | Número de tarjeta, fecha, CVV | Compras online, clonación de tarjetas | 5€ – 50€ (según saldo) |
| **Documentos escaneados** | DNI, pasaporte, nóminas | Suplantación de identidad, apertura de cuentas falsas | 10€ – 100€ |
| **Cuentas completas** | Correo + contraseña + 2FA (si lo han robado) | Acceso total para estafas, extorsión, lavado | 50€ – 500€ |
| **Accesos remotos** | VPN, RDP, escritorios remotos | Usar tu ordenador para cometer otros delitos | 3€ – 50€ |
| **Perfiles completos** | Nombre, DNI, dirección, teléfono, historial crediticio | Robo de identidad total (abrir líneas de crédito) | 500€ – 2000€ |

**Dato escalofriante:** Una cuenta de Netflix robada cuesta 1€. Una cuenta de Spotify, 0,50€. Tu vida digital entera (correo + contraseña + teléfono + DNI) puede costar menos de 20€.

---

## 3. El viaje de una contraseña robada (desde tu ordenador hasta el comprador final)

Vamos a seguir el rastro de una contraseña concreta: `Marta_1989`.

### Etapa 1 – La filtración inicial (LinkedIn, 2016)
Marta creó su cuenta de LinkedIn en 2016. Usó su correo personal y la contraseña `Marta_1989`. Un día, los servidores de LinkedIn fueron hackeados y se filtraron 164 millones de cuentas, incluyendo la de Marta. En ese momento, ella no se enteró.

### Etapa 2 – El procesamiento de los datos
Los atacantes agrupan los correos y contraseñas en archivos llamados *combolists*. Los limpian, les dan formato, y los comprimen. Luego, los distribuyen en foros underground.

### Etapa 3 – La publicación en un foro oscuro
Un usuario de un foro en Tor publica: *"LinkedIn 2016 – 164M combos – 0,001 BTC"* (unos 50€ en ese momento). Varios compradores adquieren el archivo.

### Etapa 4 – El relleno de credenciales (credential stuffing)
Uno de los compradores tiene un programa automático que toma la lista de correos y contraseñas de LinkedIn y las prueba en otros servicios: Gmail, Amazon, Netflix, PayPal, etc.

Cuando el programa prueba `Marta_1989` en Gmail… ¡funciona! Porque Marta usó la misma contraseña.

### Etapa 5 – La verificación humana
El programa marca la cuenta de Marta como "válida". Un operador humano (en Pakistán, Rusia o Brasil) entra manualmente, comprueba que hay fotos personales, documentos, y contactos. Eso sube el precio.

### Etapa 6 – La venta en un canal de Telegram
El operador publica en un canal privado de Telegram: *"Gmail full access, 5€, incluye fotos y contactos"*. Un comprador paga 5€ en criptomoneda.

### Etapa 7 – El uso final
El comprador (puede ser un estafador común o un grupo organizado) vacía su cuenta de Amazon, suplanta su identidad con sus contactos, y vende sus datos personales a otro estafador especializado en suplantación.

**Cronología total:** 7 años desde la filtración hasta el robo. Marta no supo nada hasta que fue demasiado tarde.

---

## 4. Métodos de robo que usan los cibercriminales

### 4.1 Filtraciones masivas (breaches)

**Qué es:** Una empresa sufre un hackeo y millones de cuentas se publican en internet.

**Ejemplos reales:** LinkedIn (2016, 164M), Facebook (2019, 530M), Ticketmaster (2024, 560M), y cientos más.

**Por qué es peligroso:** Tú no has hecho nada malo. La empresa falló. Pero tú pagas las consecuencias si reutilizas contraseñas.

**Qué hacer:** Usar contraseñas únicas por servicio y consultar Have I Been Pwned.

### 4.2 Malware roba-credenciales (Stealers)

**Qué es:** Un programa malicioso que se instala en tu ordenador sin que lo sepas y roba todas tus contraseñas guardadas en el navegador.

**Cómo llega:** Lo descargas sin saber (crack de un programa, adjunto de correo, enlace falso).

**Qué roba:** Contraseñas de Chrome/Firefox, cookies, archivos, wallets de criptomonedas.

**Ejemplo real (simulado):** Una persona descarga un "generador de diamantes para Free Fire" de un sitio pirata. El archivo `setup.exe` instala el juego… y también un stealer. En 10 minutos, el criminal tiene todas sus contraseñas.

### 4.3 Phishing y suplantación

**Qué es:** Te envían un correo, SMS o WhatsApp haciéndose pasar por una empresa legítima y te piden que introduzcas tu contraseña en una web falsa.

**Ejemplo real (simulado):** Recibes un SMS: *"Correos: tu paquete no puede entregarse por falta de datos. Actualiza aquí: correos-seguro.com"*. Entras, pones tu nombre y dirección… y de paso, tu tarjeta de crédito para pagar "gastos de aduana".

### 4.4 Reutilización de contraseñas (el error más común)

**Qué es:** Usas la misma contraseña en 5, 10 o 20 sitios.

**Por qué es letal:** Basta con que uno de esos sitios sea hackeado (o tenga un empleado malintencionado) para que el criminal tenga acceso a todos los demás.

**El caso típico:** Un foro de deportes es hackeado. Tu contraseña de ese foro es la misma que la de tu correo. El criminal prueba y entra a tu Gmail. Desde allí, resetea la contraseña de tu banco.

### 4.5 SIM swapping y robo de 2FA

**Qué es:** El criminal llama a tu compañía de móvil, se hace pasar por ti, y pide una nueva tarjeta SIM con tu número. Cuando la activa, recibe todos tus SMS, incluidos los códigos de 2FA.

**Perfiles de riesgo:** Personas con mucha información pública (periodistas, activistas, influencers, criptoinversores).

**Ejemplo real (simulado):** Un criptoinversor tiene 2FA por SMS en su cuenta de Binance. Un criminal encuentra su número de teléfono en una filtración. Llama a Vodafone, suplanta su identidad, y pide un duplicado de la SIM. En 1 hora, el criminal retira todas sus criptomonedas.

### 4.6 Ataques a empresas y filtraciones internas

**Qué es:** No solo hackean. A veces un empleado descontento o sobornado filtra datos de clientes. O un ordenador de la empresa se infecta con malware y roba la base de datos.

**Ejemplo real:** Una clínica privada tiene los datos de miles de pacientes (nombre, DNI, dirección, historial médico). Un empleado vende esa base de datos por 5.000€ en un foro oscuro. Los compradores la usan para suplantar identidades y pedir préstamos a nombre de los pacientes.

---

## 5. El mercado negro: dónde y cómo se venden tus datos

### 5.1 Foros oscuros (Tor)

**Cómo acceden los criminales:** Usan el navegador Tor (a veces con VPN) y acceden a foros como BreachForums, Exploit, o versiones antiguas de RaidForums (cerrado por el FBI).

**Qué se vende:** Bases de datos enteras, combolists, herramientas para hackear, tutoriales.

**Lenguaje:** Inglés, ruso, chino. A veces español.

**Moneda:** Bitcoin (BTC), Monero (XMR), o criptomonedas privadas.

**Ejemplo real (anonimizado):** Un vendedor llamado `DarkVendor` publica: *"Combolist +100k hotmail valid, 0.01 BTC"*. El comprador paga, descarga un archivo .txt con 100.000 correos y contraseñas, y empieza a probarlos en otros servicios.

### 5.2 Canales de Telegram y Discord

**Por qué son populares:** Son más fáciles de usar que Tor y menos vigilados que los foros públicos.

**Cómo se organizan:** Canales privados con invitación. El administrador publica precios y capturas de pantalla de las cuentas.

**Ejemplo real (simulado):** Un canal llamado `Ventas Premium` tiene 15.000 miembros. El administrador publica: *"PayPal verificados con saldo, desde 50€. Preguntar stock"*. Los compradores pagan, reciben las credenciales, y vacían las cuentas.

**Riesgo para el criminal:** Telegram cierra canales de estafas con frecuencia, pero abren otros al día siguiente.

### 5.3 Mercados en la web clara disfrazados

**Qué son:** Páginas web que parecen legítimas (venden "servicios SEO", "generadores de tráfico", o "cuentas verificadas") pero en realidad venden datos robados.

**Ejemplo real:** Una web llamada `seogrowthtools[.]com` vende supuestos "bots de Instagram". Pero cuando pagas (con tarjeta o cripto), te dan un archivo con cuentas de Instagram robadas.

### 5.4 El precio de tus cuentas (tabla de precios real, basada en capturas de foros)

| Servicio | Precio en negro (USD) |
|----------|----------------------|
| Netflix con 1 mes | 1,00 – 2,00 |
| Spotify Premium | 0,50 – 1,00 |
| Disney+ | 1,50 – 3,00 |
| Amazon Prime | 1,00 – 2,00 |
| Cuenta de Google (Gmail) | 2,00 – 10,00 (depende de antigüedad) |
| Facebook / Instagram | 1,00 – 5,00 |
| PayPal verificado | 20,00 – 200,00 (depende del saldo) |
| Cuenta bancaria (con login) | 50,00 – 500,00 |
| Tarjeta de crédito (con CVV) | 5,00 – 50,00 |
| Cuenta de empresa (Amazon Seller, etc.) | 100,00 – 1.000,00 |
| DNI escaneado + selfie | 10,00 – 50,00 |

**Terrorífico pero cierto:** Tu cuenta de Netflix cuesta menos que un café en Madrid. Tu cuenta del banco cuesta menos que una cena para dos.

---

## 6. Historias de víctimas (traumas reales, anonimizados)

### Caso 1 – La streamer que perdió su comunidad

**Perfil:** Sara, 26 años, streamer de Twitch con 50.000 seguidores.  
**Cómo ocurrió:** Un espectador le envió un archivo .exe disfrazado de "mod para el juego". Sara lo ejecutó. Era un stealer. El criminal robó sus cookies de Twitch, su cuenta de Discord, y su correo electrónico.

**Qué perdió:**  
- Su canal de Twitch fue cambiado a un nombre chino y usado para transmitir contenido ilegal. Twitch lo cerró permanentemente. Perdió 5 años de trabajo.  
- Su Discord fue usado para estafar a sus moderadores (les pidió "dinero para una operación urgente"). Dos moderadores le enviaron 300€ cada uno.  
- Su cuenta de PayPal, vinculada al correo, fue vaciada (1.200€).  
- El criminal publicó fotos íntimas de Sara (robadas de su iCloud) en foros de extorsión.

**Trauma:** Sara tuvo que mudarse de ciudad. Dejó de hacer streaming durante un año. Perdió su principal fuente de ingresos y su salud mental. Hoy tiene miedo de abrir cualquier archivo, incluso los de sus amigos.

**Qué aprendió:** A usar un gestor de contraseñas, 2FA con app (no SMS), y un ordenador separado solo para streaming.

---

### Caso 2 – El médico que perdió la confianza de sus pacientes

**Perfil:** Dr. Carlos, 52 años, cirujano en una clínica privada.  
**Cómo ocurrió:** La clínica sufrió un hackeo masivo. Los atacantes filtraron 10.000 registros de pacientes: nombres, DNI, teléfonos, direcciones, diagnósticos, número de tarjeta sanitaria. Carlos no hizo nada malo. Pero sus datos personales (incluido su propio historial médico) estaban en el lote.

**Qué perdió:**  
- Un paciente descubrió que sus datos estaban en un foro y demandó a la clínica. La clínica culpó a los médicos de "seguridad laxa". Carlos fue despedido indirectamente.  
- Su número de teléfono fue publicado. Recibió llamadas de extorsión: "Dime el diagnóstico de la paciente X o publicamos tus fotos íntimas" (no tenían fotos, pero él no lo sabía).  
- Su reputación: un paciente le dejó una reseña de 1 estrella en Google diciendo: "Este médico vendió mis datos". Era falso, pero nadie lo sabe.

**Trauma:** Carlos ahora tiene ansiedad al abrir su correo. Ha gastado 3.000€ en abogados para limpiar su nombre. Ha perdido dos ofertas de trabajo porque su nombre aparece en foros de filtraciones.

**Qué aprendió:** Nunca dio permiso para que la clínica almacenara sus datos personales (pero lo hicieron igual). Ahora usa un servicio de monitorización de identidad.

---

### Caso 3 – La adolescente extorsionada con sus fotos

**Perfil:** Lucía, 15 años, estudiante de secundaria.  
**Cómo ocurrió:** Un chico (o eso creía) le escribió por Instagram. Era atento, guapo, y le gustaban las mismas series. Hablaron durante 3 semanas. Él le pidió fotos íntimas "para demostrar que confiaba en él". Lucía, con 15 años y confundiendo atención con cariño, le envió dos fotos.

**El giro:** Él no era un chico de 16 años. Era un grupo de extorsión en otro país. Le escribieron: *"Tus fotos están en un grupo de Telegram de pago. Si no nos das 500€ en tarjetas regalo en 24 horas, las enviamos a tus compañeros de clase, a tus padres, y a tu instituto".*

**Qué perdió:**  
- 500€ de la tarjeta de su abuela (que usó sin permiso).  
- Su salud mental: no durmió durante 3 días. Dejó de ir a clase. Se aisló de sus amigas.  
- Casi pierde su vida: tuvo pensamientos de autolesión. Su madre la encontró llorando en su cuarto y la llevó al psicólogo.

**Trauma:** Lucía cambió de instituto. Borró todas sus redes sociales. Aún hoy, 3 años después, tiene miedo de recibir mensajes de desconocidos.

**Qué aprendió (y tú también):** Nadie que te pide fotos íntimas sin conocerte en persona es tu amigo. Corta la comunicación, guarda pruebas, y habla con un adulto de confianza inmediatamente.

---

### Caso 4 – El autónomo que quebró por un robo de credenciales

**Perfil:** Jorge, 41 años, diseñador gráfico autónomo.  
**Cómo ocurrió:** Jorge usaba la misma contraseña en su correo, su Dropbox (donde guardaba los trabajos de sus clientes), y su cuenta de PayPal. Un día, su correo apareció en una filtración de un foro de videojuegos (él ni siquiera jugaba, pero se había registrado hacía años).

**Qué perdió:**  
- Su PayPal: 4.500€ (sus ahorros). El banco no le devolvió el dinero porque la transferencia fue hecha desde "su dispositivo" (realmente era el criminal, pero con sus credenciales).  
- Su Dropbox: el criminal borró todos los archivos de sus clientes (proyectos de 6 meses). Jorge no tenía copia de seguridad local.  
- Su reputación: dos clientes le demandaron por pérdida de datos. Perdió 8.000€ en indemnizaciones.  
- Su negocio: tuvo que cerrar. Ahora trabaja en un supermercado.

**Trauma:** Jorge tuvo depresión clínica. Su familia casi pierde su casa. Hoy es un activista de la ciberseguridad y da charlas gratuitas en asociaciones de autónomos.

**Qué aprendió:** Copias de seguridad OFFLINE. Gestor de contraseñas. 2FA en todo. Y nunca mezclar cuentas personales con profesionales.

---

## 7. Cómo saber si ya estás en el mercado negro

No esperes a ser la próxima Marta, Sara, Carlos, Lucía o Jorge. Actúa hoy.

### 7.1 Herramientas gratuitas (para empezar)

| Herramienta | Qué hace | Cómo usarla |
|-------------|----------|-------------|
| **Have I Been Pwned** | Te dice en qué filtraciones aparece tu email | Pega tu email, te devuelve una lista de breaches. |
| **Firefox Monitor** | Lo mismo, de Mozilla | monitor.firefox.com |
| **Dehashed** (búsqueda limitada gratis) | Busca tu email o nombre en filtraciones | Búsqueda básica gratuita. |
| **Google Password Checkup** | Analiza tus contraseñas guardadas en Google | passwords.google.com → "Comprobar contraseñas" |
| **F-Secure Identity Theft Checker** | Búsqueda limitada de emails | oferta.f-secure.com/es-es/identity-theft-checker |

### 7.2 Búsqueda manual avanzada

Si quieres ir más allá (sin pagar):

1. Busca tu email en Google con comillas: `"micorreo@ejemplo.com"`.  
2. Busca tu nombre de usuario habitual en foros como Forocoches, Reddit, Telegram.  
3. Busca tu nombre completo + "filtración" o "breach".  
4. Si te atreves (con precaución, usa una máquina virtual), busca en Telegram canales de "combolist" o "leak" y busca tu email. No descargues nada, solo mira.

### 7.3 Señales de que tu cuenta está circulando

- Recibes correos de restablecimiento de contraseña que no pediste.  
- Te llegan códigos SMS de verificación sin que tú hayas iniciado sesión.  
- Tus amigos reciben mensajes raros desde tu cuenta.  
- Aparecen dispositivos desconocidos en tu "actividad reciente" de Google o Facebook.  
- Te llaman de "tu banco" (falso) con demasiada frecuencia.

Si ves una de estas, actúa YA (ver sección 8).

---

## 8. Acciones concretas para protegerte hoy (sin paranoia)

No necesitas ser técnico. Necesitas hacer estas 7 cosas HOY.

### ✅ Acción 1 – Cambia tu contraseña del correo (la más importante)
- Usa una frase larga y fácil de recordar: `MiPerroSeLlamaLucas!23`  
- No uses palabras de diccionario solo (pero las frases son seguras y fáciles).  
- **No reutilices esta contraseña en ningún otro servicio.**

### ✅ Acción 2 – Activa 2FA en tu correo y banco
- Usa una app como Google Authenticator, Authy, o Microsoft Authenticator.  
- **No uses SMS como 2FA si puedes evitarlo** (SIM swapping existe).  
- Guarda los códigos de recuperación en un papel (no en el ordenador).

### ✅ Acción 3 – Instala un gestor de contraseñas
- **Recomendado:** Bitwarden (gratis, código abierto).  
- Cambia las contraseñas de tus 5 servicios más importantes (banca, redes, Amazon, etc.) por contraseñas generadas aleatoriamente (20 caracteres).  
- Sincroniza en el móvil y ordenador.

### ✅ Acción 4 – Comprueba si tu email está en filtraciones
- Ve a haveibeenpwned.com. Si aparece, cambia las contraseñas de esos servicios (aunque no los uses, porque el criminal puede probar esa misma contraseña en otros sitios).

### ✅ Acción 5 – Revisa qué aplicaciones tienen acceso a tu cuenta de Google
- Ve a myaccount.google.com/permissions. Elimina las que no reconozcas o no uses.

### ✅ Acción 6 – Activa las alertas de tu banco
- Configura tu app bancaria para que te envíe un SMS o notificación por cualquier compra superior a 10€. Así sabrás al instante si hay fraude.

### ✅ Acción 7 – Crea un correo basura para registros
- Usa SimpleLogin o Firefox Relay para generar alias de correo. Así tu correo real nunca aparece en filtraciones de foros o tiendas poco fiables.

---

## 9. Glosario para no perderse

| Término | Significado |
|---------|-------------|
| **Breach** | Filtración de datos de una empresa (hackeo o error interno). |
| **Combolist** | Listado de correos y contraseñas (ej: `usuario1:pass123, usuario2:pass456`). |
| **Credential Stuffing** | Ataque automático que prueba credenciales filtradas en otros servicios. |
| **Stealer** | Malware que roba contraseñas guardadas en el navegador. |
| **2FA (Two Factor Authentication)** | Segundo factor de autenticación (código que cambia cada 30 segundos). |
| **SIM Swapping** | Engaño a la operadora para duplicar tu tarjeta SIM y recibir tus SMS. |
| **Phishing** | Correo, SMS o web falsa que suplanta a una entidad legítima. |
| **Marketplace (ilegal)** | Lugar donde se venden datos robados (foros Tor, Telegram, Discord). |
| **Fullz** (jerga inglesa) | Perfil completo con nombre, DNI, dirección, teléfono, fecha de nacimiento. |

---

## 10. Ejercicios prácticos

### Ejercicio 1 – Investiga tu propio email
Ve a haveibeenpwned.com. Introduce tu email. Si aparece en alguna filtración, escribe cuál fue y en qué año. Luego cambia esa contraseña (aunque el servicio fuera antiguo).

### Ejercicio 2 – El test de la contraseña única
Haz una lista de 10 servicios online que uses. ¿Cuántas contraseñas diferentes tienes? Si son menos de 5, estás en riesgo. Instala Bitwarden y empieza a cambiarlas.

### Ejercicio 3 – Activa 2FA en tu correo
Dedica 10 minutos a activar la verificación en dos pasos de tu cuenta de Google o Outlook. Guarda los códigos de recuperación en un papel físico.

### Ejercicio 4 – Simula un robo de cuenta
Pídele a un amigo que te envíe un enlace falso (simulado) por WhatsApp. Tú no debes hacer clic. Aplica la regla: "¿Espero este mensaje? ¿El remitente es quien dice ser? ¿Me piden algo urgente?". Si dudas, no haces clic.

### Ejercicio 5 – Charla con tu familia
Explícales a tus padres o hijos qué es una combolist y por qué no deben reutilizar contraseñas. Usa la historia de Marta como ejemplo (sin asustarlos, solo concienciando).

---

## 11. Conclusión y recursos

**Resumen ejecutivo:**

- Tus datos llevan años en el mercado negro, aunque no lo sepas.  
- Los criminales compran tus credenciales por menos de 5€ y luego las usan para robarte, extorsionarte o suplantarte.  
- La reutilización de contraseñas es el error que más cuesta.  
- El 2FA y un gestor de contraseñas son tus dos mejores amigos.  
- Revisar Have I Been Pwned debería ser tan rutinario como mirar el correo.

**Recursos gratuitos:**

- **Have I Been Pwned:** haveibeenpwned.com  
- **Bitwarden (gestor de contraseñas):** bitwarden.com  
- **Google 2FA (Authenticator):** play.google.com/store/apps/details?id=com.google.android.apps.authenticator2  
- **SimpleLogin (alias de correo):** simplelogin.io  
- **INCIBE – Guía de robo de identidad:** incibe.es  

**Si ya eres víctima:**

1. Cambia todas tus contraseñas desde un dispositivo limpio.  
2. Activa 2FA en todo.  
3. Contacta con tu banco si hubo movimientos raros.  
4. Denuncia en la policía (guardando capturas de pantalla).  
5. No te culpes. El sistema está diseñado para que falles. Ahora estás más preparado.

---
**Condor2026** – **SpectrumSecurity**
---
*MÓDULO 11 de 24.*
---
