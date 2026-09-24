# Alessandra MakeUp

Site responsivo desenvolvido para apresentar o portfólio e os serviços da Alessandra MakeUp, com contato direto pelo WhatsApp e acesso ao Instagram.

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
- `assets/`: imagens utilizadas na interface

## Contatos configurados

Os endereços oficiais estão definidos no objeto `contactLinks` do arquivo `script.js`:

```js
const contactLinks = {
  whatsapp: "https://wa.me/5514998417616?...",
  instagram: "https://www.instagram.com/alegoncalvesp/",
};
```

## Execução local

O site pode ser aberto diretamente pelo arquivo `index.html`. Para testar em um servidor local, utilize qualquer servidor estático de sua preferência.

As galerias utilizam as fotografias fornecidas para o projeto, organizadas por categoria de serviço.
