# Frontend Mentor - Solução de componente de resumo de resultados

Esta é uma solução para o [desafio do componente do cartão de visualização do produto no Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas.

## Índice

- [Visão geral](#visão geral)
   - [O desafio](#o-desafio)
   - [Captura de tela](#captura-de-tela)
   - [Links](#links)
- [Meu processo](#meu-processo)
   - [Construído com](#construído-com)
   - [O que aprendi](#o-que-aprendi)
   - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
   - [Recursos úteis](#useful-resources)
- [Autor](#autor)

## Visão geral

### O desafio

Os usuários devem ser capazes de:

- Veja o layout ideal para a interface, dependendo do tamanho da tela do dispositivo
- Veja os estados de foco e foco para todos os elementos interativos na página

### Captura de tela

![](./screenshots/desktop.png)
![](./screenshots/mobile.png)

### Links

- URL da solução: (https://github.com/felipe1590/product-preview)
- URL do site ao vivo: (https://felipe1590.github.io/product-preview/)

## Meu processo

### Construído com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- Flexbox
- Fluxo de trabalho mobile first

### O que eu aprendi

```html
<section class="foto-produto"></section>
<section class="descricao">
  <p class="descricao-previa">PERFUME</p>
  <h1 class="descricao-titulo">Gabrielle Essence Eau De Parfum</h1>
  <p class="descricao-produto">A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfumer-Creator for the House of CHANEL.</p>
  <p class="preco-atual">$149.99</p>
  <p class="preco-real">$169.99</p>
  <button class="butao">
    <img class="icone-carro" src="images/icon-cart.svg" alt=""> 
    Add to Cart
  </button>
</section>
```
Com um design diferente, dessa vez resolvi fazer de forma mais dinâmica para poder ser visualizado mais facilmente quando o projeto fosse visualizado pelo desktop. 

```css
 .container {
        width: 600px;
        height: 400px;
        display: flex;
        align-items: center;
    }

    .foto-produto {
        width: 300px;
        height: 400px;
        background: url('/images/image-product-desktop.jpg') no-repeat;
        background-size: contain;
        border-radius: 10px 0 0 10px;
    }

    .descricao {
        width: 220px;
        margin: 0;
    }
```
Dessa forma como com poucas configurações de mudança, pude retrabalhar o posicionamento dos elementos quando fosse nescessario a realocação.

### Desenvolvimento contínuo

Estou focando em aprender sobre layouts responsivos e como posso integrar isso ao JavaScript, desenvolvendo meus conhecimentos de maneira estruturada e focada no estudo aplicado do Front-end, depois de terminar todos os módulos do curso de Html e Css do Curso em Vídeo(https://www.cursoemvideo.com/) e partir para o básico de JavaScript. Estou enpenhado em produzir sites bonitos, mas semanticamente bem feitos, utilizando técnicas atualizadas de css, empregradas aos scripts simples.

### Recursos úteis

- [LANDING PAGE COM HTML e CSS!](https://www.youtube.com/watch?v=llF6vD-RljE&ab_channel=RafaellaBallerini) - Isso me ajudou simplesmente a entender como funciona o Flexbox e como o posicionamente pode ser usado em determinados momentos, integrando as técnicas mais tradionais de como montar uma página de manera responsiva. Eu realmente gostei desse padrão e vou usá-lo daqui para frente.
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a finalmente entender mais a fundo como Flexbox ao mesmo tempo pode parecer complexo no começo, mas o treino e tempo mostram que essa inovação só tem a agregar na criação de sites de maneira mais descomplicada. Recomendo a todos que ainda estão aprendendo esse conceito.

## Autor

- Website - [Felipe Gama](https://felipe1590.github.io/portfolio/)
- Frontend Mentor - [@felipe1590](https://www.frontendmentor.io/profile/felipe1590)
- Linkedin - [Felipe Gama](https://www.linkedin.com/in/felipe-gama-3a5638265/)
