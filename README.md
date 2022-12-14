<h2 align="center">Bem Vindo</h2>
<div align="center">
<img width="360px"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" />
</div>

<div align="center">
<details>
<summary>O que é Banco de dados</summary><br><b>
Um banco de dados, ou seja, uma maneira estruturada de 
armazenar e acessar dados. No caso MongoDB em especifíco,
é um banco de dados NoSQL
</b></details>



<details>
<summary>O que é Banco de dados NoSQL</summary><br><b>
NoSQL é um termo muito genérico usado para descrever qualquer
armazenamento de dados, que não usa a abordagem herdada de
tabelas de dados relacionadas. Isso significa que você está
armazenando seus dados de forma organizada, mas não em linhas e
colunas.
</b></details>




<details>
<summary>Por que NoSQL</summary><br><b>
Termo NoSQL é muito genérico então devemos restringir ainda mais
nossa definição. MongoDB é um banco de dados de documentos NoSQL,
isso significa que os dados no MongoDB são armazenados como documentos,
esses documentos, por sua vez, são armazenados no que chamamos de coleções
de documentos. Por isso MongoDB é categorizado como um banco de dados de 
documentos NoSQL.
</b></details>



<details>
<summary>Documento</summary><br><b>
Documento é uma maneira de organizar e armazenar dados
como um conjunto de pares de valor de campo.
</b></details>


#


<details>
<summary>O que é Atlas</summary><br><b>
Atlas é banco de dados em nuvem totalmente gerenciado,
construído para uma ampla variedade de aplicativos, com
MongoDB em seu Núcleo. Usuários do Atlas podem implantar
clusters.

##

<details>
<summary>Cluster</summary><br><b>
Cluster são grupos de servidores que armazenam seus dados.
Esses servidores são configurados no que chamamos de conjunto
de réplicas, que é um conjunto de algumas instâncias conectadas
do MongoDB que armazenam os mesmos dados.
</b></details>

##

<details>
<summary>Instância</summary><br><b>
Uma instância é uma única máquina, localmente ou na nuvem,
executando um determinado software. Nesse caso, é o banco de
dados MongoDB sendo executado na nuvem.
Essa configuração garante que, se algo acontecer com uma das máquinas
no conjunto de réplicas, os dados permanecerão intactos e disponíveis para uso
do aplicativo pelos membros de trabalho restantes do conjunto de réplicas.
Portanto, toda vez que você faz alterações em um documento ou coleção,
cópias redudantes desses dados são armazenadas no conjunto de réplicas.


</b></details>
</b></details>

##

<details>
<summary>Comandos</summary><br><b>

<details>
<summary>show dbs</summary><br><b>
show dbs mostra a lista de bancos de dados que estão no cluster.
</b></details>
</b></details>

<details>
<summary>use</summary><br><b>
Para indicar qual banco de dados usar, utilizamos o comando
use + Nome_Banco_Dados. Exemplo, use sample_training dessa forma
você tera acesso aquele banco.
</b></details>
</b></details>

<details>
<summary>show collections</summary><br><b>
Para visualizar as coleções no banco de dados, utilizamos o comando
show collections.
</b></details>
</b></details>

<details>
<summary>find()</summary><br><b>
Para procurar um dado utilizamos o comando find().
exemplo: db.zips.find( { "state": "NY"} ), neste exemplo
utilizamos objeto db que está apontando para o banco que dados,
sendo zips a collection e find() o comando de busca, o que se encontra
dentro de find() são document representado pelas { } e "state": "NY" o filtro
de consulta em JSON.
</b></details>
</b></details>

<details>
<summary>count</summary><br><b>
Para visualizar a quantidade de consultas utilizamos o comando .count() ao final de uma consulta, exemplo:
db.zips.find({ "state": "NY"}).count() 
Desta forma ele nos retornara o numero de documentos que se encaixam nesta
consulta.
</b></details>
</b></details>



















</div>
