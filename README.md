# Automacao-em-Python
Análise de Dados com Python. Desafio aprendido na semana "Intensivão de Python" pelo canal Hashtag Programação.
Utilizando o editor Jupyter Notebook, para a realização do desenvolvimento da programação (no momento o código não roda em outros editores de texto como Visual Studio Code).

Desafio apresentado:
 "Você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.
  O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn (desistência)  de mais de 26% dos clientes.
  Isso representa uma perda de milhões para a empresa."
  
 Resolução:
 Primeiramente foi realizado a análise do problema que estabelece o passo a passo das ações a serem tomadas, sendo elas:
   Passo 1: Importar a base de dados
   Passo 2: Visualizar a base de dados
    - Entender quais as informações tão disponíveis
    - Descobrir os erros da base de dados
   Passo 3: Tratamento de dados
    - Valores que estão reconhecidos de forma errada
    - Valores vazios (deletando as linhas e colunas vazias)
   Passo 4: Análise Inicial
    - Como estão os nossos cancelamentos?
   Passo 5: Análise Mais completa
    - Comparar cada coluna da minha tabela com a coluna de cancelamento
    - Etapa 1: criar o gráfico
    - Etapa 2: exibir o gráfico
    
  Conclusões e Ações:
   - Clientes com contrato mensal tem MUITO mais chance de cancelar:
   - Podemos fazer promoções para o cliente ir para o contrato anual;
   - Familias maiores tendem a cancelar menos do que famílias menores;

   - Podemos fazer promoções para pessoa pegar uma linha adicional de telefone;
   - MesesComoCliente baixos tem MUITO cancelamento. Clientes com pouco tempo como cliente tendem a cancelar muito;

   - A primeira experiência do cliente na operadora pode ser ruim;
   - Talvez a captação de clientes tá trazendo clientes desqualificados;
   - Ideia: a gente pode criar incentivo pro cara ficar mais tempo como cliente;
   - Quanto mais serviços o cara tem, menos chance dele cancelar;
   - Podemos fazer promoções com mais serviços para o cliente;
   
   - Tem alguma coisa no nosso serviço de Fibra que tá fazendo os clientes cancelarem;
   - Agir sobre a fibra;
   - Clientes no boleto tem MUITO mais chance de cancelar, então temos que fazer alguma ação para eles irem para as outras formas de pagamento.
