### 🌐 Site HTML5 sobre Desigualdade Social no DF 📊

Este repositório contém o código-fonte de um website desenvolvido como parte da disciplina de Padrões Web, ministrada pelo Professor Leonardo Antonialli, no 1º Semestre do curso de Análise e Desenvolvimento de Sistemas na Faculdade de Inovação e Tecnologia SENAC-DF, em 2S/2024. O projeto foi realizado em colaboração com os colegas **João Paulo Nunes da Silva** e **João Paulo Freitas da Silva**.

**O website aborda a temática da desigualdade social no Distrito Federal, explorando:**

*   **Dados e Estatísticas:** Apresentação de informações sobre a população, IDH e renda per capita do DF.
*   **História de Brasília:** Uma retrospectiva da construção da capital, contrastando o planejamento original com a realidade atual de desigualdade.
*   **Causas e Impactos:** Análise das origens e consequências da desigualdade social no DF, com vídeos explicativos.
*   **Casos de Sucesso:** Destaque para iniciativas como o Cartão Prato Cheio e o Bolsa Família, que buscam mitigar a desigualdade.

**Estrutura do Código (HTML):**

O arquivo `index.html` organiza o conteúdo em seções bem definidas:

*   **Cabeçalho (Header):** Logotipo, menu de navegação responsivo (com ícone para dispositivos móveis) e links para as principais seções.
*   **Seção Inicial:**
    *   Imagem de fundo (background).
    *   Título e subtítulo impactantes sobre a desigualdade no DF.
    *   Chamada para ação ("Veja mais abaixo").
*   **Seções de Conteúdo (Sections):**
    *   `#inicial`: Dados gerais sobre o DF (população, IDH, renda).
    *   `#historia`: História de Brasília, com imagens e textos explicativos, divididos em blocos para facilitar a leitura. Destaque para o uso de layouts flexíveis (float) e responsivos.
    *   `#causaseimpactos`:  Análise das causas e impactos, com vídeos incorporados (elemento `<video>`).
    *   `#casosdesucesso`: Apresentação de programas sociais, utilizando botões interativos ("toggle buttons") para exibir/ocultar informações detalhadas.  Cada seção tem um banner estilizado.
*   **Rodapé (Footer):** Informações sobre os autores e o professor responsável.

**Tecnologias e Recursos Utilizados:**

*   **HTML5:** Estruturação semântica do conteúdo.
*   **CSS:** Estilização visual (arquivo `style.css` externo).
*   **JavaScript:**
    *   Menu responsivo (função `myFunction()`).
    *   Navegação suave e destaque do link ativo no menu (função `setActiveLink()`).
    *   Funcionalidade dos botões "toggle" (expansão/contração de conteúdo).
*   **Font Awesome:** Ícones (ex: barras do menu).
*   **Imagens e Vídeos:** Elementos visuais para enriquecer o conteúdo.
*   **Responsividade:** Layout adaptável a diferentes tamanhos de tela (uso de `viewport`, classes CSS como `organizer`, `organizer-width`, etc.).
*    **Acessibilidade**: Foi utilizada a tag semântica correta para cada elemento, como section, div, h1, p, entre outros.

**Interatividade:** O JavaScript adiciona interatividade, como o menu responsivo e os botões que expandem/contraem o conteúdo.  O código JavaScript está incorporado diretamente no HTML (dentro da tag `<script>`), o que é aceitável para projetos menores, mas em projetos maiores, é recomendado separar o JavaScript em arquivos externos.

**Observações:**

*   O código faz uso extensivo de classes CSS para estilização, o que facilita a manutenção e a reutilização de estilos.
*   Há comentários no código JavaScript explicando a funcionalidade de algumas partes.
*   O layout utiliza técnicas de `float` e `flexbox` (implicitamente, através de classes como `float-container`, `float-child`, `organizer`, etc.) para posicionamento dos elementos.
* Foi usada uma imagem de fundo.

Este projeto demonstra a aplicação prática dos conceitos de Padrões Web, como HTML semântico, CSS, responsividade, acessibilidade, e interatividade com JavaScript. Ele aborda um tema relevante e atual, utilizando uma variedade de recursos para apresentar o conteúdo de forma clara e envolvente. O trabalho em equipe com **João Paulo Nunes da Silva** e **João Paulo Freitas da Silva** foi fundamental para o desenvolvimento e aprimoramento do website.