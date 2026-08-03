# Convert

Conversor de moedas para Real Brasileiro, desenvolvido como projeto de estudo durante a formação Full Stack da Rocketseat. A aplicação apresenta uma interface simples de formulário, com seleção de moeda estrangeira, entrada de valor e exibição do resultado convertido em reais.

![Preview do projeto](./img/screenshot.png)

## Sobre o projeto

O Convert permite converter valores de Dólar Americano, Euro e Libra Esterlina para Real Brasileiro usando cotações definidas no JavaScript. O projeto foi criado para praticar a construção de interfaces com HTML, CSS e JavaScript, trabalhando a estrutura de formulário, manipulação do DOM, tratamento de eventos e formatação de valores monetários.

Na parte visual, o projeto utiliza uma composição centralizada, campos personalizados, estados de foco e hover, variáveis CSS no `:root`, imagens de fundo e ícones SVG. Também foram trabalhados conceitos de HTML semântico, organização visual, Flexbox e estilização moderna com CSS.

## Funcionalidades

- Campo para informar o valor a ser convertido
- Bloqueio de caracteres não numéricos no campo de valor
- Seleção de moeda entre Dólar Americano, Euro e Libra Esterlina
- Conversão do valor informado para Real Brasileiro
- Exibição da cotação da moeda selecionada
- Exibição do resultado formatado no padrão monetário brasileiro
- Área de resultado exibida somente após a conversão

## Tecnologias

- HTML5
- CSS3
- JavaScript
- Flexbox
- Variáveis CSS
- Google Fonts
- SVG Icons

## Estrutura de arquivos

```bash
.
├── index.html          # Estrutura da página e formulário de conversão
├── styles.css          # Estilos globais, layout, formulário e área de resultado
├── scripts.js          # Regras de conversão, eventos e formatação monetária
└── img/
    ├── bg.png
    ├── check.svg
    ├── chevron-down.svg
    ├── logo.svg
    └── screenshot.png
```

## Como executar

Este projeto não possui dependências externas para instalação. Basta clonar o repositório e abrir o arquivo `index.html` no navegador.

```bash
git clone https://github.com/isabellesouzasv/currency-convert.git
cd currency-convert
```

Depois, abra:

```bash
index.html
```

## Licença

Projeto de estudo, livre para uso e modificação.
