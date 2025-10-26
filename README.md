# EcoForma - Site Oficial

Este repositório contém o código-fonte do site estático da EcoForma, uma empresa focada em eco-design artesanal a partir de pallets plásticos recuperados.

O site está hospedado via GitHub Pages.

## Estrutura de Arquivos

/
|-- index.html (Página Inicial)
|-- projetos.html (Galeria de todos os projetos)
|-- sobre.html (Nossa história e processo)
|-- contato.html (Formulário de contato)
|-- style.css (Folha de estilos principal)
|
|-- assets/
|   |-- logo.png (Logo vetorial da marca)
|   |-- hero-bg.jpg (Imagem de fundo para a home - *Você deve adicionar uma*)
|   |-- projetos/
|       |-- projeto-exemplo-thumb.jpg (*Adicione thumbnails aqui*)
|
|-- projetos/
|   |-- modelo-projeto.html (TEMPLATE - **Use este para criar novos**)
|   |-- projeto-varanda-eterna.html (Exemplo de projeto)

## Como Adicionar um Novo Projeto/Case

1.  **Copie o Template:** Vá até a pasta `/projetos/` e faça uma cópia do arquivo `modelo-projeto.html`.
2.  **Renomeie o Arquivo:** Renomeie a cópia para algo descritivo, como `projeto-horta-vertical.html`.
3.  **Edite o Conteúdo:** Abra o novo arquivo e edite os campos marcados com `[... ]`:
    * `[TÍTULO DO PROJETO AQUI]`
    * Imagens (principal e galeria)
    * Textos de "Desafio" e "Solução".
4.  **Adicione na Galeria:** Abra o arquivo `projetos.html` (na raiz do site).
5.  **Crie um "Card":** Copie um dos blocos `<div class="projeto-card">...</div>` e cole-o.
6.  **Atualize o Link:** Mude o link `href` e a imagem `src` para apontar para seu novo projeto e seu thumbnail.

## Deploy (GitHub Pages)

1.  Envie (push) todos esses arquivos para a branch `main` (ou `master`) do seu repositório.
2.  No GitHub, vá em **Settings** > **Pages**.
3.  Em "Build and deployment", selecione **Deploy from a branch**.
4.  Selecione a branch `main` e a pasta `/ (root)`.
5.  Clique em **Save**. Seu site estará no ar em alguns minutos.