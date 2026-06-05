## Terceiro Envio: Estilização e Responsividade (CSS)

Principais alterações e implementações visuais realizadas no projeto:

* **Estilização com Vanilla CSS:** Criação do ficheiro `style.css` e ligação a todas as páginas HTML, utilizando CSS puro e semântico sem dependência de frameworks externos.
* **Identidade Visual e Tipografia:** Implementação de variáveis CSS (`:root`) para a paleta de cores oficial do SENAI e importação da fonte *Roboto* através do Google Fonts.
* **Layout Moderno (Flexbox e Grid):** Utilização de Flexbox para estruturar o cabeçalho e menu de navegação, e implementação de CSS Grid automatizado para exibir os "Cards" de cursos e áreas de destaque.
* **Padronização de Imagens:** Aplicação da propriedade `object-fit: cover` para garantir que todas as imagens dos cards mantenham um tamanho uniforme e profissional, sem distorcer.
* **Aprimoramento de Tabelas e Formulários:** Aplicação de efeito "zebrado" (`nth-child`) na tabela de cursos para melhorar a leitura. O formulário de contacto recebeu estilização completa com feedback visual de validação nativa (`:user-invalid`), efeitos de foco (`:focus`) e botões interativos (`:hover`).
* **Design Responsivo (Mobile-First):** Criação de *Media Queries* (Breakpoints em 1023px e 767px) para garantir o funcionamento perfeito em smartphones e tablets. O menu adapta-se para o formato de bloco, as colunas empilham-se automaticamente e a tabela ganha *scroll* horizontal em ecrãs pequenos.
