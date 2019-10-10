# Beep Keyboard #

* Autor: David CM
* Descargar [versión estable][1]
* Descargar [versión de desarrollo][2]
* Compatibilidad con NVDA: de 2018.2 a 2019.2

Este complemento permite al usuario configurar NVDA para que pite con
algunos eventos de teclado.

## Características

Este complemento proporciona las siguientes características que puedes usar
para adaptar el comportamiento de teclado de NVDA:

* Pitar para mayúsculas cuando el bloqueo mayúsculas está activado: si esta
  característica está habilitada, NVDA pitará cuando escribas una letra
  mayúscula y el bloqueo mayúsculas esté activo. ¡No cometas más errores de
  mayúsculas!
* Pitar para caracteres escritos cuando la tecla shift esté presionada: con
  esta característica NVDA pitará si escribes un carácter con la tecla shift
  presionada.
* Pitar cuando cambia el estado de las teclas interruptores: con esta
  característica, NVDA producirá un tono alto cuando el interructor se
  activa, y uno bajo si se desactiva. Ten en cuenta que Windows dispone de
  una función de pitidos para teclas de alternancia incorporada en el centro
  de accesibilidad. Esta característica nativa funciona bien si no usas el
  ajuste de la disposición de teclado portátil.
* Anunciar el cambio de estado de las teclas interruptores: Solo para cuando
  "Pitar cuando cambia el estado de las teclas" está habilitado. Puedes
  habilitar o deshabilitar el anunciado de las teclas interruptores cuando
  estas cambian su estado.
* Pitar para caracteres específicos: en las opciones avanzadas, puedes
  configurar NVDA para que emita un pitido con los caracteres que desees.
* Desactivar los pitidos en los campos de contraseña: esta función está
  activada por defecto para evitar riesgos de seguridad. Desactívala si
  quieres oír pitidos en los campos de contraseña.

## Requisitos

Necesitarás NVDA 2018.2 o posterior.

## Instalación

Instala este complemento como cualquier otro.

## Uso

Para activar o desactivar características, ve  a las configuraciones de NVDA y selecciona la categoría beep keyboard. En esa categoría podrás habilitar o deshabilitar cualquier característica soportada por este complemento.

* "Pitar para mayúsculas cuando el bloqueo mayúsculas está activado" está
  habilitado por defecto.

Si necesitas ajustes adicionales, abre el cuadro de diálogo de opciones
avanzadas, que contiene las siguientes opciones:

* Ignorar caracteres escritos con la tecla shift presionada: todos los
  caracteres escritos aquí serán ignorados al emitir el pitido cuando la
  tecla shift sea presionada. Se permiten secuencias de escape, EJ. "\t"
  para tab, "\r" para la tecla enter.
* Pitar siempre para los siguientes caracteres: ingresa aquí todos los
  caracteres escritos para los que quieras que NVDA emita un pitido. Se
  permiten secuencias  de escape, EJ. "\t" para tab, "\r" para la tecla
  enter.
* Seleccionar un tono para su configuración: puedes configurar parámetros
  para todos los tonos. Selecciona uno aquí, y ajusta los parámetros en los
  siguientes cuadros de texto. Al cambiar de opción, NVDA emitirá el pitido
  del tono seleccionado con los parámetros configurados en ese momento.
* Tono: tono para el tono seleccionado actualmente.
* Duración: duración para el tono seleccionado actualmente.
* Volumen: volumen para el tono seleccionado actualmente.
* Probar el tono: este botón te permite reproducir un tono de prueba con los
  parámetros establecidos actualmente.
* Presiona el botón Aceptar para guardar las configuraciones o cancelar para
  descartarlas.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
