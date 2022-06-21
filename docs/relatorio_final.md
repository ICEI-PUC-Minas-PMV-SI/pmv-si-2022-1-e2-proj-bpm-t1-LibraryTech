# LibraryTech

`CURSO: Sistemas de Informação`

`DISCIPLINA: Projeto - Processos de Negócios`

`SEMESTRE: 1º`

`Projeto acadêmico do 2º período, realizado no primeiro semestre de 2022.`

`Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS)
Belo Horizonte – MG – Brasil`

### Equipe
Alysson Roberto Cordeiro <br>
Ana Laura Souza Rosa da Silva <br>
Fábio Rezende Dias Silva <br>
Geocacio Viviano Nascimento de Souza <br>
Guilherme Lima de Freitas <br>
Marcos Paulo Silva Costa

### Professora
Eveline Alonso Veloso

## Resumo 
Com as constantes transformações sociais, econômicas e tecnológicas da atualidade, as empresas buscam a modificação dos seus conceitos operacionais e produtivos. Essas modificações trazem a flexibilidade dos meios de serviço, redução de gastos e tempo. Com o propósito de facilitar ações rotineiras de uma biblioteca pública com foco em materiais didáticos para concursos, surge o LibraryTech, um sistema informatizado que realiza cadastro de materiais, empréstimos e devoluções de itens para gerenciar o funcionamento da biblioteca. Dentre os resultados relevantes obtidos, podemos citar a diminuição da perda de dados de empréstimo e de cadastro de material, diminuição do extravio de material do acervo e do acúmulo de papel.


## 1. Introdução
Atualmente, com o avanço da tecnologia e as constantes transformações sociais, econômicas e tecnológicas, as empresas buscam meios de se manterem no mercado, o que exige delas a modificação dos seus conceitos operacionais e produtivos. Essas modificações trazem a flexibilidade dos meios de serviço, redução de gasto e  tempo, entre outros benefícios.  Nesse cenário de crescente inovação tecnológica, os sistemas de informação propõem maior rapidez e confiabilidade nas informações geradas, apoiando a tomada de decisões.
Desse modo, Laudon e Laudon (2007) destacam a necessidade de um sistema de informação, dado como uma ferramenta de extrema importância dentro das organizações, uma vez que, consiste em um conjunto de componentes que se relacionam entre si, coletando dados, processando e fornecendo informações para o controle e gestão de qualquer tipo de organização. 
Com o propósito de facilitar ações rotineiras de uma biblioteca pública com foco em materiais didáticos para concursos, surge o LibraryTech, um sistema informatizado que realiza cadastro de materiais, empréstimos e devoluções de itens para gerenciar o funcionamento da biblioteca.

## 1.1 Objetivos geral e específicos

### 1.1.1 Geral:
O objetivo geral do LibraryTech é possibilitar a informatização de uma biblioteca que disponibiliza acesso gratuito a materiais didáticos para concursos destinados a pessoas de baixa renda. Esse sistema auxiliará não só os usuários, mas também os bibliotecários nos processos de cadastros, buscas, etc. 

### 1.1.2 Objetivos específicos:
* Cadastro dos itens: Para cada item deve se informar o título, autor, editora, categoria, número do volume e código do material;
* Empréstimo de itens: O sistema deve registrar o empréstimo de itens para os usuários cadastrados na biblioteca;
* Devolução de itens: O sistema deve registrar a devolução de itens para os usuários cadastrados na biblioteca;
* Identificação e cobrança de multas;
* Fila de espera: Gerar uma lista de espera quando um item já emprestado receber demanda de empréstimo de outros usuários;
* Negar Empréstimo: Impedir que o usuário solicite itens quando houver multas não pagas.

## 1.2. Justificativas
Nos dias de hoje, a tecnologia da informação é capaz de auxiliar todos os tipos de negócios, a aprimorar a produtividade e a eficácia de seus processos administrativos. A implantação de sistemas de informação promove produtos e serviços de melhor qualidade, maior precisão e menos erros nas informações armazenadas, aumento de produtividade e redução de custos, assim como diminuição da carga de trabalho manual. 
Nesse contexto, uma biblioteca com processos manuais para cadastro de materiais, empréstimos e devoluções de itens exige muito tempo e organização por parte dos funcionários. Dessa forma, é notável que a automatização desses processos é necessária para um rápido e eficaz atendimento ao usuário final.

## 2. Participantes do processo de negócio
### Stakeholder 1 - Estudantes de baixa renda com interesse em acervo didático. 
* Idade: Todas as idades aptas a prestarem vestibulares, concursos e provas estudantis.
* Nível de educação: Ensino Fundamental/Médio e/ou Superior Incompleto/Completo. 
* Conhecimento de Informática: Nulo ao avançado no uso de sistemas informatizados.  

### Stakeholder 2 - Funcionários da biblioteca.
* Idade: A partir de 18 anos. 
* Nível de educação: Ensino Fundamental/Médio e/ou Superior Incompleto/Completo. 
* Conhecimento de Informática: Básico ao avançado no uso de sistemas informatizados. 

## 3. Modelagem do processo de negócio

### 3.1. Análise da situação atual (AS-IS)
A atual situação da biblioteca, que envolve processos manuais de cadastro de materiais e de tomada de empréstimos de itens e suas devoluções, viabiliza a proposta de informatização do processo para evitarmos que os problemas causados por esse método continuem acontecendo. Dentre os problemas, temos o grande tempo gasto com anotações de dados em papéis que facilmente se perdem e não ficam organizados; falta de padronização nas anotações, com campos às vezes ficando vazios, rasurados e com possibilidade de escrita ilegível. As buscas manuais nas anotações realizadas para averiguar dados de empréstimos, devoluções e cadastros antes registrados é muito demorada e atrapalha o bom andamento das atividades da biblioteca. Perda de papéis com anotações de empréstimos pode levar à perda irrecuperável do material envolvido.

**Cadastro** - O cadastro de materiais no acervo é realizado de forma manual pelo bibliotecário. Após o recebimento do material, o item é avaliado em relação ao estado de conservação. Caso esteja em bom estado inicia-se o processo de cadastramento. Um formulário contendo as informações pertinentes sobre o material é preenchido. Esse procedimento é executado para cadastrar livros, artigos, revistas e afins na biblioteca. Finalizado o cadastro do material, o formulário é arquivado em um gaveteiro e o item separado é devidamente identificado para ser colocado em uma estante. O modelo AS IS da Figura 1 ilustra esse processo.
![aassiiss](https://user-images.githubusercontent.com/89880127/173992630-c15e37f0-563c-43c3-ad83-33c476d88033.png)
Figura 1 - Modelo AS-IS do Cadastro de Materiais

**Empréstimo** - Atualmente o empréstimo é realizado na biblioteca física, de forma manual. O usuário da biblioteca faz a busca em um cadastro do acervo em papel, e caso o material não conste no acervo, não há como realizar o empréstimo; caso conste no acervo, o usuário verifica a localização dele e vai até a estante indicada. Na estante, ele verifica se o material está disponível ou não; caso esteja disponível, o usuário leva o material até o bibliotecário e solicita o empréstimo e em seguida, o bibliotecário verifica se o usuário tem pendências com a biblioteca. Em caso de pendências, o empréstimo só é feito após a regularização; caso não haja pendências, o bibliotecário faz o registro do empréstimo, em um catálogo impresso, onde são anotados dados como nome, telefone, endereço, documento de quem está fazendo o empréstimo; consta também campo para escrita do nome do material que está sendo emprestado, além do número do volume e data da devolução. Finalizadas essas anotações, o catálogo impresso de empréstimo é arquivado em uma gaveta. Caso o material não esteja disponível, e seja de interesse do usuário saber a disponibilidade, ele poderá solicitar essa informação ao bibliotecário. Se o usuário quiser ser notificado da disponibilidade, o bibliotecário anotará nome e telefone para que seja feito contato quando da disponibilidade do material. O modelo AS-IS da figura 2 ilustra esse processo.
![asis emprest](https://user-images.githubusercontent.com/89880127/173992643-df5562e2-f5ed-4da3-a9e6-3e06b09f93c0.png)
Figura 2 - Modelo AS-IS do Empréstimo de Materiais

**Devolução** - Atualmente a devolução é feita na biblioteca física e registrada manualmente, devendo o funcionário da biblioteca localizar a ficha preenchida no momento do empréstimo, conferir os dados do usuário e do material que está sendo devolvido, bem como verificar se houve algum dano ao material e se a devolução está ocorrendo dentro do prazo estabelecido. Caso o material tenha sido danificado, o funcionário calcula uma multa para restituição ao acervo da biblioteca, faz o registro na ficha de empréstimo e notifica o usuário. Caso haja apenas atraso na devolução, o funcionário calcula uma multa por atraso, registra na ficha do usuário e emite o comprovante de devolução. Por fim, após o recebimento do material, o funcionário deve verificar a existência de fila de espera e, caso exista, notificar o primeiro usuário da disponibilidade do material.
![asis dev](https://user-images.githubusercontent.com/89880127/173992655-468bb0b6-6057-4ba2-a438-ff9f206efea3.png)
Figura 3 - Modelo AS-IS de Devolução de Materiais

### 3.2. Modelagem dos processos aprimorados (TO-BE)

**Cadastro** - Será possível consultar o material no sistema e escolher três opções: cadastrar material, alterar ficha de cadastro e excluir material cadastrado. Se a opção escolhida for cadastrar material, o material será cadastrado e terá seu código de identificação impresso. Se optar por alterar ficha de cadastro, a ficha será atualizada, podendo imprimir código de identificação do material ou encerrar o processo. Na opção excluir o cadastro do material, será pedida uma confirmação da exclusão, finalizando o processo.
![cadast](https://user-images.githubusercontent.com/89880127/173992669-a9a2645b-da5f-464b-9db1-c941db495869.png)
Figura 4 - Modelo TO-BE de Cadastro de Materiais

**Empréstimo** - O empréstimo de materiais ocorre por meio de um sistema automatizado em que o usuário realiza a busca do material no acervo digital e verifica a sua disponibilidade, e caso o material não exista no acervo o processo se encerra. Caso exista o material, mas esteja indisponível, é possível registrar o usuário na lista de espera. Caso o material exista e esteja disponível, e o usuário deseja realizar o empréstimo, o bibliotecário poderá preencher a ficha no sistema e registrá-la no banco de dados. Todavia, o empréstimo só será possível se o usuário não possuir pendências abertas. O sistema permite consultar se há multas. Caso haja multas e o seu pagamento seja confirmado, a regularização do usuário será registrada no banco de dados, permitindo o empréstimo.
![tobe emprestimo](https://user-images.githubusercontent.com/89880127/173992674-9fca8f2c-6901-4f9b-aa32-a3e55cf2d342.png)
Figura 5 - Modelo TO-BE do Empréstimo de Materiais

**Devolução** - O processo informatizado de devolução de materiais ocorre exclusivamente por acesso do bibliotecário, onde ele poderá consultar a ficha de empréstimo. Ao identificar a ficha de empréstimo, a devolução será registrada e confirmada no acervo digital. Será possível consultar e registrar o pagamento de multas. Não havendo multas a pagar, existe a possibilidade de inserir os dados do usuário na lista de espera. Caso haja pendências, a devolução ainda será aceita, porém não será possível inserir os dados do usuário na lista de espera.
![tobe devolução](https://user-images.githubusercontent.com/89880127/173992723-349119b6-9dd8-4c10-919c-d4b785902453.png)
Figura 6 - Modelo TO-BE da Devolução de Materiais

## 4. Projeto da arquitetura de dados da solução proposta

### 4.1. Diagrama de Entidades e Relacionamentos (DER)
Na Figura 7 é apresentado o Diagrama de Entidade e Relacionamentos desenvolvido para o projeto.
![der](https://user-images.githubusercontent.com/89880127/173991535-cfebfba0-b8df-48b1-bbd7-4c808ccefee1.png)
Figura 7 - Modelo DER da Library Tech

### 4.2. Impactos da implementação em um banco de dados NoSQL
Os bancos de dados NoSQL são as soluções não relacionais para armazenamento persistente de volumes massivos de dados, com operação em cluster. Além disso, os bancos de dados NoSQL são mais flexíveis e escaláveis horizontalmente, não aderem à estrutura de esquema rígida e nem estão restritos a um único modelo de dados como os bancos de dados SQL tradicionais. As características ACID (Atomicidade, Consistência, Isolamento e Durabilidade) não estão presentes nos bancos de dados NoSQL, o que confere aos desenvolvedores maiores esforços para garantir a integridade dos dados e confiabilidade nas transações concorrentes. Atualmente, o uso do banco de dados NoSQL vem se tornando comum e o número de desenvolvedores deste tipo de banco de dados está em constante crescimento, mas a tecnologia NoSQL não é tão madura e não é tão bem suportada quanto a tecnologia SQL.
Nesse contexto, o sistema LibraryTech, que tem como objetivo informatizar uma biblioteca de médio porte, de forma estruturada e com necessidade de integridade de dados e confiabilidade nas suas transações, com provável escalabilidade vertical e descartada a escalabilidade horizontal, notamos que a tecnologia NoSQL não se associa à esse perfil de informatização e que os bancos de dados com tecnologia SQL são mais adequados para esse modelo de negócio.

### 4.3. Modelo Relacional
![Modelo Relacional LibraryTech v_2 drawio](https://user-images.githubusercontent.com/89880127/173990005-e816578c-c019-466d-8dff-5613426e2cef.png)
Figura 8 - Modelo Relacional da Library Tech


## 5. Relatórios analíticos
![Gráfico 1](https://user-images.githubusercontent.com/89880127/173990442-be909c29-ce9d-43cd-b73a-ece628dfc418.png)
Figura 9 -   Gráfico de barras de cadastro de materiais por categoria

<br>

![Gráfico 2](https://user-images.githubusercontent.com/89880127/173990566-ed8f2002-18f9-400f-ac39-3c866acdcb91.png)
Figura 10 - Tabela de empréstimo de materiais por categoria e por mês.

## 5.1. Associação de comandos SQL com relatórios analíticos

| Nome do Relatório                                     | Comando SQL-DML (SELECT)   |
|  :------------------------:                           |  :-----------------------------------------------------------------------------------------------: |
| Empréstimos de materiais por categoria e por mês.     |select material.categoria, count(emprestimo.id_emprestimo) <br> from material, emprestimo <br> where material.id_emprestimo = emprestimo.id_emprestimo <br> group by material.categoria, month(emprestimo.data_inicio);   |
| Material cadastrado por categoria.                    | select categoria, count(id_material) <br> from material <br> group by categoria;  |


## 6. Indicadores de desempenho


| Indicador  | Objetivo  | Descrição  | Fórmula  | Fontes  de dados  | Perspectiva  |
| :--------: | :-------: | :--------: | :------: | :---------------: | :--------:   |
| Taxa de uso do acervo. | Avaliar quantitativa mente o uso dos materiais do acervo da biblioteca. | É o número total de empréstimos (E) dos materiais do acervo durante o período de um ano, dividido pelo número total de materiais do acervo (MA). | E / MA  | Tabela de empréstimo e material. | Processos internos.  |
| Empréstimos por usuário. | Avaliar a taxa de utilização dos materiais da biblioteca pelo público alvo. | É o número total de empréstimos (E) no ano dividido pela quantidade de usuários (U) da biblioteca. | E / U | Tabela de empréstimo e usuário. | Processos internos. |
| Multas por usuário. | Monitorar a quantidade de multas aplicadas aos usuários em um determinad o período de tempo. | É a relação entre o número total de multas (M) aplicadas por usuários (U) cadastrados na biblioteca. | M / U | Tabela de multa e usuário. | Clientes. |
| Quantidade de materiais não utilizados. | Avaliar a quantidade de materiais não utilizados durante um período determinado. | É a porcentagem de materiais disponíveis (MD) em relação aos materiais emprestados (ME) não utilizada durante o período de um mês. | ((MD - ME) / MD) x 100 | Tabela de empréstimo e material. | Processos internos. |
| Quantidade de empréstimos por mês. | Avaliar quantitativa mente os materiais emprestados por mês. | É o percentual da relação entre o número total de empréstimos por mês (EM Mês) pelo número total de empréstimos (TEM) de um determinado ano. | (EM mês / TEM) X 100 | Tabela de empréstimo. | Processos internos. |
| Quantidade de material cadastrado por categoria. | Avaliar quantitativa mente os materiais cadastrados por categoria. | É o percentual da relação entre o número total de materiais cadastrados por categoria (MCCat) pelo número total de materiais cadastrados (TMC). | (MCCat / TMC) x 100 | Tabela de material. | Processos internos. |
| Quantidade de empréstimos por categoria. | Avaliar quantitativa mente os materiais emprestados por categoria. | É o percentual da relação entre o número total de empréstimos por categoria (EMCat) pelo número total de empréstimos (TEM). | (EMCat / TEM) x 100 | Tabela de empréstimo e tabela de material. |Processos internos. |


## 7. Conclusão
O presente trabalho teve como propósito simplificar o funcionamento de uma biblioteca, a partir da implementação de um sistema informatizado que realiza cadastro de materiais, empréstimos e devoluções de itens, permitindo melhor armazenamento de informações, agilizando as tarefas e evitando a perda de dados. 
Devido ao pouco tempo disponível para a finalização desse trabalho, o processo de devolução não pode ser automatizado, o que pode vir a limitar a utilização do sistema. No entanto, os processos já automatizados (cadastro de materiais e empréstimo) foram devidamente testados e estão funcionando corretamente, possibilitando um uso inicial do sistema.
Assim, caso haja possibilidade de finalizarmos a automatização do processo restante (devolução) será possível o uso integral do sistema, que pode também vir a receber novos processos futuramente, de acordo com a demanda dos usuários e as indicações deles para a melhoria do sistema. Uma possibilidade de implementação de novo processo pode ser, por exemplo, o cadastro de usuários.
 
