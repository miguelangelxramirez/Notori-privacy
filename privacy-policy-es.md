---
title: Política de privacidad de Notori
permalink: /privacy-policy-es/
---

# Política de privacidad de Notori

Actualizado el 19 de octubre de 2026

## Privacidad de un vistazo

Notori es una app de notas con IA. Tus notas se guardan en tu dispositivo y, si usas iCloud, en tu propia cuenta de iCloud; Notori no tiene cuentas de usuario ni guarda tus notas en un servidor propio. La IA forma parte del servicio: para organizar tus notas y responder tus preguntas, su contenido se envía al servidor de Notori en Cloudflare y a OpenAI. Notori no vende datos, no muestra publicidad, no usa rastreadores publicitarios ni te sigue entre apps o sitios web.

## 1. Responsable y contacto

El responsable del tratamiento es Miguel Ángel Ramírez Ciarreta, persona física y desarrollador de Notori, con NIF 02309978L y domicilio en Calle Salvador Martínez 30, 28041 Madrid, España. Para cualquier pregunta o solicitud de privacidad, escribe a [miguelangelxramirez@gmail.com](mailto:miguelangelxramirez@gmail.com) (también el contacto de soporte enlazado en la ficha de Notori en App Store). No estoy inscrito en el Registro Mercantil ni adherido a códigos de conducta.

## 2. Datos guardados en tu dispositivo y en iCloud

Tus notas, enlaces, fotos y archivos adjuntos con su texto reconocido, ediciones, y los temas y relaciones derivados se guardan en el contenedor privado de la app o del App Group de Notori. Cuando iCloud está disponible, Notori sincroniza esta base de datos con tu base de datos privada de iCloud (CloudKit), de modo que puede aparecer en tus otros dispositivos con el mismo Apple Account. Para lo que Notori guarda en CloudKit, Apple actúa como encargado del tratamiento (agente del desarrollador) según el Apple Developer Program License Agreement (Anexo 4, §3.6); según ese mismo acuerdo (§3.5), Apple no accede a los datos de un contenedor privado salvo por obligación legal o a petición tuya. Notori no gestiona ninguna cuenta ni servidor para esa copia y no puede leerla. Tu cuenta de iCloud la gestiona Apple Distribution International Ltd. (Irlanda) como responsable, según las Condiciones de iCloud y la Política de privacidad de Apple. El índice de búsqueda local, los ajustes, el registro de tu aceptación del aviso de IA y su versión, el resumen para widgets y la cola de tareas de IA pendientes se guardan solo en el dispositivo y no se sincronizan. Para dejar de sincronizar, ve a Ajustes → tu nombre → iCloud, toca «Ver todo» junto a «Guardado en iCloud» y desactiva Notori; las copias que ya estén en iCloud permanecen hasta que las elimines, como se explica en el apartado 10. Apple también puede incluir datos de la app en copias del dispositivo según tus ajustes de iCloud o de copia de seguridad.

## 3. Procesamiento con IA

Antes de usar Notori aceptas una sola vez el aviso de IA, identificado por su versión; solo se te vuelve a pedir si cambia esa versión. A partir de ahí, Notori envía al Worker de Cloudflare de Notori, y este a OpenAI, lo necesario para cada tarea: el texto de tus notas y de sus archivos adjuntos; en los enlaces, la dirección, el título y el texto leído de la página; tus preguntas y fragmentos limitados de las notas relevantes para responderlas; el idioma de la app, la fecha y la hora de la nota y tu zona horaria, para interpretar expresiones como «ayer»; e identificadores técnicos aleatorios de la nota y de la solicitud. Para las fotos que guardas, también se envía una copia reducida de la imagen junto al texto reconocido en ella, para describir objetos y escenas, no solo palabras. La copia enviada se genera sin los metadatos del archivo original; la foto original permanece guardada en el dispositivo. Este envío requiere aceptar el aviso actualizado, aunque ya hubieras aceptado el procesamiento de texto. El Worker pide a OpenAI store:false, para que no guarde la respuesta, y le envía como identificador de seguridad una huella (hash SHA-256) del identificador de instalación, que OpenAI usa para detectar abusos; OpenAI no recibe tu nombre, tu correo ni tu Apple Account. OpenAI indica que, por defecto, no usa los datos de la API para entrenar sus modelos y que sus registros para detectar abusos pueden conservar contenido hasta 30 días, salvo que la ley le obligue a conservarlo más tiempo o sea necesario para proteger sus servicios o a terceros. En algunas solicitudes (organizar notas y construir temas), el Worker conserva el resultado hasta 24 horas, asociado al identificador de instalación, para poder recuperar una solicitud interrumpida sin repetirla; después se elimina automáticamente. Notori no usa la búsqueda web de OpenAI: las respuestas se basan solo en lo que envías. No hay un ajuste para desactivar la IA ni un modo de uso exclusivamente local. Si no aceptas este procesamiento, no uses Notori; puedes exportar tus notas y borrar tus datos en cualquier momento. No incluyas información que no quieras que procesen estos proveedores, en especial datos de salud u otras categorías especiales de datos, o datos de otras personas.

## 4. Lectura de enlaces

Cuando guardas un enlace, tu dispositivo descarga directamente esa página, sin cookies, para leer su título y su texto; en los vídeos de TikTok consulta además la vista previa pública que ofrece TikTok. Esa web recibe la solicitud como en cualquier visita, incluida tu dirección IP, y la trata según su propia política. El texto obtenido se guarda con la nota y se procesa con IA como se describe arriba.

## 5. Seguridad del servicio

Notori crea un identificador aleatorio y persistente de instalación, guardado en el llavero de este dispositivo, y usa Apple App Attest para comprobar que las solicitudes proceden de una copia auténtica de la app. Con ello el Worker aplica límites de frecuencia, de tamaño y de uso diario, e investiga abusos. Cloudflare guarda en la Unión Europea (Durable Objects con jurisdicción UE) la clave pública de App Attest y su recibo, asociados a una huella del identificador de instalación, y contadores de uso que se renuevan cada minuto y cada día. Cloudflare también trata tu dirección IP para establecer la conexión y conserva registros técnicos de las solicitudes (fecha, ruta, resultado e identificadores técnicos, sin el contenido de tus notas) hasta 7 días. El identificador no se usa para publicidad ni para seguimiento entre apps.

## 6. Compras

Apple procesa la información de pago. RevenueCat recibe un identificador anónimo y persistente de usuario de la app, el estado de suscripción y compra, y el idioma y la moneda de la tienda, para que Notori pueda ofrecer, restaurar y gestionar el acceso Premium y la prueba gratuita, analizar la fiabilidad de las compras y prevenir fraude. Notori no recibe los datos completos de tu tarjeta. Estos datos no se usan para seguimiento publicitario.

## 7. Finalidades y bases jurídicas

- Prestar el servicio que contratas: guardar y sincronizar tus notas, leer tus enlaces, organizarlas y responder tus preguntas con IA, y gestionar tu suscripción o tu prueba gratuita. Base jurídica: ejecución del contrato (art. 6.1.b del RGPD). Aceptar el aviso de IA forma parte de aceptar ese contrato; no es un consentimiento separado.
- Proteger el servicio: verificar el dispositivo, aplicar límites, investigar y prevenir abusos y fraude, y analizar la fiabilidad de las compras. Base jurídica: interés legítimo en mantener un servicio seguro y evitar usos fraudulentos (art. 6.1.f del RGPD).
- Cumplir obligaciones legales y atender requerimientos de las autoridades. Base jurídica: obligación legal (art. 6.1.c del RGPD).

Facilitar estos datos es un requisito contractual: son necesarios para usar Notori y, sin ellos, no podemos prestar el servicio. Notori no toma decisiones basadas únicamente en tratamiento automatizado que produzcan efectos jurídicos sobre ti o te afecten de forma significativa similar (art. 22 del RGPD): la IA solo organiza tus notas y responde tus preguntas, y los límites de uso son controles técnicos de seguridad.

## 8. Destinatarios y encargados del tratamiento

- Cloudflare, Inc. (EE. UU.), encargado del tratamiento: aloja el Worker de Notori, su almacenamiento en la UE y sus registros técnicos.
- OpenAI, encargado del tratamiento: procesa con IA el contenido descrito arriba.
- RevenueCat, Inc. (EE. UU.), encargado del tratamiento: gestiona las suscripciones.
- Apple: encargado del tratamiento para iCloud (CloudKit), donde guarda y sincroniza tus notas como se explica en el apartado 2. Además procesa los pagos de App Store, la verificación App Attest y las copias de seguridad conforme a sus propias condiciones y su política de privacidad. Notori no incluye herramientas de analítica ni de informes de fallos de terceros; si en tu dispositivo activas compartir análisis con desarrolladores, Apple puede facilitar al desarrollador informes de fallos y rendimiento.
- Las webs de los enlaces que guardas, como se explica en el apartado 4.

Notori solo comparte datos con ellos cuando es necesario para prestar el servicio, protegerlo, cumplir la ley o completar una transacción. Notori no vende datos personales.

## 9. Transferencias internacionales

Cloudflare, OpenAI y RevenueCat son empresas de EE. UU. y pueden tratar datos fuera del Espacio Económico Europeo. Cloudflare está certificada en el Marco de Privacidad de Datos UE-EE. UU., que cuenta con una decisión de adecuación de la Comisión Europea (art. 45 del RGPD), y su acuerdo de tratamiento incluye además cláusulas contractuales tipo. OpenAI y RevenueCat no figuran en ese Marco; sus transferencias se amparan en las cláusulas contractuales tipo aprobadas por la Comisión Europea e incluidas en sus acuerdos de tratamiento de datos (art. 46.2.c del RGPD). Apple también puede tratar fuera del Espacio Económico Europeo lo que Notori guarda en iCloud (CloudKit); para esas transferencias, el Apple Developer Program License Agreement prevé cláusulas contractuales tipo («Model Contract Clauses»), que Apple facilita a petición. Puedes pedir información sobre estas garantías en la dirección de contacto.

## 10. Conservación y eliminación

Tus notas se conservan en tus dispositivos y en tu iCloud hasta que las borres. Los elementos que mueves a la papelera de Notori permanecen en tus dispositivos hasta que los restauras o eliminas los datos de la app. Puedes eliminar definitivamente elementos de la papelera en cualquier momento; con iCloud activado, esa eliminación se sincroniza con tu copia privada de iCloud y con tus otros dispositivos cuando estén conectados. «Borrar todos mis datos» en Ajustes elimina tus notas y los datos derivados de este dispositivo y pide a iCloud que elimine la zona privada de Notori en tu base de datos de iCloud (CloudKit), incluidos los cambios que este dispositivo aún no ha descargado. Requiere conexión y una cuenta de iCloud. Notori indica que los datos están borrados solo cuando eso ha terminado; si no puede conectar con iCloud, te avisa de que solo se ha borrado este dispositivo y puedes repetir el borrado más tarde. Puedes exportar tus notas en Markdown desde Ajustes. Exportar y borrar tus datos también funciona sin suscripción. Si la sincronización con iCloud está desactivada, estas eliminaciones solo se aplican a este dispositivo y las copias que ya estén en iCloud deben eliminarse en los ajustes de almacenamiento de iCloud. Como las notas se sincronizan con iCloud, un cambio o una eliminación hecho en un dispositivo también se aplica en tus otros dispositivos. Eliminar la app y sus datos borra la base de datos local de ese dispositivo, pero no las copias ya sincronizadas en iCloud, que pueden volver a descargarse si reinstalas Notori con iCloud activado; puedes eliminarlas en los ajustes de almacenamiento de iCloud. Pueden quedar copias en las copias de seguridad de Apple hasta que caduquen o las elimines. En los servidores: los resultados que el Worker conserva temporalmente se eliminan automáticamente en un máximo de 24 horas; los registros técnicos de Cloudflare, en un máximo de 7 días; los registros de OpenAI para detectar abusos, en el plazo indicado en el apartado 3. La clave pública de App Attest y su recibo no caducan automáticamente: se conservan mientras sirvan para verificar esa instalación y no contienen el contenido de tus notas. RevenueCat conserva el historial de compras asociado al identificador anónimo mientras Notori utilice su servicio, salvo que se solicite su eliminación.

## 11. Tus derechos

Tienes derecho a acceder a tus datos, rectificarlos, suprimirlos, limitar su tratamiento, a su portabilidad y a oponerte al tratamiento basado en interés legítimo (arts. 15 a 21 del RGPD). Puedes ejercer gran parte de ellos en la propia app: editar o eliminar notas, exportarlas en Markdown y usar «Borrar todos mis datos». Para lo demás, escribe a [miguelangelxramirez@gmail.com](mailto:miguelangelxramirez@gmail.com); responderemos en el plazo de un mes, prorrogable en los casos que prevé el art. 12 del RGPD. Como Notori no tiene cuentas, los datos de los servidores solo están asociados a identificadores aleatorios y puede que necesitemos información adicional para relacionarlos con tu instalación (art. 11 del RGPD). Las suscripciones se gestionan en los ajustes de suscripciones de Apple. Si consideras que el tratamiento de tus datos no es correcto, puedes presentar una reclamación ante la Agencia Española de Protección de Datos ([www.aepd.es](https://www.aepd.es)) o ante la autoridad de control de tu país de residencia.

## 12. Menores

Notori no está dirigido a niños. No uses Notori si no tienes la edad mínima que exige la ley de tu país para aceptar por ti mismo el tratamiento de tus datos (en España, 14 años).

## 13. Cambios en esta política

Si esta política cambia, se actualizará la fecha de arriba. Si cambia el aviso de IA, la app te pedirá que aceptes la nueva versión antes de seguir enviando contenido a la IA. Esta misma política está publicada en <https://miguelangelxramirez.github.io/Notori-privacy/>.
