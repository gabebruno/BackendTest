<h2>Descrição da solução</h2>

* A API foi desenvolvida em .netCore 3.1, sendo necessário a instalação do software equivalente para rodar o projeto.

* Foi utilizado metodologia DDD, Testes Unitários com Theory, princípios de SOLID, Injeção de Dependências e Mock para uso do JSON como banco de dados.

* Caso optem por alterar o arquivo JSON inserido, o mesmo deve ser colocado na pasta BookSearchRepository\Mock.

* O arquivo Book.json foi alterado para que alguns campos se enquadrassem nas especificações da API, retirando espaços dos nomes dos campos e inserindo "[ ]" nos campos necessidade de implementação de List<>.

* Foi criado o método Shipping(int id) disponível na classe IBookService do projeto BookSearchDomain\Aplication para calculo dos 20% do valor do produto para frete.

* A API foi escrita em sua grande maioria, senão por inteira, de textos, variaveis e funções em Inglês.

* As publicações no GIT, por falha minha foram realizadas apenas com o projeto completo, mas tenho experiência em controle de versão com criação de branchs para novas implementações ou correçoes, uso da branch DEVELOP para concentrar a versão que deve passar por QA e a MASTER para enfim publicar o projeto em produção.

-----------------------------------------------------------------------------------------------------------------
```
Um cliente tem necessidade de buscar livros em um catálogo. Esse cliente quer ler e buscar esse catálogo de um arquivo JSON, e esse arquivo não pode ser modificado. Então com essa informação, é preciso desenvolver:

- Criar uma API simples para buscar produtos no arquivo JSON disponibilizado.
- Que seja possivel buscar livros por suas especificações(autor, nome do livro ou outro atributo)
- É preciso que o resultado possa ser ordenado pelo preço.(asc e desc)
- Disponibilizar um método que calcule o valor do frete em 20% o valor do livro.

Será avaliado no desafio:

- Organização de código;
- Manutenibilidade;
- Princípios de orientação à objetos;
- Padrões de projeto;
- Teste unitário
- Conhecimento em controle de versão;

Para nos enviar o código, crie um fork desse repositório e quando finalizar, mande um pull-request para nós.

O projeto deve ser desenvolvido em C#, utilizando o .NET Core 2.2 ou superior.

Gostaríamos que fosse evitado a utilização de frameworks, e que tivesse uma explicação do que é necessário para funcionar o projeto e os testes.
```
