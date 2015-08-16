# TeXnico

Pacote LaTeX para a elaboração de uma tese, de acordo com as especificações do Instituto Superior Técnico, e, mais especificamente, do MEEC.

## Pré-requisitos

Os seguintes pacotes LaTeX devem estar instalados:

- _helvet_
- _inputenc_
- _hyperref_
- _graphicx_
- _geometry_

Recomenda-se que seja utilizado o pacote _babel_ para especificar a língua do documento.

## Macros definidas

### Capa

#### Logotipo e Imagem

_\\ttOverrideLogo_ recebe um parâmetro, a localização do logotipo do Instituto Superior Técnico. A Assinatura A, recomendada, está incluída no repositório. A sua localização vem incluída por defeito como _TeXnico/IST\_A\_CMYK\_POS_

_\\ttSetImagem_ recebe um parâmetro, a localização da imagem opcional a figurar na capa. Caso este comando não seja chamado, nenhuma imagem aparecerá.

#### Texto

_\\ttSetTitulo_ __*__ recebe um parâmetro, o título da tese

_\\ttSetSubtitulo_ __*__ recebe um parâmetro, o subtítulo da tese

_\\ttSetAutor_ __*__ recebe um parâmetro, o autor da tese

_\\ttSetDescricao_ recebe um parâmetro, a descrição do documento. Por defeito, a descrição é _'Dissertação para obtenção do Grau de Mestre em'_

_\\ttSetCurso_ __*__ recebe um parâmetro, o nome do curso

_\\ttSetOrientador_ __*__ recebe um parâmetro, o(s) orientador(es) da tese

_\\ttSetTBloco_ recebe um parâmetro, o título do bloco de nomes que sucede o orientador. Por defeito, o título é _'Júri'_

_\\ttSetBloco_ __*__ recebe um parâmetro, o conteúdo do bloco que sucede o orientador (em princípio, Júri)

_\\ttSetData_ recebe um parâmetro, a data a figurar na capa. Por defeito, a data é a de compilação do documento (comando \\today do LaTeX)

A capa é elaborada uma vez chamado o comando _\\ttCapa_, após chamar os comandos relevantes acima. Os comandos sucedidos por um asterisco são comandos necessários à compilação do projecto (sem os quais ocorrerá um erro).



### Conteúdo

## Fontes

- Guia de Preparação da Dissertação, Direcção Académica, 2013/2014
- Regulamento de Dissertação/Trabalho de Projecto, DEEC, 2014
- Kit Normas Básicas de Identidade, RMAC Brand Design, 2011
