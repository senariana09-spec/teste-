# Novapasta — melhorias de CSS e JavaScript

## Resumo

A Novapasta recebeu uma atualização visual e funcional para deixar todas as páginas mais consistentes, responsivas e fáceis de usar. Os estilos foram centralizados em `styles.css`, enquanto os comportamentos compartilhados foram organizados em `script.js`.

## Melhorias de CSS

- Paleta visual unificada com variáveis de cor, sombras e bordas arredondadas.
- Estados de `hover`, `focus-visible`, clique e seleção para botões e campos.
- Cabeçalho e navegação mais consistentes em todas as páginas.
- Layout responsivo para celulares e telas menores.
- Cartões, painéis, imagens e formulários com acabamento visual consistente.
- Animações de entrada suaves, respeitando `prefers-reduced-motion`.
- Melhor contraste e foco visível para navegação por teclado.

## Melhorias de JavaScript

- Navegação dos botões do cabeçalho centralizada e com aba ativa automática.
- Campo de pesquisa com filtragem instantânea dos cartões e mensagens de resultado.
- Seleção visual das turmas com confirmação ao usuário.
- Feedback em forma de toast para ações importantes.
- Atualização do nome exibido após escolher um arquivo.
- Tratamento seguro dos formulários com mensagem de confirmação.
- Botões de envio e redes sociais conectados sem handlers inline duplicados.
- Animação de revelação aplicada aos principais blocos da interface.

## Correções técnicas

- Todas as 9 páginas HTML agora carregam `../styles.css` e `../script.js`.
- Referências de imagens foram ajustadas para a pasta `img`.
- Assets legados sem arquivo correspondente receberam fallbacks existentes no projeto.
- As páginas foram verificadas com servidor HTTP local e retornaram status `200`.
- O JavaScript passou na validação de sintaxe com `node --check`.
