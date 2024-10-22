Pandas: Limpeza e Tratamento de Dados
Este repositório contém um projeto de limpeza e tratamento de dados utilizando a biblioteca Pandas. O objetivo é ler dados em formato JSON, tratar inconsistências, lidar com dados nulos e duplicados, identificar e manipular outliers, e preparar as variáveis para análises futuras, como codificação de variáveis categóricas.

📂 Conteúdo
1. Leitura e Normalização de Dados
Leitura do JSON: Carregamento da base de dados no formato JSON.
json_normalize: Conversão de objetos JSON para DataFrames.
2. Exploração e Transformação Inicial
info(): Inspeção inicial dos dados.
Alteração de Tipo (cast): Modificação do tipo de uma coluna específica.
Inserção de Valores: Adição de dados em colunas específicas.
Filtragem e Remoção de Strings Vazias: Identificação e exclusão de strings vazias.
3. Tratamento de Duplicatas e Dados Nulos
Identificação e Remoção de Duplicados: Localização e exclusão de dados repetidos.
Identificação de Dados Nulos: Verificação de valores nulos no dataset.
Inserção de Valores Substitutos: Preenchimento de valores nulos com dados adequados.
Remoção de Dados Nulos: Exclusão de amostras com valores ausentes.
4. Tratamento de Outliers
Identificação de Outliers com IQR: Uso do Intervalo Interquartil (IQR) para detecção de outliers.
Visualização com Boxplot: Identificação de candidatos a outliers via boxplot.
Tratamento de Outliers:
Substituição de valores fora do intervalo.
Remoção de amostras com outliers severos.
5. Manipulação de Variáveis Categóricas
Identificação de Variáveis Categóricas: Reconhecimento das colunas com dados categóricos.
Substituição de Variáveis Binárias: Conversão de variáveis categóricas binárias para valores numéricos.
One-Hot Encoding: Aplicação de one-hot encoding para variáveis com múltiplas categorias.

🛠️ Ferramentas e Técnicas Utilizadas
Pandas para manipulação e análise dos dados.
Boxplot para detecção visual de outliers.
One-Hot Encoding para transformar variáveis categóricas em numéricas.
