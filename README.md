# Renovando Laços - Site de Conselhos para Reconciliação de Relacionamentos

Este é um site de e-commerce para venda de um e-book sobre conselhos para reconciliação de relacionamentos, com sistema de pagamento integrado.

## Estrutura do Projeto

- **index.html**: Página inicial do site
- **index-otimizado.html**: Versão otimizada da página inicial com elementos de conversão
- **produtos.html**: Página de produtos/serviços
- **sobre.html**: Página sobre a empresa
- **contato.html**: Página de contato
- **carrinho.html**: Página do carrinho de compras
- **checkout.html**: Página de finalização de compra
- **css/**: Pasta com arquivos de estilo
  - **style.css**: Estilos principais do site
  - **checkout.css**: Estilos para página de checkout
  - **conversion.css**: Estilos para elementos de conversão
  - **mercadopago.css**: Estilos para integração com Mercado Pago
- **js/**: Pasta com arquivos JavaScript
  - **script.js**: Scripts principais do site
  - **checkout.js**: Scripts para página de checkout
  - **conversion.js**: Scripts para elementos de conversão
  - **mercadopago-integration.js**: Scripts para integração com Mercado Pago
- **images/**: Pasta com imagens do site
- **pdf-content/**: Pasta com conteúdo do e-book em formato markdown
  - **00-introducao-sumario.md**: Introdução e sumário do e-book
  - **01-comunicacao-eficaz.md**: Capítulo 1 - Comunicação eficaz
  - **02-poder-do-perdao.md**: Capítulo 2 - O poder do perdão
  - **03-reconstruindo-confianca.md**: Capítulo 3 - Reconstruindo a confiança
  - **04-exercicios-praticos.md**: Capítulo 4 - Exercícios práticos
  - **05-superando-infidelidade.md**: Capítulo 5 - Superando a infidelidade
  - **06-limites-saudaveis.md**: Capítulo 6 - Limites saudáveis
  - **07-redescobrindo-intimidade.md**: Capítulo 7 - Redescobrindo a intimidade
  - **08-plano-30-dias.md**: Capítulo 8 - Plano de 30 dias

## Funcionalidades

- Design responsivo para desktop e dispositivos móveis
- Sistema de e-commerce com carrinho de compras
- Opções de pagamento: PIX (com 15% de desconto), cartão de crédito/débito e boleto bancário
- Elementos de conversão: depoimentos, FAQ, contador regressivo, etc.
- Integração com Mercado Pago para processamento de pagamentos

## Instruções de Deploy no Netlify

1. Crie uma conta no [Netlify](https://www.netlify.com/) se ainda não tiver
2. Faça login na sua conta Netlify
3. Clique em "New site from Git" ou arraste e solte a pasta do projeto na área de upload
4. Aguarde o processo de deploy
5. Seu site estará disponível em um subdomínio do Netlify (exemplo: renovando-lacos.netlify.app)

## Integrando com o Mercado Pago

Para que o sistema de pagamento funcione completamente, você precisará:

1. Criar uma conta no [Mercado Pago](https://www.mercadopago.com.br/)
2. Obter suas credenciais de acesso (Public Key e Access Token)
3. Substituir a chave pública de teste no arquivo `js/mercadopago-integration.js` pela sua chave real
4. Para processamento completo dos pagamentos, será necessário implementar um backend para comunicação segura com a API do Mercado Pago

## Customização

- Para substituir as imagens de placeholder, adicione suas próprias imagens na pasta `images/`
- Para personalizar cores e estilos, edite o arquivo `css/style.css`
- Para modificar textos e conteúdos, edite os arquivos HTML correspondentes

## Conversão do E-book para PDF

Os arquivos markdown na pasta `pdf-content/` contêm o conteúdo completo do e-book. Para convertê-los em um PDF formatado, você pode:

1. Usar ferramentas online como [Markdown to PDF](https://www.markdowntopdf.com/)
2. Usar aplicativos como Pandoc (comando: `pandoc *.md -o ebook.pdf`)
3. Importar os arquivos markdown para o Google Docs e exportar como PDF
4. Contratar um designer para formatar o PDF com design profissional

## Suporte

Para qualquer dúvida ou suporte adicional, entre em contato através do e-mail: contato@renovandolacos.com.br
