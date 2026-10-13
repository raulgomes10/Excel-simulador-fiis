# Simulador de Investimentos em Fundos Imobiliários (FIIs)

Repositório criado para documentar a reprodução de uma ferramenta interativa de simulação de investimentos em Fundos Imobiliários no Excel do Expert Felipe Aguiar, cobrindo desde o aporte mensal inicial até a projeção de patrimônio e o recebimento de dividendos.

##  Visão Geral da Ferramenta

A estruturada da planilha é organizada em cinco etapas principais para garantir precisão e dinamismo nos cálculos financeiros:

1. **Construção da Base:** Configuração inicial da planilha e dos parâmetros de simulação de investimentos.
2. **Intervalos Nomeados:** Organização de referências e fórmulas para facilitar a leitura, o entendimento e a manutenção dos dados.
3. **Perfil de Investidor (PROCV):** Criação de uma tabela de apoio associada à função PROCV para segmentar e direcionar o aporte mensal de acordo com o perfil de cada investidor.
4. **Projeção de 2 a 30 anos (VF):** Utilização da função financeira de Valor Futuro (VF) para calcular e projetar a evolução do patrimônio ao longo do horizonte temporal escolhido.
5. **Cálculo de Dividendos:** Simulação dos rendimentos mensais gerados pelos Fundos Imobiliários com base no patrimônio acumulado.

##  Perguntas de Negócio:
1.	Quanto investir por mês ?
2.	Por quantos anos ?
3.	Taxa de rendimento mensal ?
4.	Patrimônio acumulado ?
5.	Dividendos mensais ?

##  Intervalos Nomeados:
1.	Aporte
2.	Patrimônio
3.	qtd_anos
4.	Rendimento_Carteira
5.	Salario
6.	sugestao_investimento
7.	taxa_mensal

##  Percentuais de cada perfil de Investidor:
Conservador
1.	PAPEL: 35%
2.	TIJOLO: 55%
3.	HÍBRIDOS: 5%
4.	FOFs: 5%
5.	DESENVOLVIMENTO: 0%
6.	HOTELARIAS: 0%
Moderado
1.	PAPEL: 30%
2.	TIJOLO: 37%
3.	HÍBRIDOS: 10%
4.	FOFs: 7%
5.	DESENVOLVIMENTO: 8%
6.	HOTELARIAS: 8%
Agressivo
1.	PAPEL: 25%
2.	TIJOLO: 30%
3.	HÍBRIDOS: 15%
4.	FOFs: 5%
5.	DESENVOLVIMENTO: 15%
6.	HOTELARIAS: 10%

Os valores das porcentagens são apenas para exemplo, não recomendações de investimentos. 

##  Arquivos Inclusos
- **F.Invest_Reprod_Desafio 1:** A planilha resolvida contendo a ferramenta completa, as fórmulas estruturadas e as simulações de cenários.

##  Considerações Finais
Este projeto permitiu aplicar na prática conceitos avançados de modelagem financeira no Excel, unindo funções lógicas e matemáticas (como PROCV e VF) à criação de uma solução real para planejamento de investimentos.
As porcentagens e valores apresentados nessa ferramenta são apenas para exemplo. Não são recomendações de investimentos.
Em relação a ferramenta do Expert foram feitas alterações visuais, valores de porcentagens e a disposição de um gráfico de pizza dinâmico de acordo com o perfil de investidor.

