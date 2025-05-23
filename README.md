# Projeto-BD-SQLite

Este projeto é uma atividade prática de modelagem e manipulação de banco de dados utilizando **SQLite com Python** no **Google Colab**.

---

## 📚 Objetivo

- Criar um banco de dados simples com **tabelas relacionadas**
- Inserir e consultar dados com **comandos SQL**
- Utilizar **chaves primárias e estrangeiras**
- Executar consultas com **JOIN**, `SELECT`, `ORDER BY`, etc.
- Versionar o projeto no **GitHub**

---

## 🧱 Estrutura do Banco de Dados

O modelo conceitual inclui as seguintes entidades:

- **Pessoas**: id, nome, idade  
- **Produtos**: id, descrição, estoque, preço  
- **Vendas**: id da venda, id da pessoa, id do produto, quantidade

Relacionamentos:
- Uma pessoa pode realizar várias vendas
- Um produto pode estar presente em várias vendas

Imagem do modelo ER:

![Modelo ER](https://github.com/Edgarmartins16/projeto-bd-colab/blob/89b30c1f44680d41d4e99d5370c437375d94abb5/Modelo%20ER.png)

---

## 🧪 Como rodar o notebook

1. Acesse o [Google Colab](https://colab.research.google.com/)
2. Clique em **“Upload”** e selecione o arquivo `Projeto-BD-SQLite.ipynb`
3. Execute as células usando o botão ▶️ ou `Shift + Enter`

---

## 🔗 Arquivos do projeto

- `Projeto-BD-SQLite.ipynb` – código completo com a criação do banco
- `docs/modelo-er.png` – imagem do diagrama conceitual
- `README.md` – este arquivo

---

## 🛠️ Tecnologias

- Python
- SQLite3
- Google Colab
- GitHub

---

## 👨‍💻 Autor

[Edgar Alves Martins]  
Curso: [Ciência da Computação]  
Professor: [Denise Moraes do Nascimento Vieira]

---

## ✅ Status

✔️ Finalizado para entrega e estudo
