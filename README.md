**<h1>Documentação</h1>**
<br>
<h2>Dashboard Análise de Tedência</h2>
<p> O Objetivo é prever a tendicia futura de ligações recebidas</p>
<br>
<h2>Base de Dados</h2>
<p>A base de dados utilizada foi a de ligações pertecente ao fluxo de dados **CSC_TELEFONIA_GATEWAY**</p>

<p><b>Tabela Geral</b></p>
<ul>
<li>Asterisk ID
<li> Fila
<li> Atendida por 
<li> Originador 
<li> Desconexão
</ul>

<p><b>Tabela PF</b></p>
<ul>
<li>Chamadas_Historico
<li>Chamadas_Previtas 
<li>Data
<li>Limite_Inferior
<li>Limite_Superior
</ul>

<p><b>Tabela SACI</b></p>
<ul>
<li>Chamadas_Historico
<li>Chamadas_Previtas 
<li>Data
<li>Limite_Inferior
<li>Limite_Superior
</ul>

<p><b>Tabela SEMOB</b></p>
<ul>
<li>Chamadas_Historico
<li>Chamadas_Previtas 
<li>Data
<li>Limite_Inferior
<li>Limite_Superior
</ul>

<p><b>Tabela DER
</b></p>
<ul>
<li>Chamadas_Historico
<li>Chamadas_Previtas 
<li>Data
<li>Limite_Inferior
<li>Limite_Superior
</ul>

<h1>Ferramentas Utilizadas no Projeto</h1>
<p>Foi utilizado o Power BI para o desenvolvimento do Dashboard </p>

<br>

<h1>Tratamento dos Dados</h1>

<p><b>Tabela PF</b></p>
<ul>
<li>Remoção de colunas não necessarias
<li>Colunas renomeadas
<li>Execução de um script em python para a previsão 
<li>Expansão da tabela resultado
<li>Alteração na tipagem dos dados, colocado a tipagem correta  
</ul>

<p><b>Tabela SEMOB</b></p>
<ul>
<li>Remoção de colunas não necessarias
<li>Colunas renomeadas
<li>Execução de um script em python para a previsão 
<li>Expansão da tabela resultado
<li>Alteração na tipagem dos dados, colocado a tipagem correta  
</ul>

<p><b>Tabela SACI</b></p>
<ul>
<li>Remoção de colunas não necessarias
<li>Colunas renomeadas
<li>Execução de um script em python para a previsão 
<li>Expansão da tabela resultado
<li>Alteração na tipagem dos dados, colocado a tipagem correta  
</ul>

<p><b>Tabela DER</b></p>
<ul>
<li>Remoção de colunas não necessarias
<li>Colunas renomeadas
<li>Execução de um script em python para a previsão 
<li>Expansão da tabela resultado
<li>Alteração na tipagem dos dados, colocado a tipagem correta  
</ul>

<h1>Métricas</h1>
<ul>
<li>Custos
<li>Despesas
<li>Lucro
<li>Número de vendas
<li>Receita
</ul>

<br>

<h1>Relacionamentos</h1>

<ul>
<li>Pedidos(n) - (1)Produtos = muitos para um (n-1)
<li>Pedidos(1) - (1)Notas Fiscais = um para um (1-1)
<li>Vendedores(1) - (n)Notas Fiscais = um para muitos (1-n)
</ul>

<br>

<h1>Link do Dashboard</h1>
https://app.powerbi.com/view?r=eyJrIjoiMjVmMTljZGYtZDlmMy00NTMxLTkyYmQtZmRhYjliMGJiYTc0IiwidCI6Ijk0NjZmMmYwLTI4ZmQtNDYxMi04MjhkLTQ0YzdlNzU4MDA3OCJ9
