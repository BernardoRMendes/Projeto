# Projeto
**Como introdução, recomendo a leitura do arquivo PortfolioVol.pdf. Caso não tenha interesse em ler códigos em Python, vale a pena ler as thread's relacionadas ao twitter, pois elas reforçam conceitos teóricos importantes. Além disso, se você possui interesse em Machine Learning voltado a finanças, confira o aplicativo abaixo.**

**Aplicativo Metalabeling: Criei um App que generaliza o modelo apresentado na thread "3) Como aplicar Machine Learning em finanças de um modo inteligente?", para que você saiba em quais condições sua estratégia tem maior probabilidade de acerto. Vou deixar os links aqui, agradeço quem puder testar. Favor entrar em contato enviando sugestões, dúvidas, bugs, etc. Leia o Manual antes para entender a ideia e o App.**

- Link do Aplicativo: http://metalabel.mlteste.com:8501

- Manual de uso: https://s3-sa-east-1.amazonaws.com/manual.mlteste.com/ManualApp.pdf

- Planilhas de exemplo: https://s3-sa-east-1.amazonaws.com/manual.mlteste.com/planilhas.7z

**Breve Resumo de cada Projeto:**

1) LongVolSPX.ipynb: Na construção de portfólios, a interação entre as estratégias é mais importante do que a performance individual de cada uma delas. Estratégias que à primeira vista parecem ruins podem gerar valor a um portfólio de ações.
   
   -Thread relacionada: https://twitter.com/berchades/status/1384173190172217363

2) Hedge.ipynb: Utiliza o conceito de correlação condicional para verificar quais ativos atuam como hedge em diferentes partes da distribuição de retornos do Ibovespa.

   -Thread relacionada: https://twitter.com/berchades/status/1386691805153013761
   
3) Estimadores_Volatilidade_Final.ipynb: Código com indicadores de volatilidade histórica (além do tradicional close-to-close).
    
   -Thread relacionada: https://twitter.com/berchades/status/1395431999557488646

4) Correlação_Implícita.ipynb: Esse estudo mostra como a Correlação Implícita pode ser usada como uma ferramenta de avaliação de risco.

5) IndicadorPriceAction.ipynb: Nesse estudo apresento um indicador de Price Action que utiliza apenas dados de abertura, máxima, mínima e fechamento para detectar regiôes de compra e venda.

6) VaR_Modificado.ipynb: Mostramos como não devemos limitar a análise de risco ao VaR paramétrico (assumindo normalidade), apresentando uma versão modificada, com aplicações tanto para alocadores quanto para gestores.

   -Thread relacionada: https://twitter.com/berchades/status/1387819681269043207

7) FatorQualityValue.ipynb: Cria um portfólio de ações com base nos fatores Qualidade e Valor. É um método complementar à seleção por Momentum, contribuindo para a diversificação de portfólio. 

8) Portfólio com viés de Momentum ajustado pela volatilidade utilizando apenas ETF's internacionais: http://momentum.mlteste.com/

9) Portfólio com viés de Momentum ajustado pela volatilidade com ações do IBrA B3 (Índice Brasil Amplo): http://momentumbr.mlteste.com/

10) FatoresUSA.ipynb: Mostra a decomposição dos retornos em fatores e como verificar se há geração de alpha.

11) analiseportfolio.ipynb: Criação e análise de um portfólio Smart Beta (Long-Only) com ETF's setoriais de large caps americanas.
    
    
**Threads Twitter**
1) Todo investidor de longo prazo deveria entender o que é Skew e como isso impacta seu portfólio. 
  
   -https://twitter.com/berchades/status/1382713925398056962

2) Será que toda estratégia aparentemente ruim deve ser excluída do seu portfólio?
  
   -https://twitter.com/berchades/status/1384173190172217363

3) Como aplicar Machine Learning em finanças de um modo inteligente?

   -https://twitter.com/berchades/status/1384898784560353280
   
   -Aplicativo: http://app.mlteste.com:8501/
   
4) Será que o Ouro é um bom hedge para o Ibovespa?
   
   -https://twitter.com/berchades/status/1386691805153013761
   
5) Considerações sobre o VaR (Value-at-Risk) e como ajustar o position sizing considerando outros momentos da distribuição de retornos:
   
   -https://twitter.com/berchades/status/1387819681269043207
   
6) Ações para o longo prazo? Não é tão simples quanto parece...
   
   -https://twitter.com/berchades/status/1389261246935994370

7) Quanto tempo devemos esperar para rejeitar um Fator já aceito e estabelecido pela academia e por praticantes?
   
   -https://twitter.com/berchades/status/1391804423618408459
   
8) Performance acima do benchmark significa geração de Alpha?
   
   -https://twitter.com/berchades/status/1393254091741175808
   
9) O que é mais eficiente: Diversificar entre países ou entre setores?

     -https://twitter.com/berchades/status/1394335515575558146
   
10) Estimadores Volatilidade Histórica:
  
      -https://twitter.com/berchades/status/1395431999557488646
   
11) Por que volatilidade e sharpe são métricas insuficientes para avaliar o risco real de um portfólio e podem fazer você perder ainda mais que o esperado?
 
      -https://twitter.com/berchades/status/1396877847961247750

12) Você está diversificado o suficiente?
   
      -https://twitter.com/berchades/status/1400147435612250118
      
13) 5 Livros para entender e implementar técnicas de Hedge, desde o ponto de vista conceitual até a prática.

      -https://twitter.com/berchades/status/1405218098635026441
