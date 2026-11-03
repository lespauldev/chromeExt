# Política de privacidad de GLB Cleaner

**Última actualización: 2 de noviembre de 2026**

GLB Cleaner es una extensión para Google Chrome que, después de que el usuario la active pulsando el icono, elimina elementos `DIV` de la pestaña actual cuando sus clases coinciden con las palabras configuradas. El acceso se limita a la pestaña en la que el usuario realiza esa acción y no se mantiene al navegar o recargarla.

## Datos que procesa la extensión

- **Reglas de configuración:** las palabras o fragmentos de texto que el usuario introduce para identificar elementos.
- **Estado temporal por pestaña:** si GLB Cleaner está activada o desactivada en la pestaña actual. Este estado se conserva en el almacenamiento de sesión del navegador y se elimina al navegar, cerrar la pestaña o finalizar la sesión.
- **Contenido de la página actual:** mientras está activada, la extensión examina localmente los atributos `class` de elementos `DIV` de esa pestaña para compararlos con las reglas. Si coinciden, elimina esos elementos de la página mostrada.

El examen se realiza en el navegador. GLB Cleaner no recopila ni almacena el contenido de las páginas, el historial de navegación, las direcciones visitadas, datos de formularios ni información personal de los usuarios.

## Almacenamiento y sincronización

Las reglas se guardan mediante `chrome.storage.sync`. Chrome puede sincronizarlas entre los dispositivos del usuario cuando la sincronización de Chrome está habilitada. El tratamiento de esa sincronización se rige también por las políticas y la configuración de privacidad de Google. El estado de activación por pestaña se guarda temporalmente en el almacenamiento de sesión de Chrome y no se sincroniza.

GLB Cleaner no envía estos datos al desarrollador ni a servidores externos operados por el desarrollador.

## Uso y divulgación de datos

La extensión utiliza las reglas y el estado únicamente para aplicar la configuración elegida por el usuario. No vende datos, no los utiliza para publicidad ni los transmite por iniciativa propia a terceros. Si la sincronización de Chrome está habilitada, Chrome puede sincronizar las reglas conforme a la configuración y las políticas de Google.

## Permisos

GLB Cleaner solicita `storage` para guardar las reglas y `activeTab` junto con `scripting` para ejecutar su función únicamente en la pestaña actual después de que el usuario pulse el icono. No solicita acceso general a todos los sitios. La extensión no utiliza el acceso a la página para recopilar o transmitir información.

## Conservación y control

El usuario puede cambiar o borrar las reglas desde las opciones de la extensión. Al guardar la configuración sin reglas, la extensión deja de eliminar elementos. También puede desactivar GLB Cleaner desde su icono, navegar o recargar la pestaña para que cese su acceso, o desinstalarla. La disponibilidad o eliminación de las reglas sincronizadas puede depender de la configuración y las políticas de sincronización de Chrome.

## Privacidad de menores

GLB Cleaner no está dirigida específicamente a menores y no recopila deliberadamente datos personales.

## Cambios a esta política

Esta política podrá actualizarse si cambian las funciones o las prácticas de privacidad de GLB Cleaner. La fecha de actualización se indicará al principio de esta página.

## Contacto

Para consultas sobre esta política, contacta al desarrollador en: **[añadir correo de contacto antes de publicar]**.
