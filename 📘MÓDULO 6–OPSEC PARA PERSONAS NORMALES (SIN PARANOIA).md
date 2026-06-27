# 📘 MÓDULO 6 – OPSEC PARA PERSONAS NORMALES (SIN PARANOIA)

**Condor2026 – Análisis de amenazas digitales**

> *“No necesitas vivir con miedo. Solo necesitas hábitos conscientes.”*

---

## Índice

1. ¿Qué es la OpSec y por qué no es solo para espías?  
2. El equilibrio: seguridad sin paranoia  
3. Amenazas reales según tu perfil  
- Persona particular / autónomo  
- Activista / periodista  
- Adolescente / joven  
- Adulto mayor  
- Pequeña empresa  
4. OpSec para dispositivos (ordenador, móvil, tablet)  
- Actualizaciones y parches  
- Configuración de cuentas de usuario  
- Cifrado de disco  
- Copias de seguridad (regla 3-2-1 adaptada)  
5. OpSec para redes y conexiones  
- Wi-Fi doméstico (lo básico)  
- Redes públicas (qué no hacer)  
- VPN: ¿cuándo y por qué? (sin vender marcas)  
- DNS y sus riesgos  
6. OpSec para comunicaciones  
- Correo electrónico seguro (sin exagerar)  
- Mensajería: WhatsApp, Telegram, Signal  
- Llamadas y videollamadas  
7. OpSec para navegación  
- Navegadores y extensiones esenciales  
- Gestores de contraseñas (sí, pero bien usados)  
- Borrado de historial y cookies (cuándo tiene sentido)  
8. OpSec para identidades online  
- Uso de alias y correos desechables  
- Números virtuales  
- Compartimentación (separar mundos)  
9. Simulaciones formativas: errores comunes que todos cometemos  
- Ejemplo 1: El Wi-Fi del aeropuerto  
- Ejemplo 2: La contraseña reutilizada  
- Ejemplo 3: El “modo incógnito” engañoso  
10. Checklist de OpSec diaria, semanal y mensual  
11. Herramientas gratuitas recomendadas  
12. Ejercicios prácticos (sin volverte loco)  
13. Conclusión y recursos  

---

## 1. ¿Qué es la OpSec y por qué no es solo para espías?

**OpSec** (Operational Security) es el conjunto de hábitos y medidas para proteger información sensible y evitar que un adversario (atacante, acosador, competidor, etc.) pueda recopilar datos sobre ti o tus actividades.

Originalmente era un concepto militar. Hoy es para todos.

Pero ojo: OpSec no es vivir con miedo, no es esconderse, no es dejar de usar internet. Es **tomar decisiones informadas** sobre qué riesgos aceptas y cuáles mitigas.

**Ejemplo de OpSec bien entendida:**  
- Usas una VPN en el café de la esquina (riesgo medio) pero no en tu casa (riesgo bajo).  
- Tienes copias de seguridad automáticas (por si ransomware).  
- Usas un gestor de contraseñas (porque reutilizar es peligroso).  
- No publicas tu ubicación en tiempo real (por si alguien sigue tus pasos).  

No es paranoia. Es **higiene digital**, como lavarse las manos.

---

## 2. El equilibrio: seguridad sin paranoia

La paranoia es miedo irracional y desproporcionado. La OpSec es **racional y proporcionada**.

Pregúntate siempre:  
- **¿Quién es mi adversario?** (¿un estafador genérico? ¿un acosador concreto? ¿una agencia gubernamental?)  
- **¿Qué valoro proteger?** (¿mis fotos? ¿mis contraseñas bancarias? ¿mi ubicación?)  
- **¿Qué probabilidad hay de que me ataquen?** (si eres una persona normal, los ataques masivos son más probables que los dirigidos).  

Según las respuestas, ajustas la intensidad.

**Ejemplo de sobreprotección (paranoia):**  
- Usar tres VPN en cascada, navegar solo con Tails, borrar el historial cada 5 minutos, tener 12 contraseñas diferentes de 30 caracteres sin gestor. Eso es insostenible.

**Ejemplo de seguridad razonable:**  
- Gestor de contraseñas + 2FA + actualizaciones automáticas + copias de seguridad + cuidado con enlaces sospechosos.

Con eso ya evitas el 95% de las amenazas comunes.

---

## 3. Amenazas reales según tu perfil

No todos necesitan el mismo nivel de OpSec.

### Persona particular / autónomo

**Amenazas más probables:**  
- Phishing bancario o de servicios.  
- Robo de cuenta de redes sociales.  
- Estafas de soporte técnico.  
- Pérdida de datos por no tener backups.  

**OpSec suficiente:**  
- Gestor de contraseñas + 2FA.  
- Copias de seguridad automáticas (nube + disco externo).  
- Cuidado con enlaces y archivos adjuntos.  
- No publicar dirección o teléfono en redes.

### Activista / periodista / perfil de riesgo

**Amenazas adicionales:**  
- Vigilancia dirigida (gobierno, grupos extremistas).  
- Doxxing (publicación de datos personales).  
- Malware dirigido (spear phishing).  
- Intercepción de comunicaciones.  

**OpSec necesaria:**  
- Todo lo anterior, más:  
- Cifrado de disco completo.  
- Mensajería con cifrado de extremo a extremo (Signal).  
- Uso de VPN en redes públicas (o Tor para alta sensibilidad).  
- Compartimentación estricta (alias, correos separados, dispositivos distintos).  
- Formación en ingeniería social.

### Adolescente / joven

**Amenazas más probables:**  
- Acoso escolar digital.  
- Suplantación de identidad.  
- Grooming (adultos haciéndose pasar por menores).  
- Extorsión con fotos íntimas.  

**OpSec suficiente:**  
- Cuentas privadas en redes.  
- No aceptar desconocidos.  
- No compartir ubicación en tiempo real.  
- Hablar con un adulto de confianza si algo les preocupa.  
- Activar 2FA (muchos jóvenes no lo hacen).

### Adulto mayor

**Amenazas más probables:**  
- Estafas de soporte técnico (llamadas falsas de Microsoft, etc.).  
- Phishing bancario.  
- Falsos premios o herencias.  
- Suplantación de nietos pidiendo dinero.  

**OpSec suficiente:**  
- Usar llamada de verificación (colgar y llamar al familiar).  
- No instalar programas que pidan por teléfono.  
- Tener un familiar de confianza como “segundo factor humano” (consultar antes de hacer transferencias).  
- Bloquear números desconocidos en el móvil.

### Pequeña empresa / autónomo avanzado

**Amenazas más probables:**  
- Spear phishing a empleados.  
- Ransomware.  
- Robo de credenciales de clientes.  
- Competencia desleal con OSINT.  

**OpSec suficiente:**  
- Formación básica para todo el equipo.  
- Copias de seguridad fuera de la oficina.  
- Segmentación de redes (WiFi para clientes separado del interno).  
- Política de contraseñas y 2FA obligatorio.  
- Revisión de exposición pública de datos de la empresa.

---

## 4. OpSec para dispositivos

### Actualizaciones y parches

- Activa **actualizaciones automáticas** para sistema operativo, navegador y apps críticas.  
- No pospongas los reinicios por semanas.  
- Los parches de seguridad corrigen vulnerabilidades conocidas.

### Configuración de cuentas de usuario

- Usa una **cuenta sin privilegios de administrador** para el día a día.  
- Crea una cuenta admin separada que solo uses para instalar software.  
- En móvil, no hagas jailbreak o root (rompe el modelo de seguridad).

### Cifrado de disco

- **Windows:** BitLocker (si tienes Pro) o VeraCrypt (gratis).  
- **macOS:** FileVault (actívalo en Ajustes > Seguridad).  
- **Linux:** LUKS.  
- **Móvil:** El cifrado viene por defecto en Android e iOS (solo asegúrate de tener código de desbloqueo).

¿Por qué? Si te roban el portátil, sin cifrado pueden leer todos tus archivos.

### Copias de seguridad (regla 3-2-1 adaptada)

- **3** copias de tus datos importantes.  
- **2** formatos diferentes (disco duro externo + nube).  
- **1** copia fuera de tu casa (nube o disco en casa de un familiar).

Para particulares:  
- Usa **Backblaze** (pago) o **Google Drive / OneDrive** con versiónado.  
- Cada mes, conecta un disco externo y haz copia manual.  

Para activistas: no uses nubes de empresas que cooperan con gobiernos (usa Cryptomator + nube o discos cifrados).

---

## 5. OpSec para redes y conexiones

### Wi-Fi doméstico (lo básico)

- Cambia la contraseña por defecto del router (la que viene en la pegatina).  
- Usa **WPA2 o WPA3** (no WEP, no abierto).  
- Desactiva WPS (es vulnerable).  
- Si puedes, cambia el SSID (nombre de red) para que no sea el modelo del router.  
- No es necesario ocultar el SSID (da falsa seguridad y complica la conexión).

### Redes públicas (qué no hacer)

- **Nunca** hagas operaciones bancarias o compras con tarjeta en una red pública (café, aeropuerto, hotel).  
- **No** asumas que la red del hotel es segura.  
- Si necesitas usarlas, usa **VPN** (ver siguiente punto).  
- Desactiva el “compartir archivos” y la “detección de redes” en Windows cuando estés en público.  
- Olvida la red después de usarla.

### VPN: ¿cuándo y por qué? (sin vender marcas)

**¿Qué hace una VPN?** Cifra el tráfico entre tu dispositivo y el servidor VPN, ocultando tu IP real al destino final (web, servicio).

**¿Cuándo tiene sentido?**  
- Redes Wi-Fi públicas (café, aeropuerto, hotel).  
- Para ocultar tu actividad a tu proveedor de internet (si no confías en él).  
- Para evitar bloqueos geográficos (contenido de otros países).  

**¿Cuándo NO es necesaria?**  
- En tu casa (si confías en tu router y proveedor, el tráfico ya va cifrado por HTTPS en la mayoría de webs).  
- Para “ser anónimo” (la VPN sola no te hace anónimo; necesitas Tor y otros cuidados).  

**Recomendación para principiantes:**  
- Usa una VPN de pago y reputación (Mullvad, ProtonVPN, IVPN – sin afiliación).  
- Evita VPNs gratis (venden tus datos o tienen malware).  
- No creas que la VPN te protege del phishing (eso es aparte).

### DNS y sus riesgos

El DNS traduce nombres a IPs. Por defecto usas el de tu proveedor de internet. Pueden ver qué webs visitas (aunque no el contenido si es HTTPS).

Puedes cambiarlo a **DNS cifrado** (Cloudflare 1.1.1.1, Quad9, NextDNS) para más privacidad. En móvil, hay apps como **1.1.1.1** de Cloudflare (gratis, fácil).

---

## 6. OpSec para comunicaciones

### Correo electrónico seguro (sin exagerar)

- Usa un proveedor con buen filtro antiphishing (Gmail, Outlook, ProtonMail).  
- Activa 2FA en el correo (es la puerta de entrada a todas tus otras cuentas).  
- No abras adjuntos sospechosos.  
- Para temas sensibles, usa **correos temporales o alias** (SimpleLogin, Firefox Relay).  
- Cifrado de extremo a extremo (PGP) solo si eres periodista o activista de alto riesgo. Para personas normales, es excesivo.

### Mensajería: WhatsApp, Telegram, Signal

| App | Cifrado por defecto | Metadatos protegidos | Recomendación |
|-----|---------------------|----------------------|----------------|
| **Signal** | Sí (E2EE) | Muy pocos | Primera opción para conversaciones sensibles. |
| **WhatsApp** | Sí (E2EE) pero metadatos van a Meta | Pocos (Meta los guarda) | Válido para uso diario si no hablas de cosas muy sensibles. |
| **Telegram** | Solo chats secretos (no por defecto) | Muchos | No recomendado para alta privacidad. Útil para canales públicos. |

**Configuración mínima en todos:**  
- Ocultar foto de perfil a desconocidos.  
- Desactivar “última conexión” pública.  
- No permitir que te añadan a grupos sin permiso.  
- Activar verificación en dos pasos (sobre todo en Telegram y WhatsApp).

### Llamadas y videollamadas

- Signal y WhatsApp tienen llamadas cifradas.  
- En móvil, cuidado: las llamadas normales (red de telefonía) no están cifradas de extremo a extremo.  
- Para reuniones sensibles, usa Jitsi Meet (autoalojado si puedes) o Signal.

---

## 7. OpSec para navegación

### Navegadores y extensiones esenciales

- **Recomendados:** Firefox (con ajustes de privacidad), Brave, o Ungoogled Chromium.  
- **Evita:** Chrome (si te preocupa Google recolectando datos) o navegadores obsoletos.

**Extensiones útiles (no todas a la vez):**  
- **uBlock Origin** (bloquea rastreadores y anuncios).  
- **HTTPS Everywhere** (ya integrado en Firefox y Brave, pero por si acaso).  
- **ClearURLs** (elimina parámetros de rastreo de enlaces).  
- **Bitwarden** (gestor de contraseñas).  
- **Privacy Badger** (aprende a bloquear rastreadores).

No instales extensiones “limpiadoras” o “VPN gratis” desconocidas.

### Gestores de contraseñas (sí, pero bien usados)

**Recomendados:** Bitwarden (gratis, código abierto), Keepass (offline), Proton Pass.

**Errores comunes:**  
- Usar la misma contraseña maestra en todos lados (la maestra debe ser única y muy fuerte).  
- No activar 2FA en el gestor.  
- Sincronizar en la nube sin cifrado adicional (Bitwarden ya lo hace bien).

**Regla de oro:** Elige una frase larga y fácil de recordar como contraseña maestra, por ejemplo: `Silla-Rojo-42-Playa-Luna!`. Luego el gestor genera el resto.

### Borrado de historial y cookies (cuándo tiene sentido)

- **Borrar historial** sirve para que alguien con acceso físico a tu dispositivo no vea por dónde navegaste. No sirve para ser anónimo en internet.  
- **Borrar cookies** ayuda a evitar rastreo entre sesiones, pero es incómodo (cerrarás sesión en todos los sitios).  
- Una solución intermedia: usar **contenedores** en Firefox (Multi-Account Containers) o perfiles separados.

Para el usuario normal: no hace falta borrar todo a diario. Usa el modo privado/incógnito cuando hagas búsquedas sensibles.

---

## 8. OpSec para identidades online

### Uso de alias y correos desechables

- **Alias:** Usa un seudónimo en foros, redes sociales no profesionales, comentarios de noticias.  
- **Correos desechables:** Para registrarte en sitios que no son de confianza (ej: `10minutemail.net`).  
- **Alias de correo permanentes:** SimpleLogin o Firefox Relay redirigen a tu correo real sin exponerlo.

### Números virtuales

- Si un servicio te pide SMS de verificación y no confías, usa números virtuales (ej: `jmp.chat` o `Google Voice` si está disponible).  
- En España, hay servicios como `Hushed` o `Dingtone` (gratis limitado).

### Compartimentación (separar mundos)

No mezcles tu identidad real con tu alias. Ejemplo:

- **Mundo real:** Correo `nombre@dominio.com`, redes con nombre real, banco, trabajo.  
- **Mundo público:** Correo `alias@simplelogin.com`, redes sociales con seudónimo, comentarios.  
- **Mundo sensible (activistas):** Correo cifrado, Signal sin número real, Tor.

Nunca publiques en un foro con alias una foto que también está en tu Instagram real.

---

## 9. Simulaciones formativas: errores comunes

### Simulación 1 – El Wi-Fi del aeropuerto

**Escenario:** Estás en un aeropuerto, te conectas al WiFi gratuito “Aeropuerto_Free”. Entras a tu banca online para pagar un vuelo.

**Lo que pasa en la simulación:** Un formador explica que esa red podría ser falsa (evil twin) o estar interceptada. Al hacer clic en la banca, un atacante podría robar tu sesión.

**Respuesta correcta:** Nunca hacer banca en WiFi público. Usa datos móviles o VPN de confianza. Espera a llegar a casa o a una red segura.

### Simulación 2 – La contraseña reutilizada

**Escenario:** Usas la misma contraseña en Netflix, Twitter y tu correo. Un día, Netflix sufre una filtración. El atacante prueba esa contraseña en tu correo y entra.

**Simulación:** El formador muestra cómo en Have I Been Pwned se puede ver la filtración. Luego, con un voluntario, demuestra que con solo saber su email, se puede intentar acceder.

**Solución:** Gestor de contraseñas + contraseñas únicas.

### Simulación 3 – El “modo incógnito” engañoso

**Escenario:** Crees que el modo incógnito de Chrome te hace “invisible”. Buscas cosas privadas.

**Simulación:** El formador abre el modo incógnito, busca algo, luego cierra la ventana. Abre el navegador normalmente y muestra que el historial está limpio… pero el router de la oficina, el ISP y los servidores de Google sí registraron la búsqueda.

**Lección:** El modo incógnito solo evita que otro usuario de tu ordenador vea tu historial local. No te anonimiza en la red.

---

## 10. Checklist de OpSec diaria, semanal y mensual

### Cada día (2 minutos)

- [ ] ¿He recibido algún mensaje o correo sospechoso? Desconfiar.  
- [ ] ¿El navegador está actualizado? (se actualiza solo, pero comprueba).  
- [ ] ¿He cerrado sesión en servicios importantes en dispositivos compartidos?  

### Cada semana (5-10 minutos)

- [ ] Revisar actividad reciente de cuentas críticas (correo, banco, redes).  
- [ ] Verificar que las copias de seguridad automáticas han funcionado.  
- [ ] Actualizar extensiones del navegador.  
- [ ] En móvil: revisar permisos de apps (¿una linterna necesita acceso a contactos?).  

### Cada mes (15-20 minutos)

- [ ] Escanear con antivirus (Windows Defender o Malwarebytes).  
- [ ] Comprobar Have I Been Pwned.  
- [ ] Cambiar contraseñas solo si ha habido una filtración (no es necesario cada mes si usas gestor).  
- [ ] Revisar configuración de privacidad en redes sociales.  
- [ ] Hacer una copia de seguridad manual extra (disco externo).  

### Cada año (1 hora)

- [ ] Autoreconocimiento OSINT completo (Módulo 3).  
- [ ] Revisar y eliminar cuentas antiguas que no uses.  
- [ ] Actualizar la contraseña maestra del gestor (si hace más de 2 años).  
- [ ] Formación de actualización (leer un artículo sobre nuevas estafas).  

---

## 11. Herramientas gratuitas recomendadas

| Herramienta | Propósito | Enlace |
|-------------|-----------|--------|
| **Bitwarden** | Gestor de contraseñas | bitwarden.com |
| **VeraCrypt** | Cifrado de disco (alternativa a BitLocker) | veracrypt.fr |
| **Signal** | Mensajería segura | signal.org |
| **uBlock Origin** | Bloquear rastreadores | extensión navegador |
| **Firefox** | Navegador con buenos ajustes de privacidad | firefox.com |
| **1.1.1.1 (Cloudflare)** | DNS cifrado + VPN gratuita (limitada) | 1.1.1.1 |
| **ProtonVPN** (gratis) | VPN con límite de datos pero sin registro | protonvpn.com |
| **SimpleLogin** | Alias de correo (gratis 15 alias) | simplelogin.io |
| **Have I Been Pwned** | Verificar filtraciones | haveibeenpwned.com |
| **Windows Defender** | Antivirus integrado (suficiente) | (viene con Windows) |

---

## 12. Ejercicios prácticos (sin volverte loco)

### Ejercicio 1 – Instala y configura Bitwarden

- Crea una cuenta.  
- Genera una contraseña maestra fuerte y anótala en papel (guárdalo en sitio seguro).  
- Instala la extensión en tu navegador.  
- Cambia tres contraseñas importantes (correo, banco, red social) por otras generadas aleatoriamente.  
- Activa 2FA en Bitwarden si puedes.

### Ejercicio 2 – Audita tus copias de seguridad

- ¿Tienes backup automático de tus documentos? Si no, configura Google Drive o OneDrive para escritorio.  
- Compra un USB de 64GB o más. Una vez al mes, copia tus fotos y documentos importantes. Guarda el USB en un cajón diferente al ordenador.

### Ejercicio 3 – Prueba la VPN gratis

- Instala ProtonVPN gratis.  
- Conéctate a un país (ej: Países Bajos).  
- Ve a `whatismyip.com` y comprueba que tu IP cambió.  
- Navega un rato. Luego desactívala. Nota la diferencia de velocidad (normal).  

### Ejercicio 4 – El test de la red pública (simulado)

- Ve a un café con WiFi (o usa el móvil como hotspot con un nombre genérico).  
- Conéctate sin VPN.  
- Abre el banco (solo mirar, no operar).  
- Luego, actúa como si fuera un atacante: pregúntate “¿qué podría haber interceptado?”.  
- Conclusión: mejor no hacerlo. La próxima, usa datos móviles.

### Ejercicio 5 – Configura Signal

- Descarga Signal en tu móvil.  
- Invita a un amigo (o a ti mismo en otro dispositivo).  
- Envía un mensaje y comprueba que aparece “cifrado de extremo a extremo”.  
- Activa el “modo de pantalla de bloqueo” y “ocultar contenido de notificaciones”.

---

## 13. Conclusión y recursos

La OpSec no es un traje de fuerza. Es un conjunto de **pequeños hábitos** que, con el tiempo, te ahorran disgustos. No necesitas vivir como un fugitivo. Solo necesitas ser **consistente** en lo básico:

- **Contraseñas únicas + gestor + 2FA.**  
- **Actualizaciones automáticas.**  
- **Copias de seguridad.**  
- **Cuidado con enlaces y adjuntos.**  
- **Separación de identidades (alias cuando toque).**  
- **VPN en redes públicas.**  
- **Mensajería segura para lo importante.**

Si haces eso, ya estás por encima del 90% de la población y le pones muy difícil a los atacantes masivos.

**Recursos gratuitos adicionales:**

- **EFF – Surveillance Self-Defense** (guías en inglés y español parcial).  
- **SSD.eff.org** – cursos interactivos.  
- **INCIBE (España)** – guías de seguridad para familias y pymes.  
- **Have I Been Pwned** – revisa tus correos.  
- **Mozilla Foundation – Privacy not included** – analiza dispositivos y apps.

---
**Condor2026** – **SpectrumSecurity** - Especialista en OSINT, privacidad digital y análisis de amenazas.
---
*MÓDULO 7 de 24.*
---
