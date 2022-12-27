# Dashoard Template

Este projeto é um template de um dashboard com diversas funcionalidades, as quais devem ser usadas como referencias em meu projeto futuros. Esta documentação tem o objetivo de explicar alguns passos e detalhes da construção deste projeto, para que posso ser facilmente usadocomo referencia futuramente.

## Package.json

Foi copiado o package.json do repositorio https://github.com/adrianhajdin/project_syncfusion_dashboard, em seguida foi utilizado o comando:
```bash
npm i --legacy-peer-deps
```

### Dependencias

- React Icons: https://react-icons.github.io/react-icons
- ej2-react-popups: https://www.npmjs.com/package/@syncfusion/ej2-react-popups

## Padrão de estilização

### CSS

O projeto possui os estilos padrões de css que normalizam alguns paramentros inicialmente, estão nos arquivos **src/index.css** e **src/App.css**.

### Tailwind

Para o tailwind a instação foi feita na adição dos arquivos **tailwind.config.js** e **craco.config.js**.

## Arquitetura

A arquitetura do projeto consiste em:

```bash
- src
   |- components
   |- contexts
   |- data
   |- pages
```

### Data

A pasta **data** foi importada com as imagens de pessoas e de produtos, alem de um arquivo **dummy.js**, que possui alguns trechos de jsx e arrays de informações default.