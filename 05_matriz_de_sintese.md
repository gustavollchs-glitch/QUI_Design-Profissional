# Etapa 5 Matriz de síntese e organização da revisão

## Solicitação

Compare os artigos e organize a revisão por temas ou eixos. Não produza apenas uma sequência de resumos.

## Eixos da revisão

1. Grau de conformidade com as WCAG 2.1 e falhas recorrentes em sites brasileiros
2. Métodos de avaliação e seus limites: ferramentas automatizadas e divergência entre padrões
3. Barreiras à conformidade e implicações para a prática de desenvolvimento

## Matriz de síntese

|Eixo|Artigos relacionados|Convergências|Divergências|Limitações|Lacunas|
|-|-|-|-|-|-|
|1. Conformidade e falhas recorrentes|Batista e Baluz (2026); Barros et al. (2024); Camargo e Santos (2025)|Os três identificam ausência de texto alternativo e contraste inadequado como as falhas dominantes; nenhum site avaliado atinge conformidade plena|Batista e Baluz quantificam a falha em percentuais comparáveis entre instituições; Barros et al. e Camargo e Santos descrevem as falhas sem permitir comparação quantitativa|Amostras restritas: 20 sites no primeiro, 3 páginas no segundo, número não informado no terceiro|Não há estudo que acompanhe a evolução da conformidade de um mesmo conjunto de sites ao longo do tempo|
|2. Métodos de avaliação|Barros et al. (2024); Batista e Baluz (2026); Camargo e Santos (2025)|Todos usam exclusivamente ferramentas automatizadas e reconhecem, explícita ou implicitamente, que isso não cobre todos os critérios|Barros et al. obtêm pontuação alta no ASES, baseado no e-MAG, e baixa no AccessMonitor e no TAW, baseados nas WCAG; cada estudo usa um conjunto diferente de ferramentas|Ausência de testes manuais e de validação com usuários com deficiência em todos os três|Falta pesquisa que combine avaliação automatizada com teste de usabilidade com pessoas com deficiência em portais brasileiros|
|3. Barreiras e prática de desenvolvimento|Camargo e Santos (2025); Barros et al. (2024)|Ambos tratam a não conformidade como problema de implementação corrigível e propõem ajustes concretos|Camargo e Santos focam o desenvolvedor; Barros et al. focam a priorização por nível de conformidade (A, depois AA e AAA)|Nenhum dos dois investiga causas organizacionais ou formativas, apenas sintomas técnicos|Não há estudo brasileiro recente sobre por que as equipes de desenvolvimento deixam de aplicar as diretrizes, apesar da obrigação legal|

## Roteiro da revisão da literatura

### Eixo 1

* Ideia principal: A não conformidade com as WCAG 2.1 é generalizada em sites brasileiros, e as falhas se repetem em um conjunto estreito de critérios.
* Evidências que serão usadas: média de 28,63% de falhas nas federais e 27,29% nas estaduais (Batista e Baluz, 2026); notas de 5,6 a 7,3 em 10 no AccessMonitor para o Gov.br (Barros et al., 2024); problemas de contraste, fonte e texto alternativo no Meu INSS (Camargo e Santos, 2025).
* Comparação entre estudos: os três convergem quanto aos tipos de falha, mas divergem quanto à possibilidade de comparação, já que só um apresenta dados percentuais padronizados.
* Ligação com o problema: responde diretamente à primeira parte da pergunta, sobre como as diretrizes vêm sendo aplicadas.

### Eixo 2

* Ideia principal: O retrato da conformidade depende do instrumento de medida, e a avaliação automatizada isolada produz um diagnóstico incompleto.
* Evidências que serão usadas: a divergência interna em Barros et al. (2024), com 92,86% no ASES e 6 de 10 no AccessMonitor para a mesma página; o reconhecimento explícito, em Batista e Baluz (2026), de que a análise automatizada não capta nuances que exigiriam avaliação manual.
* Comparação entre estudos: Barros et al. usam quatro ferramentas e expõem a divergência; Batista e Baluz usam uma só e assumem a limitação; Camargo e Santos usam três sem discutir a discrepância entre elas.
* Ligação com o problema: mostra que parte das barreiras à conformidade é metodológica, pois o desenvolvedor pode considerar um site conforme com base em uma ferramenta que não cobre os critérios exigidos.

## Síntese crítica provisória

A literatura recente converge num diagnóstico estável: sites brasileiros de alto tráfego, tanto educacionais quanto de governo eletrônico, não atingem conformidade plena com as WCAG 2.1, e as falhas se concentram em um conjunto pequeno e recorrente de critérios, sobretudo texto alternativo, contraste e navegação por teclado. A principal divergência não está nos resultados, mas no método: a pontuação atribuída a um mesmo site varia conforme a ferramenta e o referencial, nacional ou internacional, o que sugere que a adequação ao e-MAG não assegura adequação às WCAG. Duas lacunas se destacam. A primeira é a ausência de estudos que combinem avaliação automatizada com teste com usuários com deficiência, já que os três trabalhos analisados reconhecem que critérios dependentes de julgamento humano ficam fora do escopo. A segunda é a inexistência de pesquisa sobre as causas organizacionais e formativas da não conformidade: a literatura descreve com precisão o que falha, mas não explica por que equipes de desenvolvimento seguem deixando de aplicar diretrizes públicas, gratuitas e legalmente exigidas desde 2015.

## Checklist

* [x] Os artigos foram agrupados por ideias.
* [x] Há comparações entre estudos.
* [x] As divergências foram registradas.
* [x] As lacunas são específicas e sustentadas pelas leituras.
