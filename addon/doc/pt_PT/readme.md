# bips de teclado #

* Autor: David CM
* Baixar [versão estável][1]
* Baixar [versão de desenvolvimento][2]
* Compatibilidade com NVDA: 2018.2 até 2019.1

Este extra permite ao utilizador configurar o NVDA para emitir bips com
alguns eventos de teclado.

## Funcionalidades:

Este extra fornece-lhe os seguintes recursos que pode usar para adaptar o
comportamento do teclado do NVDA:

* Bipe para maiúsculas, quando a tecla  caps lock estiver activada: se esta
  funcionalidade estiver activada, o NVDA emitirá um bipe quando digitar uma
  letra maiúscula e o caps lock estiver activado. Não cometa mais erros com
  letras maiúsculas!
* Bipe para caracteres digitados quando a tecla shift está pressionada: com
  este recurso activado, o NVDA emitirá um bip se digitar um caractere com a
  tecla shift pressionada.
* Bipe para alternar as mudanças das teclas: com este recurso, o NVDA
  emitirá um bipe maior se uma tecla de alternância for activada e um bip
  mais baixo se a desactivar. Observe que o Windows possui uma função de
  bipe de tecla de alternância integrada na Central de Facilidade de
  Acesso. Esse recurso nativo funciona melhor se não usar a configuração de
  layout de teclado do laptop.
* Anunciar alternância  de mudança de teclas: apenas quando "Bipe para
  modificar as teclas de alternância" estiver activado. Pode activar ou
  desactivar o NVDA para anunciar o estado das teclas de alternância.
* Bipe para caracteres especificados: o NVDA emitirá um bipe para todos os
  caracteres que forem definidos nas configurações avançadas.
* Desactivar o bipe nos campos de senha: este recurso encontra-se activado
  por padrão, para evitar problemas de segurança. Desactive-o, se quiser
  ouvir sinais sonoros nos campos de senha.

## Requisitos

É necessário o NVDA 2018.2 ou posterior.

## Instalação

Instale como qualquer extra do NVDA

## utilização

Para activar ou desactivar recursos, vá para as configurações do NVDA e seleccione a categoria do extra "bips de teclado". Nessa categoria, pode configurar todos os recursos suportados por este extra.

* O "Bip para maiúsculas quando o caps lock está activado" encontra-se
  activado por padrão.

Se precisar de mais configurações, abra a caixa de diálogo de configurações
avançadas, que contém as seguintes opções:

* Caracteres ignorados com shift pressionado: todos os caracteres aqui
  presentes deixarão de emitir bips, quando o shift for
  pressionado. Sequências de escape são permitidas, por ex. "\t" para tab,
  "\r" para retorno de carro.
* Emitir Bipe sempre para os seguintes caracteres: defina aqui todos os
  caracteres para os quais deseja que o NVDA emita um bip. Sequências de
  escape são permitidas, por ex. "\\t" para tab "\\r" para retorno de carro.
* Seleccione o som para configurar: Ppode configurar parâmetros para todos
  os sons. Seleccione um deles aqui e defina os seus parâmetros nas próximas
  caixas de texto. Quando alterar a selecção, o NVDA emitirá um bipe para o
  som actualmente selecionado, já com os parâmetros definidos na caixa de
  diálogo.
* Entoação do som: entoação para o som actualmente seleccionado.
* Tamanho do som: Definição do tamanho para o som actualmente seleccionado.
* Volume do som: Definição do volume para o som actualmente seleccionado.
* Teste do som: Permite testar o som actualmente seleccionado.
* Pressione o botão OK para guardar as configurações ou cancelar para as
  rejeitar.

[[!tag dev]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
