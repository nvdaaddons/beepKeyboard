# Beep Keyboard #

* Author: David CM
* Descargar [Versión estable][1]
* Download [Versión de desenvolvemento][2]
* Compatibilidade con NVDA: da 2018.2 á 2019.2

Este complemento permite ó usuario configurar NVDA para que pite con certos
eventos de teclado.

## Características

Este complemento proporciona as seguintes características que podes utilizar
para adaptar o comportamento do teclado con NVDA:

* Beep for uppercases when caps lock is on (Pitar para maiúsculas cando o
  bloqueo de maiúsculas está activado): se esta característica está
  habilitada, NVDA pitará ao escribires unha maiúscula se o bloqueo de
  maiúsculas está activado. Non cometas máis erros de maiúsculas!
* Beep for typed characters when shift is pressed (Pitar para caracteres
  escritos cando shift está premido): con esta característica NVDA pitará se
  escribes un carácter coa tecla shift premida.
* Beep for toggle keys changes (Pitar para cambios nas teclas de
  alternancia): con esta característica, NVDA pitará máis alto se unha tecla
  de alternancia se activa, e cun ton máis baixo se se desactiva. Por favor
  ten en conta que que windows ten unha característica nativa de pitidos
  para as teclas de alternancia no Centro de Accesibilidade. Esta
  característica nativa funciona ben se non utilizas a opción de
  distribución de teclado portátil.
* Announce toggle keys changes (Anunciar cambios nas teclas de alternancia):
  só cando "Beep for toggle keys changes" (Pitar para cambios nas teclas de
  alternancia) está activado. Podes habilitar ou deshabilitar que NVDA
  anuncie o estado da tecla de alternancia.
* Beep for specified characters (Pitar para os caracteres especificados):
  NVDA pitará para tódolos caracteres que configures nas opcións avanzadas.
* Deshabilitar os pitidos en campos de contrasinal: esta característica está
  habilitada por defecto para evitar riscos de seguridade. Deshabilítaa se
  queres escoitar pitidos nos campos de contrasinal.

## Requisitos

Necesitas NVDA 2018.2 ou posterior.

## Instalación

Instálao simplemente como un complemento de NVDA.

## Uso

Para habilitar ou deshabilitar características, vai ás opcións do NVDA e selecciona a categoría beep keyboard (pitidos do teclado). Nesa categoría podes configurar todas as características soportadas por este complemento.

* "Beep for uppercases when caps lock is on" (Pitar para maiúsculas cando o
  bloqueo de maiúsculas está activado) está activado por defecto.

Se necesitas máis axustes, abre o diálogo de opcións avanzadas que contén as
opcións seguintes:

* Ignore characters with shift pressed (Ignorar caracteres con shift
  premido): todos os caracteres de aquí ignoraranse no pitido cando shift
  está premido. Permítense secuencias de escapado, p.ex. "\t" para tab, "\r"
  para retorno de carro.
* Beep always for the following characters (Pitar sempre para os seguintes
  caracteres): configura aquí tódolos caracteres para os que queres que NVDA
  pite. Permítense secuencias de escapado, p.ex. "\t" para tab, "\r" para
  retorno de carro.
* Select tones to configure (Seleccionar ton a configurar: podes configurar
  parámetros para tódolos tons. Selecciona un aquí, e configura os
  parámetros nas seguintes caixas de verificación. ao cambiar a selección,
  NVDA pitará co ton seleccionado co parámetro actualmente establecido no
  diálogo.
* Tone pitch (Ton do pitido): ton do pitido para o ton actualmente
  seleccionado.
* Tone length (Lonxitude do ton): lonxitude do ton para o ton actualmente
  seleccionado.
* Tone volume (volume do ton): volumen do ton para o ton actualmente
  seleccionado.
* Test tone (Probar ton): este botón permíteche reproducir unha mostra cos
  parámetros actualmente seleccionados.
* Preme o botón Aceptar para gardar as opcións ou cancelar para descartalas.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
