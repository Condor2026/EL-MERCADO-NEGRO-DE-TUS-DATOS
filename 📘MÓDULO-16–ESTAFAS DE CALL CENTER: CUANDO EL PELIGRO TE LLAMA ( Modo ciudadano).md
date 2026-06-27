# 📘 MÓDULO 16 – ESTAFAS DE CALL CENTER: CUANDO EL PELIGRO TE LLAMA ( Modo ciudadano)

**Condor2026 – Ciberseguridad para humanos**  
*Serie completa – Módulo 16 de 50*

> *"El teléfono suena. La voz al otro lado suena profesional. Pero está entrenada para vaciarte la cuenta."*

---

## 📖 Índice de contenidos

1. **La historia de Carmen** (y cómo una llamada de 10 minutos le costó 12.000€)  
2. **¿Qué es un call center de estafas?** (la industria millonaria detrás del teléfono)  
3. **Tipos principales de estafas telefónicas**  
- 3.1 Soporte técnico falso (Microsoft, Amazon, tu ISP)  
- 3.2 Falso banco o tarjeta clonada  
- 3.3 Estafa del familiar en apuros ("abuela, necesito dinero")  
- 3.4 Falsa central de compañías de luz, agua o telecomunicaciones  
- 3.5 Estafa de las "vacaciones gratis" o "premio"  
- 3.6 Robo de 2FA por llamada (el código SMS que no se da)  
- 3.7 Extorsión con falsas deudas o impuestos  
- 3.8 Estafa del "falso secuestro" (versión extrema)  
4. **Cómo operan: la infraestructura detrás de la llamada**  
- Spoofing (suplantación de número)  
- Guiones profesionales y psicología inversa  
- Trabajadores explotados en call centers ilegales  
5. **Guiones reales desglosados** (para que los reconozcas)  
- Guión 1: "Soy de tu banco, hay un cargo falso"  
- Guión 2: "Soy de Microsoft, tu ordenador está infectado"  
- Guión 3: "Hola abuela, soy tu nieto, he tenido un accidente"  
6. **Señales de alerta universales** (imprime esta lista)  
7. **Historias de víctimas** (traumas reales, anonimizados)  
- Caso 1: La abuela que vaciaron la cuenta con el "código SMS"  
- Caso 2: El abogado que instaló TeamViewer y perdió sus clientes  
- Caso 3: La joven que recibió una llamada "de Hacienda" y pagó 3.000€  
- Caso 4: El matrimonio mayor que transfirió 40.000€ al "falso nieto"  
8. **Protocolo de actuación DURANTE la llamada** (qué decir y qué NO decir)  
9. **Qué hacer si ya caíste** (diste datos, instalaste software, transferiste dinero)  
10. **Cómo proteger a los más vulnerables** (adultos mayores, niños, personas con discapacidad)  
11. **Herramientas para bloquear y reportar llamadas fraudulentas**  
12. **Ejercicios prácticos**  
13. **Glosario**  
14. **Conclusión y recursos**  
15. **Gancho para el Módulo 17**

---

## 1. La historia de Carmen (y cómo una llamada de 10 minutos le costó 12.000€)

**Nombre real:** Carmen M., 74 años, viuda, jubilada, vive sola en Madrid. Hija de una generación que confía en la autoridad y nunca cuelga el teléfono sin ser educada.

**El día de la llamada:** Martes, 11:30 AM. Carmen acababa de volver de la compra. Sonó el teléfono fijo. En la pantalla aparecía el número de su banco. Ella lo reconoció porque estaba apuntado en su agenda junto al teléfono.

**La llamada (textual, reconstruida por Carmen para la policía):**

> *"Buenos días, señora Carmen. Soy Laura del departamento de seguridad de su banco, CaixaBank. ¿Me reconoce? El número que ve en su pantalla es el nuestro, ¿verdad?"*

Carmen: "Sí, sí, es el número que tengo apuntado."

> *"Perfecto. Mire, señora Carmen, hemos detectado un cargo fraudulento de 1.200€ en una tienda de electrónica en Valencia. ¿Reconoce usted esa operación?"*

Carmen: "¡Ay, Dios mío! No, no he comprado nada. Vivo en Madrid."

> *"Tranquila, tranquila. Estamos a tiempo de cancelarlo. Pero necesito que me ayude con unos pasos rápidos para verificar su identidad. ¿Tiene su tarjeta a mano?"*

Carmen cogió su tarjeta.

> *"Dígame los últimos 4 dígitos de su tarjeta, por favor."*

Carmen se los dio.

> *"Perfecto. Ahora, para confirmar que es usted la titular, le voy a enviar un código de verificación por SMS. ¿Me lo puede leer cuando le llegue?"*

Llegó el SMS. Carmen leyó el código.

> *"Gracias, señora Carmen. El cargo fraudulento ha sido cancelado. Pero por seguridad, le recomiendo que cambie su contraseña de la banca online. Para ayudarle, le voy a enviar otro código. ¿Me lo lee?"*

Llegó otro SMS. Carmen leyó el código.

> *"Muy bien. Ya está todo solucionado. Que tenga un buen día."*

**Lo que Carmen no sabía:**

- El número que veía en su pantalla era **suplantado** (spoofing). No era su banco.  
- El primer "código de verificación" era en realidad una autorización para añadir un dispositivo a su banca online.  
- El segundo código era la autorización para hacer una transferencia de 12.000€ a una cuenta mula.  
- En menos de 5 minutos, los estafadores habían vaciado su cuenta de ahorros.

**El despertar:** Al día siguiente, Carmen fue al banco a sacar dinero para pagar a la señora que le limpiaba la casa. El cajero le dijo: "Señora, su saldo es 0€". Ella pensó que era un error. Llamó a su hija. Su hija revisó los movimientos: "Mamá, hiciste dos transferencias de 12.000€ a una cuenta en Portugal". Carmen no había hecho ninguna transferencia.

**Consecuencias:**  
- Carmen perdió sus ahorros de toda una vida.  
- El banco le devolvió 6.000€ (por responsabilidad parcial de la entidad por no verificar adecuadamente), pero perdió 6.000€ para siempre.  
- Su hija le quitó el teléfono fijo. Ahora solo usa un móvil con números bloqueados.  
- Carmen dejó de salir de casa. Tenía miedo de que "vinieran a por ella".  
- Su hija tuvo que pedir un préstamo para pagar las facturas de su madre.

**Lo que Carmen aprendió:** El banco nunca llama pidiendo códigos SMS. Si le hubiera enseñado esa regla, hoy tendría sus ahorros.

---

## 2. ¿Qué es un call center de estafas? (la industria millonaria detrás del teléfono)

Un **call center de estafas** es una operación (muchas veces ilegal, a veces semilegal en paraísos laxos) donde decenas o cientos de operadores hacen llamadas masivas o dirigidas para engañar a las víctimas. Pueden estar en un edificio real en otro país (India, Pakistán, Colombia, Turquía, Marruecos, Ucrania) o ser grupos pequeños que trabajan desde casa.

**Datos escalofriantes:**
- Las estafas telefónicas generan más de **10.000 millones de euros al año** en todo el mundo.  
- Solo en España, se estima que **1 de cada 4 adultos mayores** ha recibido al menos una llamada de estafa en el último año.  
- El perfil más vulnerable: **mujeres de más de 65 años, que viven solas y tienen teléfono fijo** (porque los estafadores asumen que son más confiadas y educadas).

**¿Por qué son tan efectivos?**

1. **Volumen:** Hacen miles de llamadas al día con sistemas automáticos de marcación. Aunque solo caiga el 0.1%, ya tienen muchas víctimas.  
2. **Profesionalismo:** Usan guiones traducidos perfectamente por nativos, con tono de voz amable y convincente. Incluyen respuestas para todas las objeciones.  
3. **Spoofing:** Suplantan números de teléfono reales. Tu teléfono muestra el número de tu banco, de la policía, o de una empresa conocida. Es muy difícil desconfiar cuando ves un número que conoces.  
4. **Psicología:** Generan urgencia, miedo, o confianza. Saben que la gente mayor es más educada y tiende a no colgar.  
5. **Persistencia:** Si no caes hoy, te llaman mañana con otra historia. Tienen bases de datos con números que contestan.

---

## 3. Tipos principales de estafas telefónicas

### 3.1 Soporte técnico falso (Microsoft, Amazon, tu ISP)

**Cómo empieza:**  
Te llama alguien diciendo que es de "Soporte técnico de Microsoft" (o de Amazon, o de tu compañía de internet). Te dice que han detectado virus o actividad sospechosa en tu ordenador. Ofrecen "arreglarlo gratis" o por una pequeña tarifa.

**Qué quieren:**  
- Que instales software de acceso remoto (TeamViewer, AnyDesk, UltraViewer). Una vez dentro, roban archivos, instalan malware, o te piden dinero para "limpiar" algo que no existe.  
- O que pagues una "suscripción de seguridad" de 200-500€.  
- O que te conectes a tu banca online "para verificar que no haya cargos fraudulentos", y mientras tanto ellos roban tus credenciales.

**Por qué funciona:**  
La gente asocia "Microsoft" con autoridad. El "técnico" usa términos técnicos que suenan reales (el visor de eventos de Windows, el registro de Windows). Y la urgencia ("su ordenador enviará virus en 1 hora") activa el miedo.

### 3.2 Falso banco o tarjeta clonada

**Cómo empieza:**  
"Llamamos de la sección de fraudes de su banco. Hemos detectado un cargo de 800€ en una tienda de Madrid. ¿Autorizó usted esta compra?".

Si dices que no, te dicen: "Tranquilo, vamos a anularla. Para confirmar su identidad, necesito el código que le acabamos de enviar por SMS".

**Qué quieren:**  
Ese código SMS es, en realidad, el 2FA para entrar a tu banca online o autorizar una transferencia. Se lo das y ellos vacían tu cuenta.

**Variante:** Te piden que instales la app de la banca online en tu ordenador (falsa) o que entres en una web falsa.

### 3.3 Estafa del familiar en apuros (versión telefónica)

**Cómo empieza:**  
"Hola abuela, soy tu nieto. He tenido un accidente con el coche y necesito que me transfieras 1.500€ urgentemente para pagar la reparación / la fianza del hospital. No se lo digas a mis padres porque me van a matar".

**Variantes:**  
- "Soy un amigo de tu hijo, está en la comisaría y necesita que pagues la fianza".  
- "Soy tu primo, perdí mi móvil, este es mi número nuevo".  
- "Soy tu hijo, he tenido un problema con el coche, necesito dinero para el taller".

**Qué quieren:**  
Transferencia bancaria o tarjetas regalo (Amazon, Google Play, iTunes). Una vez enviado, desaparecen.

**Giro psicológico:** A veces el "falso nieto" llora, se pone nervioso, o dice que está en el hospital y le van a operar. Generan tanta angustia que la víctima no piensa en verificar.

### 3.4 Falsa central de compañías de luz, agua o telecomunicaciones

**Cómo empieza:**  
"Llamamos de Iberdrola (o Movistar, o Aguas de Barcelona). Hay un error en su factura y le hemos cobrado de más. Para hacer la devolución, necesito su número de cuenta bancaria".

**Qué quieren:**  
Datos bancarios para luego hacer cargos fraudulentos o robar la cuenta.

**Variante:** "Su recibo de la luz ha sido devuelto. Si no paga hoy, le cortaremos el suministro". Te piden que pagues con tarjeta de crédito por teléfono.

### 3.5 Estafa de las "vacaciones gratis" o "premio"

**Cómo empieza:**  
"¡Enhorabuena! Ha sido seleccionado para un viaje con todos los gastos pagados a Canarias. Solo tiene que pagar los impuestos (300€) con tarjeta de crédito ahora mismo".

**Qué quieren:**  
Los datos de la tarjeta (número, fecha, CVV) para vaciarla o hacer compras.

**Variante:** "Ha ganado un sorteo de 50.000€. Solo tiene que pagar 1.000€ de gastos de gestión para recibir el premio".

### 3.6 Robo de 2FA por llamada (el código SMS que no se da)

**Cómo empieza:**  
"Le vamos a enviar un código de verificación a su teléfono. Por favor, dígamelo para confirmar que es usted". Pueden decir que es para "activar una promoción", "verificar su cuenta de WhatsApp", "arreglar un problema de red", o "cancelar un cargo falso".

**Qué quieren:**  
El código de acceso que permite tomar el control de tu cuenta de WhatsApp, correo o banco.

**Lo más aterrador:** Este tipo de estafa funciona incluso con personas que saben que no deben dar su contraseña, porque el código SMS no es la contraseña (es el 2FA). La víctima piensa "no es mi contraseña, puedo darlo". Error.

### 3.7 Extorsión con falsas deudas o impuestos

**Cómo empieza:**  
"Soy de la Agencia Tributaria. Tiene una deuda pendiente de 3.000€. Si no la paga hoy, enviaremos a la policía a su domicilio". A veces usan amenazas de prisión o embargo de bienes.

**Qué quieren:**  
Que pagues inmediatamente con tarjeta o transferencia a una cuenta que dan por teléfono.

**Realidad:** Ninguna agencia oficial (Hacienda, Seguridad Social, Ayuntamiento) llama por teléfono para pedir pagos urgentes. Todas usan notificaciones por escrito (carta certificada, buzón electrónico).

### 3.8 Estafa del "falso secuestro" (versión extrema)

**Cómo empieza:**  
Llamada a un padre o madre: "Tenemos a tu hijo. Si no pagas 5.000€ ahora mismo, lo matamos". A veces se escucha de fondo a un supuesto hijo llorando o gritando (grabación).

**Qué quieren:**  
Transferencia inmediata o códigos de tarjetas regalo.

**Qué hacer:**  
- No entres en pánico.  
- Intenta contactar con tu hijo por otro canal (móvil, trabajo, amigos).  
- Pregunta algo que solo tu hijo sabría (el nombre de su mascota, el lugar donde estudia). Un falso secuestrador no podrá responder.  
- Cuelga y llama a la policía.

**Realidad:** La mayoría de estas llamadas son falsas. El "hijo" que se escucha es una grabación genérica. Los estafadores llaman a miles de números al azar.

---

## 4. Cómo operan: la infraestructura detrás de la llamada

### Spoofing (suplantación de número)

El estafador usa un servicio VoIP (como Twilio, o servicios ilegales de spoofing) que permite mostrar cualquier número en tu pantalla. Puede aparecer el número real de tu banco, el de la policía, o uno parecido.

**Cómo detectarlo:** No te fíes del número que ves. Si "tu banco" te llama, cuelga y llama tú al número oficial que aparece en tu tarjeta o en su web. El spoofing solo funciona en la llamada entrante; no en la saliente.

### Guiones profesionales

Los call centers ilegales tienen guiones traducidos por nativos, con respuestas preparadas para cualquier objeción. Por ejemplo:

**Víctima:** "Voy a colgar y llamar yo a mi banco".  
**Estafador (preparado):** "Claro, puede hacerlo. Pero mientras tanto, el cargo de 800€ se hará efectivo en los próximos 20 minutos. Si prefiere esperar, allá usted. Yo solo intento ayudarle".

Juegan con el miedo a la pérdida inmediata.

**Cómo contraatacar:** Cuelga igualmente. Si es real, la transacción no se hará efectiva en 20 minutos. Las entidades legítimas no te apuran.

### Los trabajadores

Muchos estafadores son víctimas también: personas en situación vulnerable que son engañadas para trabajar en call centers falsos en sus propios países (India, Pakistán, Filipinas, Colombia). Les prometen trabajo legítimo y acaban estafando por miedo o necesidad. Pero hay también operadores conscientes y malintencionados.

---

## 5. Guiones reales desglosados (para que los reconozcas)

### Guión 1 – "Soy de tu banco, hay un cargo falso"

**Estafador:** "Buenos días, soy Laura del departamento de fraudes de [nombre del banco]. Hemos detectado un cargo de 1.200€ en una tienda de Madrid. ¿Reconoce esta operación?"  
**Tú:** "No, no reconozco nada".  
**Estafador:** "Tranquilo, vamos a anularla. Para confirmar su identidad, necesito el código que le acabo de enviar por SMS. ¿Me lo puede leer?"  
**(Llega un SMS con un código de 6 dígitos)**  

**Lo que está pasando:** Ese código no es para "anular un cargo". Es para añadir un dispositivo a tu banca online o autorizar una transferencia.

**Respuesta correcta:** "No voy a darle el código. Voy a colgar y llamar yo al número de mi banco". Cuelga.

### Guión 2 – "Soy de Microsoft, tu ordenador está infectado"

**Estafador:** "Soy del soporte técnico de Microsoft. Hemos detectado que su ordenador está enviando virus a otros equipos. ¿Puede encenderlo?"  
**Tú:** "Vale, un momento".  
**Estafador:** "Ahora abra el menú inicio y escriba 'eventvwr'. ¿Ve todos esos errores en rojo? Son virus." (El visor de eventos de Windows siempre muestra errores técnicos, no virus).  
**Estafador:** "Necesito que instale este programa para arreglarlo. Le envío un enlace. Instálelo y dígame el código que aparece."

**Lo que está pasando:** El enlace es para instalar TeamViewer o AnyDesk. El código es para que el estafador tome el control remoto de tu ordenador.

**Respuesta correcta:** "Microsoft no llama a particulares. Adiós". Cuelga.

### Guión 3 – "Hola abuela, soy tu nieto, he tenido un accidente"

**Estafador (voz llorosa):** "Abuela, soy Pablo. He tenido un accidente con el coche. Estoy en la comisaría y necesito que me pagues 2.000€ de fianza. No se lo digas a mis padres porque me van a matar."  
**Tú:** "Ay, Pablo, ¿estás bien?"  
**Estafador:** "Estoy bien, pero tengo que pagar hoy mismo. Te mando un número de cuenta. Haz la transferencia ya."

**Respuesta correcta:** "Pablo, dime la palabra secreta familiar" (la que hayáis acordado). Si no la sabe, cuelga. Y llama al número real de tu nieto.

---

## 6. Señales de alerta universales (imprime esta lista)

Si escuchas alguna de estas, **cuelga inmediatamente**:

- [ ] **Te piden que hagas algo con urgencia** ("tiene que ser ahora o perderá su cuenta").  
- [ ] **Te piden tu contraseña, PIN, o número de tarjeta completo.** Nadie legítimo hace eso.  
- [ ] **Te piden el código SMS que acaba de llegar.** Ese código es para entrar a tu cuenta, no para "verificarte".  
- [ ] **Te piden que instales un programa en tu ordenador** (TeamViewer, AnyDesk, UltraViewer).  
- [ ] **Te piden que hagas una transferencia o compres tarjetas regalo** (Amazon, Google Play, iTunes) y les des los códigos.  
- [ ] **Te amenazan con la policía, prisión o corte de servicios si no pagas ya.**  
- [ ] **Te ofrecen un premio que no solicitaste** y te piden pagar impuestos o gastos de envío por adelantado.  
- [ ] **Te llaman de "tu banco" pero no usan tu nombre completo** (solo "señor/a").  
- [ ] **Te piden que no cuelgues mientras haces algo en el ordenador** (para que no verifiques con nadie).  
- [ ] **La llamada viene de un número desconocido o internacional, pero dicen ser de una empresa local.**  

**Regla de oro de las llamadas:**  
> **Cuelga. Busca el número oficial en tu documentación. Llama tú.**

---

## 7. Historias de víctimas (traumas reales, anonimizados)

### Caso 1 – La abuela que vaciaron la cuenta con el "código SMS"

**Perfil:** Pepita, 78 años, viuda, vive sola en un pueblo.  
**Estafa:** Llamada del "banco" por cargo falso. Le pidieron el código SMS.  
**Pérdida:** 18.000€ (todos sus ahorros).  
**Consecuencias:** Tuvo que volver a vivir con su hija (con la que no se llevaba bien). Depresión severa. Dejó de contestar el teléfono, incluso a sus amigos.  
**Lección:** Nunca dar el código SMS.

### Caso 2 – El abogado que instaló TeamViewer y perdió sus clientes

**Perfil:** Miguel, 45 años, abogado con despacho propio.  
**Estafa:** Llamada de "soporte técnico de Microsoft". Instaló TeamViewer.  
**Pérdida:** Los estafadores robaron 15.000€ de su cuenta de empresa. Además, instalaron un ransomware que cifró todos sus expedientes de clientes. Tuvo que pagar 5.000€ en Bitcoin para recuperarlos (y ni así, los recuperó parcialmente).  
**Consecuencias:** Perdió dos clientes importantes por violación de confidencialidad. Casi quiebra. Ahora tiene miedo de cualquier actualización de software.  
**Lección:** Microsoft no llama. Nunca instales programas remotos por teléfono.

### Caso 3 – La joven que recibió una llamada "de Hacienda" y pagó 3.000€

**Perfil:** Alba, 32 años, diseñadora gráfica autónoma.  
**Estafa:** Llamada de la "Agencia Tributaria" diciendo que tenía una deuda de 2.800€ y que si no pagaba en 1 hora, la policía iría a su domicilio a embargar sus bienes.  
**Pérdida:** 3.000€ (porque los estafadores le pidieron 200€ más por "gastos de gestión").  
**Consecuencias:** Alba tuvo que pedir un préstamo a sus padres para pagar sus facturas. Dejó de trabajar durante 2 meses por la ansiedad.  
**Lección:** Hacienda no llama. Hacienda envía cartas certificadas. Si te llaman, cuelga.

### Caso 4 – El matrimonio mayor que transfirió 40.000€ al "falso nieto"

**Perfil:** Juan y Rosa, 68 y 66 años, jubilados.  
**Estafa:** Llamada de "su nieto" (voz llorosa) diciendo que había tenido un accidente y necesitaba 40.000€ para una operación urgente (fianza + gastos médicos).  
**Pérdida:** 40.000€ (sus ahorros para la jubilación).  
**Consecuencias:** Tuvieron que vender su coche y pedir ayuda a sus hijos. Juan dejó de comer bien durante meses para ahorrar. Rosa aún tiene pesadillas con la llamada.  
**Lección:** Si un familiar te pide dinero por teléfono, verifica con otro familiar antes. Establece un código secreto familiar.

---

## 8. Protocolo de actuación DURANTE la llamada (qué decir y qué NO decir)

### Lo que NO debes hacer:

- [ ] **No digas "sí" a preguntas como "¿me escucha?"** Pueden grabar tu "sí" y usarlo para autorizar cargos.  
- [ ] **No des ningún dato personal** (nombre, dirección, DNI, fecha de nacimiento).  
- [ ] **No digas "tengo ordenador" o "tengo cuenta en X banco"** (les das información para futuras estafas).  
- [ ] **No entres en discusión.** No trates de "ganarles" o hacerles perder el tiempo (pueden ponerse agresivos o grabarte para suplantarte).  
- [ ] **No sigas instrucciones** de instalar programas, abrir enlaces, o leer códigos.

### Lo que SÍ debes hacer:

1. **Cuelga inmediatamente.** No necesitas dar explicaciones.  
2. **Si la llamada parece legítima** (porque el número es real), **no te fíes**. Cuelga y llama tú al número oficial que tengas apuntado (el de la tarjeta o la factura).  
3. **Si tienes dudas**, anota el número que aparece en tu pantalla (aunque sea falso) y búscalo en Google. Muchos números de estafa ya están reportados.  
4. **Bloquea el número** después de colgar (en el móvil; en el fijo, contacta con tu operadora).  
5. **Si la llamada te ha generado miedo o ansiedad**, háblalo con alguien de confianza. No es "solo una llamada", puede afectar a tu salud mental.

### Frases útiles para practicar (para ti o para tus familiares mayores):

- "Ahora mismo no puedo atender. Dame su nombre y número de teléfono y le llamaré yo más tarde." (un estafador real colgará).  
- "Lo siento, no hago operaciones por teléfono. Prefiero ir a la oficina."  
- "Voy a consultarlo con mi hijo/a. Adiós." (y cuelgas).

---

## 9. Qué hacer si ya caíste (diste datos, instalaste software, transferiste dinero)

### Si diste el código SMS o contraseña (banco, correo, WhatsApp):

1. **Cambia inmediatamente la contraseña** de esa cuenta desde otro dispositivo (no el que usaste en la llamada).  
2. **Activa o renueva el 2FA** (si te robaron el código, es que ya lo tenías activado; revoca todas las sesiones activas en "dispositivos conectados").  
3. **Si fue del banco**, llama al número oficial (no el de la llamada) y explica que diste un código de 2FA por error. Ellos pueden bloquear operaciones y revertir transferencias si actúas en minutos.  
4. **Si fue de WhatsApp**, abre WhatsApp (si aún puedes), ve a Ajustes > Dispositivos vinculados y cierra sesión en todos. Luego activa la verificación en dos pasos de WhatsApp (código de 6 dígitos).

### Si instalaste software de acceso remoto (TeamViewer, AnyDesk):

1. **Desconecta internet inmediatamente** (quita el cable, apaga el WiFi, o activa el modo avión).  
2. **Desinstala ese programa** desde el panel de control (Windows) o elimínalo (Mac).  
3. **Ejecuta un análisis antivirus** completo (Windows Defender offline o Malwarebytes).  
4. **Cambia todas tus contraseñas** desde otro dispositivo (porque podrían haber instalado un keylogger o robado las guardadas).  
5. **Si el equipo sigue siendo sospechoso**, formatea e instala el sistema desde cero (es la única forma de estar seguro).

### Si transferiste dinero o diste datos de tarjeta:

1. **Llama al banco oficial inmediatamente** (el número de tu tarjeta o de tu oficina). Pide que anulen la transferencia si aún no se ha procesado (en Bizum o transferencias instantáneas es casi imposible, pero inténtalo).  
2. **Si diste número de tarjeta, fecha y CVV**, solicita el bloqueo de la tarjeta y que te envíen una nueva.  
3. **Si fue transferencia a una cuenta**, denuncia a la policía con los datos del destinatario (nombre, número de cuenta, IBAN). A veces se puede congelar la cuenta si actúas rápido.  
4. **Si fueron tarjetas regalo** (Amazon, Google Play, iTunes), contacta con el servicio de soporte de la plataforma. A veces pueden anular los códigos si no se han usado aún.

### Si te han grabado diciendo "sí":

No es tan grave como parece. Para autorizar cargos necesitan más datos. Pero si te preocupa, contacta con tu banco y diles que desautorizas cualquier cargo que usara una grabación de voz.

---

## 10. Cómo proteger a los más vulnerables (adultos mayores, niños, personas con discapacidad)

### Para adultos mayores (especialmente los que viven solos y tienen teléfono fijo)

1. **Póster junto al teléfono fijo:** Imprime las "3 reglas de oro" y pégalo junto al teléfono.  
- **Regla 1:** El banco, Microsoft y Hacienda NO llaman pidiendo códigos.  
- **Regla 2:** Si te piden un código SMS, es estafa. NO lo des.  
- **Regla 3:** Cuelga y llama al número oficial (el que tienes en la tarjeta o factura).  

2. **Código secreto familiar:** Establece una palabra o frase que solo la familia sepa (ej: "Fresa con chocolate"). Si alguien llama diciendo ser un familiar y pide dinero, se le pide la palabra. Si no la sabe, colgar.

3. **Teléfono fijo sin marcación directa a servicios externos:** Algunos teléfonos permiten bloquear llamadas entrantes de números desconocidos. Consulta con tu operadora.

4. **Revisión periódica de facturas y movimientos bancarios:** Si puedes, revisa tú mismo las cuentas de tus padres una vez al mes. Los estafadores a veces hacen cargos pequeños (10-20€) que pasan desapercibidos.

5. **No culparles si caen:** Si tu padre o madre cae en una estafa, no le digas "cómo pudiste ser tan tonto". La vergüenza hace que no te lo cuenten. La próxima vez caerán más. En su lugar: "Tranquilo, nos pasa a muchos. Vamos a arreglarlo".

### Para niños (cuando usan el teléfono)

- Regla simple: "Nunca des tu nombre, dirección, o contraseña por teléfono a nadie que no sea mamá o papá, aunque diga que es de la policía o del colegio".  
- Si reciben una llamada rara, que cuelguen y te avisen.

### Para personas con discapacidad cognitiva

- Supervisión de llamadas (si es posible).  
- Teléfonos con lista blanca (solo permiten llamadas de números autorizados).  
- Explicación simple y repetida: "Si no conoces el número, no lo coges".

---

## 11. Herramientas para bloquear y reportar llamadas fraudulentas

### En el móvil (Android / iOS)

- **Bloquear número manualmente:** Después de la llamada, ve al registro de llamadas, pulsa el número y selecciona "Bloquear".  
- **Listas de spam integradas:**  
- Android (Google Phone): Ajustes > Identificador de llamadas y spam > Activar.  
- iOS: Ajustes > Teléfono > Silenciar llamadas de desconocidos (las enviará al buzón de voz).  
- **Apps especializadas (con cuidado):**  
- Truecaller (identifica spam, pero comparte tus contactos con ellos; úsala solo para consultas puntuales).  
- Hiya, Call Blocker (menos intrusivas).  

### En teléfonos fijos

- Algunos operadores ofrecen servicio de "lista Robinson" (para evitar llamadas comerciales). No es 100% efectivo contra estafas porque suplantan números, pero reduce el volumen.  
- Lo mejor es **no coger el fijo si no reconoces el número**. Si es importante, te dejarán un mensaje de voz.  
- Algunos teléfonos modernos permiten bloquear números fijos. Consúltalo con tu operadora.

### Reportar números de estafa

- **España:** Puedes reportar el número en la web de la Oficina de Seguridad del Internauta (OSI) o en la app "Alertas de fraude" de la Policía Nacional.  
- **Listas colaborativas:**  
- `quienmehllamado.es` (buscador de números reportados).  
- `listaspam.com` (foro de números de spam).  
- **Tu operadora:** Algunas permiten reportar llamadas maliciosas (Movistar, Vodafone, Orange tienen formularios).

**Importante:** Los estafadores cambian de número constantemente. Bloquear uno no es suficiente; lo importante es entrenarte para no caer.

---

## 12. Ejercicios prácticos

### Ejercicio 1 – El test de los 5 segundos

Pon un cronómetro. Cuando suene el teléfono y veas un número desconocido, tienes 5 segundos para decidir si coges. La regla: si no esperas ninguna llamada importante, **no cojas**. Deja que vaya al buzón de voz. Si es real, te dejarán mensaje.

Practica esto durante una semana.

### Ejercicio 2 – La búsqueda inversa del número

Durante una semana, cada vez que recibas una llamada de un número que no conoces (aunque no la cojas), búscalo en Google o en `quienmehllamado.es`. Apunta cuántos de esos números ya están reportados como estafa. Te sorprenderás.

### Ejercicio 3 – El código secreto familiar (repaso y práctica)

Reúne a tu familia (presencial o por grupo de WhatsApp). Acordaos de la palabra secreta (ej: "pelícano rojo" o "la casa del abuelo"). Practica: "Si alguien llama pidiendo dinero urgente en nombre de la familia, pedidle la palabra. Si no la sabe, colgad".

Luego haz una llamada simulada (sin avisar) a un familiar (usa otro móvil o un número desconocido). Finge ser un nieto en apuros. Si te pide la palabra secreta y acierta, felicítale. Si no, practica de nuevo.

### Ejercicio 4 – Graba tu respuesta estándar para el buzón de voz

Graba un mensaje corto en tu buzón de voz (el del móvil o el del fijo):

> *"En este momento no puedo atender. Si es una llamada importante, por favor deje un mensaje. Si es una empresa o un banco, cuelgo y llamo yo a su número oficial. Gracias."*

Eso filtra a los estafadores (no suelen dejar mensaje).

### Ejercicio 5 – Formación de 5 minutos semanal con tus padres

Cada domingo, dedica 5 minutos con tu familiar mayor (presencial o por teléfono) a repasar una estafa concreta. Ejemplo:  
**Tú:** "Esta semana, si te llaman del banco pidiendo un código SMS, ¿qué haces?"  
**Ellos:** "Cuelgo y llamo al número de la tarjeta".  
**Tú:** "Perfecto. Si te dicen que tu ordenador tiene virus, ¿qué haces?"  
**Ellos:** "Cuelgo".  

Repite cada semana. La repetición es la madre de la retención.

### Ejercicio 6 – Prepara el póster de la nevera

Imprime el póster de la sección 10 (3 reglas de oro) y pégalo junto al teléfono fijo de tus padres. Tómate una foto y envíala al grupo familiar para que todos lo vean.

---

## 13. Glosario

| Término | Significado |
|---------|-------------|
| **Vishing** | Estafa por llamada telefónica (voz + phishing). |
| **Spoofing** | Suplantación del número de teléfono o correo electrónico. |
| **Call center ilegal** | Operación organizada de estafas telefónicas. |
| **Código SMS** | Código de 2FA que nunca se debe dar por teléfono. |
| **SIM swapping** | Robo de la identidad móvil para recibir SMS. |
| **TeamViewer / AnyDesk** | Programas de acceso remoto legítimos, usados por estafadores. |
| **Código secreto familiar** | Palabra o frase acordada para verificar identidad. |
| **Lista Robinson** | Lista para evitar llamadas comerciales (no estafas, pero ayuda). |

---

## 14. Conclusión y recursos

**Resumen ejecutivo:**

- Las estafas de call center son una industria multimillonaria. Operan desde otros países, suplantan números reales, y usan guiones profesionales.  
- Los más vulnerables son los adultos mayores que viven solos y tienen teléfono fijo.  
- **Ninguna entidad legítima te pide códigos SMS, contraseñas, o transferencias urgentes por teléfono.**  
- La única defensa efectiva es un **protocolo simple**: cuelga, verifica por otro canal, no des códigos, no instales programas remotos.  
- El **código secreto familiar** puede salvar a tus seres queridos.

**Tu plan de acción a partir de hoy:**

1. **Enseña a tu familia las 3 reglas de oro** (póster junto al teléfono).  
2. **Establece un código secreto familiar** y practícalo.  
3. **Configura el bloqueo de llamadas desconocidas** en los móviles de los mayores.  
4. **Practica simulaciones** una vez al mes (pueden ser de 2 minutos).  
5. **Si tus padres viven solos**, revisa sus extractos bancarios y facturas con ellos una vez al mes.  
6. **Si caen, no los culpes.** Actúa rápido: cambia contraseñas, avisa al banco, denuncia.

**Recursos gratuitos adicionales:**

- **Lista Robinson** (www.listarobinson.es) – para evitar llamadas comerciales (no todas las estafas, pero reduce ruido).  
- **OSI – Oficina de Seguridad del Internauta** (www.osi.es) – ejemplos actualizados de estafas telefónicas.  
- **INCIBE – Ayuda para víctimas** (017).  
- **Quienmehllamado.es** – buscador de números reportados.  
- **Foro de estafas telefónicas en Burbuja.info** – casos reales.

---

## 15. Gancho para el Módulo 17

Ya sabes cómo detectar una estafa telefónica y proteger a tus seres queridos. Pero hay un tipo de estafa que **no te llama por teléfono ni te envía un correo**. Ocurre cuando **tú buscas ayuda** en internet después de un problema.

En el **Módulo 17** (7 de la serie ciudadano) vamos a hablar de las **estafas de soporte técnico falso en buscadores y anuncios**. Esa vez que buscas "teléfono de atención al cliente de Amazon" y llamas al primer número que aparece… que es de un estafador. O cuando tu ordenador se bloquea con un mensaje falso de "Microsoft" y un número de teléfono para "solucionarlo".

Te contaré la historia de la mujer que perdió 4.000€ por llamar al primer resultado de Google, y la del jubilado que creyó que su ordenador estaba infectado por una ventana emergente.

**No te lo pierdas. Porque la estafa puede estar esperándote en la primera página de resultados de búsqueda.**

---
**Condor2026** – **SpectrumSecurity** - Ciberseguridad para humanos.
---
*Módulo 16 de 24.*
---
