# Open Rent

This is a open pratical project proposed by the teacher [Fernando Antônio de Araújo Chacon de Albuquerque]( http://lattes.cnpq.br/0766291598953512) from the [University of Brasília (UnB)](https://www.unb.br/) and [Computer Science Department](https://cic.unb.br/).

The propose of this project is to build the basics artifacts of a Software Product Project.

## Members

* [Andrey Calaca Resende](https://github.com/andreyresende) - 180062433
* [Felipe Luís Pinheiro](https://github.com/flpinheiro) - 180052667
* [Wanderlan Alves de Jesus de Brito](https://github.com/Wander-lan) - 160148782
* [William Coelho da Silva](https://github.com/Williamcs1400) - 180029274

## [TRABALHO PRÁTICO](https://github.com/flpinheiro/ProjetoES/raw/master/SW-TRABALHO-PR%C3%81TICO.pdf)

## INTRODUÇÃO

O trabalho consiste em construir artefatos em processo de desenvolvimento de software embasado no processo OpenUP. Para subsidiar a construção dos artefatos, podem ser acessados sistemas de software existentes por meio da Internet. Por exemplo, sistemas existentes podem facilitar a construção de artefatos resultantes de atividades da disciplina requisitos
de software.

## REQUISITOS FUNCIONAIS

O sistema de software a ser desenvolvido tem o objetivo de prover suporte ao aluguel de imóveis. Por meio desse
sistema, proprietários podem anunciar imóveis para aluguel e interessados podem apresentar propostas de aluguel. Pode
ser anunciado apartamento, casa ou quarto. Ao anunciar um imóvel, o proprietário desse imóvel deve prover os
seguintes dados: classe do imóvel (apartamento, casa ou quarto), descrição, endereço, número máximo de hóspedes,
data inicial do período de disponibilidade, data final do período de disponibilidade e valor de diária mínimo. Por sua
vez, pessoas interessadas em alugar imóveis podem apresentar propostas de aluguel. Ao apresentar uma proposta de
aluguel, o interessado deve prover os seguintes dados: data inícial do período de aluguel, dada final do período de
aluguel, numero de hospedes e valor de diária proposto. Por meio do sistema sendo desenvolvido, qualquer usuário tem
acesso aos seguintes serviços: listar imóveis disponíveis, apresentar dados de imóvel.

Para acessar outros serviços, o usuário precisa ser autenticado. Para ser autenticado, o usuário deve prover os seguintes
dados: endereço de correio eletrônico e senha. Para ser autenticado, o usuário precisa ter cadastrado uma conta. Para
cadastrar uma conta, o usuário deve prover os seguintes dados: nome, endereço de correio eletrônico, senha e telefone.
Uma vez autenticado, o usuário tem acesso aos seguintes serviços relacionados à sua conta: descadastrar conta; editar
dados da conta. Quando uma conta é descadastrada, são descadastrados os imóveis e as propostas de aluguel associadas
à conta. Uma vez autenticado, o usuário tem acesso aos seguintes serviços relacionados aos imóveis: cadastrar imóvel;
descadastrar imóvel por ele cadastrado; editar dados de imóvel por ele cadastrado. Quando um imóvel é descadastrado,
são também descadastradas as propostas de aluguel associadas ao imóvel. Uma vez autenticado, o usuário tem acesso
aos seguintes serviços relacionados às propostas de aluguel: cadastrar proposta de aluguel; listar as propostas de aluguel
por ele cadastradas; apresentar dados de proposta de aluguel por ele cadastrada; descadastrar proposta de aluguel por
ele cadastrada. O usuário que cadastrou um imóvel pode também listar todas as propostas de aluguel que estão
associadas ao imóvel e pode acessar dados de cada proposta associada ao imóvel.

## REGRAS DE NEGÓCIO

O sistema sendo desenvolvido deve impor as seguintes regras de negócio: cada usuário pode cadastrar até cinco
imóveis; para cada imóvel, cada usuário pode cadastrar apenas uma proposta de aluguel; cada proposta de aluguel é
cadastrada apenas se o período solicitado para aluguel for compatível com o período disponível para aluguel, se o
número de hóspedes não for superior ao máximo aceito pelo proprietário e se o valor de aluguel proposto não for
inferior ao valor de aluguel mínimo aceito pelo proprietário.

## REQUISITOS NÃO FUNCIONAIS

1. Sistema de software destinado a prover serviços por meio da World Wide Web.
2. Adoção de estilo(s) de arquitetura.

## ARTEFATOS A SEREM CONSTRUÍDOS E ENTREGUES

1. Descrição do processo a ser seguido no projeto que resultará nos artefatos (project defined process). OK
2. Plano do projeto (project plan). OK
3. Planos das iterações (iteration plan). OK
4. Lista de ferramentas (tools).
5. Glossário (glossary). OK
6. Documento de visão (vision).
7. Descrições de requisitos que não sejam expressos por meio de casos de uso (system-wide requirements).
8. Modelo de casos de uso (use-case model) . OK
9. Descrições detalhadas dos casos de uso (use case).
10. Descrição da arquitetura do software (architecture notebook). OK
11. Projeto de interface com o usuário.
12. Projeto físico de banco de dados.
13. Descrição da infraestrutura de implantação (infrastructure).
14. Teste fumaça (smoke test) composto por casos de teste (test cases). OK
15. Protótipo de interface com o usuário.
16. Protótipo de banco de dados.

## INSTRUÇÕES E RECOMENDAÇÕES

1. Realizar o trabalho individualmente ou em equipe com até quatro participantes.
2. Ler documentação relativa a cada artefato no OpenUP.
3. Avaliar a possibilidade de adotar ou adaptar templates sugeridos no OpenUP.
4. Definir processo a ser seguido no projeto (project defined process) a partir de elementos do OpenUP.
5. Enfocar o projeto como um todo no plano de projeto (project plan).
6. Considerar que cada artefato resulta de uma iteração.
7. Considerar que cada iteração consiste de um pequeno projeto.
8. Construir um plano para cada iteração (iteraction plan).
9. Incluir descrições resumidas das ferramentas na lista de ferramentas.
10. Compor o glossário por definições de termos no domínio da aplicação.
11. Compor o modelo de casos de uso por diagramas (atores, casos de uso etc.) e por descrições textuais de atores.
12. Representar projeto de interface com o usuário por storyboard composto por wireframes.
13. Constuir cada wireframe como esboço simples de tela.
14. Representar o projeto físico do banco de dados por diagrama e texto.
15. Incluir no projeto físico informação sobre tabelas (nomes, colunas, chaves etc.) e seus relacionamentos.
16. Compor o protótipo de interface com usuário por mockups de telas.
17. Construir cada mockup como representação final de uma tela.
18. Representar cada mockup por uma página HTML.
19. Construir protótipo do banco de dados por meio da ferramenta DB Browser for SQLite.
20. Preencher os documentos com clareza.
21. Revisar a ortografia.
22. Identificar a autoria do trabalho por meio de número(s) de matrícula.
23. Fornecer os documentos textuais em arquivos no formato PDF.
24. Fornecer as páginas HTML resultantes da construção do protótipo da interface com o usuário.
25. Fernecer o arquivo resultante da construção do protótipo do banco de dados.
26. Incluir todos os artefatos em um arquivo zip com nome TRAB-PRAT-ESW-X-Y-Z-W.ZIP.
27. Informar em X, Y, Z e W os números de matrícula dos alunos que são autores do trabalho.
28. Testar se o arquivo zip pode ser descompactado com sucesso .
29. Testar se não há vírus no arquivo zip.
30. Enviar o arquivo zip dentro do prazo.

## REFERÊNCIA

* Sommerville, I. Engenharia de Software. Edição 10. Pearson, 2019. Software Engineering 10th edition
* PRESSMAN, R. Engenharia de Software: Uma abordagem profissional. AMGH, 2016.
* SOMMERVILLE, I. Engenharia de Software. Edição 10. Pearson, 2019.
* [IEEE.SWEBOK:Guide to the Software Engineering Body of Knowledge. IEEE Computer Society, 2014.](https://www.computer.org/education/bodies-of-knowledge/software-engineering)
* PRINKLADNICKI,R. et al. Métodos ágeis para desenvolvimento de software. Bookman, 2014.
* [Processos de software - OpenUP](https://www.eclipse.org/epf/downloads/configurations/pubconfig_downloads.php)
