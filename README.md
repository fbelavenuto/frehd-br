# TRS-80 FreHD BR version

### English

FreHD is a HD emulator for TRS-80 classic computer.

This board is my version made in Cadsoft Eagle software. Original project:

http://members.iinet.net.au/~ianmav/trs80/emulator.htm

`FreHD` is the project itself, `CP300_Adapter` is for Brazilian TRS-80 Model III clone

### Português

FreHD é um emulador de HD para computadores TRS-80.

Estas placas são uma versão minha feito no software Autodesk Eagle. Projeto original:

http://members.iinet.net.au/~ianmav/trs80/emulator.htm

`FreHD` é o projeto em si, `CP300_Adapter` é para o clone brasileiro TRS-80 model III.

Este projeto utiliza um microcontrolador PIC que deve ser gravado com o firmware do arquivo `FreHD_213.hex` e utiliza um circuito integrado de lógica programável (GAL) que deve ser gravado com o arquivo `gal16v8.jed`.

Para o clone CP500 é necessário a regravação da EPROM interna ou troca com o conteúdo do arquivo `CP500_FreHD.rom`.

Para o CP300 é necessário a construção do adaptador que contém uma EPROM que deve ser gravada com o conteúdo do arquivo `FreHD(3000).bin`. A EPROM utilizada é a 2732 que tem espaço para 4KBytes de dados, por ser mais fácil de se encontrar. O arquivo contém somente 2KBytes de dados e deve ser gravado no começo da EPROM (offset 0) deixando o restante da EPROM sem conteúdo.

A lista de material pode ser encontrada em formato Markdown na pasta *Doc* de cada projeto.

É necessário a confecção de um cabo multivias com 50 vias/conector 2x25 para ligação entre o FreHD e Micro (ou Adaptador) e um cabo multivias de 34 vias/conector 2x17 para a ligação do adaptador no CP300. O cabo de 50 vias pode ser aproveitado de antigos cabos SCSI e para o cabo de 34 vias pode ser aproveitado cabos de floppy sem a torção.
