# 🛒 Projeto Techno – E-commerce Simples com Vue.js

Este projeto é um e-commerce front-end de demonstração desenvolvido para aplicar e consolidar os conhecimentos em **Vue.js**, JavaScript vanilla e manipulação de estado.

A aplicação simula um fluxo de compra completo, com foco no gerenciamento dinâmico de dados e na experiência do usuário (UX).

---

## ✨ Destaques e Funcionalidades

O projeto possui um catálogo simples de 5 produtos e implementa a lógica essencial de um e-commerce:

* **Carrinho de Compras Dinâmico:** Adição, remoção e cálculo automático do valor total dos produtos no carrinho.
* **Persistência de Dados (localStorage):** O carrinho mantém os itens salvos mesmo após o usuário recarregar a página, utilizando manipulação de dados com `JSON.parse` e `JSON.stringify`.
* **Simulação de SPA com Roteamento:** Utilização do método `pushState` para alterar as rotas do endereço do site (`/produto/ID`, `/carrinho`), proporcionando uma experiência de Aplicação de Página Única (SPA) sem a necessidade de um roteador formal (como Vue Router).
* **Estrutura de Objetos:** Utilização de métodos de estruturação e manipulação de objetos para gerenciar o estado dos produtos e do carrinho.

---

## 🛠 Tecnologias Utilizadas

| Tecnologia | Categoria |
| :--- | :--- |
| **Vue.js** (v2) | Framework JavaScript para reatividade e desenvolvimento do Frontend. |
| **JavaScript** | Lógica de negócios, manipulação do DOM e comunicação com a API (pasta `/api`). |
| **HTML5** | Estrutura semântica da aplicação. |
| **CSS3** | Estilização e layout da interface. |

---

## 📸 Prévia do Projeto

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1100b556-016b-4c63-84cd-ac33d988edf6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c33155b4-8c77-471a-a722-dfed74e22a90" />


## 💡 Desafio Superado

Este projeto representou meu **"batismo de fogo"** com o Vue.js! Sendo a primeira vez em um projeto real com o framework, o maior desafio foi integrar todos os conceitos—reatividade, persistência (`localStorage`) e manipulação de rotas (`pushState`)—de forma coesa. A conclusão deste projeto solidificou minha confiança no desenvolvimento Front-End moderno.

---

## 🌐 Acesse o Projeto (Live Demo)

O projeto está disponível e rodando online para visualização:

🔗 **[Acessar Projeto E-commerce](https://taalesporjandev.github.io/projeto-techno/)**

---

## 📦 Como Rodar Localmente

Siga os passos abaixo para testar o projeto na sua máquina:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/TaalesPorjanDev/projeto-techno.git](https://github.com/TaalesPorjanDev/projeto-techno.git)
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd projeto-techno
    ```

3.  **Execute:**
    Como o projeto é puramente Front-End (HTML, CSS e JS/Vue), basta abrir o arquivo `index.html` no seu navegador favorito.

---

## 👨‍💻 Contribuições

Sinta-se à vontade para dar *feedback* e abrir *issues* se encontrar algum problema. Sugestões de melhoria são sempre bem-vindas!
