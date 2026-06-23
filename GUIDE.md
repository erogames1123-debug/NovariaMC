# Guia de NovariaMC

Esta guia explica el flujo basico para instalar NovariaMC, preparar dependencias, crear un servidor y abrirlo desde una PC o un cliente de Minecraft.

NovariaMC sigue en desarrollo activo, asi que algunas pantallas pueden cambiar con el tiempo.

## 1. Instalar la app

1. Descarga el APK mas reciente desde la pagina de Releases:
   https://github.com/ErogamesMC/NovariaMC/releases/latest
2. Instala el APK en tu dispositivo Android.
3. Abre NovariaMC.
4. Si Android pide permisos, permite los necesarios para acceso a archivos, acceso a red y funcionamiento en segundo plano.

## 2. Instalar dependencias

Abre la pantalla de dependencias desde el boton de descarga en la barra superior.

Configuracion recomendada:

- Instala Java 21 para Paper, Fabric, NeoForge modernos y versiones recientes de Minecraft.
- Instala Java 8 solo cuando trabajes con Forge antiguo o servidores legacy.
- Instala Playit si quieres que amigos fuera de tu red local se conecten.
- Instala Chunker si planeas importar o convertir mundos Bedrock `.mcworld`.

Si una dependencia falla, reinstalala desde esta pantalla antes de crear o iniciar un servidor.

## 3. Crear un servidor

1. Toca el boton `+` en la pantalla principal.
2. Elige el tipo de servidor y la version de Minecraft.
3. Espera a que NovariaMC descargue y prepare el servidor.
4. Abre la consola del servidor.
5. Inicia el servidor.

El primer inicio puede tardar mas porque Minecraft genera carpetas, ajustes, mundos y archivos de cache.

## 4. Gestionar el servidor

Desde la pantalla de gestion del servidor puedes:

- Editar los ajustes del servidor.
- Cambiar RAM, jugadores, distancia de vision, distancia de simulacion, dificultad, PvP y otras opciones.
- Gestionar archivos.
- Gestionar mundos.
- Importar archivos `.mcworld`.
- Crear y restaurar copias de seguridad.
- Buscar mods o plugins cuando el tipo de servidor lo soporte.

Deten el servidor antes de reemplazar mundos, cambiar archivos importantes o modificar configuraciones grandes de mods/plugins.

## 5. Usar el panel web local

El panel web local te permite gestionar el servidor desde una PC en la misma red Wi-Fi.

1. Abre la consola del servidor en NovariaMC.
2. Toca `Panel local para PC`.
3. Copia el enlace LAN.
4. Abre ese enlace desde el navegador de tu PC.

El telefono y la PC deben estar conectados a la misma red local.

## 6. Acceso publico con Playit

Playit permite que personas fuera de tu red local se conecten.

Flujo basico:

1. Instala Playit desde dependencias.
2. Abre la consola de un servidor.
3. Abre la pestaña de Playit.
4. Reclama o configura el agente de Playit.
5. Inicia el servidor y manten Playit activo.

Si Playit dice que el agente no tiene tuneles asignados, abre la pagina de cuenta de Playit y asigna el tunel al agente actual.

## 7. Importar mundos

Para archivos Bedrock `.mcworld`:

1. Deten el servidor.
2. Abre el gestor de archivos del servidor o las herramientas de mundos.
3. Sube el `.mcworld`.
4. NovariaMC lo importara o convertira cuando sea compatible.
5. Inicia el servidor otra vez.

Los mundos grandes pueden tardar varios minutos en procesarse.

## 8. Problemas comunes

### El servidor no inicia

- Verifica que el runtime Java correcto este instalado.
- Abre la consola y lee el primer error mostrado.
- Intenta bajar la RAM asignada.
- Asegurate de que la version del servidor coincida con el runtime seleccionado.

### Mis amigos no se pueden conectar

- Confirma que el servidor este encendido.
- Confirma que Playit este activo si estan fuera de tu red Wi-Fi.
- Revisa que el tunel apunte al puerto local correcto.
- Para configuraciones compatibles con Bedrock, verifica el puerto Bedrock correcto.

### La app se siente lenta

- Baja la RAM, la distancia de vision y la distancia de simulacion.
- Cierra otras apps.
- Mantene el telefono fresco y conectado a la corriente para servidores mas grandes.
- Prefiere tipos de servidor ligeros cuando uses dispositivos de gama baja.

### Un modpack no funciona

- Confirma que soporte la version del servidor y el loader.
- Revisa si es solo para cliente.
- Asegurate de que las dependencias requeridas esten instaladas.
- Lee los logs de la consola del servidor para detectar mods faltantes o versiones incompatibles.

## 9. Apoyar el desarrollo

Si NovariaMC te ayuda, puedes apoyar el desarrollo mediante Ko-fi:

https://ko-fi.com/uwuzzi

## 10. Aviso legal

NovariaMC es un proyecto independiente y no esta afiliado con Mojang, Microsoft, Minecraft, PaperMC, GeyserMC, Playit ni otros proyectos de terceros usados o soportados por la app.
