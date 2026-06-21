## 📘 MÓDULO 2 – INGENIERÍA SOCIAL: EL ARTE DE LA CONFIANZA ROBADA

**Condor2026 – Análisis de amenazas digitales**

> *“No hace falta vulnerar un sistema. Basta con vulnerar a la persona que lo opera.”*

---

### Índice

1. Qué es la ingeniería social y por qué es más peligrosa que el malware  
2. El ciclo del engaño social (cómo se construye una estafa)  
3. Tipos prácticos de ingeniería social  
- Pretexting (fabricación de una excusa creíble)  
- Suplantación de identidad (persona real o ficticia)  
- Cebo físico y digital (USB abandonados, concursos falsos)  
- Quid pro quo (algo a cambio de algo)  
- Tailgating (acceso físico colándose detrás de alguien)  
4. Simulaciones formativas (cómo se entrenan empresas y particulares)  
- Llamada simulada de “soporte técnico”  
- Mensaje de “recursos humanos”  
- Perfil falso en LinkedIn  
- Escenario de “amigo en apuros” por WhatsApp  
5. Señales de alerta (por canal y por tipo de engaño)  
6. Herramientas para verificar sin confiar  
7. Qué hacer si te están manipulando ahora mismo (en llamada o chat)  
8. Ejercicios prácticos para inmunizarte  
9. Conclusión y recursos  

---

### 1. Qué es la ingeniería social y por qué es más peligrosa que el malware

La ingeniería social es la manipulación psicológica de una persona para que realice una acción o revele información confidencial. No requiere código malicioso. No requiere vulnerabilidades técnicas. Solo requiere **confianza mal dirigida**.

El malware puede ser detectado por un antivirus. El engaño humano, no.

Los ataques más devastadores de los últimos años no empezaron con un exploit, sino con una llamada telefónica o un correo bien redactado.

**Casos reales (anonimizados pero reales):**

- Una empleada de finanzas recibe una llamada del “CEO” (voz clonada o simplemente con prisas) pidiendo una transferencia urgente. La hace. 200.000€ perdidos.  
- Un adolescente recibe un mensaje de “Instagram” diciendo que su cuenta será eliminada. Introduce su contraseña en un formulario falso. Le roban la cuenta y extorsionan a sus seguidores.  
- Un jubilado recibe una llamada de “su banco” avisando de un cargo fraudulento. Para “cancelarlo”, le piden que lea un código SMS. Ese código es el 2FA. Vacían su cuenta.

La ingeniería social no distingue edad, nivel educativo o sistema operativo.

---

### 2. El ciclo del engaño social (cómo se construye una estafa)

Los atacantes siguen un patrón. Si lo reconoces, rompes el ciclo.

**Fase 1 – Investigación (OSINT previo)**  
Buscan datos públicos de la víctima: nombre, empresa, hobbies, redes sociales, noticias, relaciones. En ataques masivos no hay investigación, solo spray and pray. En ataques dirigidos (spear phishing), sí.

**Fase 2 – Pretexto (la historia)**  
Inventan una situación creíble: “Soy de soporte técnico”, “Soy un amigo de tu primo”, “Ganaste un sorteo”, “Tu cuenta será bloqueada”.

**Fase 3 – Contacto**  
Por teléfono, SMS, WhatsApp, correo, redes o incluso presencial.

**Fase 4 – Explotación de emociones**  
Miedo, urgencia, autoridad, deseo, ayuda a un ser querido.

**Fase 5 – Acción deseada**  
Que des una contraseña, instales un programa, hagas una transferencia, leas un código, abras un enlace.

**Fase 6 – Desenlace**  
El atacante obtiene lo que quiere y desaparece. A veces mantiene acceso para futuros ataques.

---

### 3. Tipos prácticos de ingeniería social

#### Pretexting (excusa fabricada)

El atacante crea un escenario. Ejemplos:  
- “Llamo del departamento de IT. Hemos detectado actividad extraña en tu ordenador. Necesito que instales este software para revisar.”  
- “Hola, soy compañero de tu hijo. Tu hijo me dio tu número porque tuvo un accidente y necesita que le transfieras dinero.”

**Lo que buscan:** Que actúes sin verificar.

#### Suplantación de identidad

El atacante se hace pasar por alguien conocido o de autoridad.  
- Perfil falso de un amigo en Instagram: “Oye, te han puesto en un vídeo viral, mira este enlace.”  
- Correo que parece de RRHH: “Adjunto revisa tu nómina.”

**Detección:** Contacta a la persona supuesta por otro canal.

#### Cebo (baiting)

Ofrecen algo tentador.  
- USB con la etiqueta “Confidencial – Nóminas 2025” dejado en un parking.  
- Mensaje: “Has ganado un iPhone 16. Pincha aquí para reclamarlo.”

**Detección:** Si es demasiado bueno para ser verdad, es falso.

#### Quid pro quo (algo a cambio)

Ofrecen un beneficio a cambio de información o acción.  
- “Podemos arreglar tu problema de internet gratis, solo necesitamos acceso remoto un momento.”  
- “Contesta esta encuesta y te regalamos 50€.”

#### Tailgating (acceso físico)

Presencial. El atacante pide que le abran la puerta en una oficina.  
- “Se me olvidó la tarjeta, ¿me dejas pasar?”  
- “Soy el de mantenimiento del ascensor.”

**Prevención:** No abrir la puerta a desconocidos sin verificar identificación.

---

### 4. Simulaciones formativas (cómo se entrenan)

Así se hace profesionalmente. Puedes adaptarlo a tu familia o equipo.

#### Simulación 1 – Llamada de soporte técnico (vishing)

**Set up:** Un compañero (o tu entrenador) llama a un empleado simulando ser de IT.  
**Guión:** “Hola, soy Carlos del soporte informático. Hemos detectado que tu equipo está haciendo peticiones raras a la red. ¿Puedes abrir el menú de inicio y escribir CMD? Necesito que me digas lo que ves.” (o pedirle que instale TeamViewer)

**En una simulación real (formativa):**  
Al final, el “técnico” dice: “Esto era una simulación. Así es como podrían haber accedido a tu ordenador. La próxima vez, cuelga y llama al número oficial de soporte.”

#### Simulación 2 – Mensaje de “recursos humanos”

Se envía un correo o WhatsApp a los empleados:  
> “Hola a todos, debido a una actualización del sistema de nóminas, necesitamos que confirméis vuestros datos bancarios en este enlace interno: nominas-empresa.com/confirmar”

El dominio es falso. Quien pincha ve una página de advertencia educativa.

#### Simulación 3 – Perfil falso en LinkedIn

Se crea un perfil con un nombre genérico, foto de stock, trabajo en una empresa real. Se contacta a empleados con un mensaje:  
> “Hola, me interesa un proyecto que vi en tu perfil. ¿Podríamos conectar? Adjunto información.”

El adjunto es un enlace a una página que dice “Esto era una prueba de concienciación”.

#### Simulación 4 – “Amigo en apuros” por WhatsApp

Desde un número desconocido:  
> “Mamá / papá / [nombre], perdí mi móvil, este es mi nuevo número. Necesito que me prestes 300€ para pagar una reparación urgente. Te lo devuelvo mañana.”

En la simulación, al responder se explica que así operan los estafadores que suplantan familiares.

---

### 5. Señales de alerta (por canal y tipo de engaño)

#### 📞 En llamadas telefónicas

- [ ] Te piden que realices una acción inmediata (instalar, transferir, dar código).  
- [ ] El interlocutor se pone nervioso o te presiona si dudas.  
- [ ] Te dicen que “no cuelgues” mientras haces algo en el ordenador.  
- [ ] La llamada viene de un número desconocido o privado, pero dicen ser de una entidad con líneas oficiales.  
- [ ] Te piden tu contraseña, PIN o código de 2FA.  
- [ ] Quieren que leas un código que te llega por SMS.

**Regla de oro:** Cuelga. Llama tú al número oficial del servicio. No uses el que te dieron por teléfono.

#### 💬 En mensajes (WhatsApp, SMS, Telegram, Instagram DM)

- [ ] El número no está en tu agenda y no esperas ningún mensaje de esa persona/empresa.  
- [ ] Hay faltas de ortografía o redacción extraña.  
- [ ] Te piden que reenvíes un código (como los de verificación de WhatsApp).  
- [ ] Es un familiar pidiendo dinero urgente desde un número desconocido.  
- [ ] Te ofrecen un premio o trabajo sin apenas entrevista.  
- [ ] El enlace está acortado y no puedes ver el destino real.

#### 🌐 En correos electrónicos (ya vistos en phishing, pero aplican)

- [ ] Remitente sospechoso o dominio ligeramente alterado.  
- [ ] Saludo genérico (“Estimado usuario”).  
- [ ] Adjunto inesperado o enlace a página de login falsa.  
- [ ] Te piden confirmar datos personales.

#### 🚪 Presencial

- [ ] Alguien te pide que le abras una puerta sin acreditación.  
- [ ] Se ofrece a “ayudarte” con un problema técnico sin que tú lo pidieras.  
- [ ] Te deja un USB o dispositivo “encontrado” cerca de tu oficina.

---

### 6. Herramientas para verificar sin confiar

| Situación | Herramienta o acción |
|------------|------------------------|
| Recibes una llamada sospechosa | Cuelga. Busca el número oficial en Google (no el que te dieron). Llama tú. |
| Te escriben de un banco por SMS | No respondas. Entra a la app del banco desde tu móvil, no desde el enlace. |
| Un “amigo” te pide dinero por WhatsApp | Llama a su número real o pregúntale algo que solo él sepa. |
| Te ofrecen un trabajo por LinkedIn | Investiga la empresa: dominio web, antigüedad, empleados reales. Busca opiniones. |
| Te llega un USB encontrado | No lo conectes. Destrúyelo o entrégaselo a seguridad informática. |
| Sospechas de un perfil falso | Búsqueda inversa de su foto de perfil (Google Images, TinEye). |

---

### 7. Qué hacer si te están manipulando ahora mismo

**En una llamada que empieza a oler mal:**

1. **No digas nada más.**  
2. Di: “Ahora mismo no puedo atenderte. Dame un número de teléfono oficial y te llamo yo más tarde.”  
3. Si insisten, cuelga directamente.  
4. Si te piden un código SMS, **no lo leas**. Ese código suele ser la llave de tu cuenta.  
5. Anota el número y la hora (para posibles denuncias).

**En un chat o mensaje:**

1. No hagas clic en enlaces.  
2. No descargues archivos.  
3. Haz una captura de pantalla.  
4. Verifica por otro canal (llama a la persona o empresa).  
5. Bloquea y denuncia si es claramente falso.

**Si ya caíste (diste datos, transferiste dinero, instalaste algo):**

- **Inmediatamente**: cambia tus contraseñas desde otro dispositivo.  
- Si diste datos bancarios: llama al banco oficial.  
- Si instalaste un programa de acceso remoto: desconecta internet y apaga el ordenador.  
- Si transferiste dinero: contacta con tu banco, a veces se puede revertir en los primeros minutos.  
- Guarda toda la evidencia (capturas, número, hora).  
- Denuncia en policía.

---

### 8. Ejercicios prácticos para inmunizarte

#### Ejercicio 1 – Caza el pretexto

Pídele a un amigo que te invente una historia creíble por teléfono (sin previo aviso) para que le des un dato ficticio (ej: “tu color favorito” o “tu última compra online”). Tú debes identificar en menos de 30 segundos si es real o falso. Después de 5 intentos, tu intuición mejora.

#### Ejercicio 2 – Verifica en dos pasos

Durante una semana, cada vez que alguien te pida algo importante por mensaje o llamada (incluso si parece tu jefe o familiar), acostúmbrate a verificar por otro canal: llama al número que tienes guardado, no al que te está escribiendo.

#### Ejercicio 3 – Analiza mensajes reales de spam

Abre tus SMS de spam. Elige uno. Escribe un pequeño informe:
- ¿Qué emoción intenta activar?  
- ¿Cuál es el pretexto?  
- ¿Qué acción pide?  
- ¿Qué señal de alarma detectas?

#### Ejercicio 4 – Simulación familiar

Reúne a tu familia o compañeros de piso. Lee en voz alta un escenario:  
> “Te llama tu banco diciendo que hay un cargo sospechoso de 800€ y te piden que confirmes tu número de tarjeta para cancelarlo. ¿Qué haces?”

Cada persona responde. Luego explicas la respuesta correcta: **cuelgas y llamas al número oficial del banco**.

#### Ejercicio 5 – El código SMS que no se da

Explica a alguien mayor de tu entorno: “Si alguien te llama por teléfono y te dice que te va a llegar un código por SMS y que se lo leas, es un engaño. Ese código sirve para entrar en tu cuenta. Nunca se lo des a nadie.”

Ponlo a prueba: tú mismo le envías un código de verificación (simulado, no real) y le dices por teléfono: “¿Me lees el código?”. Si lo lee, entonces corriges y repites el entrenamiento.

---

### 9. Conclusión y recursos

La ingeniería social explota lo mejor de nosotros: la confianza, la solidaridad, el respeto a la autoridad. Por eso duele tanto caer. Pero **no es falta de inteligencia**, es falta de **protocolo**.

Tu nuevo protocolo:

1. **Pausa** (aunque te estén apurando).  
2. **Verifica** por otro canal.  
3. **Nunca** des códigos SMS, contraseñas o acceso remoto por teléfono.  
4. **Cuelga** si la persona te presiona.  
5. **Habla** de esto con los que te rodean.

**Recursos gratuitos:**

- **Incibe (España)** – guías de ingeniería social.  
- **OSI (Oficina de Seguridad del Internauta)** – ejemplos reales.  
- **Have I Been Pwned** – para saber si tu email está en filtraciones (los atacantes usan eso).  
- **Google Reverse Image Search** – para comprobar fotos de perfil falsas.

---

**Condor2026** – Especialista en OSINT, privacidad digital y análisis de amenazas.

