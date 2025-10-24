# ♻️ ReciclaTech - Conectando Sustentabilidade e Tecnologia

## 🌟 Visão Geral do Projeto

O **ReciclaTech** é uma plataforma que visa promover a sustentabilidade e a economia circular, conectando pessoas que desejam **doar** eletrônicos usados em bom estado com aquelas que precisam **adquirir** esses itens. O projeto foi construído com foco em **semântica, acessibilidade e responsividade**, utilizando as melhores práticas do HTML5 e SCSS.

## ✨ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando uma *stack* de front-end limpa e moderna:

| Categoria | Tecnologia | Uso |
| :--- | :--- | :--- |
| **Linguagem de Marcação** | HTML5 | Semântica, Acessibilidade (ARIA) e Estrutura de Conteúdo. |
| **Estilização** | SCSS (Sass) | Modularização (`_partials`), reuso de código (variáveis) e aninhamento. |
| **Layout** | Flexbox | Estrutura de todos os componentes (Navbar, Hero, Cards, Footer) e responsividade. |
| **Unidades** | REM | Uso consistente para tipografia e espaçamento, garantindo escalabilidade e acessibilidade. |

## 🛠️ Estrutura e Funcionalidades

O design da página principal é dividido nas seguintes seções:

1.  **Header & Navbar:**
      * Logo linkável (`<a>` com `<h1>`).
      * Links de navegação semânticos (`<ul>`/`<li>`).
      * Botão de Ação Principal (`<a class="start-now-button">`) com estilo de botão e semântica de link.
      * Linha divisória (`<hr>`).
2.  **Hero Section:**
      * Layout com Flexbox, alterando de **Row** (Desktop) para **Column** (Mobile).
      * Ações principais (Doar/Adquirir) implementadas como links (`<a>`) por serem ações de navegação.
3.  **Data Section:**
      * Exibição de métricas (Eletrônicos doados, Famílias beneficiadas, Satisfação) em uma faixa de fundo.
      * Uso de Flexbox para espaçamento uniforme.
4.  **How It Works Section:**
      * Divisão em cartões (`Para Doadores` e `Para Adquirentes`).
      * Passos sequenciais implementados com listas ordenadas semânticas (`<ol>`).
5.  **Products Section:**
      * Layout de grade de cartões de produtos (`.category`).
6.  **Footer:**
      * Estrutura de colunas com links, informações e ícones sociais.

## ⚙️ Configuração e Instalação

Para executar e trabalhar neste projeto, siga os passos abaixo:

1.  **Clone o Repositório:**

    ```bash
    git clone https://github.com/MrClaro/recicla-tech.git
    cd reciclatech
    ```

2.  **Instale o Compilador Sass:**
    Este projeto utiliza SCSS. Certifique-se de ter o [Dart Sass](https://sass-lang.com/install/) ou uma ferramenta de compilação (como Live Sass Compiler no VS Code ou Webpack/Gulp) configurada.

3.  **Compile o SCSS:**
    Se estiver usando a CLI do Sass, execute o comando:

    ```bash
    sass --watch style.scss:style.css
    ```

4.  **Para visualizar:**
   
    Abra o arquivo `index.html` diretamente no seu navegador.
    
    ou
    
    Abra via lite-server
     ```bash
    npm install --global lite-server
    lite-server
    ```
      
## 🤝 Contribuição e Contato

Sinta-se à vontade para sugerir melhorias ou reportar problemas.
