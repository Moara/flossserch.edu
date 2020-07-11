## Operationalization of the Criteria

To verify the feasibility of automating this selection approach, we detail each criterion, reporting when and how it should be used, and how it could be implemented. To describe each criterion, we take inspiration from the project components presented by Gama et al, and define a presentation template, composed of name, intention, applicability, motivation, consequence, implementation and the type of data entry. 

### Linguagem de Programação.


```markdown
Nome: Linguagem de Programação.

Intenção: Retornar projetos FLOSS de uma linguagem de programação específica dentre os  projetos disponíveis.

Motivação: Considere que um professor deseja utilizar um projeto FLOSS hospedado no GitHub para ensinar manutenção de software para seus alunos, sem que estes realizem commits no repositório original. Milhares de projetos estão disponíveis  neste repositório, mas o professor deseja utilizar projetos que foram implementados em linguagens de programação já utilizadas por seus alunos anteriormente.
Podemos resolver esse problema selecionando os projetos por linguagem de programação específica, uma vez que acreditamos que a linguagem utilizada no projeto é uma consideração essencial para estudantes. Se o projeto estiver escrito em uma linguagem com o qual os alunos já estejam familiarizados, esse será um obstáculo a menos para se preocuparem.

Aplicabilidade: Use o critério Linguagem de Programação, quando
deseja obter projetos FLOSS implementados em uma linguagem de programação específica. 

Consequências: O critério Linguagem de Programação tem os seguintes benefícios e desvantagens: i) Ele retorna projetos com linguagens de programação específicas. Esse critério é utilizado como parâmetro de busca para localizar, dentre  os 3

5rrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrghv projetos disponíveis no repositório %do \textit{GitHub}
, aquele que possui a linguagem de programação informada como a linguagem predominante naquele projeto; ii) Muitos projetos podem ser retornados. Existem linguagens de programação que são comumente utilizada mais do que outras. Sendo assim,um número maior de projetos podem ser retornados, quando informado uma linguagem de programação que é mais utilizada na implementação do código fonte (ex. Java);
iii) Caso o projeto possua multilinguagens de programação, a busca por projetos com a linguagem de programação especificada será realizada, considerando apenas a linguagem de programação predominante no projeto.

\textit{Implementação:} Para implementar esse critério pode ser utilizada a API V3 do \textit{GitHub} que possui o \textit{Objeto Linguagem} representando uma determinada linguagem encontrada nos repositórios.

\textit{Entrada de Dados:} Pode ser apresentado um checkbox para que o professor escolha a linguagem de programação desejada. Esse checkbox deve permitir a escolha de uma ou várias linguagens. 
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/flosssearch/flossserch.edu/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
