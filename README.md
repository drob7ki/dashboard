# Web Scraping com JavaScript e SQLite3

## 📌 Sobre o Projeto

Este projeto demonstra como utilizar **JavaScript** para realizar **Web Scraping**, coletando informações de páginas da web e armazenando esses dados em um banco de dados **SQLite3** para consultas e análises futuras.

Durante a execução, o sistema acessa um site utilizando requisições HTTP, interpreta o conteúdo HTML e extrai informações relevantes, como:

* Quantidade de links da página;
* Número de imagens;
* Título da página;
* Outras informações que podem ser configuradas no código.

Após a coleta, os dados são armazenados em um banco de dados SQLite3, permitindo que permaneçam disponíveis mesmo após o encerramento da aplicação.

---

## 🚀 Tecnologias Utilizadas

* JavaScript (Node.js)
* Axios
* Cheerio
* SQLite3

---

## ⚙️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Acesse a pasta do projeto

```bash
cd seu-repositorio
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Execute o projeto

```bash
node index.js
```

> Caso o arquivo principal tenha outro nome (como `app.js` ou `scraper.js`), substitua `index.js` pelo nome correspondente.

---

## 📂 Estrutura do Projeto

```
/
├── index.js
├── package.json
├── banco.db
├── README.md
└── node_modules/
```

---

## 💾 Por que utilizar um banco de dados?

Os dados coletados ficam apenas na memória durante a execução do programa. Se eles não forem armazenados:

* são perdidos quando o programa é encerrado;
* não podem ser analisados posteriormente;
* não permitem comparações entre diferentes coletas.

Por isso, o projeto utiliza o **SQLite3**, um banco de dados leve e eficiente que salva as informações de forma estruturada e possibilita consultas utilizando SQL.

---

## 📊 Objetivo

O objetivo deste projeto é demonstrar, na prática, como integrar:

* Web Scraping com JavaScript;
* Manipulação de HTML utilizando Cheerio;
* Requisições HTTP com Axios;
* Persistência de dados utilizando SQLite3.

Essa combinação é muito utilizada em aplicações que precisam coletar, armazenar e analisar informações disponíveis na internet.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos, com o objetivo de demonstrar a integração entre **JavaScript**, **Web Scraping** e **SQLite3**.
