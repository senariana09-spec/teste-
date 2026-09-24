# Melhorias da Novapasta

## O que foi atualizado

A interface recebeu uma camada visual compartilhada em `styles.css`, com paleta consistente, cartões, estados de foco, hover e clique, responsividade para telas menores, acessibilidade básica e redução de movimento quando solicitada pelo sistema.

O arquivo `script.js` centraliza a navegação entre páginas, mantém a aba ativa, adiciona pesquisa instantânea, feedback visual para botões, seleção de turmas, mensagens de confirmação, tratamento de arquivo escolhido e comportamento seguro para formulários.

Também foram corrigidos os caminhos dos principais assets existentes e removidos handlers inline duplicados para evitar conflitos entre páginas.

## Arquivos principais

- `styles.css`: sistema visual compartilhado.
- `script.js`: interações compartilhadas.
- `pages/*.html`: páginas conectadas aos recursos compartilhados.
