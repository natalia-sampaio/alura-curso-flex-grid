# Guia de estilos | Style guide

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma | Link to the figma project](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte | Font

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores | Colors

corpo|body: `#1D232A`

cabeçalho|header: `#1D232A`

cabeçalho mobile|mobile header: `#15191C`

menu lateral|side bar: `#15191C`

cartão|card: `#2C343A`

fonte|font: `#FFFFFF`

fonte alternativa|alt font: `#95999C`

links: `#0480DC`

botão|button: `#0480DC`

sombras|shadow: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones | Icons

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas|Shirts = `\e900`

Carrinho|Shopping cart = `\e901`

Inicio|Start = `\e902`

Integrantes|Members = `\e903`

Menu = `\e904`

Moeda|Currency = `\e905`

Notificação|Notification = `\e906`

Pico|Location = `\e908`

Picos|Location = `\e909`

Pinturas|Paintings = `\e90a`

Play = `\e90b`

Relogio|Clock = `\e90c`

Seta-baixo|Down arrow = `\e90d`

Videos = `\e90e`

Visualizacao|View = `\e90f`

## Espaçamentos | Spacing

Espaço interno botão|Internal button spacing: `8px`

Espaço entre elementos do botão|Spacing between button elements: `8px`

Espaço entre elementos|Spacing between elements: `16px/8px`

Espaçamento interno do corpo|Internal body spacing: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos | Sizes

Tamanho do dispositivo mobile|Mobile device size: `360px`

Tamanho do dispositivo desktop|Desktop size: `1440px`

Largura máxima do conteúdo principal|Max. width of main content: `1120px`

Largura máxima de um cartão desktop|Max. width of a card: `256px`

Altura mínima de um cartão|Min. width of a card: `320px`