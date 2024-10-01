# AUTORAS

*   Camila Mota;
*   Fatima Teixeira;
*   Ingrid Macário;
*   Jéssika Correa.

# RESUMO

O State of Data Brazil é atualmente o maior e mais abrangente mapeamento do mercado de trabalho em dados no Brasil. Desde sua criação, a pesquisa tem se destacado como uma ferramenta fundamental para o entendimento das tendências e desafios enfrentados pelos profissionais dessa área. A quarta edição, realizada entre 16 de outubro e 6 de dezembro de 2023, representa um marco importante, consolidando a pesquisa como referência no setor de dados.

Com a participação de 5.293 profissionais brasileiros, esta edição trouxe uma visão ainda mais aprofundada sobre o perfil, as demandas e as expectativas desses profissionais, em um cenário que está em constante transformação.

Os participantes responderam a perguntas que exploravam aspectos essenciais como perfil demográfico, formação acadêmica, áreas de atuação, nível de remuneração e rotatividade no setor. Esses temas ajudam a mapear o contexto no qual os profissionais de dados estão inseridos, oferecendo insights valiosos para empresas e profissionais que buscam compreender melhor as dinâmicas do setor.

A edição 2023 trouxe novidades importantes, como a inclusão de perguntas sobre Inteligência Artificial Generativa e Modelos de Linguagem de Grande Escala (LLMs). Esses tópicos refletem a crescente adoção dessas tecnologias no ambiente corporativo e o impacto que elas estão começando a ter no mercado de trabalho.

A realização da pesquisa State of Data Brazil é fruto de um esforço conjunto entre a Data Hackers, a maior comunidade de dados do Brasil, e a Bain & Company, uma das principais consultorias de gestão global.

Esse foi o projeto vencedor do Desafio Final do Bootcamp (Re)Start!



# OBJETIVO

O objetivo deste relatório, proposto pela [Re]start Bootcamp - Data Girls, é a condução de análises planejadas sobre o mercado de trabalho no setor de dados, utilizando como referência a base de dados 'State of Data Brazil 2023'. Este estudo visa identificar tendências emergentes, avaliar a demanda por competências específicas, e compreender as dinâmicas do mercado, incluindo fatores como a oferta e a procura de profissionais qualificados, salários médios, e a evolução das funções e responsabilidades na área de dados. Este relatório faz parte do desafio final do bootcamp e visa aplicar os conhecimentos adquiridos, assim contribuindo para a formação das profissionais na área de dados.

# DESENVOLVIMENTO

## Dataset: limpeza e tratamento
Este trabalho utilizou as bibliotecas pandas, matplotlib e seaborn.

O pandas é uma biblioteca essencial para a manipulação e análise de dados em Python, oferecendo estruturas de dados flexíveis e operações para trabalhar com tabelas de dados (DataFrames) e séries temporais. Ele facilita a limpeza, transformação e análise de dados, permitindo transferências como filtragem, agregação e integração de diferentes fontes de dados.

Enquanto, o matplotlib é uma biblioteca de visualização de dados que possibilita a criação de gráficos e plotagens altamente personalizáveis. É amplamente utilizado para gerar visualizações estáticas, animadas e interativas.

Por fim, o seaborn é uma biblioteca de visualização baseada no matplotlib que oferece uma interface de alto nível para a criação de gráficos estatísticos. Projetado para trabalhar de forma integrada com o pandas, o seaborn simplifica a geração de visualizações complexas, como mapas de calor, gráficos de dispersão com regressão e gráficos de violino. Ele facilita a análise de distribuições de dados e relações entre variações, fornecendo uma representação gráfica mais intuitiva dos dados.

A combinação dessas bibliotecas permite um fluxo de trabalho eficiente, desde a preparação dos dados até a criação de visualizações que facilitam a interpretação e comunicação dos resultados.

### Parte 1: Panorama Geral
O perfil sociodemográfico dos profissionais da área de dados oferece um panorama crucial para compreender a diversidade e as características da força de trabalho nesse setor em crescimento. Saber mais sobre a idade, gênero, escolaridade, localização geográfica e experiências profissionais desses indivíduos permite identificar tendências e desafios relacionados à inclusão, formação e desenvolvimento de carreira.

Essas informações ajudam empresas a planejar estratégias de recrutamento e retenção, adaptando-se a um mercado cada vez mais competitivo e que exige diversidade para a inovação. Além disso, um conhecimento aprofundado sobre o perfil dos profissionais pode influenciar políticas de educação, oferecendo oportunidades de capacitação mais alinhadas às demandas atuais e futuras do setor.

Nessa etapa, foram realizadas as seguintes perguntas:
##### 1. Qual o perfil sociodemográfico dos profissionais da área?
##### 2. Qual é a remuneração dos profissionais?
##### 3. Quantos profissionais estão em cada nível (junior, pleno, sênior e gestor)?
##### 4. Os profissionais da área estão satisfeitos?
##### 5. Quais são as principais ferramentas utilizadas?

Como exemplo, tem-se a análise do Pergunta 1:
![image](https://github.com/user-attachments/assets/fab6136d-3aed-4b81-bc4a-e570346dfcb9)

Neste ponto analisamos a distribuição de gêneros dos profissionais neste conjunto de dados, optamos por usar um gráfico de barras. Onde:

- No eixo X (horizontal) representa as categorias "Masculino", "Feminino", "Prefiro não informar" e "Outro";
- No eixo Y ( vertical) está representado a quantidade de pessoas.

A maioria dos profissionais identificados são do gênero masculino, correspondendo a 74,9% do total. 24,6% do profissionais são femininos. Uma pequena parte, 0,3%, prefere não informar o gênero, enquanto 0,2% se identificam como "outro".


### Parte 2: Se aprofundando no mercado de trabalho
Nessa etapa, na busca por compreender a participação das mulheres em diferentes aspectos do mercado de dados, foram propostas análises com o objetivo de contribuir para o desafio final do bootcamp. O foco no trabalho feminino visa fomentar o debate sobre essas profissionais, incentivando reflexões que podem desempenhar um papel crucial no acompanhamento da evolução delas no setor de dados.

Nessa etapa, foram realizadas as seguintes perguntas:

##### 1. Quantidade de Mulheres por nível de experiência.
##### 2. Quantidade de Mulheres no cargo de gestor.
##### 3. Origem das profissionais da área de dados.
##### 4. Média de remuneração por regiões do Brasil.
##### 5. Nível de ensino por gênero.

Como exemplo, tem-se a análise do Pergunta 5:
![image](https://github.com/user-attachments/assets/e2792795-3cf9-4264-ad11-5e9f41dd4594)

Diferente das outras análises, ao analisarmos todas as identidades presentes no dataset original, podemos enxergar com mais clareza as disparidades entre gêneros, como observados na análise anterior. Para tal, realizamos um agrupamento de gênero e nível de ensino para observação desse cenário.

# CONCLUSÃO 

A análise da participação feminina em diferentes contextos profissionais revela um cenário de crescente diversidade, mas também aponta para desafios persistentes na equidade de gênero, especialmente em cargos de liderança.

Observa-se que as mulheres estão cada vez mais presentes em áreas historicamente dominadas por homens, como Tecnologia da Informação e Engenharia, com um número significativo de profissionais em carreiras técnicas e analíticas. Esse avanço demonstra a quebra de barreiras e a maior aceitação das mulheres em áreas que exigem forte base em ciência, tecnologia, engenharia e matemática. Além disso, há uma presença notável em economia, administração e negócios, áreas que tradicionalmente oferecem oportunidades para ascensão a cargos estratégicos.

No entanto, o gráfico sobre a presença de mulheres em cargos de gestão revela uma discrepância preocupante: apenas 13,3% das mulheres ocupam posições de liderança, enquanto a grande maioria ainda está em funções não-gerenciais.

Esse dado destaca a necessidade de políticas mais inclusivas e práticas de promoção interna que favoreçam o desenvolvimento de carreiras femininas até os níveis de decisão e liderança.

Além disso, a análise mostra que há uma distribuição equilibrada das mulheres em diferentes níveis de experiência profissional, sugerindo que a força de trabalho feminina está presente em várias camadas da organização. No entanto, há espaço para maior transparência e incentivo ao compartilhamento de informações, como indicado pelo alto número de respostas de "não respondeu" sobre o nível profissional.

Ao analisar as médias salariais por regiões do Brasil e por gênero, observa-se que as Regiões Centro-Oeste e Sudeste apresentam os maiores salários para mulheres nas áreas de dados. No entanto, ao comparar os salários entre gêneros, identificou-se que, na Região Centro-Oeste, os homens ganham em média 9,7% a mais do que as mulheres. Curiosamente, na Região Norte, embora os salários sejam os mais baixos, a diferença salarial entre homens e mulheres é a menor do país, com os homens ganhando cerca de 4,3% a mais.

Por fim, no âmbito educacional, as mulheres estão presentes em todos os níveis de ensino, embora em uma proporção menor. Contudo, a maioria das mulheres ainda se concentra em cursos de graduação/bacharelado e pós-graduação, sugerindo um foco predominante na formação superior de nível inicial, seguida por especialização.

Em resumo, embora as mulheres tenham conquistado um espaço importante em várias áreas profissionais, ainda existem barreiras claras à equidade, especialmente em relação à ocupação de cargos de liderança e à representatividade em certos campos de atuação. É fundamental que as organizações adotem estratégias mais inclusivas para que as mulheres possam não apenas ingressar, mas também prosperar e liderar em suas respectivas áreas de atuação.
