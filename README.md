# Programação - Magick IA

Este projeto é uma página web estática que simula uma loja de cartas colecionáveis ou produtos relacionados a um universo de "Magick IA". Ele apresenta uma lista de cartas com filtros interativos por categoria e preço máximo.

## Funcionalidades

*   **Listagem de Produtos:** Exibe uma coleção de cartas, cada uma com imagem, nome, categoria, preço e um botão de compra (link para WhatsApp).
*   **Filtros Interativos:**
    *   Filtra cartas por `Categoria` (Comum, Rara, Épica).
    *   Filtra cartas por `Preço Máximo`.
    *   Aplica os filtros ao clicar no botão "Aplicar filtros".
*   **Design Responsivo:** A interface se adapta a diferentes tamanhos de tela, garantindo uma boa experiência de usuário em desktops, tablets e smartphones.

## Tecnologias Utilizadas

*   **HTML5:** Estrutura semântica da página.
*   **CSS3:** Estilização e responsividade da interface.
    *   `reset.css`: Para normalização de estilos entre navegadores.
    *   `estilos.css`: Estilos principais da aplicação.
    *   `responsivo.css`: Media queries para adaptação a diferentes dispositivos.
*   **JavaScript:** Lógica para a funcionalidade de filtragem de cartas.
*   **Google Fonts:** Utilização da fonte `Roboto` para tipografia.

## Como Executar o Projeto

Para visualizar este projeto localmente, siga os passos abaixo:

1.  **Clone o repositório** (se estiver em um, ou apenas baixe os arquivos):
    ```bash
    git clone <URL_DO_REPOSITORIO>
    # ou baixe o ZIP e descompacte
    ```
2.  **Abra o arquivo `index.html`** em seu navegador web preferido.

Nenhuma instalação de dependências ou servidor web é necessária, pois trata-se de um projeto front-end estático.

## Estrutura de Pastas

```
.
├── index.html
└── src/
    ├── css/
    │   ├── estilos.css
    │   ├── reset.css
    │   └── responsivo.css
    ├── imagens/
    │   ├── carta-arkanon.png
    │   ├── ... (outras imagens de cartas e logo)
    │   └── seta-para-baixo.png
    └── js/
        └── index.js
```
