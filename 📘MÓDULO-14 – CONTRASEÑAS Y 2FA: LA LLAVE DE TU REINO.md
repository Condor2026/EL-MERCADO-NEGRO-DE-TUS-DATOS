# 📘 MÓDULO 14 – CONTRASEÑAS Y 2FA: LA LLAVE DE TU REINO

**Condor2026 – Ciberseguridad para humanos**  
*Serie completa – Módulo 14 de 50*

> *"Tu contraseña no es una puerta. Es una hoja de papel en una biblioteca pública. El 2FA es el candado que te falta."*

---

## 📖 Índice de contenidos

1. **La historia de Ricardo** (y cómo perdió 50.000€ por una contraseña que creía segura)  
2. **Por qué tu contraseña no es tan segura como crees**  
- Cómo las rompen los criminales (ataques de diccionario, fuerza bruta, credenciales filtradas)  
- El mito de "contraseña123" (y sus variantes)  
- La reutilización, el error que más cuesta  
3. **La anatomía de una buena contraseña** (para humanos, no para máquinas)  
- Frases largas y fáciles de recordar  
- Lo que NO funciona (sustituciones de letras, números al final)  
4. **El gestor de contraseñas: tu mejor amigo digital**  
- Qué es, cómo funciona, por qué es seguro  
- El gestor gratuito que recomiendo (Bitwarden) y cómo configurarlo en 10 minutos  
- La contraseña maestra (la única que tienes que recordar)  
5. **El 2FA: la segunda cerradura**  
- Qué es y por qué el SMS no es suficiente  
- Tipos de 2FA (SMS, app, hardware, backup codes)  
- Cómo activarlo en tu correo, banco y redes sociales  
- El error mortal: perder los códigos de recuperación  
6. **Qué hacer si te roban la contraseña o el móvil**  
7. **Historias de víctimas** (traumas reales, anonimizados)  
- Caso 1: La abogada que usaba la misma contraseña en todo  
- Caso 2: El informático al que le robaron el móvil y con él todas sus cuentas  
- Caso 3: La youtuber que perdió su canal de 2 millones de seguidores  
- Caso 4: El directivo que tenía 2FA por SMS y le hicieron SIM swapping  
8. **Ejercicios prácticos**  
9. **Glosario**  
10. **Conclusión y recursos**  
11. **Gancho para el Módulo 15**

---

## 1. La historia de Ricardo (y cómo perdió 50.000€ por una contraseña que creía segura)

**Nombre real:** Ricardo G., 47 años, empresario de transporte. Ingresos anuales de 200.000€. Se consideraba "precavido digitalmente".

**Su contraseña:** `Ricardo47` (su nombre + su edad). La usaba desde hacía 10 años. La usaba en su correo, en su banca online, en Amazon, en su cuenta de empresa, y en una docena de servicios más.

**Lo que Ricardo no sabía:**

- Su correo apareció en una filtración de una tienda online en la que compró una vez (una tienda de electrónica barata).  
- Esa filtración incluía su correo y la contraseña `Ricardo47`.  
- La filtración se vendió en un foro oscuro por 3 dólares.

**El ataque:** Un criminal compró la filtración, probó la combinación `correo@ejemplo.com : Ricardo47` en el banco de Ricardo... y funcionó. Porque él usaba la misma contraseña.

**La noche del robo:** El criminal entró a la banca online de Ricardo, cambió el límite de transferencias (no tenía 2FA activado), e hizo tres transferencias por un total de 50.000€ a cuentas mula. En 20 minutos, el dinero había pasado por 6 cuentas y se había convertido en criptomoneda.

**El despertar:** Ricardo recibió un correo del banco: "Se han realizado transferencias por importe de 50.000€. Si no reconoce esta operación, contacte con nosotros." Ya era tarde.

**Consecuencias:**  
- El banco le devolvió 20.000€ (porque consideró que su negligencia era parcial). Perdió 30.000€ para siempre.  
- Su mujer casi le pide el divorcio (confiaban en él para las finanzas familiares).  
- Su empresa estuvo al borde de la bancarrota (tuvo que pedir un préstamo para pagar a proveedores).  
- La vergüenza le impidió contarlo a nadie durante dos años.

**Lo que Ricardo aprendió:** Su "contraseña segura" no lo era. Su error no fue la contraseña débil, sino **reutilizarla** y **no tener 2FA**. Nunca volvió a usar la misma clave en dos sitios.

---

## 2. Por qué tu contraseña no es tan segura como crees

### 2.1 Cómo las rompen los criminales

Los criminales no están sentados adivinando "contraseña123" a mano. Usan programas automáticos.

| Método | Cómo funciona | Lo que busca |
|--------|---------------|--------------|
| **Ataque de diccionario** | Prueba millones de palabras comunes en varios idiomas | `password`, `admin`, `123456`, `qwerty`, `amor`, `secreto` |
| **Ataque de fuerza bruta** | Prueba todas las combinaciones posibles (letras, números, símbolos) | Cualquier contraseña corta (menos de 8 caracteres) |
| **Ataque de reglas** | Combina diccionario con variaciones comunes | `contraseña1`, `Password2023`, `admin123` |
| **Credential stuffing** | Prueba credenciales filtradas en otros servicios | Correos y contraseñas de filtraciones pasadas |
| **Ataque de máscara** | Prueba patrones comunes | `nombre+edad`, `nombre+apellido`, `cumpleaños` |

**Lo aterrador:** Una contraseña de 6 caracteres (solo letras minúsculas) se rompe en **segundos**. Una de 8 caracteres (minúsculas + números) se rompe en **horas**. Una de 12 caracteres aleatorios puede tardar años. Pero si la contraseña está en un diccionario, el tiempo es irrelevante.

### 2.2 El mito de "contraseña123" (y sus variantes)

Estas son las contraseñas más usadas en 2024 (y por tanto, las primeras que prueban los criminales):

| Posición | Contraseña |
|----------|------------|
| 1 | 123456 |
| 2 | password |
| 3 | 123456789 |
| 4 | 12345 |
| 5 | 12345678 |
| 6 | qwerty |
| 7 | 111111 |
| 8 | 1234567 |
| 9 | 123123 |
| 10 | abc123 |

Si tu contraseña está en esta lista, cámbiala AHORA.

### 2.3 La reutilización, el error que más cuesta

El 65% de las personas usa la misma contraseña en múltiples cuentas. Esto es un desastre porque:

- Una tienda online barata tiene una seguridad pésima. La hackean y filtran tus datos.  
- El criminal prueba esa combinación en tu banco, tu correo, Amazon, PayPal.  
- Si alguna funciona, lo has perdido todo.

**No importa lo buena que sea tu contraseña. Si la reutilizas, eres vulnerable.**

---

## 3. La anatomía de una buena contraseña (para humanos, no para máquinas)

### 3.1 Frases largas y fáciles de recordar

Olvídate de `P@ssw0rd!2024`. Eso es difícil de recordar y no tan segura como crees.

**Método de la frase:** Elige una frase de 4-6 palabras aleatorias, fácil de visualizar, y añade algún número o símbolo al final.

**Ejemplos:**  
- `MiPerroSeLlamaLucas!23`  
- `CaféConLecheEnLaPlaya7`  
- `GatitaBlancaSaltaVentana9`

**Por qué funciona:**  
- Es larga (más de 20 caracteres) → difícil de romper por fuerza bruta.  
- No está en diccionarios comunes (no es una frase hecha como "esteesmipassword").  
- Es fácil de recordar porque tiene sentido para ti.

**Lo que NO funciona:**  
- Sustituciones de letras: `P@ssw0rd` (los criminales conocen esas sustituciones).  
- Números al final: `password123` (lo prueban automáticamente).  
- Palabras del diccionario solas: `tiburón` (se rompe al instante).

### 3.2 La regla de oro

> **Una contraseña por cuenta. Cada cuenta, una contraseña única. Sin excepciones.**

No importa si es una cuenta de un foro que usas una vez al año. Usa una contraseña única. Porque si ese foro es hackeado, esa contraseña no te salpicará en otros sitios.

Esto es imposible de hacer sin un gestor de contraseñas. Y por eso necesitas uno.

---

## 4. El gestor de contraseñas: tu mejor amigo digital

### 4.1 Qué es, cómo funciona, por qué es seguro

Un gestor de contraseñas es una aplicación que:
- Genera contraseñas largas, aleatorias y únicas para cada servicio.  
- Las guarda en una base de datos cifrada.  
- La única contraseña que tienes que recordar es la **maestra** (la que abre el cofre).  
- Se sincroniza entre tu ordenador, tu móvil y tu tableta.  
- Rellena automáticamente las contraseñas en los sitios web (así también evitas phishing, porque no te autocompletará en páginas falsas).

**¿Es seguro?** Sí, si usas un gestor reputado (Bitwarden, Keepass, 1Password, Proton Pass). Usan cifrado de nivel militar. Nadie puede leer tus contraseñas excepto tú (ni siquiera la empresa del gestor).

**El riesgo real:** Olvidar la contraseña maestra, o que alguien la robe. Por eso la contraseña maestra tiene que ser **muy fuerte** y **nunca usarla en otro sitio**.

### 4.2 El gestor gratuito que recomiendo: Bitwarden (y cómo configurarlo en 10 minutos)

**Por qué Bitwarden:**  
- Código abierto (auditable por expertos).  
- Gratis para uso personal (funcionalidades más que suficientes).  
- Apps para Windows, Mac, Linux, Android, iOS.  
- Extensión para navegadores.  
- Sincronización en la nube (cifrada de extremo a extremo).

**Configuración en 10 minutos:**

1. Ve a bitwarden.com. Crea una cuenta (correo y contraseña maestra).  
2. **Contraseña maestra:** Usa una frase larga, por ejemplo `MiCasaEnLaPlayaEsAzul!42`. **No la olvides. No la guardes en un post-it.**  
3. Instala la extensión del navegador (Chrome, Firefox, Edge, etc.). Inicia sesión.  
4. Instala la app en el móvil. Inicia sesión.  
5. Empieza a añadir cuentas:  
- Cuando entres en un sitio web, Bitwarden te preguntará si quieres guardar la contraseña. Di que sí.  
- Para sitios ya existentes, añade manualmente la entrada (nombre del sitio, tu usuario, contraseña actual).  
6. Usa el generador de contraseñas de Bitwarden para cambiar tus contraseñas importantes por nuevas, aleatorias, de 20 caracteres.  
7. Cambia las contraseñas de tus 5 servicios clave: correo, banco, redes sociales, Amazon, PayPal. Los demás, ve cambiándolos poco a poco.

**El secreto:** La única contraseña que tienes que recordar es la maestra. Todo lo demás, que Bitwarden lo recuerde por ti.

### 4.3 La contraseña maestra (la única que tienes que recordar)

Tu contraseña maestra es la llave de todas tus llaves. Si alguien la obtiene, tiene acceso a todo. Por tanto:

- **Debe ser muy fuerte:** Frase de 4-6 palabras + números + símbolo.  
- **No la uses en ningún otro sitio** (ni en el trabajo, ni en redes, ni para nada).  
- **No la guardes en el ordenador** (ni en un archivo de texto, ni en el móvil). Escríbela en un papel y guárdala en un cajón seguro (o en una caja fuerte).  
- **Activa 2FA en Bitwarden** (usando una app como Google Authenticator o Authy). Así, aunque roben tu contraseña maestra, no podrán acceder sin el código.

---

## 5. El 2FA: la segunda cerradura

### 5.1 Qué es y por qué el SMS no es suficiente

**2FA (Two Factor Authentication)** = necesitas dos cosas para entrar en tu cuenta:
1. Algo que sabes (tu contraseña).  
2. Algo que tienes (un código que cambia cada 30 segundos, o una llave física).

Si solo tienes contraseña (1FA), el criminal solo necesita tu contraseña. Si tienes 2FA, necesita tu contraseña **y** tu teléfono (o tu llave física).

**¿Por qué el SMS no es suficiente?**  
- Los criminales pueden hacer **SIM swapping** (engañar a tu operadora para que den un duplicado de tu SIM).  
- Las redes SS7 (la infraestructura de telefonía) tienen vulnerabilidades que permiten interceptar SMS.  
- Es mejor que nada, pero **no es seguro**.

**Qué usar en su lugar:**  
- **Apps de autenticación:** Google Authenticator, Microsoft Authenticator, Authy, Aegis, 2FAS.  
- **Llaves físicas:** YubiKey (más seguro, pero cuesta dinero).  
- **Códigos de respaldo** (imprímelos).

### 5.2 Tipos de 2FA (de peor a mejor)

| Tipo | Seguridad | Dónde se usa | Riesgo |
|------|-----------|--------------|--------|
| SMS | Baja | Muchos bancos y servicios | SIM swapping, interceptación |
| App autenticadora | Alta | Google, Microsoft, GitHub, Twitter, etc. | Robo de teléfono (si no tiene código de bloqueo) |
| Llave física (U2F) | Muy alta | Google, GitHub, Dropbox, etc. | Perder la llave física |
| Códigos de respaldo | Depende de cómo los guardes | Servicios que permiten 2FA | Si los guardas en el mismo dispositivo, no sirven |

**Recomendación para empezar:** Activa 2FA con app autenticadora (Google Authenticator o Authy) en tu correo, en tu banco (si lo permite), en tus redes sociales, y en Bitwarden.

### 5.3 Cómo activar 2FA en tus cuentas clave

**Google / Gmail:**
1. Ve a myaccount.google.com/security.  
2. "Verificación en dos pasos" → Activar.  
3. Elige "Aplicación de autenticación". Escanea el código QR con tu app (Google Authenticator).  
4. Guarda los códigos de respaldo (imprímelos o escríbelos).  

**Microsoft / Outlook:**
1. Ve a account.microsoft.com/security.  
2. "Verificación en dos pasos" → Activar.  
3. Sigue el mismo proceso.  

**Bancos (cada uno tiene su sistema):**
- Algunos tienen su propia app para generar códigos.  
- Otros permiten usar Google Authenticator.  
- Otros solo SMS (mejor que nada, actívalo igual).  

**Redes sociales (Twitter, Instagram, Facebook):**
- Ajustes → Seguridad → Autenticación en dos pasos → App autenticadora.  

**Bitwarden:**
- Ajustes → Seguridad → Autenticación de dos pasos → Aplicación autenticadora.  

### 5.4 El error mortal: perder los códigos de recuperación

Cuando activas 2FA, el servicio te da entre 5 y 10 **códigos de recuperación de un solo uso**. Están diseñados para usarlos si pierdes el móvil o no puedes generar el código.

**El error:** Guardarlos solo en el móvil o en el ordenador. Si pierdes ambos, quedarás bloqueado de por vida.

**La solución:**  
- Imprime los códigos y guárdalos en un cajón seguro (o en una caja fuerte).  
- Copia los códigos en un papel y dáselo a un familiar de confianza (en un sobre cerrado).  
- No los guardes en el gestor de contraseñas (si pierdes el acceso al gestor, no podrás usarlos).

---

## 6. Qué hacer si te roban la contraseña o el móvil

### Si crees que tu contraseña ha sido robada (por phishing, filtración, o reutilización)

1. **Cambia la contraseña inmediatamente** desde un dispositivo limpio (no el posiblemente infectado).  
2. **Activa el 2FA** si no lo tenías.  
3. **Revisa la actividad reciente** de la cuenta (dispositivos conectados, correos reenviados, reglas de filtro).  
4. **Cierra todas las sesiones activas** ("cerrar sesión en todos los dispositivos").  
5. **Cambia la misma contraseña en cualquier otro sitio donde la hayas reutilizado** (por eso no se deben reutilizar).

### Si te roban el móvil (y tienes 2FA en el autenticador)

1. **No entres en pánico.** Tienes tiempo.  
2. **Usa los códigos de recuperación** (impresos, recuerda). Úsalos para entrar en tus cuentas críticas (correo, banco, Bitwarden).  
3. **Desactiva el 2FA temporalmente** (si el servicio lo permite) y vuélvelo a activar con un nuevo dispositivo.  
4. **Llama a tu operadora** para que bloquee la SIM (evita que usen tu número para SIM swapping).  
5. **Cambia las contraseñas** de tus cuentas más importantes (desde un ordenador limpio).  
6. **Si el móvil tenía la app del banco**, contacta con el banco para que revoquen la sesión.

**Prevención:** Siempre ten una copia de los códigos de recuperación impresos y guardados en lugar seguro.

---

## 7. Historias de víctimas (traumas reales, anonimizados)

### Caso 1 – La abogada que usaba la misma contraseña en todo

**Perfil:** Eva, 38 años, abogada con despacho propio.

**Cómo ocurrió:** Eva usaba `Eva1986` en su correo personal, su correo profesional, su banca, su despacho, y su cuenta de Amazon. Un día, un sitio de venta de ropa donde compró fue hackeado. Su contraseña apareció en una filtración. Un criminal probó `Eva1986` en su correo profesional y entró.

**Lo que perdió:**  
- El criminal leyó correos de sus clientes (datos confidenciales). Los publicó en un foro.  
- Perdió dos clientes importantes por violación de confidencialidad.  
- Estuvo a punto de perder su licencia profesional (el colegio de abogados la investigó).  
- Contrató a una empresa de ciberseguridad por 8.000€ para limpiar su huella.

**Lección:** Una sola contraseña reutilizada puede costarte no solo dinero, sino tu carrera.

### Caso 2 – El informático al que le robaron el móvil y con él todas sus cuentas

**Perfil:** Iván, 29 años, informático (supuestamente experto en seguridad).

**Cómo ocurrió:** Le robaron el móvil en el metro. Iván tenía 2FA activado en muchas cuentas, pero **no tenía los códigos de recuperación guardados fuera del móvil**. Tampoco tenía copias de seguridad.

**Lo que perdió:**  
- No pudo acceder a su correo de Gmail (perdió 8 años de archivos).  
- No pudo acceder a su cuenta de GitHub (perdió proyectos de código).  
- No pudo acceder a su cuenta de Twitter (10.000 seguidores).  
- Tardó 3 meses en recuperar el correo (con ayuda del soporte de Google).  
- Perdió el acceso a su cuenta de Bitwarden (tuvo que resetear todas sus contraseñas una por una).

**Lección:** La arrogancia informática mata. Los códigos de recuperación impresos son la diferencia entre un susto y un desastre.

### Caso 3 – La youtuber que perdió su canal de 2 millones de seguidores

**Perfil:** Carla, 24 años, youtuber de belleza. 2 millones de suscriptores. Ingresos anuales por publicidad y patrocinios: 200.000€.

**Cómo ocurrió:** Recibió un correo falso que parecía de YouTube: *"Su canal ha sido denunciado por infracción de derechos de autor. Verifique su cuenta aquí para evitar la suspensión."* Carla hizo clic en el enlace, introdujo su contraseña... y los criminales la robaron. No tenía 2FA activado.

**Lo que perdió:**  
- Los criminales cambiaron el nombre del canal, la foto, y subieron vídeos de criptoestafas.  
- YouTube tardó 6 semanas en devolverle el control (perdió ingresos por 30.000€).  
- Perdió la confianza de sus seguidores: muchos se dieron de baja.  
- Ahora tiene 1,2 millones de seguidores (800.000 menos).  
- Su salud mental se resintió. Dejó de publicar durante 3 meses.

**Lección:** Si generas ingresos de tu cuenta online, el 2FA debería ser obligatorio, no opcional.

### Caso 4 – El directivo que tenía 2FA por SMS y le hicieron SIM swapping

**Perfil:** Carlos, 51 años, director financiero de una empresa mediana.

**Cómo ocurrió:** Un criminal llamó a su operadora de telefonía (Vodafone) haciéndose pasar por él. Usó datos personales obtenidos de una filtración (nombre, DNI, fecha de nacimiento). La operadora, sin verificar adecuadamente, emitió un duplicado de su SIM.

**Lo que pasó:**  
- El criminal recibió todos sus SMS, incluidos los códigos de 2FA de su banca y su correo.  
- Entró en su banca online, cambió las contraseñas (le llegaban los SMS al criminal), y transfirió 40.000€.  
- Carlos se quedó sin cobertura en el móvil. Cuando fue a la tienda de Vodafone, ya era tarde.

**Consecuencias:**  
- Perdió 40.000€. El banco alegó que no era responsable porque los códigos se enviaron correctamente (al número del cliente, pero el criminal tenía el duplicado).  
- Su empresa casi le despide por negligencia.  
- Carlos ahora tiene 2FA con app autenticadora, no con SMS.

**Lección:** Si puedes, nunca uses SMS como 2FA. Una app autenticadora (Google Authenticator, Authy) es mucho más segura.

---

## 8. Ejercicios prácticos

### Ejercicio 1 – La prueba de la contraseña

Ve a **haveibeenpwned.com/Passwords** (sitio de Troy Hunt). Introduce una de tus contraseñas (no la maestra, una que uses o hayas usado). Te dirá si aparece en filtraciones. Si aparece, **cámbiala ya**.

### Ejercicio 2 – Crea tu frase maestra

Escribe 5 frases que podrían ser tu contraseña maestra. Ejemplo: `MiGatoVuelaDeNoche99`. Elige la más fácil de recordar. Escríbela en un papel y guárdala en un cajón. Nunca la digas a nadie.

### Ejercicio 3 – Instala Bitwarden hoy

Dedica 20 minutos a seguir la guía de la sección 4.2. Instala Bitwarden, añade tus 5 cuentas más importantes, cámbiales la contraseña por una generada aleatoriamente (20 caracteres). Notarás que no necesitas recordarlas.

### Ejercicio 4 – Activa 2FA en tu correo

Sigue la guía de la sección 5.3 para activar 2FA en tu cuenta de Google o Microsoft. Usa Google Authenticator o Authy. **Guarda los códigos de recuperación impresos.** Pon una copia en tu cartera y otra en un cajón de casa.

### Ejercicio 5 – El test del familiar

Pídele a un familiar (o a tu pareja) que haga el ejercicio 3 y 4. Explícale por qué es importante. Ayúdale a configurar Bitwarden y el 2FA. Una hora de tu tiempo puede ahorrarle años de disgustos.

### Ejercicio 6 – La auditoría de 2FA

Haz una lista de tus 10 cuentas más importantes (correo, banco, redes, Amazon, PayPal, Bitwarden, iCloud/Google Drive, trabajo, etc.). Revisa una por una:  
- ¿Tiene 2FA?  
- ¿Qué tipo? (SMS, app, llave física)  
- ¿Tengo los códigos de recuperación guardados en papel?

Las que no tengan 2FA, actívaselas. Las que tengan solo SMS, cámbialas a app autenticadora.

---

## 9. Glosario

| Término | Significado |
|---------|-------------|
| **Contraseña maestra** | La única contraseña que recuerdas (la de tu gestor). |
| **Gestor de contraseñas** | App que guarda y genera contraseñas únicas. |
| **2FA** | Segundo factor de autenticación (algo que tienes). |
| **Autenticador (app)** | App que genera códigos que cambian cada 30 segundos. |
| **Códigos de recuperación** | Códigos de un solo uso para cuando pierdes el 2FA. |
| **SIM swapping** | Engaño a la operadora para duplicar tu tarjeta SIM. |
| **Credential stuffing** | Ataque que prueba credenciales filtradas en otros servicios. |
| **Diccionario (ataque)** | Prueba millones de palabras comunes. |
| **Fuerza bruta** | Prueba todas las combinaciones posibles. |

---

## 10. Conclusión y recursos

**Resumen ejecutivo:**

- Tu contraseña no es segura si es corta, común, o está reutilizada.  
- La solución es un **gestor de contraseñas** (Bitwarden, gratuito) que genere y guarde contraseñas únicas para cada servicio.  
- La única contraseña que tienes que recordar es la **maestra**. Hazla larga y fácil de recordar (una frase).  
- El **2FA** es tu segunda cerradura. Actívalo en todas tus cuentas importantes.  
- **Nunca uses SMS como 2FA** si puedes evitarlo. Usa una app autenticadora.  
- **Guarda los códigos de recuperación impresos** en un lugar seguro. No confíes solo en el móvil.

**Recursos gratuitos:**

- **Bitwarden:** bitwarden.com  
- **Have I Been Pwned (para contraseñas):** haveibeenpwned.com/Passwords  
- **Google Authenticator:** apps de Google (Android/iOS).  
- **Authy** (alternativa con copia de seguridad en la nube, más cómoda pero menos segura): authy.com  
- **INCIBE – Guía de contraseñas:** incibe.es  

**Si ya eres víctima de robo de contraseña:**

1. Cambia la contraseña desde un dispositivo limpio.  
2. Activa 2FA si no lo tenías.  
3. Revisa la actividad reciente de la cuenta.  
4. Cierra todas las sesiones activas.  
5. Si el banco está implicado, llama al número oficial.

---

## 11. Gancho para el Módulo 15

Ya sabes cómo proteger tus contraseñas y activar el 2FA. Tienes las llaves de tu reino bien guardadas. Pero hay un tipo de ataque que **no necesita tu contraseña ni tu 2FA**. Un ataque que se aprovecha de tu deseo de ganar dinero rápido, de tu miedo a perderlo, o de tu confianza en falsos gurús.

En el **Módulo 15** (5 de la serie ciudadano) vamos a hablar de **estafas financieras y de inversión**: cómo reconocer una pirámide, un bróker falso, o una app de trading que solo quiere tu dinero.

Te contaré la historia del ingeniero que perdió 80.000€ en una "inversión garantizada", la de la jubilada que vendió su casa por un falso premio, y la del grupo de Telegram que prometía multiplicar criptomonedas.

**No te lo pierdas. Porque el dinero que tanto te ha costado ganar puede desaparecer en minutos si no sabes identificar las señales.**

---
**Condor2026** – **SpectrumSecurity**
---
*Módulo 14 de 24.*
---
