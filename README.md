# Practica 1 De Redes - DNS y hosting:

## Paso 1. Registro en afraid.org y elección del subdominio

  1. Accede al servicio FreeDNS (afraid.org) y crea una cuenta de usuario.
  2. Explora los dominios disponibles y selecciona uno que permita el registro
  de subdominios gratuitos.
  3. Registra un subdominio que consista en tus apellidos y nombre, separados
  por guiones. Por ejemplo, perez-lopez-juan.mooo.com.

Advertencia: Para el registro en FreeDNS se envía un correo de activación que es
posible que tarde minutos u horas.

## Paso 2. Creación del repositorio y activación de GitHub Pages

  1. Accede a tu cuenta de GitHub.
  2. Crea un nuevo repositorio que se utilizará para alojar el sitio web.
  3. Configura el repositorio para que se publique mediante GitHub Pages,
  utilizando una de las opciones disponibles.
  4. Activa el acceso con HTTPS.
  5. Comprueba que GitHub Pages genera una URL temporal de acceso al sitio.

Advertencia: Los cambios en GitHub Pages pueden tardar unos minutos en reflejarse. 
Tenlo en cuenta antes de asumir que existe un error de configuración.

## Paso 3. Creación del sitio web mínimo

  1. Crea un archivo index.html en el repositorio configurado.
  2. El contenido del sitio debe incluir, como mínimo:
    • Texto identificativo del alumno, incluyendo nombre y un enlace a su
    dirección de correo electrónico.
    • Un enlace visible a la página https://freedns.afraid.org con el texto
    “Free DNS”, tal y como se indica en el propio servicio.
    • Utilizar, al menos, las etiquetas HTML: h1, h2 y p.
  3. Publica los cambios y verifica que el sitio es accesible a través de la URL
  proporcionada por GitHub Pages.

Nota: No es necesario incluir hojas de estilo ni contenido avanzado, aunque está
permitido. El objetivo es comprobar el correcto funcionamiento del acceso web.

## Paso 4. Configuración DNS del subdominio

  1. Accede al panel de gestión de afraid.org.
  2. Configura los registros DNS necesarios para que el subdominio apunte al
  sitio publicado en GitHub Pages. En este caso, es necesario crear varios
  registros A para las direcciones IP de GitHub Pages.
  3. Guarda los cambios y espera a que la configuración se propague.

Advertencia: La propagación DNS no es inmediata. En algunos casos puede
tardar varios minutos u horas.

## Paso 5. Comprobación del acceso al sitio web

  1. Accede al sitio web utilizando el subdominio registrado.
  2. Verifica que el contenido se muestra correctamente y que el navegador
  resuelve el nombre sin errores.
  3. Realiza la comprobación desde un navegador o dispositivo distinto si es
  posible.

## Paso 6. Verificación del acceso mediante HTTPS

  1. Comprueba que el sitio web es accesible mediante HTTPS.
  2. Verifica que el navegador no muestra advertencias de seguridad.
  3. Asegúrate de que el acceso seguro funciona correctamente usando el
  subdominio configurado
