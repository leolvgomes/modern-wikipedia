# Projeto Wikipédia - Vinícius Júnior (HTML Puro)

Este projeto é uma recriação simplificada da página da Wikipédia do jogador Vinícius Júnior, desenvolvida inteiramente em HTML puro, sem uso de CSS ou JavaScript.
O objetivo é praticar a estruturação de conteúdo em HTML, utilizando apenas os elementos semânticos da linguagem — como tabelas, listas, títulos e links — de forma semelhante às primeiras versões da Wikipédia.

---

## Objetivo do projeto

O projeto foi criado para:

* Exercitar a organização e hierarquia de conteúdo em HTML.
* Reproduzir um layout simples no estilo Wikipédia.
* Praticar o uso de elementos básicos como `<h1>`, `<p>`, `<table>`, `<ul>` e `<a>`.
* Compreender como o HTML puro pode estruturar informações de maneira clara e acessível.

---

## Estrutura do projeto

```
/
├── index.html     # Página principal (biografia do Vinícius Júnior)
└── README.md      # Documentação do projeto
```

---

## Conteúdo da página

A página está dividida em seções, simulando o formato de um artigo da Wikipédia:

### Cabeçalho e introdução

* Exibe o nome completo Vinícius José Paixão de Oliveira Júnior.
* Parágrafo inicial com informações básicas: data de nascimento, posição, clubes e seleção.

### Linha do tempo da carreira

* Uma tabela simples mostrando os clubes em que o jogador atuou, com anos, jogos e gols.

### Carreira

* Detalhes sobre o início no Flamengo, transferência para o Real Madrid e trajetória profissional.

### Seleção Brasileira

* Informações sobre convocações, competições disputadas e importância na equipe nacional.

### Estilo de jogo

* Descrição das características técnicas, habilidades e papel tático do jogador.

### Títulos e prêmios

* Listagem de conquistas com clubes, seleção e prêmios individuais, usando listas aninhadas `<ul>`.

### Estatísticas

* Tabela com número de jogos, gols e assistências por temporada.

### Vida pessoal

* Informações sobre ações sociais, Instituto Vinícius Júnior e ativismo contra o racismo.

---

## Tecnologias utilizadas

| Tecnologia         | Uso                                                                         |
| ------------------ | --------------------------------------------------------------------------- |
| **HTML5**          | Estrutura e marcação da página                                              |
| *(sem CSS)*        | O design é propositalmente simples, seguindo o padrão da Wikipédia clássica |
| *(sem JavaScript)* | Todo o conteúdo é estático e organizado apenas com HTML                     |

---

## Como visualizar

1. Baixe ou clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/wikipedia-viniciusjr.git
   ```

2. Abra o arquivo `index.html` diretamente no navegador:

   * Clique duas vezes sobre o arquivo **index.html**, ou
   * Use o comando no terminal:

     ```bash
     start index.html
     ```

---

## Estrutura HTML utilizada

Principais elementos empregados:

* `<h1>` a `<h3>` → Hierarquia de títulos
* `<p>` → Parágrafos
* `<a>` → Hiperlinks
* `<table>`, `<tr>`, `<th>`, `<td>` → Tabelas de carreira e estatísticas
* `<ul>` e `<li>` → Listas de títulos e prêmios
* `<b>` e `<i>` → Ênfase em textos
* `<br>` → Quebras de linha pontuais

---

## Possíveis melhorias futuras

* Adicionar CSS leve para dar cor e espaçamento ao conteúdo.
* Implementar uma sidebar com imagem e informações rápidas.
* Tornar o conteúdo responsivo com HTML semântico + CSS.
* Adicionar links reais para as páginas do Flamengo, Real Madrid e Seleção Brasileira.
* Criar versões para outros jogadores (ex: Neymar, Rodrygo, Endrick).

---

## Autor

**Leonardo Oliveira Gomes**
Estudante de Engenharia de Software no Inatel
Projeto desenvolvido para prática de HTML estruturado e organização de conteúdo estático.

---

“Construído apenas com HTML, assim como a internet começou.”
