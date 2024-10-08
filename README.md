<h1 align='center'>Análise de Críticas de Jogos no Steam</h1>
<h4 align='center'>🚧Projeto em andamento🚧</h4>

<h2>Descrição</h2>
<p>Este projeto tem como objetivo descobrir o que faz um jogo ser bem avaliado no Steam, utilizando técnicas de análise de dados. Através de um conjunto de dados consolidado de críticas, preços, horas jogadas e outras variáveis relacionadas aos jogos, realizamos análises de correlação para entender os fatores que influenciam as avaliações dos usuários.</p>

<p>O projeto utiliza <strong>Python</strong> e integra <strong>Programação Orientada a Objetos (POO)</strong> com bibliotecas de análise de dados como <strong>Pandas</strong>, <strong>Numpy</strong>, e <strong>Matplotlib</strong>.</p>

<h2>Download dos Datasets</h2>
<p>Os datasets utilizados neste projeto podem ser baixados através dos links abaixo:</p>
<ul>
  <li><a href="https://www.kaggle.com/datasets/fronkongames/steam-games-dataset" target="_blank">Dataset 1: Dataset de informações dos jogos na Steam</a></li>
  <li><a href="https://www.kaggle.com/datasets/andrewmvd/steam-reviews" target="_blank">Dataset 2: Dataset de reviews dos jogos na Steam</a></li>
</ul>
<p>Todos os datasets estão no formato <code>.csv</code> para facilitar o uso com bibliotecas como <strong>Pandas</strong>.</p>


<h2>🎯Objetivo</h2>
<p>Explorar padrões em críticas de jogos no Steam para identificar quais fatores têm impacto direto nas notas que os jogos recebem. Nosso objetivo é entender como variáveis como tempo de jogo, preço, produtora e ano de lançamento afetam as avaliações dos jogadores.</p>

<h2>💻Tecnologias Utilizadas</h2>
<ul>
  <li><strong>Python🐍</strong></li>
  <li><strong>Programação Orientada a Objetos (POO)</strong></li>
  <li><strong>Pandas🐼</strong></li>
  <li><strong>Numpy🧮</strong></li>
  <li><strong>Matplotlib📊</strong></li>
</ul>

<h2>Funcionalidades</h2>
<ul>
  <li>Agrupamento e manipulação de dados das críticas de jogos com suas respectivas informações.</li>
  <li>Análises de correlação entre:
    <ul>
      <li>Tempo de jogo e nota.</li>
      <li>Preço do jogo e nota.</li>
      <li>Quantidade de notas ruins, médias e boas ao longo dos anos de lançamento.</li>
      <li>Produtora do jogo e a nota.</li>
    </ul>
  </li>
  <li><strong>Pipeline de dados</strong> reutilizável para automatizar a coleta e atualização de dados.</li>
</ul>

<h2>❔Como Utilizar</h2>
<ol>
  <li>Clone o repositório:
    <pre><code>git clone https://github.com/seu-usuario/nome-do-repositorio.git</code></pre>
  </li>
  <li>Instale as dependências:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li>Execute o script principal:
    <pre><code>python main.py</code></pre>
  </li>
  <li>Para visualizar gráficos e análises, acesse o diretório <code>visualizations</code> onde os gráficos gerados serão armazenados.</li>
</ol>

<h2>🗂Estrutura do Projeto</h2>
<ul>
  <li><code>main.py</code>: Arquivo principal que executa a coleta e análise dos dados.</li>
  <li><code>data/</code>: Contém os datasets utilizados no projeto.</li>
  <li><code>visualizations/</code>: Armazena as visualizações gráficas geradas pelo projeto.</li>
  <li><code>pipeline.py</code>: Script responsável pelo pipeline de dados.</li>
  <li><code>README.md</code>: Este arquivo.</li>
  <li><code>requirements.txt</code>: Lista de bibliotecas necessárias para rodar o projeto.</li>
</ul>

<h2>🔎Análises Realizadas</h2>
<p>As seguintes correlações são exploradas no projeto:</p>
<ul>
  <li><strong>Tempo de jogo x Nota:</strong> Como o tempo investido pelos jogadores está relacionado à avaliação final.</li>
  <li><strong>Preço x Nota:</strong> Avaliando se o preço afeta positivamente ou negativamente as avaliações dos usuários.</li>
  <li><strong>Notas ao longo do tempo:</strong> Analisando a quantidade de notas ruins, médias e boas em relação ao ano de lançamento.</li>
  <li><strong>Produtora x Nota:</strong> Avaliando se determinadas produtoras tendem a receber melhores ou piores avaliações.</li>
</ul>

<h2>Resultados</h2>
<p>Nenhum resultado específico definido até o momento, já que o projeto está focado em coleta e análise de dados.</p>

<h2>Futuras Implementações</h2>
<ul>
  <li>Criar um dashboard interativo para visualizar as correlações em tempo real.</li>
  <li>Implementar técnicas de <strong>Machine Learning</strong> para prever a avaliação de jogos futuros com base nos dados históricos.</li>
</ul>

<h2>Contribuições</h2>
<p>Contribuições são bem-vindas! Sinta-se à vontade para abrir <strong>issues</strong> e enviar <strong>pull requests</strong>.</p>

<h2>Licença</h2>
<p>Este projeto está licenciado sob a licença MIT.</p>
