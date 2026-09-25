# Alessandra MakeUp

Site responsivo desenvolvido para apresentar o portfólio e os serviços da Alessandra MakeUp, com contato direto pelo WhatsApp e acesso ao Instagram.

O website foi criado como trabalho para o Bootcamp Desenvolvimento Web Responsivo da graduação em Ciência da Computação.

**Visualização:** [alessandramakeup.kauanystudio.com.br](https://alessandramakeup.kauanystudio.com.br/)

## Tecnologias

- HTML5 para a estrutura semântica do conteúdo
- CSS3 para identidade visual, layout e responsividade
- JavaScript para menu móvel, navegação, animações, indicador de leitura e configuração dos links de contato

O projeto não utiliza frameworks, bibliotecas externas, backend ou sistema próprio de agendamento.

## Estrutura

- `index.html`: conteúdo e estrutura da página
- `galeria.html`: álbum completo com todas as 31 fotografias, organizado por categoria
- `maquiagem.html`: portfólio de maquiagem para eventos
- `design-sobrancelhas.html`: portfólio de design de sobrancelhas
- `micropigmentacao.html`: portfólio de micropigmentação
- `styles.css`: estilos e adaptação para computador, tablet e celular
- `script.js`: interações e configuração dos contatos
- `vercel.json`: configuração das URLs públicas sem a extensão `.html`
- `assets/`: imagens utilizadas na interface

## URLs públicas

Na Vercel, as páginas são acessadas por `/`, `/galeria`, `/maquiagem`, `/design-sobrancelhas` e `/micropigmentacao`. Os endereços antigos terminados em `.html` redirecionam para essas URLs.

## Contatos configurados

Os endereços oficiais estão definidos no objeto `contactLinks` do arquivo `script.js`:

```js
const contactLinks = {
  whatsapp: "https://wa.me/5514996417616?...",
  instagram: "https://www.instagram.com/alegoncalvesp/",
};
```

## Execução local

Para testar localmente, sirva esta pasta com um servidor estático e abra a página inicial pelo endereço raiz do servidor. Os links entre páginas usam esse endereço como referência.

As galerias utilizam as fotografias fornecidas para o projeto, organizadas por categoria de serviço.
