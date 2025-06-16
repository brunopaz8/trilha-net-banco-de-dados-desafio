# 📚 Desafio de Código SQL 🗃️

Este repositório contém a resolução de um **desafio de projeto em SQL**, proposto durante um curso da **[Digital Innovation One (DIO)](https://www.dio.me/)**. O objetivo é praticar e consolidar conhecimentos em SQL por meio de consultas, manipulação de dados e resolução de problemas comuns em bancos de dados relacionais.

O exercício contribui para o aprimoramento das habilidades em escrita de queries, compreensão de estruturas de tabelas e uso de comandos essenciais como `SELECT`, `JOIN`, `GROUP BY`, entre outros.

---

## 🟣 Proposta

Você deverá realizar **12 consultas** ao banco de dados, cada uma retornando um tipo específico de informação.

A estrutura do banco de dados está representada no seguinte diagrama:

### 🗂️ Estrutura das Tabelas

* **Filmes**: Armazena informações sobre os filmes.
* **Atores**: Armazena informações dos atores.
* **Gêneros**: Armazena os gêneros dos filmes.
* **ElencoFilme**: Representa o relacionamento *muitos para muitos* entre filmes e atores (um ator pode participar de vários filmes, e um filme pode ter vários atores).
* **FilmesGenero**: Representa o relacionamento *muitos para muitos* entre filmes e gêneros (um filme pode ter mais de um gênero, e um gênero pode estar presente em vários filmes).

---

## 🛠️ Preparando o Banco de Dados

Execute o arquivo `Script Filmes.sql` no seu SQL Server. O script está disponível na pasta `Scripts` deste repositório ([clique aqui](Script%20Filmes.sql)). Ele irá:

* Criar o banco de dados `Filmes`;
* Criar todas as tabelas mencionadas;
* Inserir os dados necessários para realizar o desafio.

---

## 🎯 Objetivo

Você deverá escrever consultas SQL que retornem os seguintes resultados. Abaixo de cada item, há uma imagem com o **retorno esperado** — sua saída deve corresponder ao exemplo.

---

###


## 1️⃣ - Buscar o nome e ano dos filmes

![Exercicio 1](Imagens/1.png)

## 2️⃣ - Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano

![Exercicio 2](Imagens/2.png)

## 3️⃣ - Buscar pelo filme de volta para o futuro, trazendo o nome, ano e a duração

![Exercicio 3](Imagens/3.png)

## 4️⃣ - Buscar os filmes lançados em 1997

![Exercicio 4](Imagens/4.png)

## 5️⃣ - Buscar os filmes lançados APÓS o ano 2000

![Exercicio 5](Imagens/5.png)

## 6️⃣ - Buscar os filmes com a duracao maior que 100 e menor que 150, ordenando pela duracao em ordem crescente

![Exercicio 6](Imagens/6.png)

## 7️⃣ - Buscar a quantidade de filmes lançadas no ano, agrupando por ano, ordenando pela duracao em ordem decrescente

![Exercicio 7](Imagens/7.png)

## 8️⃣ - Buscar os Atores do gênero masculino, retornando o PrimeiroNome, UltimoNome

![Exercicio 8](Imagens/8.png)

## 9️⃣ - Buscar os Atores do gênero feminino, retornando o PrimeiroNome, UltimoNome, e ordenando pelo PrimeiroNome

![Exercicio 9](Imagens/9.png)

## 🔟 - Buscar o nome do filme e o gênero

![Exercicio 10](Imagens/10.png)

## 1️⃣1️⃣ - Buscar o nome do filme e o gênero do tipo "Mistério"

![Exercicio 11](Imagens/11.png)

## 1️⃣2️⃣ - Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel

![Exercicio 12](Imagens/12.png)

## 📂 Resolução

A resolução completa do desafio, com os scripts SQL utilizados para cada consulta, está disponível na pasta [`Resolução`](Resolução/) deste repositório.



