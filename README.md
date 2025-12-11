# Projeto-em-Python-An-lise-de-Cursos-no-Exterior

🎯 Visão Geral
Este projeto utiliza técnicas de Análise Exploratória de Dados (EDA) para auxiliar aqueles que o desejo ou planejamento de estudar no exterior. O objetivo é fornecer insights baseados em dados sobre:

Custo de Vida (Housing, Alimentação, Transporte) nas principais cidades de intercâmbio.

Melhores Cursos e Especializações mais demandados e bem avaliados.

Comparativo de Investimento Total (Cursos + Custo de Vida) por destino.

Todo o projeto foi desenvolvido no ambiente Google Colab, garantindo reprodutibilidade e facilidade de execução.

🛠️ Metodologia e Tecnologias
O projeto seguiu as seguintes fases:

Coleta de Dados: Os dados foram obtidos através de fontes públicas (simulação de datasets de custo de vida e rankings universitários).

Limpeza e Transformação: Tratamento de valores nulos, padronização de moedas (conversão para BRL ou USD) e criação de métricas comparativas.

Análise Exploratória (EDA): Foco na distribuição e correlação entre custo de vida e qualidade dos cursos.

Visualização: Utilização de gráficos para comparar destinos.

Tecnologias Utilizadas:

Ambiente: Google Colab

Linguagem: Python

Bibliotecas: pandas, seaborn e matplotlib

🔑 Principais Descobertas e Resultados
1. Custo de Vida por Destino 🏙️
A análise detalhada do custo de vida revelou grandes variações que impactam o investimento final do estudante:

Destinos de Alto Custo: Cidades como Nova York (EUA) e Londres (Reino Unido) apresentaram os maiores custos mensais de moradia (aluguel), exigindo um planejamento financeiro robusto.

Destinos Acessíveis: Cidades como Halifax (Canadá) e Hobort (Austrália) demonstraram um equilíbrio entre qualidade de vida e custo, sendo opções mais viáveis para orçamentos medianos.

2. Melhores Cursos e Especializações 🎓
A análise focou em rankings de universidades e na demanda de mercado por especializações:

Especializações de Alto Retorno: Inteligência Artificial (IA), Data Science e Engenharia de Software foram consistentemente listadas em universidades de elite e com alto salário médio pós-graduação.

Melhores Cursos (Qualidade vs Custo): Foi possível identificar universidades com excelente reputação em áreas como Marketing Digital e Gestão de Projetos que oferecem programas com custos de matrícula inferiores aos top-tier globais.

3. Custo-Benefício Total
O projeto concluiu que o melhor custo-benefício está frequentemente em países europeus com foco em Portugal e Holanda, que oferecem alta qualidade educacional com custo de vida significativamente menor que EUA, Canadá ou Reino Unido.

⚙️ Como Reproduzir o Projeto (Google Colab)
Para explorar a análise completa e os gráficos gerados, basta seguir este passo a passo:

Acesse o Notebook: Clique no link do arquivo [![Excel](/content/International_Education_Costs.csv) ou abra-o diretamente no Google Colab.

Instale as Dependências: Execute a primeira célula do notebook para instalar as bibliotecas necessárias (!pip install ...).

Execute as Células: Siga a ordem das células para carregar, limpar, analisar e visualizar os dados.
