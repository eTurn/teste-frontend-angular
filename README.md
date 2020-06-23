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
Sua missão é criar uma página com função de  listar, detalhar e calcular nota média de *looks* em uma loja virtual.

## Requisitos
* Usuário terá a capacidade de filtrar por disponível/indisponível, faixa de preço e categoria
* O usuário deve ter capacidade de diferenciar na lista o produto disponível/indisponível com facilidade
* Nota média deve ser calculada utilizando a API math.js. A nota mínima é **1** e máxima é **5**
  * Para usar a API deve ser feito um GET para a API http://api.mathjs.org/v4 e deve ser enviado como **parâmetro** a seguinte estrutura: `{ expr=sum(2,1,2) / 3}` onde **2,1,2** são as notas recebidas para o look e **3** é a quantidade de notas recebidas. Para este exemplo o total é de: 1.6666666666666667. O valor deve ser arredondado para 1 casa decimal, no exemplo ficaria 1.6 e então marcar a nota média do look.

## Estrutura da página

* Filtro (Consultas **client side**)
   * Disponível 
   * Preço 
   * Categorias
* Sessão resultados
   * Look item
     * Imagem (Exibir a imagem com flag **destacada = true**)
     * Nome do look
     * Cateogoria 
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
