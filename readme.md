## Questões Teóricas

#### 1. Qual a função do "head" no HTML?
R: Cabeçalho do site. Informações e confirgurações gerais para o browser. Por ex: Título do site (na aba do navegador), linguagem, descrições e etc.

#### 2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
R: Não. Para isso, precisamos adaptar o nosso site, pois ele terá um tamanho "padrão" definido e assim teremos que adaptá-lo.

#### 3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem? 
R: Não. Os navegadores fazem essa renderização e transformam os códigos HTML e CSS em imagem para quem está acessando o site.

#### 4. Qual a função das tags H (h1, h2, h3, etc) no HTML? 
R: Marcam diferentes níveis de títulos na página. Também importante para mostrar informações mais importantes para motores de busca e acessibilidade.

#### 5. O que é SEO e como funciona? 
R: Otimização de sites para motores de busca, utilizando ele, melhora a posição do site nos mecanismos de busca. Os motores de buscas armezam os dados relevantes (palvras-chaves) do site, para qualificar a relevância de cada um. Quanto mais específico e melhor otimizado o site estiver, melhor rankeado ficará quando o público-alvo procurar pelo assunto. 

#### 6. O uso de media query é obrigatório em todas as páginas?
R: Não necessariamente. Caso a aplicação não precise ser responsiva, não é necessário adicionar "medias queries". Quando queremos que ela se adapte a várias resoluções, aí sim, adicionamos o Media Query para os pontos de quebra.

#### 7. Qual a diferença entre CSS Inline e CSS em um arquivo?
R: CSS Inline é aplicado diretamente na tag HTML, dentro do próprio arquivo "index", por exemplo. Já o CSS em arquivo, é carregado posteriormente, sendo ele, referenciado no HTML.

#### 8. Como criar animações no CSS? Dê um exemplo.
R: Segue abaixo uma animação, onde o texto deslizará da direta para esquerda:
"p {
  animation-duration: 5s;
  animation-name: slidein;
  animation-iteration-count: infinite;
}

@keyframes slidein {
  from {
    margin-left: 80%;
    width: 50%;
  }

  to {
    margin-left: 10%;
    width: 50%;
    color: blue;
  }
}"

#### 9. Qual a diferença entre class e ID no CSS?.
R: Classe podemos utilizar em vários elementos do site/sistema, enquanto o ID é único.

#### 10. Quais os diferentes tipos de seletores CSS?
R: Existem várias formas de selecionarmos elementos no CSS. As mais comuns são pelas TAG's, Classes e ID's. Podendo ainda selecionarmos por Atributos, universais e etc.
