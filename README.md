# Melhorias com Flexbox aplicadas às páginas

## Estruturação geral com Flexbox
### Body
- Adicionada a propriedade `display: flex` com `flex-direction: column` para estruturar a página verticalmente.
- Garante que o rodapé permaneça na base da página, mesmo que o conteúdo principal não ocupe toda a altura da tela.

### Main
- Utilizado `display: flex` para organizar as seções verticalmente e alinhar centralmente o conteúdo.
- Adicionado espaçamento entre os elementos com a propriedade `gap`.

### Image Container
- Aplicado `display: flex`, com `flex-direction: column` e alinhamento central, para organizar as imagens e suas legendas de forma harmônica e visualmente agradável.

---

## Centralização e alinhamento
### Main
- Centralizados os elementos de texto e imagens dentro do contêiner principal para uma experiência visual mais organizada e profissional.

### Link
- Adicionado `align-self: flex-end` no link para posicioná-lo à direita, melhorando a estética do layout.

---

## Melhoria de responsividade
- O uso de Flexbox permite que os elementos se adaptem automaticamente a diferentes tamanhos de tela.
- Adicionado **media queries** para ajustar o tamanho da fonte e o espaçamento em telas menores, mantendo a consistência do design.

---

## Benefícios
### Flexbox no body
- Organização eficiente dos elementos principais (header, main, footer).
- Espaçamento adequado e rodapé fixo em telas grandes.

### Flexbox no main
- Estrutura vertical bem definida, com alinhamento centralizado e espaçamento consistente entre as seções.

### Centralização com Flexbox no .image-container
- Imagens e legendas são alinhadas ao centro, proporcionando um layout mais agradável.

### Responsividade aprimorada
- Layout ajustado para dispositivos menores, garantindo usabilidade e acessibilidade.

---

Essas melhorias otimizam o design das páginas, tornando-as mais modernas, responsivas e organizadas.
