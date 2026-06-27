# 📘 MÓDULO 3 – TU HUELLA DIGITAL ES UN MAPA: OSINT DEFENSIVO

**Condor2026 – Análisis de amenazas digitales**

> *“No puedes proteger lo que no sabes que estás mostrando.”*

---

## Índice

1. ¿Qué es la huella digital y por qué debería importarte?  
2. OSINT ofensivo vs defensivo: la misma moneda, dos caras  
3. Qué información pública puede encontrarse de ti (sin ser hacker)  
- Nombre y apellidos  
- Correo electrónico  
- Número de teléfono  
- Dirección física  
- Redes sociales  
- Registros públicos, dominios, empresas  
- Fotos y metadatos  
4. Cómo hacer un autoreconocimiento OSINT paso a paso (legal y seguro)  
- Fase 1: Motor de búsqueda avanzada  
- Fase 2: Búsqueda de correos en filtraciones  
- Fase 3: Análisis de redes sociales  
- Fase 4: Búsqueda de imágenes inversa  
- Fase 5: Verificación de cuentas olvidadas  
5. Ejemplo simulado: rastreando un perfil ficticio  
6. Qué hacer cuando encuentras información que no debería estar pública  
7. Estrategias defensivas: no puedes borrarlo todo, pero puedes enterrarlo  
- Reducción de exposición  
- Dilución de datos (ruido)  
- Separación de identidades  
- Monitorización continua  
8. Herramientas gratuitas para OSINT defensivo  
9. Ejercicios prácticos para reducir tu huella  
10. Conclusión y recursos  

---

## 1. ¿Qué es la huella digital y por qué debería importarte?

Tu huella digital es el conjunto de datos que dejas involuntaria (y voluntariamente) al usar internet. Incluye:

- Perfiles en redes sociales (incluso los abandonados).  
- Comentarios en foros, noticias, blogs.  
- Correos electrónicos filtrados.  
- Datos de empresas o dominios que has registrado.  
- Fotos que otros subieron de ti.  
- Direcciones y teléfonos en guías o directorios.  
- Afiliaciones profesionales, estudios, trabajos anteriores.

**¿Por qué importa?**  
Porque un atacante, un acosador, un estafador o incluso un empleador malintencionado pueden usar esa información para:

- Ingeniería social más creíble.  
- Doxxing (publicar tu domicilio o datos privados).  
- Suplantación de identidad.  
- Acoso.  
- Robo de cuentas (preguntas de seguridad basadas en datos reales).

La mayoría de la gente descubre su huella **después** de un incidente. La idea es que lo hagas **antes**.

---

## 2. OSINT ofensivo vs defensivo: la misma moneda, dos caras

**OSINT ofensivo** (el que hacen atacantes, investigadores, periodistas, fuerzas de seguridad): recopilar información pública de un objetivo para un fin (bueno o malo).  

**OSINT defensivo** (lo que vas a aprender): recopilar información pública sobre **ti mismo** o tu organización para detectar fugas, reducir exposición y anticiparte a ataques.

Son exactamente las mismas técnicas. Lo que cambia es la intención y el objetivo.

En este módulo, tú eres tu propio objetivo. Vas a aprender a verte como te ve un desconocido con Google y un par de herramientas gratuitas.

---

## 3. Qué información pública puede encontrarse de ti (sin ser hacker)

Vamos por partes. Esto es lo que alguien puede descubrir con solo tu nombre, correo o teléfono.

### Por nombre y apellidos

- Redes sociales (LinkedIn, Facebook, Instagram, Twitter, TikTok, etc.)  
- Artículos de prensa, blogs, foros donde hayas comentado.  
- Páginas de empresas donde trabajas o trabajaste.  
- Resultados deportivos, sorteos públicos, donaciones.  
- Perfiles de GitHub (aunque no pongas tu nombre, a veces sale).  

### Por correo electrónico

- Redes donde te has registrado (buscando en bases de datos filtradas).  
- Comentarios en foros públicos.  
- Filtraciones de contraseñas (haveibeenpwned).  
- Asociación con otros nombres (si usas el mismo correo en varios sitios).  

### Por número de teléfono

- Perfiles de WhatsApp, Telegram, Signal (si permites que te encuentren por número).  
- Directorios inversos (páginas que venden datos).  
- Anuncios de segunda mano (Wallapop, Milanuncios) donde publicaste.  
- Filtraciones de aplicaciones.  

### Dirección física

- Registros de propiedad inmobiliaria (públicos en algunos países).  
- Padrón municipal (acceso restringido pero a veces filtrado).  
- Facturas de servicios filtradas.  
- Directorios antiguos.  

### Fotos y metadatos

- Fotos subidas por ti o por otros que contengan geolocalización.  
- Metadatos EXIF (cámara, fecha, GPS, modelo de dispositivo).  
- Reconocimiento facial (PimEyes, Search by image).  

---

## 4. Cómo hacer un autoreconocimiento OSINT paso a paso

Haz esto en un **día tranquilo**, sin prisas. Anota todo lo que encuentres.

### Fase 1: Motor de búsqueda avanzada

Usa Google, Bing o Startpage (más privado).

**Búsquedas clave:**

- `"Nombre Apellido"` (con comillas, búsqueda exacta).  
- `"Nombre Apellido" ciudad` (si quieres acotar).  
- `site:linkedin.com/in "Nombre Apellido"`  
- `Nombre Apellido filetype:pdf` (documentos donde aparezcas).  
- `"correo@ejemplo.com"`  

**Operadores útiles:**

- `intitle:Nombre` → página con Nombre en el título.  
- `inurl:apellido` → URL que contiene el apellido.  
- `-palabra` → excluir palabra (ej: `"Juan Pérez" -policía`).  
- `before:2022-01-01` → resultados anteriores a esa fecha.

**Ejercicio:** Haz 10 búsquedas distintas con tu nombre. Abre los primeros 5 resultados de cada una. ¿Hay algo que no sabías que estaba público?

---

### Fase 2: Búsqueda de correos en filtraciones

Ve a **haveibeenpwned.com** (de Troy Hunt). Introduce tu correo. Te dirá en qué filtraciones aparece.

Si quieres ir más allá (sin pagar), puedes buscar en **Firefox Monitor** o **Dehashed** (versión limitada). También en **breachdirectory.org** (con precaución, a veces pide captcha).

**Importante:** Si tu correo aparece en filtraciones, cambia YA las contraseñas de esos servicios y activa 2FA.

---

### Fase 3: Análisis de redes sociales

Haz una lista de todas las redes donde tienes cuenta. Incluso las que no usas.

Para cada una, **comprueba desde una ventana de incógnito** (sin iniciar sesión):

- ¿Puede alguien ver tu lista de amigos?  
- ¿Publicaciones antiguas?  
- ¿Tu número de teléfono o correo?  
- ¿Fotos en las que te etiquetan?  

**Instagram:** ve a ajustes > Cuenta privada (si quieres protegerte).  
**LinkedIn:** ajusta quién puede ver tu email y teléfono.  
**Facebook:** revisa “¿Quién puede ver mis publicaciones futuras?” y “Revisar etiquetas”.

**Ejercicio:** Busca tu propio nombre en Twitter, Instagram y Facebook desde una ventana de incógnito. Apunta qué ve un extraño.

---

### Fase 4: Búsqueda de imágenes inversa

Toma una foto de tu rostro que hayas usado en alguna red social. Sube esa imagen a:

- **Google Images** (icono de cámara en la barra de búsqueda).  
- **Bing Visual Search** (similar).  
- **Yandex Images** (muy potente, a veces encuentra más que Google).  
- **TinEye** (busca usos exactos).

Verás dónde más aparece esa foto (perfiles falsos, páginas webs, foros). Si encuentras un perfil falso con tu foto, denúncialo.

**Precaución:** No subas fotos íntimas ni documentos a buscadores públicos. Usa solo fotos de perfil públicas.

---

### Fase 5: Verificación de cuentas olvidadas

A veces tienes cuentas en foros, plataformas de empleo, o servicios que ya no usas. Siguen estando públicas.

**Cómo encontrarlas:**

- Busca `"Nombre Apellido"` + `"usuario"` o `"comentario"`.  
- Usa **Namechk** (namechk.com) o **Knowem** para ver en qué sitios está tomado tu nombre de usuario habitual.  
- Piensa en alias que usabas hace años. Búscalos.

Si encuentras una cuenta olvidada y no puedes recuperarla, intenta pedir su eliminación al soporte del sitio.

---

## 5. Ejemplo simulado: rastreando un perfil ficticio

Vamos a simular que nos llamamos **Laura Méndez**, vivimos en Barcelona, y queremos ver qué encuentra un atacante.

**Paso 1 – Búsqueda en Google:**  
`"Laura Méndez" Barcelona`  

Resultados:  
- Perfil de LinkedIn (aparece su empresa actual: “Atención al cliente en Telefónica”).  
- Un comentario en un foro de 2018 sobre videojuegos con su nombre real.  
- Una noticia de 2020 donde su asociación de vecinos la cita.

**Paso 2 – Correo:**  
Buscamos `"laura.mendez@algo.com"` → aparece en un PDF de una lista de correos filtrado en 2019 (Have I Been Pwned lo confirma). Su contraseña antigua estaba expuesta.

**Paso 3 – Redes sociales:**  
Desde ventana incógnito vemos su Instagram público: fotos de su gato, su barrio, y una historia destacada con su número de teléfono visible (tapado en un papel). Su Facebook tiene el teléfono visible en la biografía.

**Paso 4 – Imagen inversa:**  
Subimos su foto de perfil de LinkedIn a Google. Aparece también en un perfil de Pinterest con el mismo nombre. Ese perfil tiene un tablero con “Mis vacaciones en Málaga” y fechas exactas (cuándo no estaba en casa).

**Conclusión para Laura (en el ejercicio defensivo real):**  
- Cerrar o hacer privado el foro antiguo.  
- Pedir eliminar el PDF filtrado (difícil) pero al menos cambiar contraseñas.  
- Ocultar teléfono en Instagram y Facebook.  
- No publicar fechas de vacaciones en redes públicas.  
- Revisar cada 6 meses.

Este es el nivel de detalle que puede obtener un acosador. Por eso el autoreconocimiento es clave.

---

## 6. Qué hacer cuando encuentras información que no debería estar pública

### Caso 1: La información está en una web que controlas (tu blog, perfil, etc.)

- Entra en la configuración y elimínala o hazla privada.  
- Si es una red social, cambia la visibilidad a “solo amigos” o “solo yo”.

### Caso 2: La información está en una web que NO controlas (terceros)

- Ejemplo: un periódico publicó tu nombre completo y dirección.  
- **Primero**: Contacta con el webmaster o la atención al público. Pide la eliminación amablemente (Ley de Protección de Datos si estás en la UE, artículo 17 “Derecho al olvido”).  
- **Segundo**: Si no responden, usa formularios de Google para eliminar resultados de búsqueda (solo en la UE, con motivos legítimos).  
- **Tercero**: Denuncia a la Agencia de Protección de Datos de tu país si la web no elimina datos sensibles.

### Caso 3: La información está en una filtración masiva (ejemplo: 10 millones de emails)

- No puedes eliminar la filtración. Solo puedes mitigar:  
- Cambiar contraseñas.  
- Activar 2FA.  
- Usar alias de correo para servicios futuros (ej: `laura+compras@gmail.com`).  
- Monitorizar si alguien usa tu identidad.

### Caso 4: Es una cuenta falsa que usa tus datos

- Denuncia en la red social.  
- Si es grave (suplantación para estafar), guarda pruebas y ve a la policía (denuncia por suplantación de identidad).

---

## 7. Estrategias defensivas: no puedes borrarlo todo, pero puedes enterrarlo

El 100% de privacidad no existe. Pero puedes:

### A. Reducción de exposición

- Borra cuentas antiguas que no uses (puedes usar `justdeleteme.xyz` para guías).  
- Configura todo en privado por defecto.  
- No des tu correo principal en formularios web; usa correos temporales o alias (ej: SimpleLogin, Firefox Relay).  
- No publiques tu número de teléfono en redes. Si necesitas darlo a alguien, hazlo por privado.

### B. Dilución de datos (ruido)

Si no puedes eliminar algo, entiérralo bajo información irrelevante.  
- Crea perfiles en redes sociales con nombres similares pero sin tus datos reales.  
- Publica contenido genérico (comentarios sobre cosas no personales) con tu nombre en sitios de baja relevancia.  
- Así, cuando alguien te busque, encontrará ruido mezclado con datos reales.

### C. Separación de identidades

- Usa un alias para actividades no sensibles (compras, foros, newsletters).  
- Otro alias para temas profesionales.  
- Nombre real solo donde sea necesario (bancos, gobierno, trabajo).  
- No cruces identidades (ej: no uses el mismo correo para el trabajo y para el foro de gamers).

### D. Monitorización continua

- Configura **Google Alerts** con tu nombre, tu correo, tu teléfono (sin prefijo internacional). Cada vez que aparezcan en la web, recibirás un correo.  
- Usa **Mention** (plan gratuito limitado) para redes sociales.  
- Revisa Have I Been Pwned una vez al mes.  
- Una vez al año, repite el autoreconocimiento completo.

---

## 8. Herramientas gratuitas para OSINT defensivo

| Herramienta | Para qué sirve | Enlace / cómo |
|--------------|----------------|----------------|
| **Google / Bing / Yandex** | Búsqueda avanzada de tu nombre | Buscar con operadores |
| **Have I Been Pwned** | Ver filtraciones de tu email | haveibeenpwned.com |
| **Firefox Monitor** | Similar, de Mozilla | monitor.firefox.com |
| **Google Alerts** | Monitorizar tu nombre en la web | google.com/alerts |
| **Namechk** | Ver dónde está tomado tu usuario | namechk.com |
| **TinEye / Google Images** | Búsqueda inversa de fotos | tineye.com |
| **JustDeleteMe** | Guías para borrar cuentas | justdeleteme.xyz |
| **SimpleLogin / Firefox Relay** | Alias de correo | simplelogin.io |
| **Epieos** (gratis limitado) | Datos asociados a email/teléfono | epieos.com |
| **GhostProject** | Buscar contraseñas viejas filtradas (con cuidado) | ghostproject.fr |

**Nota:** No uses herramientas de OSINT ofensivo para espiar a otros. Úsalas solo para ti.

---

## 9. Ejercicios prácticos para reducir tu huella

### Ejercicio 1 – La lista de cuentas olvidadas

Tómate una hora. Abre un documento. Escribe cada red social, foro o servicio que hayas usado en los últimos 10 años. Luego:

- Intenta acceder. Si no recuerdas la contraseña, usa “recuperar cuenta”.  
- Si la recuperas, decide: borrarla (si no la usas) o privatizarla.  
- Si no puedes recuperarla, busca si aparece tu nombre público. Si aparece, contacta al soporte.

### Ejercicio 2 – Configuración de privacidad en redes

Revisa estas tres redes hoy mismo (si las usas):  
- **Instagram:** Ajustes > Privacidad > Cuenta privada (ON).  
- **Facebook:** Ajustes > Privacidad > “¿Quién puede ver tus publicaciones futuras?” → Solo amigos. Además, desactiva que te encuentren por teléfono.  
- **LinkedIn:** Perfil > Configuración > Visibilidad > Cambiar a “Solo conexiones” para email y teléfono.

### Ejercicio 3 – Google Alerts para tu nombre

Crea una alerta con tu nombre completo entre comillas: `"Nombre Apellido"`. Elige “una vez al día” o “en el momento”. En una semana, revisa qué resultados te llegaron.

### Ejercicio 4 – El atacante imaginario

Escribe un pequeño guion: “Si yo fuera un acosador que solo sabe mi nombre y mi ciudad, ¿qué tres datos públicos podría encontrar en 30 minutos?”. Luego busca realmente esos tres datos. Si los encuentras, ya sabes qué proteger.

### Ejercicio 5 – Borra metadatos de fotos futuras

Descarga una app para eliminar EXIF en tu móvil (ej: Photo Exif Editor en Android, Metapho en iOS). Antes de subir una foto a redes, elimina la geolocalización y los datos de cámara.

---

## 10. Conclusión y recursos

Tu huella digital es como una fotografía de tu vida en internet. Puede ser borrosa o nítida. Un atacante quiere la nítida. Tú puedes hacer que sea borrosa sin dejar de usar internet.

**Resumen de acciones inmediatas:**

1. **Hoy mismo:** Configura todas tus redes sociales como privadas.  
2. **Esta semana:** Revisa Have I Been Pwned con tus correos principales. Cambia contraseñas donde haya filtraciones.  
3. **Este mes:** Haz el autoreconocimiento completo (Fases 1 a 5). Anota lo que encuentres y elimina/oculta lo que puedas.  
4. **Cada 6 meses:** Repite el proceso. La huella digital cambia.

**Recursos gratuitos adicionales:**

- **Incibe (España):** Guías de privacidad digital.  
- **EFF (Electronic Frontier Foundation):** “Surveillance Self-Defense”.  
- **Mozilla Foundation:** “Privacy not included”.

---

**Condor2026** – Especialista en OSINT, privacidad digital y análisis de amenazas.

---
