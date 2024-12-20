# Bipe para Teclado (Beep Keyboard) #

* Autor: David CM
* Baixe a [versão estável][1]
* Baixe a [versão em desenvolvimento][2]
* Compatibilidade com NVDA: 2018.2 até 2019.2

Esse complemento permite que o usuário configure o NVDA para emitir bipes
com alguns eventos do teclado.

## Recursos

Esse complemento fornece os seguintes recursos que você pode usar para
adaptar o comportamento do teclado no NVDA:

* Bipar para maiúsculas quando o caps lock está ativado: se esse recurso
  estiver ativado, o NVDA emitirá um bipe quando você digitar uma maiúscula
  e o caps lock estiver ativado. Não cometa mais erros em maiúsculas!
* Bipar para caracteres digitados quando a tecla shift for pressionada: com
  esse recurso, o NVDA emitirá um bipe se você digitar um caractere com a
  tecla shift pressionada.
* Bipar para alteração das teclas de alternância: com esse recurso, o NVDA
  emitirá um bipe mais alto se uma tecla de alternância for ativada e um tom
  mais baixo se for desativada. Observe que o Windows possui uma função de
  bipe de teclas de alternância embutida na Central de Facilidade de
  Acesso. Esse recurso nativo funciona bem se você não usar a configuração
  de leiaute do teclado de laptop.
* Anunciar as alterações das teclas de alternância: apenas quando "Bipar
  para alteração das teclas de alternância" estiver ativada. Você pode
  ativar ou desativar o NVDA para anunciar o status da tecla de alternância.
* Bipar para caracteres especificados: NVDA emite um bipe para todos os
  caracteres que você definiu nas configurações avançadas.
* Desativar bipe nos campos de senha: esse recurso é ativado por padrão para
  evitar riscos de segurança. Desative-o se desejar ouvir um bipe nos campos
  de senha.

## Requisitos

Necessita do NVDA 2018.2 ou posterior.

## Instalação

Basta instalá-lo como um complemento do NVDA.

## Uso

Para ativar ou desativar os recursos, vá para as configurações do NVDA e selecione a categoria do bipe para teclado. Nessa categoria, você pode configurar todos os recursos suportados por este complemento.  

* "Bipar para maiúsculas quando o caps lock está ativado" está ativado por
  padrão.

Se você precisar de mais configurações, abra o diálogo de configurações
avançadas que contém as seguintes opções:

* Caracteres ignorados com shift pressionado: todos os caracteres aqui serão
  ignorados para bipar quando shift for pressionado. Sequências de escape
  são permitidas, ex.: "\t" para tab, "\r" para retorno de carro (fim de
  linha).
* Bipar sempre para os seguintes caracteres: defina aqui todos os caracteres
  que você deseja que o NVDA bipe. Sequências de escape são permitidas, ex.:
  "\t" para tab, "\r" para retorno de carro (fim de linha).
* Selecionar tom para configurar: você pode configurar parâmetros para todos
  os tons. Selecione um aqui e defina os parâmetros nas próximas caixas de
  texto. Ao alterar a seleção, o NVDA bipará para o tom atual selecionado
  com os parâmetros atuais definidos na caixa de diálogo.
* Frequência do tom: a frequência do tom selecionado atualmente.
* Duração do som: duração do som selecionado atualmente.
* Volume do tom: volume do tom selecionado atualmente.
* Tom de teste: esse botão permite executar um teste com os parâmetros
  definidos atualmente.
* Pressione o botão OK para salvar as configurações ou cancelar para
  descartar.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard

[2]: https://addons.nvda-project.org/files/get.php?file=beepkeyboard
