# Dashboard RH
## Introdução
Este projeto de Power BI foca em análises de Recursos Humanos (RH) e tem como objetivo oferecer insights sobre diversos aspectos relacionados à gestão de pessoas dentro de uma organização. Por meio de visualizações interativas e indicadores-chave, o dashboard proporciona uma visão abrangente que facilita a tomada de decisões estratégicas.

O conjunto de dados utilizado inclui colunas abrangendo informações detalhadas sobre os colaboradores, como idade, salário, promoções, viagens a trabalho e níveis de satisfação no ambiente organizacional, entre outros. A análise realizada busca identificar tendências, padrões e áreas de melhoria, apoiando o alinhamento das práticas de RH com os objetivos da empresa.

## Dados
Como o projeto está escrito em português do Brasil, realizei a tradução das colunas para o nosso idioma diretamente no Power Query do Power BI. Durante o processo, identifiquei algumas inconsistências nos dados. Por exemplo, na coluna "Viagens a Trabalho", havia uma duplicidade de valores com grafias diferentes: “No_Travel” e “no_travel”. Esse tipo de situação reforça a importância de verificar os valores únicos presentes nos dados para garantir a consistência da análise.

Outra modificação foi a exclusão de uma coluna de "Contagem de Funcionários", onde todos os registros possuíam o valor fixo “1”. Essa coluna se mostrou redundante, pois é possível realizar essa contagem diretamente em DAX ao contabilizar cada linha retornada, desde que o ID do Funcionário seja único em todos os registros.

## Colunas

**ID do Funcionário:** Identificação única do funcionário

**Idade:** Idade do funcionário

**Faixa Etária:** Faixa etária à qual o funcionário pertence

**Status de Desligamento:** Indica se o funcionário deixou a organização ou ainda está ativo

**Viagens a Trabalho:** Frequência de viagens a trabalho do funcionário

**Taxa Diária:** Remuneração diária do funcionário

**Departamento:** Departamento em que o funcionário trabalha

**Distância até o Trabalho:** Distância em milhas da casa do funcionário até o local de trabalho

**Nível de Educação:** Nível de educação alcançado pelo funcionário

**Área de Formação:** Área de formação do funcionário

**Contagem de Funcionários:** Número total de funcionários

**Número do Funcionário:** Identificador único de cada funcionário

**Satisfação com o Ambiente:** Nível de satisfação do funcionário com o ambiente de trabalho

**Gênero:** Gênero do funcionário

**Taxa Horária:** Remuneração por hora do funcionário

**Envolvimento no Trabalho:** Nível de envolvimento do funcionário no trabalho

**Nível do Cargo:** Nível da posição ocupada pelo funcionário

**Função no Trabalho:** Função desempenhada pelo funcionário na organização

**Satisfação no Trabalho:** Nível de satisfação do funcionário com o trabalho

**Estado Civil:** Estado civil do funcionário

**Renda Mensal:** Renda mensal do funcionário

**Faixa Salarial:** Classificação da renda mensal em faixas salariais

**Taxa Mensal:** Remuneração mensal do funcionário

**Empresas Anteriores:** Número de empresas nas quais o funcionário já trabalhou

**Maior de 18 Anos:** Indica se o funcionário tem mais de 18 anos

**Horas Extras:** Indica se o funcionário trabalha horas extras ou não

**Aumento Salarial (%):** Percentual de aumento salarial do funcionário

**Avaliação de Desempenho:** Avaliação de desempenho do funcionário

**Satisfação com Relacionamentos:** Nível de satisfação do funcionário com os relacionamentos no trabalho

**Horas Padrão:** Carga horária padrão do funcionário

**Nível de Opções de Ações:** Nível de opções de ações concedidas ao funcionário

**Anos de Experiência:** Total de anos de experiência profissional do funcionário

**Treinamentos no Último Ano:** Número de treinamentos realizados pelo funcionário no último ano

**Equilíbrio Trabalho-Vida:** Nível de satisfação do funcionário com o equilíbrio entre trabalho e vida pessoal

**Anos na Empresa:** Número de anos que o funcionário trabalhou na empresa atual

**Anos na Função Atual:** Número de anos que o funcionário está na função atual

**Anos desde a Última Promoção:** Número de anos desde a última promoção do funcionário

**Anos com o Gerente Atual:** Número de anos que o funcionário trabalha com o gerente atual

## Dashboads
### Dashboard 1
<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio_page-0001.jpg" alt="Exemplo de Imagem" width="1000">
</p>
### Dashboard 2
<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio_page-0002.jpg" alt="Exemplo de Imagem" width="1000">
</p>
### Dashborad 3
<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio_page-0003.jpg" alt="Exemplo de Imagem" width="1000">
</p>

## Conclusão
A construção dos três dashboards demonstrou habilidades essenciais em análise de dados e visualização, envolvendo o uso avançado do Power BI para transformar grandes volumes de dados em insights acionáveis. A criação de relatórios dinâmicos e interativos, com foco em métricas-chave, facilitou a tomada de decisões estratégicas. A integração de fontes de dados diversas e a personalização de visualizações reforçam a capacidade de atender às necessidades específicas de cada área. Além disso, o trabalho evidenciou a importância da clareza na comunicação dos resultados por meio de dashboards intuitivos e de fácil interpretação.


