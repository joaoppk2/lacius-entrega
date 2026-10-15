# Integração do visual Lacius

Este repositório é a referência visual completa de uma proposta de redesign, não o código do sistema Lacius. Ao receber o link deste repositório com um pedido de importação, leia este arquivo, README.md, index.html, styles.css e app.js antes de implementar.

## Objetivo
Importar o visual e as interações da landing page para o projeto de destino, preservando os recursos reais do produto. Não basta copiar os textos: reproduza composição, cores, espaçamento, tipografia, fotos, logo e comportamento responsivo.

## Fonte de verdade
- index.html: conteúdo, ordem das seções, imagens e estrutura semântica.
- styles.css: tokens de cor, dimensões, grids e breakpoints. Este arquivo prevalece sobre descrições ou imagens de referência.
- app.js: comportamento dos seletores e do menu.
- assets/: logo PNG transparente e quatro fotos locais. Copie estes arquivos; não substitua por ícones, placeholders ou imagens remotas.

## Processo
1. Inspecione a estrutura e a tecnologia do projeto de destino. Não substitua o projeto inteiro nem remova rotas ou recursos existentes.
2. Se for um site estático, use index.html, styles.css, app.js e assets/ diretamente. Não há build nem dependências.
3. Se for React, Next, Vue ou outra tecnologia, converta a estrutura em componentes da tecnologia existente. Adapte os caminhos das imagens e limite o CSS à landing page para não afetar o sistema.
4. Preserve o logo PNG sem recortar, com a proporção original, sobre o cabeçalho verde escuro. Preserve largura fluida, sem limitar toda a página a uma coluna central estreita.
5. Preserve os dois seletores independentes: quatro categorias de módulos (Documentos e equipe inicialmente) e três exemplos (Documento revisado inicialmente). Mostre apenas o grupo ou exemplo selecionado. Não recrie o botão Ver todos nem a antiga navegação duplicada.
6. Preserve menu móvel, fechamento com Escape, foco visível, botões por teclado, estados aria-pressed, avisos de seleção e links diretos aos exemplos. Sem JavaScript, o conteúdo permanece acessível.
7. Não adicione animação de entrada na rolagem nem deslocamentos nos botões. O filtro usa apenas opacidade de 160 ms e respeita prefers-reduced-motion.
8. Ligue acesso, cadastro e demonstração aos fluxos reais já existentes no destino. Nesta referência os CTAs apontam ao site oficial; não crie um cadastro fictício nem um backend novo.
9. Não altere alegações comerciais, prazo da demonstração ou descrições dos módulos sem confirmação da empresa. Os fluxos são ilustrativos, não telas reais do software.
10. Mantenha o aviso discreto de proposta não oficial no rodapé durante avaliação. Sua remoção só cabe numa integração oficial expressamente aprovada pela empresa.

## Validação obrigatória
Execute o projeto de destino e teste em 375, 768, 1024, 1440 e 2560 px. Confira imagens, ausência de rolagem horizontal, quatro categorias, três exemplos, links dos módulos para os exemplos, FAQ, menu e teclado. Verifique console e rede. Compare capturas de tela da referência e da integração nas mesmas dimensões; não declare fidelidade visual baseado apenas em testes ou compilação.

Não são necessários segredos, login, banco de dados ou pacotes para executar esta referência. Não copie credenciais ou configurações do ambiente de origem.
