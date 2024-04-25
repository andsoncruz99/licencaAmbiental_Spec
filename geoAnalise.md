![alt text](image.png)

# MÓDULO DE GEOPROCESSAMENTO

## ESPECIFICAÇÃO DE REQUISITOS

### PROBLEMA DE NEGÓCIO

Parte integrante do processo de Licenciamento Ambiental, este processo é requisitado sob demanda e tem diversas atividades relativas não apenas a medição de áreas, como a identificação inteligente de diferentes pontos e elementos dentro de uma propriedade rural ou empreendimento.

Os analistas, bem como equipe técnica relacionada a fiscalização, têm como um dos pontos principais, a correta definição destes elementos, a fim de avaliar se a solicitação de licença está em concordância com a legislação vigente, como também, fiscalizar a atuação de propriedades e empreendimentos, no que tange aos impactos acarretados no meio-ambiente.

Devido a importância da atividade, bem como ao número de solicitações de emissão de licenças e atividades de fiscalização demandadas à equipe técnica, bem como o volume e a diversidade dos dados que devem se analisados em cada processo, existe a necessidade de recursos tecnológicos que amparem a tomada de decisão da equipe técnica, utilizando recursos de Geoprocessamento de forma eficiente e assertiva.

Com o desenvolvimento do módulo de Geoprocessamento, o sistema deverá permitir a equipe técnica competente realizar a análise das propriedades rurais e empreendimentos, possibilitando a visualização de diversos shapes e layers, bem como a identificação de diferentes elementos contidos nos shapes (linhas, polígonos, pontos). Também deverá ser possível realizar a medição de áreas, bem como operações diversas com polígonos, e também cruzamento de informações dos shapes com bases de sensoriamento já existentes.

### HISTÓRIA PRINCIPAL

Durante o processo de lincenciamento o técnico analisando a documentação poderá, a qualquer momento, entender pela necissidade de análise qaunto ao geo posicionamento do empreendimento proposto bem como se tal localização impacta sobre áreas legalmente protegidas. Para tanto este deve encaminhar, via sistema, o processo ao setor adequado, os ténicos devem, a partir dos dados e documentos anexados pelo solicitante, determinar a localização do imóvel e do empreendimento na área indicado, identificar área do empreendimento e confrotenates e indicar se a atividade proposta na localização indicada encontra restrição em algum aspecto legal.

### REQUISITOS FUNCIONAIS

#### R1 - Manter grupos/categorias de atividades

Sistema deve permitir a criação de grupo ou categorias para agrupamento das atividades, a fim de facilitar a o cadastro e a manutenção dos requisitos, de acorde com os tipos de análise esperado.

##### R1.1 - Deve permitir a busca de regsitro por grupo ou por atividade

##### R1.2 - Cada atividade só poderá está em um grupo

##### R1.3 - Deve permitir a inclusão/remoção de atividades nos grupos

#### R2 - Manter Bases GeoReferênciadas

##### R2.1 – Permitir inserir diversas bases

##### R2.2 – Permitir atualizar bases cadastradas

##### R2.3 – Permitir remover bases cadastrada

##### R2.4 – Visualizar uma base existente

##### R2.5 – Vincular uma base a um processo de licenciamento

##### R2.6 – Emitir relatório de bases vencidas

#### R3 - Manter relação de pre-requistos documentais às análise, a partir dos grupos

#### R4 - Indentificar se a área proposta sobrepõe área já cadastrada

#### R5 - Identificar se a área proposta sobrepõe áreas nas Bases GeoReferênciadas

#### R6 - Permitir download das Bases cadastradas

#### R7 - Permitir download dos arquivos incluídos pelo solicitante

#### R8 - Permitir a elaboração e emissão de Parecer Técnico conforme [modelo de Parecer](Modelo%20de%20PARECER%20Simples.pdf)

#### R9 - Permitir anexar documentos em pdf e juntá-los como anexo ao parecer

#### R10 - Permitir a incluisão e conculta de diversos pareceres

### REQUISITOS NÃO FUNCIONAIS

Não se aplica

### MODELO DE DADO PROPOSTO

### PROTÓTIPOS
