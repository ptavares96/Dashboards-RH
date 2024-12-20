# Dashboard RH
## Introdução
Este projeto de Power BI foca em análises de Recursos Humanos (RH) e tem como destacar a distribuição dos funcionários dentro de uma empresa. 

O conjunto de dados utilizado inclui colunas com informações  sobre os funcionários: como idade, salário, promoções, viagens a trabalho e níveis de satisfação no ambiente organizacional, entre outros. A análise enteder a distribuição dos funcionários dentro do setor, buscando identificar algum padrão nessa distribuição. 

## Dados
Como o projeto está escrito em português do Brasil, realizei a tradução das colunas para o nosso idioma diretamente no Power Query do Power BI. Durante o processo, identifiquei algumas inconsistências nos dados. Por exemplo, na coluna "Viagens a Trabalho", havia uma duplicidade de valores com grafias diferentes: “No_Travel” e “no_travel”. Esse tipo de situação reforça a importância de verificar os valores únicos presentes nos dados para garantir a consistência da análise.

Outra modificação foi a exclusão de uma coluna de "Contagem de Funcionários", onde todos os registros possuíam o valor fixo “1”. Essa coluna se mostrou redundante, pois é possível realizar essa contagem diretamente em DAX ao contabilizar cada linha retornada da tabela.

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

## Dashboards
No primeiro Dashborad vemos que:
* O total de funcionários que esta empresa já teve é de **1480**.
* Atualmete a empresa conta com **1242** funcionários.
* A taxa de desligamento da empresa é de **16,1%**.
* A média de satisfação dos funcionários ativos com abiente e trabalho é de **2,8**.
* A média de equilíbrio de trabalho-vida e o envolvimento no trabalho dos funcionários ativos é de **2,8%**.
* Maior parte dos funcionários estão no setor de Pesquisa e Desenvolvimento.
* O setor de Vendas possui a maior taxa de desligamento de **20,7%**
* Há mais funcionários nas funções de Executivo de Vendas.
* Representante de Vendas é onde há mais desligamento com **39,3%** de taxa.

<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio%20RH_page-0001.jpg" alt="Exemplo de Imagem" width="1000">
</p>

No segundo Dashboard:
* A maior parte dos funcionários possuem idade entre 26 e 35 anos.
* **50,42%** dos Funcionários são do gênero masculino e **40,58%** de gênero feminino.
* **47,91%** dos funcionários são casados, **23,67%** são divorciados e **28,42%** são solteiros.
* Maior parte dos funcionários são formados na área de Ciências Biológicas.
* Maior parte dos funcioários estão nível de Educação (3) que corresponde ao Ensino Médio completo. 

<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio%20RH_page-0002.jpg" alt="Exemplo de Imagem" width="1000">
</p>

Sobre o Dashboard 3:
* A média de salário na empresa é de **R$6500,00**.
* **39,9%** dos funcionários já receberam alguma promoção.
* O aumento salarial dos funcionários é de **15,2%**.
* **71,9%** dos funcionários raramente viajam a trabalho, **16,9%** viajam frequentemente e **11,2%** não viajam.
* **76,7%** dos funcionários não fazem horas extras enquanto **23,3%** dos funcionários realizam.
* A maior parte dos funcionários recebem menos de R$5000,00.
* 7 anos é a média que um funcionário permanece na empresa.
* Em média um funcionário fica 4 anos na mesma função.
* 2 anos é média que um funcionário recebe uma promoção. 
<p align="center">
  <img src="https://github.com/ptavares96/Dashboards-RH/blob/main/Imagens/Relat%C3%B3rio%20RH_page-0003.jpg" alt="Exemplo de Imagem" width="1000">
</p>


