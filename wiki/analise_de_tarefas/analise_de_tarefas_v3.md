| Data | Versão | Descrição | Autor |
| --- | --- | --- | --- |
| 14/10/2019 | [1.0](analise_de_tarefas_v1.md) | Análise de Tarefas | Emanuel Holanda |
| 29/10/2019 | [2.0](analise_de_tarefas_v2.md) | Análise de Tarefas | Emanuel Holanda e Iuri Severo |
| 13/11/2019 | 3.0 | Refatoração        | Gabriela Lemos                |

# Análise de Tarefas
<p align=”justify”> &emsp;&emsp;A análise de tarefa tem como objetivos 	identificar necessidades de treinamento: entender as competências e habilidades das tarefas complexas e auxiliar na identificação de problemas de desempenho. Para isso, é necessário analisar e relacionarmos (1) o que as pessoas fazem, (2) porque fazem e (3) quais as consequencias caso não façam corretamente. </p>
<p align=”justify”> &emsp;&emsp;Assim, para conseguirmos enxergar tais relacionamentos e identificar os problemas de design da aplicação, a análise de tarefas propõe uma decomposição de uma tarefa complexa em seus componentes, que são seus conhecimentos procedimentais e declarativos. Quando utilizada na etapa de design de um software, ela geralmente é realizada em um nível mais alto de abstração, visto que muitos detalhes a respeito do sistema ainda não estarão bem definidos.</p>
<p align=”justify”> &emsp;&emsp;Como visto, a análise de tarefas possui diversos objetivos, porém, para o projeto analisado, atribuiu-se a função principal de definir como seria o fluxo de serviço das funcionalidades da página web, assim como identificar e entender parte das necessidades do usuário. Para isso foi utilizada o tipo hierárquico da análise, onde se observa um objetivo principal do usuário e, a partir da decomposição dele, encontra-se as tarefas realizadas.
</p>

### Possíveis imprecisões

* O ator é colocado em uma hierarquia acima de uma tarefa a ser realizada.
* Algumas tarefas não estão muito bem hierarquizadas (tarefas localizadas em anunciar produto, por exemplo). 
* Há no diagrama tarefas ambíguas: "Procurar por produto na página inicial", "Pesquisar pelo produto". A proposta é explorar mais as funcionalidades do aplicativo de forma clara. Por exemplo, não foi enaltecido a questão de seções do site (eletrônicos, moda, etc.).
* A tarefa "Entrar no site" aparece, mas o diagrama já sugere que o usuário está na aplicação. O que deve ser analisado é o processo dentro da aplicação, então fica implícito no diagrama a ação do usuário de entrar no site. Ademais, acredito que sua correta adaptação seria "Efetuar login".
* A questão de entrega do produto é uma tarefa do usuário que, entretanto, não faz parte da aplicação.

## **Diagrama da Análise de Tarefas**

### Diagrama geral
![](https://user-images.githubusercontent.com/43069991/68847033-b9d35d80-06ac-11ea-8dd2-01e4d0e705b5.png)
![](https://user-images.githubusercontent.com/43069991/68845971-09188e80-06ab-11ea-9b9a-0e9aba214864.png)

### Diagrama da tarefa "Vender"
![](https://user-images.githubusercontent.com/43069991/68846992-a58f6080-06ac-11ea-97d0-77603ef44709.png)

### Diagrama da tarefa "Comprar"
![](https://user-images.githubusercontent.com/43069991/68845914-f1410a80-06aa-11ea-9248-1363d00e0483.png)

<p align="justify"> &emsp;&emsp;
Como a OLX permite seus usuário comprarem e venderem produtos, o diagrama geral das tarefas é dividido em dois. Para uma melhor visualização, as tarefas que se relacionam foram pintadas na mesma cor e os diagramas próprios de cada tarefa principal também foi disponibilizado.
</p>


## Referências
* [Análise de Tarefas. Análise Hierárquica de Tarefas](https://docplayer.com.br/13376795-Analise-de-tarefas-analise-hierarquica-de-tarefas.html), acessado dia 29/10/2019
* [Análise de Tarefas](https://www.portaleducacao.com.br/conteudo/artigos/enem/analise-de-tarefas/19733), acessado dia 29/10/2019
* Documentos disponibilizados pelo professor no [Moodle](https://aprender.ead.unb.br/course/view.php?id=2608)
