# Etapa 6 Redação do artigo

## Solicitação

Escreva a primeira versão completa do artigo seguindo a estrutura abaixo.

Considerando *INTRODUÇÃO*, *METODOLOGIA*, *REVISÃO DA LITERATURA*, *SÍNTESE CRÍTICA*, *CONSIDERAÇÕES FINAIS* E *RESUMO*, a escrita deve ter entre **600 a 700 palavras**.

# Acessibilidade digital em interfaces web brasileiras: aplicação das diretrizes WCAG 2.1 e barreiras à conformidade

## Palavras-chave

Acessibilidade web; WCAG 2.1; inclusão digital

## Introdução

A migração de serviços essenciais para o ambiente digital ampliou o alcance do Estado e das instituições de ensino, mas também criou uma nova forma de exclusão. Quando uma interface ignora critérios de acessibilidade, impede que pessoas com deficiência exerçam direitos básicos, como solicitar um benefício previdenciário ou realizar uma matrícula. No Brasil, a acessibilidade digital não é recomendação: a Lei nº 13.146/2015 a estabelece como obrigação, e as WCAG 2.1 fornecem os critérios técnicos para cumpri-la, organizados em quatro princípios, perceptível, operável, compreensível e robusto. Ainda assim, relatos de não conformidade se repetem em portais de grande acesso, o que revela uma lacuna pouco explorada entre a norma e sua aplicação. Este artigo analisa, a partir da literatura recente, como as WCAG 2.1 vêm sendo aplicadas em sites brasileiros e quais barreiras limitam a conformidade.

## Metodologia

Trata-se de revisão bibliográfica de natureza teórica e abordagem qualitativa. A busca foi feita na Biblioteca Digital da Sociedade Brasileira de Computação e em periódicos nacionais de Sistemas de Informação, com os descritores "acessibilidade web", "WCAG" e "e-MAG" combinados ao recorte brasileiro. Foram incluídos estudos empíricos publicados entre 2021 e 2026 sobre conformidade de sites brasileiros, e excluídos trabalhos sem avaliação empírica e sobre aplicativos móveis nativos. Após triagem por título e resumo, três artigos compuseram o corpus, analisado por categorização temática em eixos, confrontando convergências, divergências e lacunas.

## Revisão da literatura

### Grau de conformidade e falhas recorrentes

Os três estudos convergem num diagnóstico de não conformidade generalizada. Batista e Baluz (2026) avaliaram vinte sites de universidades públicas com o QualWeb e encontraram média de falhas de 28,63% nas federais e 27,29% nas estaduais. Barros et al. (2024) analisaram três páginas do Gov.br e concluíram que nenhuma atinge os requisitos legais. Camargo e Santos (2025) identificaram os mesmos problemas no Meu INSS. Em todos, predominaram a ausência de texto alternativo e o contraste inadequado, seguidos de dificuldades de navegação por teclado. A convergência é notável porque os estudos usam ferramentas distintas e examinam setores diferentes.

### Métodos de avaliação e seus limites

A comparação dos métodos revela uma fragilidade compartilhada. Os três trabalhos empregam apenas ferramentas automatizadas e reconhecem que critérios dependentes de julgamento humano ficam fora do escopo. Barros et al. (2024) expõem o problema: a mesma página obteve 92,86% no ASES, baseado no e-MAG, e nota 6 de 10 no AccessMonitor, baseado nas WCAG 2.1. O instrumento, portanto, condiciona o diagnóstico.

### Síntese crítica

A tendência dominante é a estabilidade do problema: o mesmo conjunto estreito de falhas se repete entre 2022 e 2026, em setores distintos. A principal divergência é metodológica e sugere que a conformidade com o padrão nacional não assegura conformidade com o internacional, o que pode gerar falsa sensação de adequação. Duas lacunas se destacam: nenhum estudo combina avaliação automatizada com teste junto a usuários com deficiência, e nenhum investiga as causas organizacionais ou formativas da não conformidade. A literatura descreve o que falha, mas não por que equipes seguem descumprindo diretrizes públicas, gratuitas e exigidas por lei há mais de uma década.

## Considerações finais

A literatura indica que as WCAG 2.1 são aplicadas de modo parcial e inconsistente em sites brasileiros, e que as barreiras à conformidade são técnicas, mas também metodológicas e formativas. O achado mais relevante é a recorrência de falhas elementares, corrigíveis com baixo custo, o que desloca o problema da dificuldade técnica para a prioridade dada à acessibilidade no ciclo de desenvolvimento. A revisão limita-se a três estudos de avaliação automatizada, o que restringe a generalização. Pesquisas futuras poderiam validar esses resultados com usuários com deficiência e investigar a formação em acessibilidade nos cursos de computação.

## Resumo

A acessibilidade digital é obrigação legal no Brasil desde 2015, mas sua aplicação efetiva permanece incerta. Este artigo analisa como as WCAG 2.1 vêm sendo aplicadas em interfaces web brasileiras e quais barreiras limitam a conformidade. Realizou-se revisão bibliográfica qualitativa de três estudos empíricos publicados entre 2024 e 2026, analisados por categorização temática. Os resultados indicam não conformidade generalizada em portais educacionais e de governo eletrônico, com predomínio de falhas de texto alternativo, contraste e navegação por teclado, e mostram que o diagnóstico varia conforme a ferramenta adotada. Conclui-se que as barreiras não são apenas técnicas: corrigir as falhas mais frequentes depende menos de complexidade do que de prioridade no desenvolvimento.

## Referências

BARROS, Ygor Santos; OUTÃO, Juliana Carvalho Silva do; SACRAMENTO, Carolina; FERREIRA, Simone Bacellar Leal; PIMENTEL, Mariano Gomes; SANTOS, Rodrigo Pereira dos. Avaliação de acessibilidade da plataforma Gov.br por ferramentas automatizadas. In: LATIN AMERICAN SYMPOSIUM ON DIGITAL GOVERNMENT (LASDiGov), 12., 2024, Brasília. **Anais**. Porto Alegre: Sociedade Brasileira de Computação, 2024. p. 50-61. DOI: 10.5753/wcge.2024.2282.

BATISTA, Heron Eduardo Nepomuceno; BALUZ, Rodrigo Augusto Rocha Souza. Avaliação de sites das instituições de ensino superior de acordo com as diretrizes de acessibilidade para conteúdo web (WCAG 2.1): uma análise comparativa das principais universidades federais e estaduais do Brasil. **iSys: Revista Brasileira de Sistemas de Informação**, v. 18, n. 1, p. 14:1-14:27, 2026.

BRASIL. Lei nº 13.146, de 6 de julho de 2015. Institui a Lei Brasileira de Inclusão da Pessoa com Deficiência. **Diário Oficial da União**, Brasília, DF, 7 jul. 2015.

CAMARGO, Marcos Vinicius Lopes; SANTOS, Sylvana Karla S. L. Avaliação da acessibilidade digital do site de governo Meu INSS com foco no desenvolvedor. In: SIMPÓSIO BRASILEIRO SOBRE FATORES HUMANOS EM SISTEMAS COMPUTACIONAIS (IHC), 24., 2025, Belo Horizonte. **Anais Estendidos**. Porto Alegre: Sociedade Brasileira de Computação, 2025. p. 175-179. DOI: 10.5753/ihc_estendido.2025.13256.

## Checklist

* [x] A introdução termina com o objetivo.
* [x] A metodologia descreve o processo realmente realizado.
* [x] A revisão compara os artigos.
* [x] A conclusão responde ao problema.
* [x] O resumo representa o texto completo.
