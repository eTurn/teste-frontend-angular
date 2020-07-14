# Teste de frontend AngularJS e-turn sistemas

Olá Dev! Tudo bem?

Nós da ***e-turn*** estamos sempre em busca de profissionais interessantes e interessados, com boa capacidade de aprendizado, comunicação, adaptação e principalmente bom senso!

Este teste tem como objetivo avaliar e desafiar você. Não é obrigatório realizá-lo completamente, queremos apenas reconhecer seu esforço e potencial para aprender, se adaptar e tomar decisões.

*Let's code!!!*

# Habilidadades
* HTML5
* CSS3
* Less/SASS
* Responsive Web Design
* JavaScript
* AngularJS
* Experiência em controle de versão com **Git**
* Task Runners (desejável)

# Desafio 
Sua missão é criar uma página com função de  listar, detalhar e calcular nota média de *looks* usando uma API externa em uma loja virtual.

## Requisitos
* Usuário terá a capacidade de filtrar por disponível/indisponível, faixa de preço e categoria
* O usuário deve ter capacidade de diferenciar na lista o produto disponível/indisponível com facilidade
* Preço médio estará sempre entre  **1** e **4**
* Nota média deve ser calculada utilizando a API math.js. A nota mínima é **1** e máxima é **5**
  * Para usar a API deve ser feito um GET para a API http://api.mathjs.org/v4 e deve ser enviado como **parâmetro** a seguinte estrutura: `{ expr=sum(2,1,2) / 3}` onde **2,1,2** são as notas recebidas para o look e **3** é a quantidade de notas recebidas. Para este exemplo o total é de: *1.6666666666666667*. O valor deve ser arredondado para uma casa decimal, no exemplo ficaria 1.7 e então marcar a nota média do look.

## Estrutura da página

* Filtro (Consultas **client side**)
   * Disponível 
   * Preço 
   * Categorias
* Sessão resultados
   * Look item
     * Imagem (Exibir a imagem com flag **destacada = true**)
     * Nome do look
     * Categoria 
     * Nota média (calcular via api)
     * Preço médio
     * Disponibilidade
     * Saiba mais (Abrir sessão detalhes)
 * Sessão Detalhes
    * Imagens (Exibir lista de imagens navegável)
    * Nome do look
    * Nota média (Obter o valor já calculado ou calcular novamente, fica a critério)
    * Texto
  

## Regras
* É permitido realizar pesquisas na internet
* É permitido o uso de framework CSS (da sua escolha)
* Na parte de JS deve ser utilizado **AngularJS**
* Os dados para serem exibidos devem ser lidos do arquivo *produtos.js* localizado dentro da pasta *data*
* As imagens existentes no arquivo produtos.js estão na pasta *arquivos/produtos*



# Proposta de layout
![picture alt](https://github.com/eTurn/teste-frontend-angularjs/blob/master/arquivos/Wireframe/pagina_looks.jpg "Wireframe")

## Paleta de cores
Sugestão de paleta de cores e tipografia 
![picture alt](https://github.com/eTurn/teste-frontend-angularjs/blob/master/arquivos/Wireframe/paleta_cores.jpg "Wireframe")

# Artefatos para entrega
Envie um arquivo comprimido em formato **.rar**  para o e-mail *vagas@eturn.com.br* contendo o código fonte e um arquivo README.md explicando o passo a passo de como podemos inicializar e visualizar seu projeto.

Você pode utilizar recursos ou bibliotecas de terceiros que achar convenientes para o cenário dado. Liste estas bibliotecas no arquivo README e uma explicação breve de por quê utilizou cada uma.

Desenvolva para browsers modernos e teste neles. Aconselhamos realizar testes no Chrome, Firefox e Safari.

# O que será analisado no código?
## 1. Layout: 
* 1.1 Foram utilizadas as cores da paleta? 
* 1.2 O layout está em uma qualidade satisfatória para liberação em ambiente de produção?
* 1.3 Foram adicionados recursos de navegação (Exibição da tela de detahe de cada look)?
* 1.4 Foi implantado algum slider para exibir o detalhe do look?
* 1.5 O valor numérico do preço médio foi convertido para cifrões (conforme wireframe) no layout?
* 1.6 A nota média foi convertida para estrelinhas (conforme wireframe) no layout?
* 1.7 A disponibilidade de cada produto ficou destacada facilitando a identifação?

## 2. Código:
* 2.1 Os dados dos produtos foram obtidos através de código?
* 2.2 Os dados para preenchimento do filtro foram obtidos através de código?
* 2.3 Os filtros estão funcionando de forma correta?
* 2.4 Limpar filtro está exibindo novamente os dados que haviam sido filtrados?
* 2.5 Na tela principal foi exibida a imagem marcada como destacada no arquivo?
* 2.6 Foi utilizada a API recomendada para fazer o cálculo da nota?
* 2.7 Foi obtida a imagem destacada de forma correta?
* 2.8 Foram utilizadas boas práticas de desenvolvimento?


**IMPORTANTE**
Não comite seu código em nenhum repositório público.

***Boa sorte***
