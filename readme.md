# Rush Alura 1
A Alura liberou uma conta premium para alunos do CIn - UFPE por 30 dias, vou aprender o máximo que puder, vou criar os repositórios para cada curso feito e também fazer algumas anotações. 

## Print de como ficou a página
![printprojeto](https://github.com/GuiCPessoa/RushAlura1/assets/93964438/d8fa5ba8-879b-4a86-b15e-9db076cd0f3e)



## Tags semânticas
header, main e footer, servem tanto para otimizar a leitura pelos navegadores e ajuda os desenvolvedores que vão fazer a manutenção do código

A tag button pode ser utilizada para ações como envios de formulários já a tag a, seu papel é apenas redirecionar o usuário para diferentes URLs.

## CSS
O Background serve para configurar todas as propriedades do plano de funto em uma declaração mais implícita.

Já o Background-color para mudarmos a cor de fundo de um elemento

.class irá selecionar elementos com os atribuitos de uma classe específica, ou seja, conseguimos selecionar partes para o CSS estilizar, uma parte especifica, através dos seletores de classe.

## Box Model
Padrão margin, border, padding, content

O padding é o espaçamento que tem ENTRE o conteúdo e a borda.

A borda contorna o padding, espaçamento entre a margem e padding

## Flexbox

A ideia do flex é dar ao contêiner a capacidade de alterar a largura/altura (e a ordem) de seus itens, para melhor preencher o espaço disponivel. O conteiner flex expande para preencher ou reduz para evitar o estouro. Independe de direção, diferente dos regulares block-vertical e inline-horizontal.

flex-direction, flexbox é além do empacotamento opcional um conceito de layout de direção única, itens flexiveis horizontal e colunas verticalmente.
.container{
    flex-direction: row, column e reverse nos dois
}


justify-content, define o alinhamento ao longo do eixo principal, ajudando a distribuir sobras de espaço livre extra

items-align, define o comportamento padrão de como os itens são dispostos ao longo do eixo transversal na linha atual.  :center, itens centralizados no eixo cruzado

Gap, row-gap, column-gap, controla o espaço entre os itens flexíveis, como o proprio nome já diz, espaçamento entre itens, espaço entre linha e entre colunas


Definindo o valor da propriedade display como flex, criarmos um conteiner flex, nesse ponto todos os elementos que estão dentro do contêiner são chamados de elementos-filhos e apresentarão comportamento padronizado.

align-items e justify-content, ambas propriedades atuam no elemento-pai com a responsa de espaçamento dos elementos-filhos



## Div
Div - Divisão, o conteúdo principal precisa de um nome significativo. <main>. Se estou trabalhando com um agrupamento de elementos que querem dizer uma coisa só, posso usar <section>. Já a <div> é puramente visual e serve apenas para juntar os dois botões em um lugar só, não possui valor semântico.