# Link na Bio - Developer Profile

Um projeto de página estática "Link na Bio" desenvolvido para centralizar links profissionais e portfólios de desenvolvedores. Construído com arquitetura minimalista, focado em alta performance e responsividade.

## Tecnologias Utilizadas

Este projeto foi construído empregando apenas tecnologias web nativas, a fim de garantir o mínimo de requisições de rede e máxima velocidade de carregamento:

*   **HTML5:** Estrutura semântica.
*   **CSS3:** Utilização de variáveis nativas (`:root`), Flexbox para posicionamento de elementos e animações puras (`@keyframes`).
*   **SVG Inline:** Vetores embarcados diretamente no DOM para zerar chamadas HTTP adicionais, eliminando completamente dependências de bibliotecas de ícones de terceiros.

## Arquitetura e Funcionalidades

*   **Zero Dependencies:** Ausência completa de frameworks ou bibliotecas externas (como React, Tailwind CSS ou Bootstrap), resultando em uma aplicação extremamente leve.
*   **Deep Dark Theme:** Interface estilizada em tons escuros absolutos, com detalhes sutis em contraste, voltada especificamente para o nicho de engenharia de software.
*   **Mobile-First Design:** Layout projetado primariamente para dispositivos móveis. Em resoluções maiores, a interface é encapsulada em um contêiner restrito para manter a fidelidade visual de uma aplicação nativa (app-like feel).
*   **Single-file Deployment:** Estrutura unificada em um único arquivo `index.html`. Toda a estilização e ícones estão inseridos no próprio arquivo, facilitando o deploy instantâneo em qualquer servidor estático ou CDN (GitHub Pages, Vercel, AWS S3, etc).

## Como Executar

Por tratar-se de uma página estática pura, não há processos de build, compilação ou execução de scripts.

1. Clone o repositório em sua máquina:
   ```bash
   git clone https://github.com/italo-01/Meu-site.git
   ```
2. Abra o arquivo `index.html` em qualquer navegador web.

## Autor

**Italo Costa**
*   GitHub: [@italo-01](https://github.com/italo-01)
*   LinkedIn: [Italo Costa](https://www.linkedin.com/in/italo-costa/)
