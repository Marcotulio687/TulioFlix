Aqui está um **README.md** profissional, organizado e explicando o funcionamento do seu projeto **TulioFlix**, com foco no HTML, CSS e JavaScript utilizados.

---

# 📺 TulioFlix — Catálogo de Filmes com OMDb API

TulioFlix é um projeto inspirado no design da Netflix, desenvolvido em **HTML**, **CSS** e **JavaScript**, que consome a **OMDb API** para listar filmes, exibir catálogos por gênero, permitir buscas e abrir detalhes em um **modal interativo**.

Este projeto foi desenvolvido com o objetivo de praticar consumo de APIs, manipulação de DOM e criação de interfaces modernas.

---

## 🚀 Funcionalidades Principais

### ✔️ Tela inicial com carrossel (Hero)

* Exibe automaticamente filmes de ação em um carrossel que troca a cada 6 segundos.
* Título e sinopse são atualizados dinamicamente.

### ✔️ Catálogo completo por gêneros

* Filmes divididos em: **Ação, Comédia, Drama, Ficção Científica e Terror**.
* Cada gênero possui um carrossel horizontal.
* Botões de seta permitem navegar pelos filmes.

### ✔️ Navegação do catálogo com setas

* O carrossel permite navegar para ambos os lados.
* O deslocamento é feito por scroll horizontal.

### ✔️ Busca dinâmica

* Ao digitar e pressionar **Enter**, os resultados aparecem em uma seção separada.
* Apagar o campo de busca retorna ao catálogo original.

### ✔️ Modal de informações do filme

* Ao clicar em um card, abre-se um modal com:

  * Pôster em alta resolução
  * Título
  * Sinopse
  * Ano, duração e nota IMDb
  * Botões estilizados de ação

### ✔️ Layout responsivo

* Ajustes de tamanho e reorganização para telas menores.
* Modal adaptável para mobile.

### ✔️ Footer personalizado

Inclui créditos do desenvolvedor.

---

## 🧩 Estrutura do Código

### 📁 **HTML**

O HTML estrutura:

* O **header** com o título TulioFlix e campo de busca.
* A sessão **Hero**, onde o carrossel principal é exibido.
* As linhas de filmes (**genre-row**) geradas dinamicamente pelo JavaScript.
* A área de resultados da busca.
* O **modal** que aparece ao clicar em um filme.
* O **footer** com créditos.

Também utiliza Google Fonts para uma aparência moderna.

---

## 🎨 CSS — Estilização Moderna

O estilo segue um tema escuro inspirado na Netflix.

### Destaques:

* **Fundo escuro** com contrastes em vermelho.
* Cards com efeito **hover + glow vermelho**.
* Carrosséis horizontais estilizados.
* Hero com **blur**, saturação e brilho reduzido para efeito cinematográfico.
* Layout totalmente responsivo.

---

## 🧠 JavaScript — Lógica e Integração com a API

A lógica do projeto está concentrada no script principal dentro da página.

### Principais funções:

#### 🔹 `fetchMovie(id)`

Faz requisições à **OMDb API**, retornando dados completos do filme.

#### 🔹 `loadCatalog()`

Carrega dinamicamente todo o catálogo:

* Cria cada gênero
* Preenche com cards individuais
* Atribui eventos de clique para abrir o modal

#### 🔹 `scrollLeft()` e `scrollRight()`

Controlam a navegação do carrossel via scroll horizontal.

#### 🔹 `openModal(data)` / `closeModal()`

Abrem e fecham o modal com informações detalhadas.

#### 🔹 Busca dinâmica

* Tecla **Enter** mostra apenas os resultados.
* Apagar o texto retorna ao catálogo.
* Clicar no **logo** também reseta a interface.

#### 🔹 `loadHero()`

Controla o carrossel principal:

* Alterna imagens
* Atualiza título e descrição
* Usa setInterval para trocar automaticamente

---

## 🔑 OMDb API Key

O projeto usa a API:

```
https://www.omdbapi.com/
```

Com a chave:

```
5ecaaf94
```

*(Recomendado futuramente ocultar a chave em um backend.)*

---

## 🛠 Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **JavaScript ES6**
* **OMDb API**
* Google Fonts

---

## 📌 Possíveis Melhorias Futuras

* Sistema de favoritos com LocalStorage.
* Melhor implementação do carrossel infinito.
* Página de detalhes individual para cada filme.
* Login fictício com animações.
* Skeleton loading para evitar telas vazias.

---

## 👨‍💻 Autor

**Marco Túlio Ferreira Soares**
© 2025 — TulioFlix

---

Se quiser, posso gerar também:

* **README em inglês**
* **Versão estilizada em Markdown com imagens**
* **README com badges do GitHub**
* **README com instruções de instalação**
